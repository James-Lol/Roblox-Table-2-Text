# Roblox-Table-2-Text
Turn roblox lua tables to text [Functions do not work]


Heres how to use it :

local TestTable = {
    [1] = "First",
    [2] = nil,
    [3] = "2",
    [4] = nil,
    [5] = nil,
    [6] = "Sixth",
    ["test"] = {[1] = true}
}

local Result = TableToString(TestTable)
print(Result)
