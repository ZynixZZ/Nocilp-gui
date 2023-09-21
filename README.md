-- Designed & Scripted By ScousePotMongs --
-- Discord: Brother Omar#9562 --

local Noclip = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Title = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local FullNoclip = Instance.new("TextButton")
local Console = Instance.new("TextLabel")
 
Noclip.Name = "Noclip"
Noclip.Parent = game.CoreGui
Noclip.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = Noclip
Main.BackgroundColor3 = Color3.new(0, 0, 0)
Main.BackgroundTransparency = 0.25
Main.BorderColor3 = Color3.new(0.333333, 0, 1)
Main.BorderSizePixel = 2
Main.Position = UDim2.new(0.411496341, 0, 0.728652716, 0)
Main.Size = UDim2.new(0.17609489, 0, 0.151802659, 0)
Main.Active = true
Main.Draggable = true

Title.Name = "Title"
Title.Parent = Main
Title.BackgroundColor3 = Color3.new(0.333333, 0, 1)
Title.BackgroundTransparency = 0.25
Title.BorderColor3 = Color3.new(0.333333, 0, 1)
Title.BorderSizePixel = 2
Title.Position = UDim2.new(0.00217006868, 0, -0.405953586, 0)
Title.Size = UDim2.new(1, 0, 0.400000006, 0)

TextLabel.Parent = Title
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Size = UDim2.new(0.994818628, 0, 1, 0)
TextLabel.Font = Enum.Font.SourceSansItalic
TextLabel.Text = "NoClip"
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true

FullNoclip.Name = "FullNoclip"
FullNoclip.Parent = Main
FullNoclip.BackgroundColor3 = Color3.new(0.54902, 0.54902, 0.54902)
FullNoclip.BackgroundTransparency = 0.60000002384186
FullNoclip.BorderSizePixel = 0
FullNoclip.Position = UDim2.new(0, 0, 0.1875, 0)
FullNoclip.Size = UDim2.new(1, 0, 0.275000006, 0)
FullNoclip.Font = Enum.Font.SourceSans
FullNoclip.Text = "   Toggle Noclip                                                  >>"
FullNoclip.TextColor3 = Color3.new(1, 1, 1)
FullNoclip.TextScaled = true
FullNoclip.TextSize = 14
FullNoclip.TextWrapped = true
FullNoclip.TextXAlignment = Enum.TextXAlignment.Left

Console.Name = "Console"
Console.Parent = Main
Console.BackgroundColor3 = Color3.new(0.54902, 0.54902, 0.54902)
Console.BackgroundTransparency = 0.60000002384186
Console.Position = UDim2.new(0.00217006868, 0, 0.574999988, 0)
Console.Size = UDim2.new(1, 0, 0.275000006, 0)
Console.Font = Enum.Font.SourceSans
Console.Text = "   Status: Ready To Use "
Console.TextColor3 = Color3.new(0, 1, 0)
Console.TextScaled = true
Console.TextSize = 14
Console.TextWrapped = true
Console.TextXAlignment = Enum.TextXAlignment.Left

FullNoclip.MouseButton1Click:connect(function()
if Console.Text == "   Status: Ready To Use " then 
noclip = true 
Console.Text = "   Status: On "
        Console.TextColor3 = Color3.new(0,185,0)
game:GetService('RunService').Stepped:connect(function()
if noclip then
game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		         end
        end)
    elseif Console.Text == "   Status: On " then
        noclip = false
        Console.Text = "   Status: Off "
        Console.TextColor3 = Color3.new(170,0,0)
elseif Console.Text == "   Status: Off " then 
	noclip = true 
Console.Text = "   Status: On "
        Console.TextColor3 = Color3.new(0,185,0)
    end
end)
