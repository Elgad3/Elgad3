local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Elgad3", "Sentinel")
    -- MAIN
    local Main = Window:NewTab("Hacker")
    local MainSection = Main:NewSection("Hacker")


    MainSection:NewButton("Admin", "Give me admin", function()
            loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
            end)
    
     MainSection:NewButton("VIP", "Give me VIP", function()
         loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
  end)

    MainSection:NewButton("Kill", "Give Kill player", function()
     loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\68\56\117\81\76\49\109\84\39\41\41\40\41\10")()
            end)

    MainSection:NewToggle("Speed", " Give me Speed", function(state)
        if state then
            game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
        else
            game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        end
    end)

    
    MainSection:NewToggle("Jump", " Give me Give", function(state)
        if state then
              loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Infinite%20Jump.txt"))()
        else
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        end
    end)

  MainSection:NewButton("Btools", "Give me Btools", function()
         loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/BTools.txt"))()
  end)

   MainSection:NewButton("Click Teleport", "Give me Click Teleport", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Click%20Teleport.txt"))()
    end)

     MainSection:NewButton("Remove Legs", "Give me Remove Legs ", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Remove%20Legs.txt"))()
    end)

     MainSection:NewButton("Night", "Give me Night ", function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Night%20Time%20Toggle.txt"))()
    end)

     MainSection:NewButton("Invisible Character", "Give me Invisible Character ", function()
    loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Invisible%20Character.txt"))()
    end)


    --LOCAL Maps
    local Player = Window:NewTab("Maps")
    local PlayerSection = Player:NewSection("Maps")
  
       PlayerSection:NewButton("Brookhaven 🏡RP", "Map Brookhaven 🏡RP", function()
       loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
    end)
    
    PlayerSection:NewButton("Arsenal", "Map Arsenal", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HonestlyDex/DexHub/main/Arsenal"))()
    end)

    PlayerSection:NewButton("🔪 Survive the Killer!", "Map 🔪 Survive the Killer!", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FOXTROXHACKS/ElToro/main/Hub.lua"))()
    end)

    PlayerSection:NewButton("⚡Ninja Legends", "Map ⚡Ninja Legends", function()


getgenv().Color = Color3.fromRGB(0, 128, 255)
loadstring(game:HttpGet("https://raw.githubusercontent.com/StormSKz12/StirkeHub1/main/Gameincluded"))()
    end)

    PlayerSection:NewButton("Super Hero Tycoon", "Map Super Hero Tycoon", function()
      loadstring(game:HttpGet("https://pastebin.com/raw/HkfCDTkz", true))()
    end)

     PlayerSection:NewButton("Impossible Glass Bridge Obby! (Squid Game)", "Map Impossible Glass Bridge Obby! (Squid Game)", function()
while true and task.wait() do
for i,v in pairs(game:GetService("Workspace")["Glass Bridge"].GlassPane:GetDescendants()) do
   if v.Name == 'TouchInterest' then
       v.Parent.Transparency = 1
       end
   end
end
    end)

     PlayerSection:NewButton("Tower of Hell", "Map Tower of Hell", function()
     loadstring(game:HttpGet('https://pastebin.com/raw/BbVHjH56'))()
    end)
    
     PlayerSection:NewButton("🏖️ BIG Paintball!", "🏖️ BIG Paintball!", function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
    end)

     PlayerSection:NewButton("[💰2x] Flag Wars!", "Map [💰2x] Flag Wars!", function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/FlagWars"))()
    end)

     PlayerSection:NewButton("⬆️ GET TO THE TOP! ⬆️ [NEW SHOP!]", "Map ⬆️ GET TO THE TOP! ⬆️ [NEW SHOP!]", function()
     local v1 = -1000000000000000000
     local v2 = 0
     local event = game:GetService("ReplicatedStorage").GameValues.SendItem
     event:FireServer(v1, v2)
    end)

     PlayerSection:NewButton("Mega Easy Obby 🌟 800 Stages!", "Map Mega Easy Obby 🌟 800 Stages!", function()
     loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
    end)
