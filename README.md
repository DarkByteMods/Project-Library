# $ Project Library

# Project Library Is Maded By A Mobile for A Mobile,It is a simple Ui Library that has toggle,button,textbox, soon we will add more

```lua
local uiLibrary = UI.new("Project X")
```
```lua
-- Add tabs
local tab1 = uiLibrary.addTab("Tab 1")
```
```lua
local button2 = tab2.addButton("Button 2", function()
    print("Button 2 clicked!")
end
```
```lua
local toggle1 = uiLibrary.addToggle(tab1, "Toggle 1", function(state)
    if state then
        print("Toggle 1 is on")
    else
        print("Toggle 1 is off")
    end
end)
```
