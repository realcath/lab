# Catlib

- Load UI

```lua
local CatLib = loadstring(game:HttpGet("https://raw.githubusercontent.com/realcath/lab/refs/heads/main/cat/libary/catlibz"))()
```

-

- Create Window

```lua
local window = CatLib:CreateWindow({
	Title = "My Hub",
	Subtitle = "By zerozxk",
	Icon = "rbxassetid://",
	Size = UDim2.new(0, 500, 0, 300),
	FloatingButton = {
		Enabled = true,
		Icon = "rbxassetid://",
		Size = UDim2.new(0, 60, 0, 60),
		Position = UDim2.new(0, 20, 0, 100),
		Shape = "Square"
	}
})
```

-

- Create Toggle

```lua
tab1:AddToggle({
	Name = "Toggle",
	Description = "My Toggle",
	Default = false,
	Callback = function(value)
	end
})
```

-

- Create ToggleConfirmation
