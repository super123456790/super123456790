--if you die you will be kicked
game:GetService("RunService").RenderStepped:connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Health == 0 then
wait(1)
game.Players.LocalPlayer:Kick("lol noob")
end
end)
