# Reanimation For Roblox

Docs:



# Basic Stuff

# `_G.Reanimated`
- Will always trigger when your reanimated or not, for example:
  - `repeat wait() until _G.Reanimated == true`

# `_G.ReanimationType` 
- There are currently 3 Reanims All of them are for R6.
  - `_G.ReanimationType = "Simple"` Simple Reanimate No Fling
  - `_G.ReanimationType = "Fling"` Simple Reanimate Torso Fling
  - `_G.ReanimationType = "PDeath" ` Permament Death Reanimate

# `_G.Velocity`
- Allows you to change your player velocity, for example
  - `_G.Velocity = Vector3.new(36,0,0)`

# Permament Death

# `_G.FlingBlock` 
  - Enables Fling 
    - `_G.FlingBlock = true`

# `_G.FlingBlockTransparency` 
  - Allows you to change fling block transparency
    - `_G.FlingBlockTransparency = 0.5`

# `_G.HighlightFlingBlock` 
  - Allows you to highlight the fling block
    - `_G.HighlightFlingBlock = true`

# `_G.FlingBlockPosition` 
  - Allows you to change position of root part (Only Bodyparts(not accessories) for now)
    - `_G.FlingBlockPosition = "Torso"`

# `_G.HighlightFlingBlockColor`
  - Changes The Block Highlighting color
    - `_G.HighlightFlingBlockColor = Color3.fromRGB(0,0,0)`


# Credits
- Gelatek: All Of Stuff
- Mizt: Helped with permament death
