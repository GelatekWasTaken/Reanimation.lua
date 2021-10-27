_G.Velocity = Vector3.new(-17.743, 0, -17.743)
_G.ReanimationType = "Simple"

-- Godmode Settings (Will not work on simple/fling)
_G.FlingBlock = true
_G.FlingBlockTransparency = 0.5
_G.HighlightFlingBlock = true 
_G.FlingBlockPosition = "Torso"
_G.HighlightFlingBlockColor = Color3.fromRGB(0,0,0)

loadstring(game:HttpGet("https://raw.githubusercontent.com/GelatekWasTaken/Reanimation.lua/main/Reanimate.lua"))()
