# Unprefection-Library-UI

---
##Loadstring

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/ThanaphatSuporn/Unprefection-Library-UI/refs/heads/main/Source"))()
```

##Window

```lua
local Window = Library:Window("Title Here","Fonts here")
```
##Fonts (Leaves as emtpy to default)

```
PatrickHand
Arimo
Garamond
LuckiestGuy
```

##Button

```
Library:Button("Name",function()
  --Code
end)
```

##Toggle Button

```
Library:Toggle("Name",function(Enabled)
  --Code
end)
```
