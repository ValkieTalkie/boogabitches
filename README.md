-- Objects
 
local ScreenGui = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local Booga = Instance.new("Frame")
local BoogaTop = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local Exit = Instance.new("TextButton")
local Speed = Instance.new("TextButton")
local SpeedBind = Instance.new("TextBox")
local AutoPickUp = Instance.new("TextButton")
local AutoPickUpBind = Instance.new("TextBox")
local AutoBreak = Instance.new("TextButton")
local Breakkey = Instance.new("TextBox")
local InfinityChest = Instance.new("TextButton")
local GodHut = Instance.new("TextButton")
local RevizV2 = Instance.new("TextButton")
local AutoEatbtn = Instance.new("TextButton")
local VoidTpbtn = Instance.new("TextButton")
local RemoveAllEffectsbtn = Instance.new("TextButton")
local CraftAnyItem = Instance.new("TextButton")
local CraftItem = Instance.new("TextBox")
local ESPbtn = Instance.new("TextButton")
local DropAllItemsbtn = Instance.new("TextButton")
local RemoveRainbtn = Instance.new("TextButton")
local TpSpambtn = Instance.new("TextButton")
local AutoCampfirebtn = Instance.new("TextButton")
local AutoWallTrapbtn = Instance.new("TextButton")
local AutoEatFoodNamekb = Instance.new("TextBox")
local TpSpamPlayerNamekb = Instance.new("TextBox")
local DropAllItemsItemNamekb = Instance.new("TextBox")
local DropAllItemskb = Instance.new("TextBox")
local AutoEatkb = Instance.new("TextBox")
local Recipes = Instance.new("TextButton")
local Credits = Instance.new("TextLabel")
local Booga2 = Instance.new("Frame")
local BoogaTop2 = Instance.new("Frame")
local Exit2 = Instance.new("TextButton")
local EmeraldHelmet = Instance.new("TextButton")
local EmeraldDivider = Instance.new("Frame")
local EmeraldChestplate = Instance.new("TextButton")
local EmeraldPick = Instance.new("TextButton")
local EmeraldGreaves = Instance.new("TextButton")
local EmeraldBlade = Instance.new("TextButton")
local EmeraldAxe = Instance.new("TextButton")
local EmeraldBag = Instance.new("TextButton")
local VoidShroud = Instance.new("TextButton")
local EmeraldDivider2 = Instance.new("Frame")
local GodDivider = Instance.new("Frame")
local GodDivider2 = Instance.new("Frame")
local GodRock = Instance.new("TextButton")
local GodHalo = Instance.new("TextButton")
local GodChestplate = Instance.new("TextButton")
local GodAxe = Instance.new("TextButton")
local GodBag = Instance.new("TextButton")
local GodLegs = Instance.new("TextButton")
local GodPick = Instance.new("TextButton")
local VoidChestplate = Instance.new("TextButton")
local VoidDivider2 = Instance.new("Frame")
local VoidDivider = Instance.new("Frame")
local VoidBag = Instance.new("TextButton")
local VoidGreaves = Instance.new("TextButton")
local OOFHorn = Instance.new("TextButton")
 
-- Properties
 
ScreenGui.Parent = game.CoreGui
 
Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Open.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
Open.BorderSizePixel = 2
Open.Position = UDim2.new(0.433682919, 0, 0.0281030443, 0)
Open.Size = UDim2.new(0, 151, 0, 26)
Open.Font = Enum.Font.SourceSansSemibold
Open.Text = "Open/Close"
Open.TextColor3 = Color3.new(1, 1, 1)
Open.TextScaled = true
Open.TextSize = 14
Open.TextWrapped = true
 
Booga.Name = "Booga"
Booga.Parent = ScreenGui
Booga.Active = true
Booga.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Booga.BackgroundTransparency = 0.30000001192093
Booga.BorderColor3 = Color3.new(1, 0, 0.498039)
Booga.BorderSizePixel = 2
Booga.Position = UDim2.new(1.70000005, 1, 1.70000005, 1)
Booga.Size = UDim2.new(0, 474, 0, 468)
 
BoogaTop.Name = "BoogaTop"
BoogaTop.Parent = Booga
BoogaTop.Active = true
BoogaTop.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
BoogaTop.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
BoogaTop.BorderSizePixel = 2
BoogaTop.Size = UDim2.new(0, 474, 0, 27)
 
Title.Name = "Title"
Title.Parent = BoogaTop
Title.Active = true
Title.BackgroundColor3 = Color3.new(1, 1, 1)
Title.BackgroundTransparency = 1
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.00210970454, 0, 0, 0)
Title.Size = UDim2.new(0, 473, 0, 27)
Title.Font = Enum.Font.SourceSansSemibold
Title.Text = "Booga Bitches Revamp V2"
Title.TextColor3 = Color3.new(1, 1, 1)
Title.TextScaled = true
Title.TextSize = 14
Title.TextWrapped = true
 
Exit.Name = "Exit"
Exit.Parent = Booga
Exit.BackgroundColor3 = Color3.new(0.901961, 0.380392, 0.380392)
Exit.BorderSizePixel = 0
Exit.Position = UDim2.new(0.915611804, 0, 0.00854700897, 0)
Exit.Size = UDim2.new(0, 28, 0, 19)
Exit.Font = Enum.Font.SourceSans
Exit.Text = "X"
Exit.TextColor3 = Color3.new(1, 1, 1)
Exit.TextSize = 14
 
Speed.Name = "Speed"
Speed.Parent = Booga
Speed.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Speed.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
Speed.BorderSizePixel = 2
Speed.Position = UDim2.new(0.035864979, 0, 0.0726495758, 0)
Speed.Size = UDim2.new(0, 116, 0, 27)
Speed.Font = Enum.Font.SourceSansSemibold
Speed.Text = "Speed"
Speed.TextColor3 = Color3.new(1, 1, 1)
Speed.TextScaled = true
Speed.TextSize = 14
Speed.TextWrapped = true
 
SpeedBind.Name = "SpeedBind"
SpeedBind.Parent = Booga
SpeedBind.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
SpeedBind.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
SpeedBind.BorderSizePixel = 2
SpeedBind.Position = UDim2.new(0.035864979, 0, 0.151709408, 0)
SpeedBind.Size = UDim2.new(0, 116, 0, 27)
SpeedBind.Font = Enum.Font.SourceSans
SpeedBind.Text = "Keybind"
SpeedBind.TextColor3 = Color3.new(1, 1, 1)
SpeedBind.TextScaled = true
SpeedBind.TextSize = 14
SpeedBind.TextWrapped = true
 
AutoPickUp.Name = "AutoPickUp"
AutoPickUp.Parent = Booga
AutoPickUp.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoPickUp.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoPickUp.BorderSizePixel = 2
AutoPickUp.Position = UDim2.new(0.356540084, 0, 0.0747863278, 0)
AutoPickUp.Size = UDim2.new(0, 116, 0, 27)
AutoPickUp.Font = Enum.Font.SourceSansSemibold
AutoPickUp.Text = "Auto Pickup"
AutoPickUp.TextColor3 = Color3.new(1, 1, 1)
AutoPickUp.TextScaled = true
AutoPickUp.TextSize = 14
AutoPickUp.TextWrapped = true
 
AutoPickUpBind.Name = "AutoPickUpBind"
AutoPickUpBind.Parent = Booga
AutoPickUpBind.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoPickUpBind.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoPickUpBind.BorderSizePixel = 2
AutoPickUpBind.Position = UDim2.new(0.356540084, 0, 0.151709408, 0)
AutoPickUpBind.Size = UDim2.new(0, 116, 0, 27)
AutoPickUpBind.Font = Enum.Font.SourceSans
AutoPickUpBind.Text = "Keybind"
AutoPickUpBind.TextColor3 = Color3.new(1, 1, 1)
AutoPickUpBind.TextScaled = true
AutoPickUpBind.TextSize = 14
AutoPickUpBind.TextWrapped = true
 
AutoBreak.Name = "AutoBreak"
AutoBreak.Parent = Booga
AutoBreak.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoBreak.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoBreak.BorderSizePixel = 2
AutoBreak.Position = UDim2.new(0.700421929, 0, 0.0726495758, 0)
AutoBreak.Size = UDim2.new(0, 116, 0, 27)
AutoBreak.Font = Enum.Font.SourceSansSemibold
AutoBreak.Text = "Autobreak"
AutoBreak.TextColor3 = Color3.new(1, 1, 1)
AutoBreak.TextScaled = true
AutoBreak.TextSize = 14
AutoBreak.TextWrapped = true
 
Breakkey.Name = "Breakkey"
Breakkey.Parent = Booga
Breakkey.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Breakkey.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
Breakkey.BorderSizePixel = 2
Breakkey.Position = UDim2.new(0.700421929, 0, 0.149572656, 0)
Breakkey.Size = UDim2.new(0, 116, 0, 27)
Breakkey.Font = Enum.Font.SourceSans
Breakkey.Text = "Keybind"
Breakkey.TextColor3 = Color3.new(1, 1, 1)
Breakkey.TextScaled = true
Breakkey.TextSize = 14
Breakkey.TextWrapped = true
 
InfinityChest.Name = "InfinityChest"
InfinityChest.Parent = Booga
InfinityChest.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
InfinityChest.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
InfinityChest.BorderSizePixel = 2
InfinityChest.Position = UDim2.new(0.035864979, 0, 0.405982912, 0)
InfinityChest.Size = UDim2.new(0, 116, 0, 27)
InfinityChest.Font = Enum.Font.SourceSansSemibold
InfinityChest.Text = "Infinity Chest (q)"
InfinityChest.TextColor3 = Color3.new(1, 1, 1)
InfinityChest.TextScaled = true
InfinityChest.TextSize = 14
InfinityChest.TextWrapped = true
 
GodHut.Name = "GodHut"
GodHut.Parent = Booga
GodHut.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodHut.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodHut.BorderSizePixel = 2
GodHut.Position = UDim2.new(0.360759497, 0, 0.405982912, 0)
GodHut.Size = UDim2.new(0, 116, 0, 27)
GodHut.Font = Enum.Font.SourceSansSemibold
GodHut.Text = "Godhut (g)"
GodHut.TextColor3 = Color3.new(1, 1, 1)
GodHut.TextScaled = true
GodHut.TextSize = 14
GodHut.TextWrapped = true
 
RevizV2.Name = "RevizV2"
RevizV2.Parent = Booga
RevizV2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
RevizV2.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
RevizV2.BorderSizePixel = 2
RevizV2.Position = UDim2.new(0.700421929, 0, 0.247863248, 0)
RevizV2.Size = UDim2.new(0, 116, 0, 27)
RevizV2.Font = Enum.Font.SourceSansSemibold
RevizV2.Text = "Reviz Admin"
RevizV2.TextColor3 = Color3.new(1, 1, 1)
RevizV2.TextScaled = true
RevizV2.TextSize = 14
RevizV2.TextWrapped = true
 
AutoEatbtn.Name = "AutoEatbtn"
AutoEatbtn.Parent = Booga
AutoEatbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoEatbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoEatbtn.BorderSizePixel = 2
AutoEatbtn.Position = UDim2.new(0.702531695, 0, 0.566239357, 0)
AutoEatbtn.Size = UDim2.new(0, 116, 0, 27)
AutoEatbtn.Font = Enum.Font.SourceSansSemibold
AutoEatbtn.Text = "Auto Eat"
AutoEatbtn.TextColor3 = Color3.new(1, 1, 1)
AutoEatbtn.TextScaled = true
AutoEatbtn.TextSize = 14
AutoEatbtn.TextWrapped = true
 
VoidTpbtn.Name = "VoidTpbtn"
VoidTpbtn.Parent = Booga
VoidTpbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidTpbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidTpbtn.BorderSizePixel = 2
VoidTpbtn.Position = UDim2.new(0.700421929, 0, 0.329059809, 0)
VoidTpbtn.Size = UDim2.new(0, 116, 0, 27)
VoidTpbtn.Font = Enum.Font.SourceSansSemibold
VoidTpbtn.Text = "Void TP"
VoidTpbtn.TextColor3 = Color3.new(1, 1, 1)
VoidTpbtn.TextScaled = true
VoidTpbtn.TextSize = 14
VoidTpbtn.TextWrapped = true
 
RemoveAllEffectsbtn.Name = "RemoveAllEffectsbtn"
RemoveAllEffectsbtn.Parent = Booga
RemoveAllEffectsbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
RemoveAllEffectsbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
RemoveAllEffectsbtn.BorderSizePixel = 2
RemoveAllEffectsbtn.Position = UDim2.new(0.702531636, 0, 0.410256416, 0)
RemoveAllEffectsbtn.Size = UDim2.new(0, 116, 0, 27)
RemoveAllEffectsbtn.Font = Enum.Font.SourceSansSemibold
RemoveAllEffectsbtn.Text = "Remove All Effects"
RemoveAllEffectsbtn.TextColor3 = Color3.new(1, 1, 1)
RemoveAllEffectsbtn.TextScaled = true
RemoveAllEffectsbtn.TextSize = 14
RemoveAllEffectsbtn.TextWrapped = true
 
CraftAnyItem.Name = "CraftAnyItem"
CraftAnyItem.Parent = Booga
CraftAnyItem.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
CraftAnyItem.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
CraftAnyItem.BorderSizePixel = 2
CraftAnyItem.Position = UDim2.new(0.0421940945, 0, 0.232905984, 0)
CraftAnyItem.Size = UDim2.new(0, 116, 0, 27)
CraftAnyItem.Font = Enum.Font.SourceSansSemibold
CraftAnyItem.Text = "Craft Any Item"
CraftAnyItem.TextColor3 = Color3.new(1, 1, 1)
CraftAnyItem.TextScaled = true
CraftAnyItem.TextSize = 14
CraftAnyItem.TextWrapped = true
 
CraftItem.Name = "CraftItem"
CraftItem.Parent = Booga
CraftItem.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
CraftItem.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
CraftItem.BorderSizePixel = 2
CraftItem.Position = UDim2.new(0.035864979, 0, 0.316239327, 0)
CraftItem.Size = UDim2.new(0, 116, 0, 27)
CraftItem.Font = Enum.Font.SourceSans
CraftItem.Text = "Item Name"
CraftItem.TextColor3 = Color3.new(1, 1, 1)
CraftItem.TextScaled = true
CraftItem.TextSize = 14
CraftItem.TextWrapped = true
 
ESPbtn.Name = "ESPbtn"
ESPbtn.Parent = Booga
ESPbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
ESPbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
ESPbtn.BorderSizePixel = 2
ESPbtn.Position = UDim2.new(0.364978909, 0, 0.487179488, 0)
ESPbtn.Size = UDim2.new(0, 116, 0, 27)
ESPbtn.Font = Enum.Font.SourceSansSemibold
ESPbtn.Text = "ESP"
ESPbtn.TextColor3 = Color3.new(1, 1, 1)
ESPbtn.TextScaled = true
ESPbtn.TextSize = 14
ESPbtn.TextWrapped = true
 
DropAllItemsbtn.Name = "DropAllItemsbtn"
DropAllItemsbtn.Parent = Booga
DropAllItemsbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
DropAllItemsbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
DropAllItemsbtn.BorderSizePixel = 2
DropAllItemsbtn.Position = UDim2.new(0.0337552726, 0, 0.56410259, 0)
DropAllItemsbtn.Size = UDim2.new(0, 116, 0, 27)
DropAllItemsbtn.Font = Enum.Font.SourceSansSemibold
DropAllItemsbtn.Text = "Drop All Items"
DropAllItemsbtn.TextColor3 = Color3.new(1, 1, 1)
DropAllItemsbtn.TextScaled = true
DropAllItemsbtn.TextSize = 14
DropAllItemsbtn.TextWrapped = true
 
RemoveRainbtn.Name = "RemoveRainbtn"
RemoveRainbtn.Parent = Booga
RemoveRainbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
RemoveRainbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
RemoveRainbtn.BorderSizePixel = 2
RemoveRainbtn.Position = UDim2.new(0.035864979, 0, 0.482905984, 0)
RemoveRainbtn.Size = UDim2.new(0, 116, 0, 27)
RemoveRainbtn.Font = Enum.Font.SourceSansSemibold
RemoveRainbtn.Text = "Remove Rain"
RemoveRainbtn.TextColor3 = Color3.new(1, 1, 1)
RemoveRainbtn.TextScaled = true
RemoveRainbtn.TextSize = 14
RemoveRainbtn.TextWrapped = true
 
TpSpambtn.Name = "TpSpambtn"
TpSpambtn.Parent = Booga
TpSpambtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
TpSpambtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
TpSpambtn.BorderSizePixel = 2
TpSpambtn.Position = UDim2.new(0.362869203, 0, 0.241452992, 0)
TpSpambtn.Size = UDim2.new(0, 116, 0, 27)
TpSpambtn.Font = Enum.Font.SourceSansSemibold
TpSpambtn.Text = "TP Spam"
TpSpambtn.TextColor3 = Color3.new(1, 1, 1)
TpSpambtn.TextScaled = true
TpSpambtn.TextSize = 14
TpSpambtn.TextWrapped = true
 
AutoCampfirebtn.Name = "AutoCampfirebtn"
AutoCampfirebtn.Parent = Booga
AutoCampfirebtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoCampfirebtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoCampfirebtn.BorderSizePixel = 2
AutoCampfirebtn.Position = UDim2.new(0.702531636, 0, 0.487179428, 0)
AutoCampfirebtn.Size = UDim2.new(0, 116, 0, 27)
AutoCampfirebtn.Font = Enum.Font.SourceSansSemibold
AutoCampfirebtn.Text = "Auto Campfire"
AutoCampfirebtn.TextColor3 = Color3.new(1, 1, 1)
AutoCampfirebtn.TextScaled = true
AutoCampfirebtn.TextSize = 14
AutoCampfirebtn.TextWrapped = true
 
AutoWallTrapbtn.Name = "AutoWallTrapbtn"
AutoWallTrapbtn.Parent = Booga
AutoWallTrapbtn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoWallTrapbtn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoWallTrapbtn.BorderSizePixel = 2
AutoWallTrapbtn.Position = UDim2.new(0.367088586, 0, 0.566239357, 0)
AutoWallTrapbtn.Size = UDim2.new(0, 116, 0, 27)
AutoWallTrapbtn.Font = Enum.Font.SourceSansSemibold
AutoWallTrapbtn.Text = "Auto Wall"
AutoWallTrapbtn.TextColor3 = Color3.new(1, 1, 1)
AutoWallTrapbtn.TextScaled = true
AutoWallTrapbtn.TextSize = 14
AutoWallTrapbtn.TextWrapped = true
 
AutoEatFoodNamekb.Name = "AutoEatFoodNamekb"
AutoEatFoodNamekb.Parent = Booga
AutoEatFoodNamekb.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoEatFoodNamekb.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoEatFoodNamekb.BorderSizePixel = 2
AutoEatFoodNamekb.Position = UDim2.new(0.702531636, 0, 0.638888896, 0)
AutoEatFoodNamekb.Size = UDim2.new(0, 116, 0, 27)
AutoEatFoodNamekb.Font = Enum.Font.SourceSans
AutoEatFoodNamekb.Text = "Item Name"
AutoEatFoodNamekb.TextColor3 = Color3.new(1, 1, 1)
AutoEatFoodNamekb.TextScaled = true
AutoEatFoodNamekb.TextSize = 14
AutoEatFoodNamekb.TextWrapped = true
 
TpSpamPlayerNamekb.Name = "TpSpamPlayerNamekb"
TpSpamPlayerNamekb.Parent = Booga
TpSpamPlayerNamekb.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
TpSpamPlayerNamekb.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
TpSpamPlayerNamekb.BorderSizePixel = 2
TpSpamPlayerNamekb.Position = UDim2.new(0.35864979, 0, 0.326923072, 0)
TpSpamPlayerNamekb.Size = UDim2.new(0, 116, 0, 27)
TpSpamPlayerNamekb.Font = Enum.Font.SourceSans
TpSpamPlayerNamekb.Text = "Player Name"
TpSpamPlayerNamekb.TextColor3 = Color3.new(1, 1, 1)
TpSpamPlayerNamekb.TextScaled = true
TpSpamPlayerNamekb.TextSize = 14
TpSpamPlayerNamekb.TextWrapped = true
 
DropAllItemsItemNamekb.Name = "DropAllItemsItemNamekb"
DropAllItemsItemNamekb.Parent = Booga
DropAllItemsItemNamekb.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
DropAllItemsItemNamekb.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
DropAllItemsItemNamekb.BorderSizePixel = 2
DropAllItemsItemNamekb.Position = UDim2.new(0.0358649828, 0, 0.638888955, 0)
DropAllItemsItemNamekb.Size = UDim2.new(0, 116, 0, 27)
DropAllItemsItemNamekb.Font = Enum.Font.SourceSans
DropAllItemsItemNamekb.Text = "Item Name"
DropAllItemsItemNamekb.TextColor3 = Color3.new(1, 1, 1)
DropAllItemsItemNamekb.TextScaled = true
DropAllItemsItemNamekb.TextSize = 14
DropAllItemsItemNamekb.TextWrapped = true
 
DropAllItemskb.Name = "DropAllItemskb"
DropAllItemskb.Parent = Booga
DropAllItemskb.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
DropAllItemskb.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
DropAllItemskb.BorderSizePixel = 2
DropAllItemskb.Position = UDim2.new(0.035864979, 0, 0.713675261, 0)
DropAllItemskb.Size = UDim2.new(0, 116, 0, 27)
DropAllItemskb.Font = Enum.Font.SourceSans
DropAllItemskb.Text = "Keybind"
DropAllItemskb.TextColor3 = Color3.new(1, 1, 1)
DropAllItemskb.TextScaled = true
DropAllItemskb.TextSize = 14
DropAllItemskb.TextWrapped = true
 
AutoEatkb.Name = "AutoEatkb"
AutoEatkb.Parent = Booga
AutoEatkb.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
AutoEatkb.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
AutoEatkb.BorderSizePixel = 2
AutoEatkb.Position = UDim2.new(0.702531636, 0, 0.715811968, 0)
AutoEatkb.Size = UDim2.new(0, 116, 0, 27)
AutoEatkb.Font = Enum.Font.SourceSans
AutoEatkb.Text = "Keybind"
AutoEatkb.TextColor3 = Color3.new(1, 1, 1)
AutoEatkb.TextScaled = true
AutoEatkb.TextSize = 14
AutoEatkb.TextWrapped = true
 
Recipes.Name = "Recipes"
Recipes.Parent = Booga
Recipes.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Recipes.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
Recipes.BorderSizePixel = 2
Recipes.Position = UDim2.new(0.360759497, 0, 0.839743614, 0)
Recipes.Size = UDim2.new(0, 116, 0, 27)
Recipes.Font = Enum.Font.SourceSansSemibold
Recipes.Text = "Recipes"
Recipes.TextColor3 = Color3.new(1, 1, 1)
Recipes.TextScaled = true
Recipes.TextSize = 14
Recipes.TextWrapped = true
 
Credits.Name = "Credits"
Credits.Parent = Booga
Credits.Active = true
Credits.BackgroundColor3 = Color3.new(1, 1, 1)
Credits.BackgroundTransparency = 1
Credits.BorderColor3 = Color3.new(1, 1, 0)
Credits.BorderSizePixel = 2
Credits.Position = UDim2.new(0.00210970454, 0, 0.929487169, 0)
Credits.Size = UDim2.new(0, 473, 0, 34)
Credits.Font = Enum.Font.SourceSansSemibold
Credits.Text = "GUI Made by Miu Iruma#4693"
Credits.TextColor3 = Color3.new(1, 1, 1)
Credits.TextScaled = true
Credits.TextSize = 14
Credits.TextWrapped = true
 
Booga2.Name = "Booga2"
Booga2.Parent = ScreenGui
Booga2.Active = true
Booga2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
Booga2.BackgroundTransparency = 0.30000001192093
Booga2.BorderColor3 = Color3.new(1, 0, 0.498039)
Booga2.BorderSizePixel = 2
Booga2.Position = UDim2.new(1.70000005, 1, 1.70000005, 1)
Booga2.Size = UDim2.new(0, 474, 0, 468)
 
BoogaTop2.Name = "BoogaTop2"
BoogaTop2.Parent = Booga2
BoogaTop2.Active = true
BoogaTop2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
BoogaTop2.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
BoogaTop2.BorderSizePixel = 2
BoogaTop2.Size = UDim2.new(0, 474, 0, 27)
 
Exit2.Name = "Exit2"
Exit2.Parent = Booga2
Exit2.BackgroundColor3 = Color3.new(0.901961, 0.380392, 0.380392)
Exit2.BorderSizePixel = 0
Exit2.Position = UDim2.new(0.915611804, 0, 0.00854700897, 0)
Exit2.Size = UDim2.new(0, 28, 0, 19)
Exit2.Font = Enum.Font.SourceSans
Exit2.Text = "X"
Exit2.TextColor3 = Color3.new(1, 1, 1)
Exit2.TextSize = 14
 
EmeraldHelmet.Name = "EmeraldHelmet"
EmeraldHelmet.Parent = Booga2
EmeraldHelmet.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldHelmet.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldHelmet.BorderSizePixel = 2
EmeraldHelmet.Position = UDim2.new(0.03164557, 0, 0.126068383, 0)
EmeraldHelmet.Size = UDim2.new(0, 93, 0, 27)
EmeraldHelmet.Font = Enum.Font.SourceSansSemibold
EmeraldHelmet.Text = "Emerald Helmet"
EmeraldHelmet.TextColor3 = Color3.new(1, 1, 1)
EmeraldHelmet.TextScaled = true
EmeraldHelmet.TextSize = 14
EmeraldHelmet.TextWrapped = true
 
EmeraldDivider.Name = "EmeraldDivider"
EmeraldDivider.Parent = Booga2
EmeraldDivider.Active = true
EmeraldDivider.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldDivider.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldDivider.BorderSizePixel = 2
EmeraldDivider.Position = UDim2.new(0.03164557, 0, 0.0769230798, 0)
EmeraldDivider.Size = UDim2.new(0, 447, 0, 11)
 
EmeraldChestplate.Name = "EmeraldChestplate"
EmeraldChestplate.Parent = Booga2
EmeraldChestplate.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldChestplate.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldChestplate.BorderSizePixel = 2
EmeraldChestplate.Position = UDim2.new(0.261603385, 0, 0.126068383, 0)
EmeraldChestplate.Size = UDim2.new(0, 93, 0, 27)
EmeraldChestplate.Font = Enum.Font.SourceSansSemibold
EmeraldChestplate.Text = "Emerald Chestplate"
EmeraldChestplate.TextColor3 = Color3.new(1, 1, 1)
EmeraldChestplate.TextScaled = true
EmeraldChestplate.TextSize = 14
EmeraldChestplate.TextWrapped = true
 
EmeraldPick.Name = "EmeraldPick"
EmeraldPick.Parent = Booga2
EmeraldPick.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldPick.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldPick.BorderSizePixel = 2
EmeraldPick.Position = UDim2.new(0.748945177, 0, 0.121794872, 0)
EmeraldPick.Size = UDim2.new(0, 93, 0, 27)
EmeraldPick.Font = Enum.Font.SourceSansSemibold
EmeraldPick.Text = "Emerald Pick"
EmeraldPick.TextColor3 = Color3.new(1, 1, 1)
EmeraldPick.TextScaled = true
EmeraldPick.TextSize = 14
EmeraldPick.TextWrapped = true
 
EmeraldGreaves.Name = "EmeraldGreaves"
EmeraldGreaves.Parent = Booga2
EmeraldGreaves.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldGreaves.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldGreaves.BorderSizePixel = 2
EmeraldGreaves.Position = UDim2.new(0.506329119, 0, 0.123931624, 0)
EmeraldGreaves.Size = UDim2.new(0, 93, 0, 27)
EmeraldGreaves.Font = Enum.Font.SourceSansSemibold
EmeraldGreaves.Text = "Emerald Greaves"
EmeraldGreaves.TextColor3 = Color3.new(1, 1, 1)
EmeraldGreaves.TextScaled = true
EmeraldGreaves.TextSize = 14
EmeraldGreaves.TextWrapped = true
 
EmeraldBlade.Name = "EmeraldBlade"
EmeraldBlade.Parent = Booga2
EmeraldBlade.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldBlade.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldBlade.BorderSizePixel = 2
EmeraldBlade.Position = UDim2.new(0.03164557, 0, 0.211538464, 0)
EmeraldBlade.Size = UDim2.new(0, 93, 0, 27)
EmeraldBlade.Font = Enum.Font.SourceSansSemibold
EmeraldBlade.Text = "Emerald Blade"
EmeraldBlade.TextColor3 = Color3.new(1, 1, 1)
EmeraldBlade.TextScaled = true
EmeraldBlade.TextSize = 14
EmeraldBlade.TextWrapped = true
 
EmeraldAxe.Name = "EmeraldAxe"
EmeraldAxe.Parent = Booga2
EmeraldAxe.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldAxe.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldAxe.BorderSizePixel = 2
EmeraldAxe.Position = UDim2.new(0.261603385, 0, 0.211538464, 0)
EmeraldAxe.Size = UDim2.new(0, 93, 0, 27)
EmeraldAxe.Font = Enum.Font.SourceSansSemibold
EmeraldAxe.Text = "Emerald Axe"
EmeraldAxe.TextColor3 = Color3.new(1, 1, 1)
EmeraldAxe.TextScaled = true
EmeraldAxe.TextSize = 14
EmeraldAxe.TextWrapped = true
 
EmeraldBag.Name = "EmeraldBag"
EmeraldBag.Parent = Booga2
EmeraldBag.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldBag.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldBag.BorderSizePixel = 2
EmeraldBag.Position = UDim2.new(0.506329119, 0, 0.209401712, 0)
EmeraldBag.Size = UDim2.new(0, 93, 0, 27)
EmeraldBag.Font = Enum.Font.SourceSansSemibold
EmeraldBag.Text = "EmeraldBag"
EmeraldBag.TextColor3 = Color3.new(1, 1, 1)
EmeraldBag.TextScaled = true
EmeraldBag.TextSize = 14
EmeraldBag.TextWrapped = true
 
VoidShroud.Name = "VoidShroud"
VoidShroud.Parent = Booga2
VoidShroud.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidShroud.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidShroud.BorderSizePixel = 2
VoidShroud.Position = UDim2.new(0.719409287, 0, 0.623931646, 0)
VoidShroud.Size = UDim2.new(0, 93, 0, 27)
VoidShroud.Font = Enum.Font.SourceSansSemibold
VoidShroud.Text = "Void Shroud"
VoidShroud.TextColor3 = Color3.new(1, 1, 1)
VoidShroud.TextScaled = true
VoidShroud.TextSize = 14
VoidShroud.TextWrapped = true
 
EmeraldDivider2.Name = "EmeraldDivider2"
EmeraldDivider2.Parent = Booga2
EmeraldDivider2.Active = true
EmeraldDivider2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
EmeraldDivider2.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
EmeraldDivider2.BorderSizePixel = 2
EmeraldDivider2.Position = UDim2.new(0.0232067518, 0, 0.288461536, 0)
EmeraldDivider2.Size = UDim2.new(0, 447, 0, 11)
 
GodDivider.Name = "GodDivider"
GodDivider.Parent = Booga2
GodDivider.Active = true
GodDivider.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodDivider.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodDivider.BorderSizePixel = 2
GodDivider.Position = UDim2.new(0.0232067518, 0, 0.324786335, 0)
GodDivider.Size = UDim2.new(0, 447, 0, 11)
 
GodDivider2.Name = "GodDivider2"
GodDivider2.Parent = Booga2
GodDivider2.Active = true
GodDivider2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodDivider2.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodDivider2.BorderSizePixel = 2
GodDivider2.Position = UDim2.new(0.0147679336, 0, 0.538461566, 0)
GodDivider2.Size = UDim2.new(0, 447, 0, 11)
 
GodRock.Name = "GodRock"
GodRock.Parent = Booga2
GodRock.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodRock.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodRock.BorderSizePixel = 2
GodRock.Position = UDim2.new(0.03164557, 0, 0.455128193, 0)
GodRock.Size = UDim2.new(0, 93, 0, 27)
GodRock.Font = Enum.Font.SourceSansSemibold
GodRock.Text = "God Rock"
GodRock.TextColor3 = Color3.new(1, 1, 1)
GodRock.TextScaled = true
GodRock.TextSize = 14
GodRock.TextWrapped = true
 
GodHalo.Name = "GodHalo"
GodHalo.Parent = Booga2
GodHalo.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodHalo.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodHalo.BorderSizePixel = 2
GodHalo.Position = UDim2.new(0.03164557, 0, 0.369658113, 0)
GodHalo.Size = UDim2.new(0, 93, 0, 27)
GodHalo.Font = Enum.Font.SourceSansSemibold
GodHalo.Text = "God Halo"
GodHalo.TextColor3 = Color3.new(1, 1, 1)
GodHalo.TextScaled = true
GodHalo.TextSize = 14
GodHalo.TextWrapped = true
 
GodChestplate.Name = "GodChestplate"
GodChestplate.Parent = Booga2
GodChestplate.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodChestplate.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodChestplate.BorderSizePixel = 2
GodChestplate.Position = UDim2.new(0.261603385, 0, 0.369658113, 0)
GodChestplate.Size = UDim2.new(0, 93, 0, 27)
GodChestplate.Font = Enum.Font.SourceSansSemibold
GodChestplate.Text = "God Chestplate"
GodChestplate.TextColor3 = Color3.new(1, 1, 1)
GodChestplate.TextScaled = true
GodChestplate.TextSize = 14
GodChestplate.TextWrapped = true
 
GodAxe.Name = "GodAxe"
GodAxe.Parent = Booga2
GodAxe.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodAxe.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodAxe.BorderSizePixel = 2
GodAxe.Position = UDim2.new(0.261603385, 0, 0.455128193, 0)
GodAxe.Size = UDim2.new(0, 93, 0, 27)
GodAxe.Font = Enum.Font.SourceSansSemibold
GodAxe.Text = "God Axe"
GodAxe.TextColor3 = Color3.new(1, 1, 1)
GodAxe.TextScaled = true
GodAxe.TextSize = 14
GodAxe.TextWrapped = true
 
GodBag.Name = "GodBag"
GodBag.Parent = Booga2
GodBag.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodBag.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodBag.BorderSizePixel = 2
GodBag.Position = UDim2.new(0.506329119, 0, 0.452991456, 0)
GodBag.Size = UDim2.new(0, 93, 0, 27)
GodBag.Font = Enum.Font.SourceSansSemibold
GodBag.Text = "God Bag"
GodBag.TextColor3 = Color3.new(1, 1, 1)
GodBag.TextScaled = true
GodBag.TextSize = 14
GodBag.TextWrapped = true
 
GodLegs.Name = "GodLegs"
GodLegs.Parent = Booga2
GodLegs.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodLegs.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodLegs.BorderSizePixel = 2
GodLegs.Position = UDim2.new(0.506329119, 0, 0.367521375, 0)
GodLegs.Size = UDim2.new(0, 93, 0, 27)
GodLegs.Font = Enum.Font.SourceSansSemibold
GodLegs.Text = "God Legs"
GodLegs.TextColor3 = Color3.new(1, 1, 1)
GodLegs.TextScaled = true
GodLegs.TextSize = 14
GodLegs.TextWrapped = true
 
GodPick.Name = "GodPick"
GodPick.Parent = Booga2
GodPick.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
GodPick.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
GodPick.BorderSizePixel = 2
GodPick.Position = UDim2.new(0.748945177, 0, 0.365384609, 0)
GodPick.Size = UDim2.new(0, 93, 0, 27)
GodPick.Font = Enum.Font.SourceSansSemibold
GodPick.Text = "God Pick"
GodPick.TextColor3 = Color3.new(1, 1, 1)
GodPick.TextScaled = true
GodPick.TextSize = 14
GodPick.TextWrapped = true
 
VoidChestplate.Name = "VoidChestplate"
VoidChestplate.Parent = Booga2
VoidChestplate.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidChestplate.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidChestplate.BorderSizePixel = 2
VoidChestplate.Position = UDim2.new(0.371308029, 0, 0.626068354, 0)
VoidChestplate.Size = UDim2.new(0, 93, 0, 27)
VoidChestplate.Font = Enum.Font.SourceSansSemibold
VoidChestplate.Text = "Void Chestplate"
VoidChestplate.TextColor3 = Color3.new(1, 1, 1)
VoidChestplate.TextScaled = true
VoidChestplate.TextSize = 14
VoidChestplate.TextWrapped = true
 
VoidDivider2.Name = "VoidDivider2"
VoidDivider2.Parent = Booga2
VoidDivider2.Active = true
VoidDivider2.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidDivider2.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidDivider2.BorderSizePixel = 2
VoidDivider2.Position = UDim2.new(0.00632911548, 0, 0.797008574, 0)
VoidDivider2.Size = UDim2.new(0, 447, 0, 11)
 
VoidDivider.Name = "VoidDivider"
VoidDivider.Parent = Booga2
VoidDivider.Active = true
VoidDivider.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidDivider.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidDivider.BorderSizePixel = 2
VoidDivider.Position = UDim2.new(0.0147679336, 0, 0.583333373, 0)
VoidDivider.Size = UDim2.new(0, 447, 0, 11)
 
VoidBag.Name = "VoidBag"
VoidBag.Parent = Booga2
VoidBag.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidBag.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidBag.BorderSizePixel = 2
VoidBag.Position = UDim2.new(0.373417735, 0, 0.715811968, 0)
VoidBag.Size = UDim2.new(0, 93, 0, 27)
VoidBag.Font = Enum.Font.SourceSansSemibold
VoidBag.Text = "Void Bag"
VoidBag.TextColor3 = Color3.new(1, 1, 1)
VoidBag.TextScaled = true
VoidBag.TextSize = 14
VoidBag.TextWrapped = true
 
VoidGreaves.Name = "VoidGreaves"
VoidGreaves.Parent = Booga2
VoidGreaves.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
VoidGreaves.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
VoidGreaves.BorderSizePixel = 2
VoidGreaves.Position = UDim2.new(0.03164557, 0, 0.630341887, 0)
VoidGreaves.Size = UDim2.new(0, 93, 0, 27)
VoidGreaves.Font = Enum.Font.SourceSansSemibold
VoidGreaves.Text = "Void Greaves"
VoidGreaves.TextColor3 = Color3.new(1, 1, 1)
VoidGreaves.TextScaled = true
VoidGreaves.TextSize = 14
VoidGreaves.TextWrapped = true
 
OOFHorn.Name = "OOFHorn"
OOFHorn.Parent = Booga2
OOFHorn.BackgroundColor3 = Color3.new(0.12549, 0.129412, 0.176471)
OOFHorn.BorderColor3 = Color3.new(1, 0.00392157, 0.356863)
OOFHorn.BorderSizePixel = 2
OOFHorn.Position = UDim2.new(0.748945177, 0, 0.450854689, 0)
OOFHorn.Size = UDim2.new(0, 93, 0, 27)
OOFHorn.Font = Enum.Font.SourceSansSemibold
OOFHorn.Text = "OOF Horn"
OOFHorn.TextColor3 = Color3.new(1, 1, 1)
OOFHorn.TextScaled = true
OOFHorn.TextSize = 14
OOFHorn.TextWrapped = true
 
Open.MouseButton1Down:connect(function()
Booga:TweenPosition(UDim2.new(0.079, 0, 0.074, 0), 'Out','Bounce', 1)
Open.Visible = true
Booga.Visible = true
end)
 
Exit.MouseButton1Down:connect(function()
Booga:TweenPosition(UDim2.new(0.079, 0, 1.7, 0), 'Out','Bounce', 1)
Open.Visible = true
end)
 
Recipes.MouseButton1Down:connect(function()
Booga2:TweenPosition(UDim2.new(0.433, 0, 0.074, 0), 'Out','Bounce', 1)
Booga2.Visible = true
end)
 
Exit2.MouseButton1Down:connect(function()
Booga2:TweenPosition(UDim2.new(0.079, 0, 1.7, 0), 'Out','Bounce', 1)
end)
 
VoidBag.MouseButton1Click:connect(function()
local A_1   = "Void Bag"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
VoidShroud.MouseButton1Click:connect(function()
local A_1   = "Void Shroud"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
VoidChestplate.MouseButton1Click:connect(function()
local A_1   = "Void Chestplate"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
VoidGreaves.MouseButton1Click:connect(function()
local A_1   = "Void Greaves"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
 
 
EmeraldAxe.MouseButton1Click:connect(function()
local A_1   = "Emerald Axe"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldBlade.MouseButton1Click:connect(function()
local A_1   = "Emerald Blade"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldPick.MouseButton1Click:connect(function()
local A_1   = "Emerald Pick"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldBag.MouseButton1Click:connect(function()
local A_1   = "Emerald Bag"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldHelmet.MouseButton1Click:connect(function()
local A_1   = "Emerald Helmet"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldChestplate.MouseButton1Click:connect(function()
local A_1   = "Emerald Chestplate"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
EmeraldGreaves.MouseButton1Click:connect(function()
local A_1   = "Emerald Greaves"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
 
 
GodAxe.MouseButton1Click:connect(function()
local A_1   = "God Axe"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodRock.MouseButton1Click:connect(function()
local A_1   = "God Rock"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodPick.MouseButton1Click:connect(function()
local A_1   = "God Pick"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodHalo.MouseButton1Click:connect(function()
local A_1   = "God Halo"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodChestplate.MouseButton1Click:connect(function()
local A_1   = "God Chestplate"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodLegs.MouseButton1Click:connect(function()
local A_1   = "God Legs"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
GodBag.MouseButton1Click:connect(function()
local A_1   = "God Bag"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
 
OOFHorn.MouseButton1Click:connect(function()
local A_1   = "OOF Horn"
local Event = game:GetService("ReplicatedStorage").Events.CraftItem
Event:FireServer(A_1)
end)
 
 
 
InfinityChest.MouseButton1Down:connect(function()
 local plr = game:GetService("Players").LocalPlayer
       local mouse = plr:GetMouse()
       mouse.KeyDown:connect(function(key)
           if key == "q" then
       local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
       Torso = game.Players.LocalPlayer.Character.UpperTorso
       b = Torso.Position + Torso.CFrame.lookVector * 10
       local c = b.x
       local d = b.y - 2
       local e = b.z
       for i = 1,1 do
       local A_1 = "Infinity Chest"
       local A_2 = CFrame.new(c, d, e, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
       local A_3 = 0
           Event:FireServer(A_1, A_2, A_3)
       end end end)
end)
 
 
CraftAnyItem.MouseButton1Click:connect(function()
    local event = game.ReplicatedStorage.Events.CraftItem
    local item = CraftItem.Text
    event:FireServer(item)
end)
 
GodHut.MouseButton1Click:connect(function()
        local plr = game:GetService("Players").LocalPlayer
        local mouse = plr:GetMouse()
        mouse.KeyDown:connect(function(key)
            if key == "g" then
        local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
        Torso = game.Players.LocalPlayer.Character.UpperTorso
        b = Torso.Position + Torso.CFrame.lookVector * 10
        local c = b.x
        local d = b.y - 2
        local e = b.z
        for i = 1,1 do
        local A_1 = "God Hut"
        local A_2 = CFrame.new(c, d, e, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
        local A_3 = 0
            Event:FireServer(A_1, A_2, A_3)
        end end end)
end)
 
AutoPickUp.MouseButton1Click:connect(function()
local Objects;
local Pickup = function(Character)
    local myPos = Character.HumanoidRootPart.Position
    local Objects = {}
    for i,v in pairs(workspace:GetChildren()) do
        if v:FindFirstChild("Pickup") ~= nil and v.ClassName == "Part" then
            local Pos = v.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
            elseif v:FindFirstChild("Pickup") ~= nil and v:FindFirstChild("Part") ~= nil and v.Part.ClassName == "Part" then
            local Pos = v.Part.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
             elseif v:FindFirstChild("Pickup") ~= nil and v.ClassName == "UnionOperation" then
             local Pos = v.Position
            local Distance = (myPos - Pos).magnitude
            if Distance < 40 then
                table.insert(Objects, v)
            end
        end
    end
    for i,v in pairs(Objects) do
    for i=1,10 do
    v.Position = myPos
    game:GetService("ReplicatedStorage").Events.Pickup:FireServer(v)
    end
    end
end
wait(1)
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
 
mouse.KeyDown:connect(function(key)
    if key == AutoPickUpBind.Text then
print'AutoPicked-up YEET'
Pickup(game.Players.LocalPlayer.Character)
end
end)
end)
 
local plr = game:GetService("Players").LocalPlayer
local char = plr.Character
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
local hum = char:FindFirstChild("HumanoidRootPart")
 
--SpeedVariables
local plr = game:GetService("Players").LocalPlayer
local char = plr.Character
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
local hum = char:FindFirstChild("HumanoidRootPart")
--yeet
Speed.MouseButton1Down:connect(function()
    local plr = game:GetService("Players").LocalPlayer
    local char = plr.Character
    local mouse = game:GetService("Players").LocalPlayer:GetMouse()
    local hum = char:FindFirstChild("HumanoidRootPart")
    mouse.KeyDown:connect(function(key)
        if key == SpeedBind.Text then
            loop = true
            while loop do
                hum.CFrame = hum.CFrame + hum.CFrame.lookVector * 3
                wait()
            end
            end
            end)
    end)
    
    mouse.KeyUp:connect(function(key)
        if key == SpeedBind.Text then
            loop = false
        end
end)
 
AutoBreak.MouseButton1Click:connect(function()
local mouse = game:GetService("Players").LocalPlayer:GetMouse()
local breaking=false
mouse.KeyDown:connect(function(key)
    if key == Breakkey.Text then
        breaking = true
        while breaking and wait(0.1) do
local part = game:GetService("Players").LocalPlayer:GetMouse().Target
local one = game:GetService("ReplicatedStorage").RelativeTime.Value
local two = {part,part,part,part}
game:GetService("ReplicatedStorage").Events.SwingTool:FireServer(one, two)
        end
        end
end)
mouse.KeyUp:connect(function(key)
    if key == Breakkey.Text then
        breaking = false
    end
    end)
end)
 
RevizV2.MouseButton1Click:connect(function()
    loadstring(game:HttpGet("https://pastebin.com/raw/8zh7FiHv"))()
end)
 
RemoveRainbtn.MouseButton1Click:Connect(function()
            if workspace:FindFirstChild('RainPart') ~= nil then
                workspace.RainPart:Destroy()
                game.ReplicatedStorage.Sounds.Nature.Rain:Stop()
                game.ReplicatedStorage.Sounds.Nature.Thunder:Stop()
                game.Lighting.Rain:Destroy()
                game.ReplicatedStorage.Skies.Shine:Clone().Parent = game.Lighting
            end
end)
 
TpSpambtn.MouseButton1Down:connect(function()
for i,v in pairs(game:GetService("Players"):GetChildren()) do
    if v.Name:lower():find(TpSpamPlayerNamekb.Text:lower()) then
    if v.Name == "Infinity_Chest" or v.Name == "BlueBearTimx" then
    print("Fools you cannot kill the devs")
else
        player = game.Players.LocalPlayer.Character
        repeat
        player.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame
        wait(.001)
        until v.Character.Humanoid.Health <= 0
     end
     end
     end
end)
 
Important = {Players = game:GetService("Players"), Workspace = game:GetService("Workspace"), CoreGui = game:GetService("CoreGui")}
 
local enabledesp = false
 
function CreateESP(plr)
    
    if plr ~= nil then
        
        local GetChar = plr.Character
        if not GetChar then return end
        
        local GetHead do
            
            repeat wait() until GetChar:FindFirstChild("Head")
            
        end
        GetHead = GetChar.Head        
        
        local bb = Instance.new("BillboardGui", Important.CoreGui)
        bb.Adornee = GetHead
        bb.ExtentsOffset = Vector3.new(0, 1, 0)
        bb.AlwaysOnTop = true
        bb.Size = UDim2.new(0, 5, 0, 5)
        bb.StudsOffset = Vector3.new(0, 3, 0)
        bb.Name = "ESP_PLAYER_" .. plr.Name
 
        local displayframe = Instance.new("Frame", bb)
        displayframe.ZIndex = 10
        displayframe.BackgroundTransparency = 1
        displayframe.Size = UDim2.new(1,0,1,0)
        
        local name = Instance.new("TextLabel", displayframe)
        name.Name = "Name"
        name.ZIndex = 10
        name.Text = plr.Name
        name.Visible = true
        name.TextColor3 = Color3.new(170,0,0)
        name.BackgroundTransparency = 1
        name.Size = UDim2.new(1,0,10,0)
        name.Font = Enum.Font.SourceSansLight
        name.TextSize = 20
        name.TextStrokeTransparency = .5
        
    end
    
end
 
ESPbtn.MouseButton1Click:Connect(function()
    for i,v in pairs(Important.Players:GetChildren()) do
        
        CreateESP(v)      
    end
end)
 
DropAllItemsbtn.MouseButton1Click:Connect(function()
 
Player = game.Players.LocalPlayer
Mouse = Player:GetMouse()
 
function PressedE(key)
    Key = key:lower()
    if Key == DropAllItemskb.Text then
    for i=1, 100 do
game.ReplicatedStorage.Events.DropBagItem:FireServer(DropAllItemsItemNamekb.Text)
end
end
end
Mouse.KeyDown:connect(PressedE)
end)
 
 
RemoveAllEffectsbtn.MouseButton1Click:Connect(function()
game.Lighting.FogEnd = 1200000
game.Lighting.Brightness = 3
game.Lighting.GlobalShadows = false
end)
 
VoidTpbtn.MouseButton1Click:Connect(function()
game:GetService("TeleportService"):Teleport(2021740958)
print('VoidTP Credits: Flareo!')
end)
 
AutoEatbtn.MouseButton1Click:Connect(function()
if game.PlaceId == 1262182609 or game.PlaceId == 2021740958 then
local lol = 1
local plr = game:GetService("Players").LocalPlayer
local mouse = plr:GetMouse()
mouse.KeyDown:connect(function(key)
    if key == AutoEatkb.Text then
    lol = 0
    while lol == 0 do
    wait()
local Event = game:GetService("ReplicatedStorage").Events.UseBagItem
    Event:FireServer(AutoEatFoodNamekb.Text)
    Event:FireServer(AutoEatFoodNamekb.Text)
    Event:FireServer(AutoEatFoodNamekb.Text)
end end end)
local plr = game:GetService("Players").LocalPlayer
local mouse = plr:GetMouse()
mouse.KeyUp:connect(function(key)
    if key == AutoEatkb.Text then
    lol = 1
end end) end
end)
AutoCampfirebtn.MouseButton1Click:Connect(function()
local Fires = 1
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
h = game.Players.LocalPlayer.Character.LowerTorso.Position
local c = h.x + 5
local d = h.y - 2
local e = h.z
local j = h.x
local k = h.y - 2
local l = h.z
local aa = h.x - 5
local bb = h.y - 2
local cc = h.z
local aaa = h.x
local bbb = h.y - 2
local ccc = h.z + 5
local aaaa = h.x
local bbbb = h.y - 2
local cccc = h.z - 5
for i = 1,1 do
local C_1 = "Chest"
local C_2 = CFrame.new(j, k, l, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
local C_3 = 0
Event:FireServer(C_1, C_2, C_3)
end
for i = 1,Fires do
local A_1 = "Campfire"
local A_2 = CFrame.new(c, d, e, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
local A_3 = 0
Event:FireServer(A_1, A_2, A_3)
end
for i = 1,Fires do
local B_1 = "Campfire"
local B_2 = CFrame.new(aa, bb, cc, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
local B_3 = 0
Event:FireServer(B_1, B_2, B_3)
end
for i = 1,Fires do
local D_1 = "Campfire"
local D_2 = CFrame.new(aaa, bbb, ccc, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
local D_3 = 0
Event:FireServer(D_1, D_2, D_3)
end
for i = 1,Fires do
local E_1 = "Campfire"
local E_2 = CFrame.new(aaaa, bbbb, cccc, 1, 0, 0, 0, 1, -5.56028681e-08, 0, -5.56028681e-08, 1)
local E_3 = 0
Event:FireServer(E_1, E_2, E_3)
end
    end)
 
AutoWallTrapbtn.MouseButton1Click:Connect(function()
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
h = game.Players.LocalPlayer.Character.LowerTorso.Position
local aa = h.x + 13
local bb = h.y - 2
local cc = h.z
local aaa = h.x - 13
local bbb = h.y - 2
local ccc = h.z
local aaaa = h.x
local bbbb = h.y - 2
local cccc = h.z + 13
local aaaaa = h.x
local bbbbb = h.y - 2
local ccccc = h.z - 13
local k_1 = "Stone Wall"
local k_2 = CFrame.new(aaaa, bbbb, cccc, -0.99862951, 9.53660761e-12, 0.0523360483, -9.54969524e-12, 1, 2.71050543e-20, -0.0523360483, 4.99793241e-13, -0.99862951)
local k_3 = 177
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
Event:FireServer(k_1, k_2, k_3)
local l_1 = "Stone Wall"
local l_2 = CFrame.new(aaaaa, bbbbb, ccccc, -0.99862951, 9.53660761e-12, 0.0523360483, -9.54969524e-12, 1, 2.71050543e-20, -0.0523360483, 4.99793241e-13, -0.99862951)
local l_3 = 177
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
Event:FireServer(l_1, l_2, l_3)
local m_1 = "Stone Wall"
local m_2 = CFrame.new(aaa, bbb, ccc, 1.19248806e-08, 3.87430191e-06, -1, 4.62005888e-14, 1, -3.87430191e-06, 1, 0, 1.19248806e-08)
local m_3 = 270
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
Event:FireServer(m_1, m_2, m_3)
local n_1 = "Stone Wall"
local n_2 = CFrame.new(aa, bb, cc, 1.19248806e-08, 3.87430191e-06, -1, 4.62005888e-14, 1, -3.87430191e-06, 1, 0, 1.19248806e-08)
local n_3 = 270
local Event = game:GetService("ReplicatedStorage").Events.PlaceStructure
Event:FireServer(n_1, n_2, n_3)
    end)
