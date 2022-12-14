local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local window = kavoUi.CreateLib("Main Title","BloodTheme")
 
---Tabs
 
local Tab1 = window:NewTab("Main")
local Tab1Section = Tab1:NewSection("Main")
local Tab2 = window:NewTab("Sup")
local Tab2Section = Tab2:NewSection("Nothing")
local Tab3 = window:NewTab("Credits")
local Tab3Section = Tab3:NewSection("thatall")
local Tab3Section = Tab3:NewSection("mehubloxSC")

---buttons

Tab1Section:NewButton("Proxhub","Makes You Ie",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/TrixAde/Proxima-Hub/main/Main.lua"))()
end)

Tab1Section:NewButton("Semigod","Ifk",function()
_G.GM = true -- Change true to false to disable, made by shitass / peke#7374
while _G.GM do task.wait()
local retardargs = {
["dir"] = Vector3.new(0,0,0), -- The pos doesnt matter
["origin"] = Vector3.new(0,0,0), -- The pos doesnt matter
["shooter"] = game:GetService("Players").LocalPlayer -- Change to any player if LP doesnt work
}
game:GetService'ReplicatedStorage'["damageMe"]:FireServer(-math.huge, retardargs)
end
end)

Tab1Section:NewButton("Infjump","Jsks",function()
local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)

Tab1Section:NewButton("Collect souls","M",function()
workspace:WaitForChild("Souls").DescendantAdded:Connect(function(v)
    if v:IsA("TouchTransmitter") and v.Parent:IsA("BasePart") and lp.Character and lp.Character:FindFirstChildWhichIsA("Humanoid") and lp.Character:FindFirstChildWhichIsA("Humanoid").RootPart then
        firetouchinterest(lp.Character:FindFirstChildWhichIsA("Humanoid").RootPart,v.Parent,0)
    end
end)
end)


Tab2Section:NewButton("Ghoric","Mak",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/typical-overk1ll/scripts/main/HorrificHousing",true))()
end)

Tab2Section:NewButton("horifc","Makes",function()
loadstring(game:HttpGet("https://paste.ee/r/GzZjj", true))()
end)
