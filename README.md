        _G.farm = true
local g = game.Workspace.tools
while _G.farm == true do
wait()
for fk, fl in pairs((g:GetChildren())) do
    if fl:IsA("Tool") then
        game:GetService("Players").LocalPlayer.Character.Humanoid:EquipTool(fl)
    end
end
end
