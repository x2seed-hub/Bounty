getgenv().Config = {
    ["Default Team"] = "Marines",
    ["Auto Team"] = {["Enabled"] = true,
        ["Lock"] = {
            ["Bounty"] = {0, 30000000}, 
            ["Hornor"] = {0, 30000000}
        }
    },
    ["Panic % Health"] = {30, 50},
    ["Skip"] = { 
        ["Fruit"] = {["Enabled"] = true,
            ["List"] = {
                "Portal-Portal",
                "Chop-Chop",
                "Kitsune-Kitsune"
            }
        },
        ["V4"] = true
    },
    ["Hunt Method"] = {
        ["Use Move Predict"] = true,
        ["Hit and Run"] = true
    },
    ["Spam All Skill On V4"] = {
        ["Enabled"] = false,
        ["Weapons"] = {"Melee", "Blox Fruit", "Sword", "Gun"}
    },
    ["Chat Spamming"] = {
        ["Enabled"] = false,
        ["Message"] = {".gg/CejANXn8sa", "No Skill? Use Rua Hup Now"}
    },
    ["Misc"] = {
        ["Cam Farm"] = false,
        ["Hop Region"] = "Singapore", --// Best region in Asia
        ["White Screen"] = false,
        ["Click Delay"] = 0.15,
        ["Hide Map"] = false -- For Fps Boost
    },
    ["Items"] = {["Prioritize"] = {"Melee", "Gun"},
        ["Melee"] = {["Prioritize"] = {"Z", "C", "X"},
            ["Z"] = {true, 1.2, 0.8},
            ["X"] = {true, 0.2, 0},
            ["C"] = {true, 0.1, 0},
        },
        ["Blox Fruit"] = {["Prioritize"] = {"C", "Z", "X", "F"},
            ["Z"] = {false, 0, 0},
            ["X"] = {false, 0, 0},
            ["C"] = {false, 0, 0},
            ["V"] = {false, 0, 0},
            ["F"] = {false, 0, 0},
        },
        ["Sword"] = {["Prioritize"] = {"Z", "X"},
            ["Z"] = {false, 0, 0},
            ["X"] = {false, 0, 0},
        },
        ["Gun"] = {["Prioritize"] = {"Z", "X"},
            ["Z"] = {true, 0.1, 0},
            ["X"] = {true, 0.3, 0},
        },
    }
}

getgenv().Counter = {["Enabled"] = true,
    ["Webhook"] = {["Enabled"] = false,
        ["Url"] = ""
    },
    ["Theme"] = {["Enabled"] = true,
        ["Theme Character"] = "Yae", -- Yae
        ["Custom"] = {["Enabled"] = false,
            ["File Config"] = {
                ["Background"] = "",
                ["Character"] = "",
                ["Icon"] = "",
                ["Button Image"] = "",
                ["Color"] = {
                    ["Text"] = Color3.fromRGB(255, 255, 255),
                    ["Stroke"] = Color3.fromRGB(255, 255, 255)
                }
            }
        }
    }
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/ErutTheTeru/script/main/blox-autobounty.lua"))()
