-- Gui to Lua
-- Version: 3.2

-- Instances:

local Whitelist = Instance.new("ScreenGui")
local RezxHub = Instance.new("ScrollingFrame")
local Tab = Instance.new("Frame")
local RezxHubText = Instance.new("TextLabel")
local CheckText = Instance.new("TextLabel")
local Wait = Instance.new("TextLabel")
local Line = Instance.new("Frame")

--Properties:

Whitelist.Name = "Whitelist"
Whitelist.Parent = game.CoreGui
Whitelist.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

RezxHub.Name = "RezxHub"
RezxHub.Parent = Whitelist
RezxHub.Active = true
RezxHub.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RezxHub.BackgroundTransparency = 1.000
RezxHub.Position = UDim2.new(0.398923844, 0, 0.388467371, 0)
RezxHub.Size = UDim2.new(0, 263, 0, 24)
RezxHub.BottomImage = ""
RezxHub.CanvasSize = UDim2.new(0, 0, 0, 0)
RezxHub.MidImage = ""
RezxHub.ScrollBarThickness = 0
RezxHub.ScrollingEnabled = false
RezxHub.TopImage = ""

Tab.Name = "Tab"
Tab.Parent = RezxHub
Tab.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Tab.BorderColor3 = Color3.fromRGB(25, 25, 25)
Tab.Size = UDim2.new(0, 263, 0, 106)

RezxHubText.Name = "RezxHubText"
RezxHubText.Parent = Tab
RezxHubText.Active = true
RezxHubText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RezxHubText.BackgroundTransparency = 1.000
RezxHubText.Position = UDim2.new(0.117870726, 0, 0, 0)
RezxHubText.Size = UDim2.new(0, 200, 0, 24)
RezxHubText.Font = Enum.Font.Sarpanch
RezxHubText.Text = "REZX HUB"
RezxHubText.TextColor3 = Color3.fromRGB(255, 255, 255)
RezxHubText.TextSize = 14.000

CheckText.Name = "CheckText"
CheckText.Parent = Tab
CheckText.Active = true
CheckText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CheckText.BackgroundTransparency = 1.000
CheckText.Position = UDim2.new(0.117870726, 0, 0.264150947, 0)
CheckText.Size = UDim2.new(0, 200, 0, 50)
CheckText.Font = Enum.Font.Sarpanch
CheckText.Text = ""
CheckText.TextColor3 = Color3.fromRGB(85, 170, 255)
CheckText.TextSize = 14.000

Wait.Name = "Wait"
Wait.Parent = Tab
Wait.Active = true
Wait.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Wait.BackgroundTransparency = 1.000
Wait.Position = UDim2.new(0.117870726, 0, 0.735849082, 0)
Wait.Size = UDim2.new(0, 200, 0, 28)
Wait.Font = Enum.Font.Sarpanch
Wait.Text = "NOT SUPPORT SOME EXECUTOR"
Wait.TextColor3 = Color3.fromRGB(255, 255, 255)
Wait.TextSize = 13.000

Line.Name = "Line"
Line.Parent = Tab
Line.Active = true
Line.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Line.BorderColor3 = Color3.fromRGB(85, 85, 255)
Line.Position = UDim2.new(0, 0, 0.735849082, 0)
Line.Size = UDim2.new(0, 263, 0, 0)

-- Scripts:

	local script = Instance.new('LocalScript', RezxHub)

	local RezxHub = script.Parent
	local Tab = script.Parent.Tab
	local Line = script.Parent.Tab.Line
	local RezxHubText = script.Parent.Tab.RezxHubText
	local CheckText = script.Parent.Tab.CheckText
	local waitText = script.Parent.Tab.Wait
	
	if game.PlaceId == 2753915549 then -- Not A New World
		
		RezxHub:TweenSize(UDim2.new(0, 263,0, 76), "Out", "Sine", 0.5)
		wait(1)
		CheckText.Text = ("Checking")
		wait(1)
		CheckText.Text = ("Checking.")
		wait(1)
		CheckText.Text = ("Checking..")
		wait(1)
		CheckText.Text = ("Checking...")
		RezxHub:TweenSize(UDim2.new(0, 263,0, 109), "Out", "Sine", 0.5)
		wait(2.5)
		CheckText.Text = ("BLOXFRUIT PAID (STARTER WORLD)")
		wait(2)
		RezxHub:TweenSize(UDim2.new(0, 263,0, 23), "Out", "Sine", 0.5)
		wait(1)
		loadstring(game:HttpGet("https://raw.githubusercontent.com/RezxHub/RezxHubBloxFruit/main/README.md"))()
		RezxHub:TweenSize(UDim2.new(0, 0,0, 23), "Out", "Sine", 0.5)
		wait(3)
		RezxHub:Destroy()
	end
	
	if game.PlaceId == 4442272183 then -- New World
		
		RezxHub:TweenSize(UDim2.new(0, 263,0, 76), "Out", "Sine", 0.5)
		wait(1)
		CheckText.Text = ("Checking")
		wait(1)
		CheckText.Text = ("Checking.")
		wait(1)
		CheckText.Text = ("Checking..")
		wait(1)
		CheckText.Text = ("Checking...")
		RezxHub:TweenSize(UDim2.new(0, 263,0, 109), "Out", "Sine", 0.5)
		wait(2.5)
		CheckText.Text = ("BLOXFRUIT PAID (NEW WORLD)")
		wait(2)
		RezxHub:TweenSize(UDim2.new(0, 263,0, 23), "Out", "Sine", 0.5)
		wait(1)
		loadstring(game:HttpGet("https://raw.githubusercontent.com/RezxHub/RezxHubBloxFruit/main/README.md"))()
		RezxHub:TweenSize(UDim2.new(0, 0,0, 23), "Out", "Sine", 0.5)
		wait(3)
		RezxHub:Destroy()
	end
