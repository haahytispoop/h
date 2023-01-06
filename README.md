local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("New script", "Ocean")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Main")
Section:NewToggle("autoclick", "", function(state)
    if state then
        getgenv().bubble = true;

while wait() do
    if getgenv().bubble == true then
        local args = {[1] = {[1] = {[1] = false},[2] = {[1] = 2}}}workspace.Stuff.Remotes:FindFirstChild("blow bubble"):FireServer(unpack(args))
    end
end
    else
        getgenv().bubble = false;

while wait() do
    if getgenv().bubble == true then
        local args = {[1] = {[1] = {[1] = false},[2] = {[1] = 2}}}workspace.Stuff.Remotes:FindFirstChild("blow bubble"):FireServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("autosell", "", function(state)
    if state then
        getgenv().sell = true;

while wait() do
    if getgenv().sell == true then
        local args = {[1] = {[1] = {[1] = true},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("sell bubbles"):FireServer(unpack(args))
    end
end
    else
        getgenv().sell = false;

while wait() do
    if getgenv().sell == true then
        local args = {[1] = {[1] = {[1] = true},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("sell bubbles"):FireServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("autocommon egg", "", function(state)
    if state then
        getgenv().egg = true;

while wait() do
    if getgenv().egg == true then
        local args = {[1] = {[1] = {[1] = "Common Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().egg = false;

while wait() do
    if getgenv().egg == true then
        local args = {[1] = {[1] = {[1] = "Common Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto spotted egg", "", function(state)
    if state then
        getgenv().degg = true;

while wait() do
    if getgenv().degg == true then
        local args = {[1] = {[1] = {[1] = "Spotted Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().degg = false;

while wait() do
    if getgenv().degg == true then
        local args = {[1] = {[1] = {[1] = "Spotted Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto safe egg", "", function(state)
    if state then
        getgenv().segg = true;

while wait() do
    if getgenv().segg == true then
        local args = {[1] = {[1] = {[1] = "Safe Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().segg = false;

while wait() do
    if getgenv().segg == true then
        local args = {[1] = {[1] = {[1] = "Safe Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto magma egg", "", function(state)
    if state then
        getgenv().megg = true;

while wait() do
    if getgenv().megg == true then
        local args = {[1] = {[1] = {[1] = "Magma Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().megg = false;

while wait() do
    if getgenv().megg == true then
        local args = {[1] = {[1] = {[1] = "Magma Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto void egg", "", function(state)
    if state then
        getgenv().vegg = true;

while wait() do
    if getgenv().vegg == true then
        local args = {[1] = {[1] = {[1] = "Void Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().vegg = false;

while wait() do
    if getgenv().vegg == true then
        local args = {[1] = {[1] = {[1] = "Void Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto galaxy egg", "", function(state)
    if state then
        getgenv().gegg = true;

while wait() do
    if getgenv().gegg == true then
        local args = {[1] = {[1] = {[1] = "Galaxy Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().gegg = false;

while wait() do
    if getgenv().gegg == true then
        local args = {[1] = {[1] = {[1] = "Galaxy Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto lantern egg", "", function(state)
    if state then
        getgenv().lanteregg = true;

while wait() do
    if getgenv().lanteregg == true then
        local args = {[1] = {[1] = {[1] = "Lantern Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().lanteregg = false;

while wait() do
    if getgenv().lanteregg == true then
        local args = {[1] = {[1] = {[1] = "Lantern Egg"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
Section:NewToggle("auto new egg", "", function(state)
    if state then
        getgenv().newegg = true;

while wait() do
    if getgenv().newegg == true then
        local args = {[1] = {[1] = {[1] = "New Year Egg (2022)"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    else
        getgenv().newegg = false;

while wait() do
    if getgenv().newegg == true then
        local args = {[1] = {[1] = {[1] = "New Year Egg (2022)"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("buy egg"):InvokeServer(unpack(args))
    end
end
    end
end)
local Tab = Window:NewTab("Codes")
local Section = Tab:NewSection("redeem")
Section:NewButton("Redeem all codes", "", function()
    local args = {[1] = {[1] = {[1] = "happynewyear"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
    local args = {[1] = {[1] = {[1] = "2022"},[2] = {[1] = false}}}workspace.Stuff.Remotes:FindFirstChild("redeem twitter code"):InvokeServer(unpack(args))
end)
local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("TP")
Section:NewButton("1 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-400.397308, 959.909912, -576.128601, 0.910760105, -1.30580879e-08, -0.412935853, -1.9790475e-08, 1, -7.52718918e-08, 0.412935853, 7.67268347e-08, 0.910760105)
end)
Section:NewButton("2 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-386.652557, 5200.00342, -560.927124, 0.763037622, 2.38311362e-08, -0.646354079, 4.20775592e-08, 1, 8.65437357e-08, 0.646354079, -9.32331261e-08, 0.763037622)
end)
Section:NewButton("3 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-417.92337, 11341.374, -580.766724, 0.655655921, 4.50191671e-08, 0.755059838, 2.78777312e-09, 1, -6.2044073e-08, -0.755059838, 4.27844995e-08, 0.655655921)
end)
Section:NewButton("4 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-396.427368, 21343.1836, -583.371582, 0.975999475, -4.00648297e-08, 0.217772871, 1.57480162e-08, 1, 1.13396936e-07, -0.217772871, -1.0724586e-07, 0.975999475)
end)
Section:NewButton("5 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-398.697388, 33369.9648, -597.155151, -0.989989579, -1.63100449e-08, -0.141140655, -2.06458957e-08, 1, 2.92557516e-08, 0.141140655, 3.18768656e-08, -0.989989579)
end)
Section:NewButton("6 Island", "", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-385.855591, 40970.0117, -567.991089, -0.990209937, -2.53788013e-08, 0.139586166, -2.99004377e-08, 1, -3.02960572e-08, -0.139586166, -3.41731443e-08, -0.990209937)
end)
local Tab = Window:NewTab("Destroy")
local Section = Tab:NewSection("delete")
Section:NewButton("vip area", "", function()
    game.Workspace.MAP.Areas.VIP:Destroy()
end)
