if _G.wl_key then
return
end
_G.wl_key= ""
repeat wait()
until game:IsLoaded() 
if game.PlaceId == 8569358381 then
getgenv().Main = {
["Enabled"] = true, -- Start
["AutoDupe"] = true, -- Auto Dupe
["AutoFind"] = false, -- Auto Find Sam Not Work For Now
}

getgenv().TpPos = {
["Enabled"] = true, -- Auto Tp To Position
["TeleportTo"] = CFrame.new(4795, 570, -7047) --- TP TO Postion Drop Compass

--                            DONT KNOW HO TOW GET POSITION?????
--                    USE IT: setclipboard(tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position))
}
loadstring(game:HttpGet('https://scripts.luawl.com/hosted/2445/20270/OPLAnarchy.lua'))()
else game:Shutdown() end
