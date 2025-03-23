-- Kratos Hub - Auto Farm V5

getgenv().Configs = {
    ["Team"] = "Pirates", -- Escolha entre "Pirates" ou "Marines"
    ["FPS Boost"] = true, -- Melhora o FPS reduzindo gráficos
    ["Auto Farm"] = {
        ["Enable"] = true, -- Ativa ou desativa o auto farm
        ["TargetNPC"] = "Bandit", -- NPC alvo
        ["QuestNPC"] = "Bandit Quest Giver", -- NPC da missão
        ["FlySpeed"] = 0.5, -- Velocidade do voo
        ["NoClip"] = true -- Ativa atravessar paredes durante o voo
    },
    ["Auto Equip"] = {
        ["FightingStyle"] = "Combat" -- Escolha entre "Combat", "Dark Step", "Electric", etc.
    },
    ["Anti Crash"] = false -- Futuro sistema pra evitar crashes
}

-- Carrega o script principal
loadstring(game:HttpGet("https://raw.githubusercontent.com/SeuNome/SeuRepo/main/KratosHub.lua"))()
