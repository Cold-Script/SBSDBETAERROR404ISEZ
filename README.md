local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/RedzLibV5/main/Source.Lua"))()

local Window = redzlib:MakeWindow({
  Title = "YOUHUB",
  SubTitle = "Superbox Siege Defense!!!",
  SaveFolder = "testando | redz lib v5.lua"
})
local Tab1 = Window:MakeTab({"Misc", "cherry"})
local Tab2 = Window:MakeTab({"Item", "swords"})
local Tab3 = Window:MakeTab({"Setting", "user"})

Tab1:AddButton({"Give Inf Point (Fake)",Description = "Give Inf Point But Its Fake",function()
  game.Players.LocalPlayer.Point.Value = 9999999999999999999999999999
 end})
 Tab1:AddButton({"Give Inf Cash (Fake)",Description = "Give Inf Cash But Its Fake",function()
  game.Players.LocalPlayer.Cash.Value = 9999999999999999999999999999
 end})

Tab2:AddSlider({
  Name = "Slider",
  Min = 1,
  Max = 10,
  Increase = 1,
  Default = 5,
  Callback = function(Value)
    
  end
})

