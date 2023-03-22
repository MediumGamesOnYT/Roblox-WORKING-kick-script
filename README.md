here is the kick script.
it should work in any game ,use at your own risk



local player = game.Players.LocalPlayer
local mouse = player:GetMouse()

mouse.Button1Down:Connect(function()
    local target = mouse.Target
    if target.Parent:FindFirstChild("Humanoid") then
        game:GetService("Players"):FindFirstChild(target.Parent.Name):Kick("You have been kicked.")
    end
end)




if it doesnt work contact me and ill make a new one
