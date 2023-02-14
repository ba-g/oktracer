# oktracer

-- made by Memelouse#3150
getgenv().Settings = {
    AimlockKey = "e",
    AimPart = "Head",
    CheckIfJumpedpart = "UpperTorso",
    AimRadius = 20,
    Disableontargetdeath = true,
    Disableonplayerdeath = false,
    ThirdPerson = true,
    FirstPerson = true,
    Undergroundresolver = false,
    DetectAntiLock = true,
    AntiLockSpeedDetection = 70,
    TeamCheck = false,
    PredictMovement = true,
    PredictionVelocity = 0.16221418,
    CheckIfJumped = true,
    Smoothness = true,
    Notificationmode = false,
    SmoothnessAmount = 0.019
}

getgenv().Visual = {
    Thickness = 3.4,
    Transparency = 1,
    Color = Color3.fromRGB(0, 255, 0),
    FOV = false,
    LINE = false
}

getgenv().Misc = {
    PermKorblox = false,
    PermHeadless = false
}


loadstring(game:HttpGet("https://raw.githubusercontent.com/xwel333/aimlock/main/aimlock"))()
