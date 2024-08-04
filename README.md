# BatmanHub
**This script is still in __beta__ mode, any bugs will soon be fixed.**

# Lite Version
```
if getgenv().BatmanHubLoaded ~= true then
    getgenv().BatmanHubLoaded = true
   loadstring(game:HttpGet("https://github.com/l0ckerV5/BatmanHub/raw/main/Sources/Lite"))()
else
    game.StarterGui:SetCore("SendNotification",  { Title = "BatmanHub Lite"; Text = "This script is already executed!"; Icon = "rbxassetid://18634360365"; Duration = 15; })
end
```

**Scripted by l0ckerV5**
