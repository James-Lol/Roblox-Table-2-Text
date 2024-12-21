# Roblox-Table-2-Text
Turn roblox lua tables to text [Functions do not work]


Heres how to use it :

local TestTable = {
    "First",
    nil,
    [3] = "Third",
    [4] = nil,
    [5] = nil,
    "Sixth",
    ["test"] = {true},
}


local Result = TableToString(TestTable)
print(Result)
