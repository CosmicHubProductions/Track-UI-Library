# Track UI Library
The best and the most simple UI Library for roblox exploits!

I've decided to make my own UI Library for people who wish to make script hubs on roblox!

─────────────────────

Loading the library.
```
local Library = loadstring(Game:HttpGet("https://raw.githubusercontent.com/CosmicHubProductions/Track-UI-Library/refs/heads/main/lua.txt"))()
```
─────────────────────

Creating a window.
```
local MainWindow = Library:NewWindow("Main")
```
─────────────────────

Creating a section.
```
local Section = MainWindow:NewSection("Section")
```
─────────────────────

Creating a button.
```
Main:CreateButton("Button", function()
print("HI")
end)
```
─────────────────────

Creating a textbox.
```
Main:CreateTextbox("TextBox", function(text)
        print(text)
end)
```
─────────────────────

Creating a dropdown.
```
Main:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)
print(text)
end)
```
─────────────────────

Creating a slider.
```
Main:CreateSlider("Slider", 0, 100, 15, false, function(value)
print(value)
 end)
```
─────────────────────

Creating a color picker.
```
Cheats:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
print(value)
end)
```
