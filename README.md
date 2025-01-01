local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/Arazjafaro/Bako-hub/refs/heads/main/BAKO%20HUB')))()
local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Bako Hub",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Scanner Pink!",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Matthew201322/Doors-Scriptee/refs/heads/main/the%20tablet.luau"))()
		print("Scanner Pink button pressed")
	end    
})

Tab:AddButton({
	Name = "Shears!",
	Callback = function()
		_G.Luck = 100
		_G.Spawns = false
		_G.Durability = 5
		_G.MaxDurability = 5
		_G.InfiniteUses = false
		_G.DurabilityTakenEachSnip = 0.25
		_G.SnipSpeed = 1.25
		_G.Regens = true
		_G.RegenSpeed = 1
		_G.RegenAmount = 0.1

		loadstring(game:HttpGet("https://raw.githubusercontent.com/iimateiYT/Scripts/main/Buffed%20Shears%20On%20Everything.lua"))()
		print("Shears button pressed")
	end    
})

Tab:AddButton({
	Name = "Seek Gun",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/Scripts/main/seekgun.lua"))()
		print("Seek Gun button pressed")
	end    
})

Tab:AddButton({
	Name = "Star Jug",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/Scripts/refs/heads/main/StarJug.lua"))()
		print("Star Jug button pressed")
	end    
})

Tab:AddButton({
	Name = "Giggle!",
	Callback = function()
		getgenv().GIGGLE_SPAWN_CONFIG = {
			Damage = 6,
			AttackingTime = math.random(7, 10),
			FallSpeed = 3,
			Stunnable = true,
			StunTime = 5,
			RagdollThrowForce = 50,
			RagdollDissapears = true,
			RoomSpawning = {Enabled = true},
			PlayerSpawning = {MinRadius = -20, MaxRadius = 20},
			SpawningKey = {Enabled = false, Key = "G"}
		}
		loadstring(game:HttpGet("https://raw.githubusercontent.com/DripCapybara/Test/refs/heads/main/Doors/GiggleSpawn.lua"))()
		print("Giggle button pressed")
	end    
})

Tab:AddButton({
	Name = "Inf Crucifix Anything",
	Callback = function()
		_G.Uses = 99999999999
		_G.Range = 999
		_G.OnAnything = true
		_G.Fail = false

		loadstring(game:HttpGet('https://raw.githubusercontent.com/PenguinManiack/Crucifix/main/Crucifix.lua'))()
		print("Inf Crucifix Anything button pressed")
	end    
})

Tab:AddButton({
	Name = "Troll Face!",
	Callback = function()
		loadstring(game:HttpGet("https://api.hugebonus.xyz/scripts/TrollFaceSpawner.lua"))()
		print("Troll Face button pressed")
	end    
})

Tab:AddButton({
	Name = "Spiral Lighter",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Teilsthebfdifan/Guiding-modhub/refs/heads/main/obf_tzC4VKEz8q97nq1JEmMWTW2Ke86o75zoN5gE6DOB475Gn4H99HoKS9i7sSa4zU95.lua.txt"))()
		print("Spiral Lighter button pressed")
	end    
})

Tab:AddButton({
	Name = "Wonder Bottle!",
	Callback = function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Agadigas/Doors/refs/heads/main/Wonder%20Bottle%20OFICIAL"))()
		print("Wonder Bottle button pressed")
	end    
})

OrionLib:Init()
