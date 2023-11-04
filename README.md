repeat wait() until game:IsLoaded();
local id = game.PlaceId
if id == 13772394625 then
loadstring(game:HttpGet("https://raw.githubusercontent.com/CQWEO/BladeBallScript/main/WarBladeBall"))()
else
if _G.Mode == "Vietnamese"  then
    game.Players.LocalPlayer:Kick("Đây Không Phải Là Tựa Game Blade Ball")
     wait(1)
        game:Shutdown()
    else
