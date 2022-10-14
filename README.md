
game.Players.PlayerAdded:Connect(function(player)
        if player:GetRoleInGroup(14809209) == "Helperyklife" and "Developer" and "Co Owner" and "Owner" then
          game.Players.LocalPlayer:Kick("Admin Join")
           end
end)




local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Noobx Hub", "GrapeTheme")
local Tab = Window:NewTab("Teleport")
local Section = Tab:NewSection("-Teleport-")
Section:NewButton("Lobby", "Tp", function()
    print("Clicked")    
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-155.97119140625, 239.67654418945312, 113.08960723876953)}):Play()
end)
Section:NewButton("Run Quest", "Teleport quest", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-249.39117431640625, 239.479736328125, 427.82073974609375)}):Play()
end)
Section:NewButton("Gk Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(46.72754669189453, 239.77964782714844, -289.8209228515625)}):Play()
end)
Section:NewButton("Dribble Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-870.6663208007812, 256.85455322265625, -252.27044677734375)}):Play()
end)
Section:NewButton("Power Quest", "Tp", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(487.0538024902344, 706.873779296875, 30.567270278930664)}):Play()
end)
Section:NewButton("Stamina Quest", "Go to shop", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-263.9170837402344, 239.65492248535156, 107.51399993896484
)}):Play()
end)
Section:NewButton("Ice Cream Quest", "Go to shop", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(794.8023071289062, 286.2003173828125, -265.8494873046875)}):Play()
end)
local Tab = Window:NewTab("Cheat")
local Section = Tab:NewSection("Regen Energy")
Section:NewButton("Click Dog", "Regen", function()
    print("Clicked")
game:GetService("Players").LocalPlayer.Character.TPGaining.Get:FireServer()
end)
local Section = Tab:NewSection("Semi-click red(Increase Power Kick)")
Section:NewButton("Click Cat", "For fw", function()
    print("Clicked")
 pairs(game:GetService("Players").LocalPlayer.PlayerGui.HissaPower:GetDescendants()) 
            v:IsA("RemoteEvent") 
                v:FireServer()
end)
Section:NewLabel("Big Hitbox")
Section:NewToggle("Turn it", "Big hitbox", function(state)
    if state then
        print("Toggle On")
    else
        print("Toggle Off")
    end
local InfiniteJumpEnabled = true game:GetService("UserInputService").JumpRequest:connect(function() if InfiniteJumpEnabled then game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping") end end)
game.Players.LocalPlayer.UserId = "2205774994"
_G.HeadSize = 25 _G.Disabled = true game:GetService('RunService').RenderStepped:connect(function() if _G.Disabled then for i,v in next, game:GetService('Players'):GetPlayers() do if v.Name ~= game:GetService('Players').LocalPlayer.Name then pcall(function() v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize) v.Character.HumanoidRootPart.Transparency = 0.9 v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue") v.Character.HumanoidRootPart.Material = "Neon" v.Character.HumanoidRootPart.CanCollide = false end) end end end end)
end)

local Tab = Window:NewTab("Hack Farm")
local Section = Tab:NewSection("Run Quest")
Section:NewLabel("Get the quest first!and do it too!!!")
Section:NewLabel("you need to wait 1.5+ sec! and then click!")
Section:NewButton("Press To Skip Run", "Ez", function()
    print("Clicked")
wait(6)
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-270.1602783203125, 239.62811279296875, 460.0502624511719
)}):Play()
wait(6)
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-270.1602783203125, 239.62811279296875, 460.0502624511719
)}):Play()
end)
local Section = Tab:NewSection("Ice cream Quest Test")
Section:NewButton("Firstclickhere", "", function()
    print("Clicked")
    local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(-940.8973999023438, 256.8545227050781, 81.0558090209961)}):Play()
    
end)
Section:NewButton("Then click here", "", function()
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(795.686767578125, 286.2003173828125, -263.8690185546875)}):Play()
end)
local Section = Tab:NewSection("Dribble Farm")
local Section = Tab:NewSection("you need to get the quest first")
Section:NewButton("noob", "ButtonInfo", function()
    print("Clicked")
--Drible
getgenv().test = true

while test do

wait()

if game:GetService("Players").LocalPlayer.PlayerGui:FindFirstChild("GetDribbleQuestStuff") ~= nil then

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game:GetService("Workspace").Map.SnowyArea.DRIBLLETOUCHPART.CFrame

end

end
end)
local Tab = Window:NewTab("More")
local Section = Tab:NewSection("Rejoin")
Section:NewButton("Click", "rejoin", function()
    print("Clicked")
local ts = game:GetService("TeleportService")

local p = game:GetService("Players").LocalPlayer

 

ts:Teleport(game.PlaceId, p)
end)
local Section = Tab:NewSection("Nothing")
Section:NewButton("Don't click", "", function()
    print("Clicked")
game.Players.LocalPlayer:Kick('You got ban!!')
end)
Section:NewButton("Auto Farm Lv Money", "GG", function()
    print("Clicked")

while true do wait(1)
for i, v in pairs(game:GetService("Workspace").IceCreamGuy:GetDescendants()) do
                       if v:FindFirstChild("ProximityPrompt") then
                            fireproximityprompt(v.ProximityPrompt)
                       end
end
wait(.5)
game:GetService("Players").LocalPlayer.PlayerGui.MoneyAndEXPQuest.MainFrame.Frame.Agree.Visible = true
wait(.1)
local getbox = game:GetService("Workspace").GettingBoxPart
local putbox =  game:GetService("Workspace").PUTTINGBoxPart
local humanoidroot = game.Players.LocalPlayer.Character.HumanoidRootPart

firetouchinterest(humanoidroot,getbox,0)
wait(.1)
firetouchinterest(humanoidroot,getbox,1)
end
end)
Section:NewButton("UnTackle", "ButtonInfo", function() 
    print("Clicked")
game.Players.LocalPlayer.Character.Tackle:Destroy()
end)
Section:NewButton("Prestige Guy", "ButtonInfo", function() 
    print("Clicked")
local TweenService = game:GetService("TweenService")
local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(1, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0), 
{CFrame = CFrame.new(745.6356201171875, 376.3001403808594, -1038.4832763671875)}):Play()
end)


































