# loadstring 
```lua
local library = loadstring(game.HttpGet(game, "https://raw.githubusercontent.com/nahnahanah/Open-Main-Source-0x/refs/heads/main/Open%20Main%20Source%200x"))()
```
# create Window 
```lua
local w1 = library:Window("Title goes here")
```
# create buttons 
```lua
w1:Button(
    "Print Hi",
    function()
        print("Hi")
    end
)
```
# create toggle button 
```lua
w1:Toggle(
    "Freeze",
    "frz",
    false,
    function(toggled)
        game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = toggled
    end
)
```
# create slider 
```lua
w1:Slider(
    "WalkSpeed",
    "WS",
    16,
    300,
    function(value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value
    end
)
```
# create label text 
