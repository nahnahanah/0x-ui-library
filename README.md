# loadstring 
Need for the ui library to work
```lua
local library = loadstring(game.HttpGet(game, "https://raw.githubusercontent.com/nahnahanah/Open-Main-Source-0x/refs/heads/main/Open%20Main%20Source%200x"))()
```
# create Window 
create window,this can be a tab too
```lua
local w1 = library:Window("Title goes here")
```
# create buttons 
Add Buttons to the ui
```lua
w1:Button(
    "Button"
)
```
# create toggle button 
add toggle button to ui
```lua
w1:Toggle(
    "Toggle Button",
    "frz",
    false
)
```
# create slider 
add slider to ui
```lua
w1:Slider(
    "Slider",
    "WS",
    16,
    300
)
```
# create label text 
add label text to ui
```lua
w1:Label("0 x 3 7")
```
