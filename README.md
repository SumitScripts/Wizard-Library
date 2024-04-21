# Main Library Source
Main Source code of Wizard Library
```lua
local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wizard"))()
```

# Starter Gui Message 
```lua
wait(1.2)

game.StarterGui:SetCore("SendNotification", {

Title = "explain"; -- the title (ofc)

Text = "Note"; -- what the text says (ofc)

Icon = ""; -- the image if u want.

Duration = 5; -- how long the notification should in secounds

})
```
 # Window
-- Window or baseplate Make tab or section
```lua
local Window = Library:NewWindow("Window")
 ```
# Section
-- Section - Section Usefull you don't want ok?
```lua
local Section = Window:NewSection("SectionName")
 ```
# Button
-- Button Add Scripts in it

```lua
Section:CreateButton("ButtonName", function()
print("Clicked")
end)
```
# TextBox
-- TextBox You can make keysystem 
```lua
Section:CreateTextbox("TextBox", function(text)
        print(text)
end)
```
# Toggle
 
-- You Can Make Toggles
```lua
Section:CreateToggle("ToggleName", function(value)
print(value)
end)
```
# DropDown
 
-- DropDown is Same As TextBox But Different
```lua
Section:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)
print(text)
end)
```
# Slider
 
-- Slider You Can Make Speed Silder or jump Slider
```lua
Section:CreateSlider("Slider", 0, 100, 15, false, function(value)
print(value)
 end)
```
# Picker

-- Picker You Can make esp 
```lua
Section:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
print(value)
end)
```
# Credits

-- Wizard Ui By BloodBall
