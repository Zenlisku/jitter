repeat wait() until game:IsLoaded()

getgenv().speed = 0.00000001 
getgenv().AntiLockKey = nil


if game:IsLoaded() then

end
 
local Player = game:GetService("Players").LocalPlayer
local ID = 11481218
 
if true then
local StarterGui = game:GetService("StarterGui")
 
    StarterGui:SetCore("SendNotification", {
        Title = "Jitter";
        Text = "Loading...",AntiLockKey;
    })
    local toggle = false
local plr = game:GetService("Players").LocalPlayer
local mouse = plr:GetMouse() 
local speedx = speed -- 0.08 is default, the higher the value is, the slower it lags, the lower the value is the faster it lags.
_G.Antilag = false

function yo(key) 
    key = key:lower() and key:upper()
  if key == AntiLockKey then 
    if toggle == false then
        _G.Antilag = true
        toggle = true
            while _G.Antilag == true do
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
            wait(speedx)
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
            wait()
        end
    elseif toggle == true then
        _G.Antilag = false
        toggle = false
    end
  end
end

mouse.KeyDown:Connect(yo)
else
    local StarterGui = game:GetService("StarterGui")
 
    StarterGui:SetCore("SendNotification", {
        Title = "Error";
        Text = "...";
    })
end
