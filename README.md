# Unprefection-Library-UI

Still unfinished

## Loadstring

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/ThanaphatSuporn/Unprefection-Library-UI/refs/heads/main/Source"))()
```
---

## Window

```lua
local Window = Library:Window("Title Here","Fonts here")
```
---

## Fonts (Leaves as emtpy to default)

```txt
PatrickHand
Arimo
Garamond
LuckiestGuy
```
---

## Button

```lua
Window:Button("Name",function()
  --Code
end)
```
---

## Toggle Button

```lua
Window:Toggle("Name",function(Enabled)
  --Code
end)
```

---

## Label

```lua
Window:Label("Text")
```
