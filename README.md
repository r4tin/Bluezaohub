-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local ImageLabel = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local Frame_3 = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local Frame_4 = Instance.new("Frame")
local UICorner_5 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local ImageButton = Instance.new("ImageButton")
local ImageButton_2 = Instance.new("ImageButton")
local ImageButton_3 = Instance.new("ImageButton")
local TextButton = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ImageLabel.Parent = ScreenGui
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.284328371, 0, 0.289002568, 0)
ImageLabel.Size = UDim2.new(0, 543, 0, 251)
ImageLabel.Image = "http://www.roblox.com/asset/?id=18539883920"

UICorner.Parent = ImageLabel

Frame.Parent = ImageLabel
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0570902377, 0, 0.0398406386, 0)
Frame.Size = UDim2.new(0, 100, 0, 22)

UICorner_2.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0900000036, 0, 0.318181813, 0)
TextLabel.Size = UDim2.new(0, 78, 0, 8)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Auto Farm"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

Frame_2.Parent = ImageLabel
Frame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.53591162, 0, 0.0398406386, 0)
Frame_2.Size = UDim2.new(0, 100, 0, 22)

UICorner_3.Parent = Frame_2

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0900000036, 0, 0.318181813, 0)
TextLabel_2.Size = UDim2.new(0, 78, 0, 8)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Players"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

Frame_3.Parent = ImageLabel
Frame_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(0.276243091, 0, 0.0398406386, 0)
Frame_3.Size = UDim2.new(0, 100, 0, 22)

UICorner_4.Parent = Frame_3

TextLabel_3.Parent = Frame_3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.109999999, 0, 0.318181813, 0)
TextLabel_3.Size = UDim2.new(0, 78, 0, 8)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Visual"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

Frame_4.Parent = ImageLabel
Frame_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(0.76795578, 0, 0.0398406386, 0)
Frame_4.Size = UDim2.new(0, 100, 0, 22)

UICorner_5.Parent = Frame_4

TextLabel_4.Parent = Frame_4
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.109999999, 0, 0.318181813, 0)
TextLabel_4.Size = UDim2.new(0, 78, 0, 8)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Config"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 14.000

ImageButton.Parent = ImageLabel
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.276243091, 0, 0.29880479, 0)
ImageButton.Size = UDim2.new(0, 228, 0, 100)
ImageButton.Image = "http://www.roblox.com/asset/?id=18539883920"

ImageButton_2.Parent = ImageLabel
ImageButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton_2.BorderSizePixel = 0
ImageButton_2.Position = UDim2.new(0.296500921, 0, 0.35059762, 0)
ImageButton_2.Size = UDim2.new(0, 207, 0, 74)
ImageButton_2.Image = "http://www.roblox.com/asset/?id=18539883920"

ImageButton_3.Parent = ImageLabel
ImageButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton_3.BorderSizePixel = 0
ImageButton_3.Position = UDim2.new(0.359116018, 0, 0.430278897, 0)
ImageButton_3.Size = UDim2.new(0, 135, 0, 31)
ImageButton_3.Image = "http://www.roblox.com/asset/?id=18539883920"

TextButton.Parent = ImageButton_3
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.140740737, 0, 0, 0)
TextButton.Size = UDim2.new(0, 96, 0, 23)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Carregar script"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextLabel_5.Parent = ScreenGui
TextLabel_5.BackgroundColor3 = Color3.fromRGB(42, 42, 42)
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.283582091, 0, 0.267263412, 0)
TextLabel_5.Size = UDim2.new(0, 543, 0, 17)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Bluezao HUB"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 14.000

-- Scripts:

local function BWBCC_fake_script() -- Frame_2.LocalScript 
	local script = Instance.new('LocalScript', Frame_2)

	
end
coroutine.wrap(BWBCC_fake_script)()
local function VUHSQ_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

		local u = script.Parent
	
	function skibidi()	
		game:GetService("Players").LocalPlayer:Kick("Negro com o cu cheio de esperma detectado.")
	end
	
	u.MouseButton1Down:Connect(skibidi)
end
coroutine.wrap(VUHSQ_fake_script)()
