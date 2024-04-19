# $ Project Library

# Project Library Is Maded By A Mobile for A Mobile
# UI LIBRARY
```lua
loadstring(game:HttpGet("[https://pastebin.com/raw/GTZYwsPY](https://raw.githubusercontent.com/noGlxcka/Project-Library/main/UiLibrary)"))()
```

# TITLE
```lua
local uiLibrary = UI.new("Project X")
```
# TABS
```lua
-- Add tabs
local tab1 = uiLibrary.addTab("Tab 1")
```
# BUTTON
```lua
local button2 = tab2.addButton("Button 2", function()
    print("Button 2 clicked!")
end
```
# TOGGLE
```lua 
local toggle1 = uiLibrary.addToggle(tab1, "Toggle 1", function(state)
    if state then
        print("Toggle 1 is on")
    else
        print("Toggle 1 is off")
    end
end)
```
# DROPDOWN
```lua
-- Add dropdown to tab1
local dropdown1 = uiLibrary.addDropdown(tab1, {"Option 1", "Option 2", "Option 3"}, "Select an option", function(selectedOption)
    if selectedOption == "Option 1" then
        print("hi")
    elseif selectedOption == "Option 2" then
        print("hello")
    elseif selectedOption == "Option 3" then
        print("Greetings!")
    end
end)
```
# THIS UI MAY HAVE AN ERROR AS IT IS ONLY SIMPLE.
