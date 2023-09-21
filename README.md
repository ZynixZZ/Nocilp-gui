-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local NoclipGui = Instance.new("ScreenGui")
local DragFrame = Instance.new("ImageLabel")
local NoclipFrame = Instance.new("ImageLabel")
local On = Instance.new("TextLabel")
local Noclip = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local Roundify = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local X = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local Frame = Instance.new("Frame")
local TextButton_3 = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

NoclipGui.Name = "NoclipGui"
NoclipGui.Parent = ScreenGui

DragFrame.Name = "DragFrame"
DragFrame.Parent = NoclipGui
DragFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DragFrame.BackgroundTransparency = 1.000
DragFrame.Position = UDim2.new(0.0757299438, 0, 0.0495575368, 0)
DragFrame.Size = UDim2.new(0.200000003, 0, 0.100000001, 0)
DragFrame.ScaleType = Enum.ScaleType.Slice
DragFrame.SliceCenter = Rect.new(100, 100, 100, 100)
DragFrame.SliceScale = 0.667

NoclipFrame.Name = "NoclipFrame"
NoclipFrame.Parent = DragFrame
NoclipFrame.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
NoclipFrame.BackgroundTransparency = 0.600
NoclipFrame.BorderSizePixel = 0
NoclipFrame.Position = UDim2.new(2.98172498, 0, 6.12007523, 0)
NoclipFrame.Size = UDim2.new(1.46938503, 0, 2.54469037, 0)
NoclipFrame.Visible = false
NoclipFrame.ImageColor3 = Color3.fromRGB(0, 0, 0)
NoclipFrame.ImageTransparency = 1.000
NoclipFrame.ScaleType = Enum.ScaleType.Slice
NoclipFrame.SliceCenter = Rect.new(100, 100, 100, 100)

On.Name = "On"
On.Parent = NoclipFrame
On.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
On.BackgroundTransparency = 1.000
On.Position = UDim2.new(0.758313119, 0, 0.669421434, 0)
On.Size = UDim2.new(0.241621062, 0, 0.330578566, 0)
On.Font = Enum.Font.SciFi
On.Text = "Noclip is off"
On.TextColor3 = Color3.fromRGB(255, 255, 255)
On.TextScaled = true
On.TextSize = 14.000
On.TextWrapped = true

Noclip.Name = "Noclip"
Noclip.Parent = NoclipFrame
Noclip.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Noclip.BackgroundTransparency = 1.000
Noclip.Position = UDim2.new(-0.00456204405, 0, 0.11937926, 0)
Noclip.Size = UDim2.new(1, 0, 0.672906339, 0)
Noclip.Font = Enum.Font.SciFi
Noclip.Text = "Noclip"
Noclip.TextColor3 = Color3.fromRGB(255, 255, 255)
Noclip.TextScaled = true
Noclip.TextSize = 14.000
Noclip.TextWrapped = true

TextButton.Parent = Noclip
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.828415871, 0, -0.406988889, 0)
TextButton.Size = UDim2.new(0, 86, 0, 42)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextSize = 50.000

Roundify.Name = "Roundify"
Roundify.Parent = NoclipFrame
Roundify.AnchorPoint = Vector2.new(0.5, 0.5)
Roundify.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Roundify.BackgroundTransparency = 1.000
Roundify.Position = UDim2.new(1.02292264, 0, 0.711400688, 0)
Roundify.Size = UDim2.new(2.04584527, 24, 1.42280149, 24)
Roundify.Image = "rbxassetid://3570695787"
Roundify.ImageColor3 = Color3.fromRGB(24, 24, 24)
Roundify.ImageTransparency = 1.000
Roundify.ScaleType = Enum.ScaleType.Slice
Roundify.SliceCenter = Rect.new(100, 100, 100, 100)
Roundify.SliceScale = 0.120

TextLabel.Parent = NoclipFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 255, 255)
TextLabel.BackgroundTransparency = 0.600
TextLabel.Position = UDim2.new(0, 0, -0.169147491, 0)
TextLabel.Size = UDim2.new(0, 493, 0, 46)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Noclip GUI v1.0.0"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 50.000

X.Name = "X"
X.Parent = NoclipFrame
X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
X.BackgroundTransparency = 1.000
X.Position = UDim2.new(0.81626308, 0, -0.169535726, 0)
X.Size = UDim2.new(0, 93, 0, 47)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(170, 0, 0)
X.TextSize = 50.000

TextButton_2.Parent = DragFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 255, 127)
TextButton_2.Position = UDim2.new(-0.378649771, 0, 5.79646063, 0)
TextButton_2.Size = UDim2.new(0, 167, 0, 80)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Open Noclip GUI"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 26.000

TextLabel_2.Parent = DragFrame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(65, 65, 65)
TextLabel_2.Position = UDim2.new(-0.378649771, 0, 8.67437649, 0)
TextLabel_2.Size = UDim2.new(0, 509, 0, 53)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Made By Shadow, Youtube: https://www.youtube.com/channel/UCNovziZnQUN5b3bGDYPTJ1Q"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 14.000

Frame.Parent = TextLabel_2
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0, 0, 1.03773582, 0)
Frame.Size = UDim2.new(0, 509, 0, 45)

TextButton_3.Parent = TextLabel_2
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BackgroundTransparency = 1.000
TextButton_3.Position = UDim2.new(0.917485237, 0, 1.05660379, 0)
TextButton_3.Size = UDim2.new(0, 42, 0, 19)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "OK"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 20.000

TextLabel_3.Parent = TextLabel_2
TextLabel_3.BackgroundColor3 = Color3.fromRGB(66, 66, 66)
TextLabel_3.Position = UDim2.new(0, 0, -0.490566045, 0)
TextLabel_3.Size = UDim2.new(0, 507, 0, 25)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Notification"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 20.000

-- Scripts:

local function GLEKL_fake_script() -- Noclip.NoScript 
	local script = Instance.new('LocalScript', Noclip)

	local function UpdateText(Obj,strl)
		Obj.Text = strl
	end
	local On = false
	local function SetOn()
		if On == false then
			On = true
		else
			On = false
		end
	end
	local Player = game.Players.LocalPlayer
	local Button = script.Parent
	
	Button.MouseButton1Up:Connect(function()
		SetOn()
		if On then
			UpdateText(Button, "Clip")
			UpdateText(script.Parent.Parent.On,"Noclip is On")
		
		else
		UpdateText(Button, "Noclip")
			UpdateText(script.Parent.Parent.On, "Noclip is off")
		end
		while On do
			wait()
			pcall(function()
				Player.Character.Humanoid:ChangeState(11)
			end)
		end
	end)
end
coroutine.wrap(GLEKL_fake_script)()
local function ZBOJNK_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
	
	
	
end
coroutine.wrap(ZBOJNK_fake_script)()
local function NMNOMDP_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local frame = script.Parent.Parent.NoclipFrame
	local open = false
	
	script.Parent.MouseButton1Click:Connect(function()
		if frame.Visible == false then
			frame.Visible = true
		end
	end)
	
end
coroutine.wrap(NMNOMDP_fake_script)()
local function ZULPZ_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
	
	
	
end
coroutine.wrap(ZULPZ_fake_script)()
local function YWWA_fake_script() -- NoclipGui.Dragify 
	local script = Instance.new('LocalScript', NoclipGui)

	local UIS = game:GetService("UserInputService")
	function dragify(Frame)
	    dragToggle = nil
	    local dragSpeed = 0.50
	    dragInput = nil
	    dragStart = nil
	    local dragPos = nil
	    function updateInput(input)
	        local Delta = input.Position - dragStart
	        local Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	        Frame:TweenPosition(Position,"Out","Quad",.5,true)
	    end
	    Frame.InputBegan:Connect(function(input)
	        if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) and UIS:GetFocusedTextBox() == nil then
	            dragToggle = true
	            dragStart = input.Position
	            startPos = Frame.Position
	            input.Changed:Connect(function()
	                if input.UserInputState == Enum.UserInputState.End then
	                    dragToggle = false
	                end
	            end)
	        end
	    end)
	    Frame.InputChanged:Connect(function(input)
	        if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
	            dragInput = input
	        end
		end)
		
		Frame.InputEnded:connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
				dragStart = nil
				dragInput = nil
			end
		end)
	    game:GetService("UserInputService").InputChanged:Connect(function(input)
	        if input == dragInput and dragToggle then
	            updateInput(input)
	        end
	    end)
	end
	
	dragify(script.Parent.DragFrame)
end
coroutine.wrap(YWWA_fake_script)()
