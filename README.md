--troll script
--screengui
local ScreenGui = Instance.new("ScreenGui")
local background = Instance.new("Frame")
local TextButton = Instance.new("TextButton")

--script

ScreenGui.Parent = game.StarterGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

background.Name = "background"
background.Parent = ScreenGui
background.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
background.BorderSizePixel = 0
background.Size = UDim2.new(0, 1410, 0, 678)
background.Style = Enum.FrameStyle.RobloxRound

TextButton.Parent = background
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.475439489, 0, 0.395886779, 0)
TextButton.Size = UDim2.new(0, 210, 0, 90)
TextButton.Style = Enum.ButtonStyle.RobloxButtonDefault
TextButton.Font = Enum.Font.PatrickHand
TextButton.Text = "start script"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
TextButton.MouseButton1Down:connect(function()
	game.Players.LocalPlayer:Kick("stop hack noob")
end)
