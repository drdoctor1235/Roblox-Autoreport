# Roblox-Autoreport
You will need an executor. for pc i recommend solara. its free and easy to use.
For mobile i recommend Arceus X, Delta, and Hydrogen.
when you are wanting to use this script, please whatch this tutorial: 


getgenv().autoreportcfg = {
    Webhook = "", -- you can leave it empty if u want ingame notifs 
    autoMessage = { -- whispers to people if they get autoreported
       enabled = true,
       Message = 'so sad you got autoreported :(',
    },
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/finopps/Roblox-Autoreport/main/robloxautoreport.lua"))()
