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
Section:CreateButton("Button", function()
print("HI")
end)
```
─────────────────────

Creating a textbox.
```
Section:CreateTextbox("TextBox", function(text)
        print(text)
end)
```
─────────────────────

Creating a dropdown.
```
Section:CreateDropdown("DropDown", {"Hello", "World", "Hello World"}, 2, function(text)
print(text)
end)
```
─────────────────────

Creating a slider.
```
Section:CreateSlider("Slider", 0, 100, 15, false, function(value)
print(value)
 end)
```
─────────────────────

Creating a color picker.
```
Section:CreateColorPicker("Picker", Color3.new(255, 255, 255), function(value)
print(value)
end)
```
─────────────────────
# Curious how to use the library?
In order to make a script using this UI library, you have to do these steps.

1. At the first line of your script insert the Library loadstring.
2. Create a window using the preset.
3. Add a section to the window with the preset.
4. Create a button or anything of your choice, remember to change Main in the beggining of the preset to what you set the name of your Section. In the presets it's just Section, you don't need to change that.

After you've done everything your script hub should now be good to go!
