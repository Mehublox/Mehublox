local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local window = kavoUi.CreateLib("horfic","BloodTheme")
 
---Tabs
 
local Tab1 = window:NewTab("scrip")
local Tab1Section = Tab1:NewSection("acript")
local Tab2 = window:NewTab("gui")
local Tab2Section = Tab2:NewSection("Nothing")
local Tab3 = window:NewTab("Credits")
local Tab3Section = Tab3:NewSection("thatall")
local Tab3Section = Tab3:NewSection("mehubloxSC")

---buttons

Tab2Section:NewButton("Proxhub","Makes You Ie",function()
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


Tab2Section:NewButton("fly","Mak",function()
loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end)

Tab2Section:NewButton("horifc","Makes",function()
loadstring(game:HttpGet("https://paste.ee/r/GzZjj", true))()
end)
