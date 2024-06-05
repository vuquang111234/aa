getgenv().Configs = {
	Main = {
		SkipFarm = true,
		HopIfCantKill = true,
		BlockAllHop = false,
		
		FastAttack = true,
		
		Start = true,
	},

	FirstSea = {
	        -- World 1
		AutoPole = true, -- จะตีเเค่ถ้ามันเกิดไม่ได้ตีจนกว่าจะได้
		AutoSaber = true,
		AutoSecondSea = true,
	},

	SecondSea = {
		-- World 2
		AutoRengoku = true,

		AutoSecondSea = true,
		AutoQuestFlower = true,
		AutoRaceV3 = true,
		AutoBartiloQuest = true,
		AutoCursedCaptain = true,
		AutoDarkbeard = true,
		AutoFactory = true,
		AutoThirdSea = true,
		
		AlliesFruit = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough"}, -- จะไม่ใช้ผลพวกนี้ในการเปิดประตูไปโลก3
	},

	ThirdSea = {
		-- World 3
		AutoHallowScythe = true,
		AutoBuddySword = true,
		AutoDoughKing = true,
		AutoSpikeyTrident = true,
		AutoTushita = true,
		AutoEliteHunter = true,
		AutoDarkDagger = true,
		AutoYama = true,
		AutoCanvander = true,
		SkipGetItemGuitar = true, -- จะไม่ หาของทำ soul guiter ในโลก 2 เบบ หาจนกว่าจะได้ will not find item until get all item for do soul guiter ( open recommend เเนะนำให้เปิด )
		AutoSoulGuitar = true, 
		AutoRainbowHaki = true,
		AutoCursedDualKatana = true,
	},

	FightingStyle = {
		-- Fighting Style 
		AutoGodHuman = true,
		AutoSuperhuman = true,
		AutoDeathStep = true,
		AutoSharkmanKarate = true,
		AutoElectricClaw = true,
		AutoDargonTalon = true,
	},

	Mastery = {
		-- Auto Farm Mastery
		AutoDFMastery = true,
		SettingsSkill = { -- ถ้าไม่ใส่จะใช้ mode auto
			-- ["Z"] = 0.1,
			-- ["X"] = 0.1,
			-- ["C"] = 0.1,
			-- ["V"] = 0.1, -- อันไหนไม่เอาลบออกไปเลย
		},
		AutoSwordMastery = true,
		SelectRaritySword = {"Mythical","Legendary"}, -- Common , Uncommon,Rare,Legendary,Mythical
	
	},

	Settings = {
		-- code
		
		SelectRedeemCodeLevel = 1,

		-- Raids

		SelectRateFruitRaid = 1000000, -- if fruit price less u rate then we use it to auto raids
		LimitFragmentsRaids = 100000,
	},

	FruitsSettings = {
		-- Devil Fruit
	
		SelectMainDF = {"Dragon-Dragon","Spirit-Spirit","Venom-Venom","Dough-Dough"}, -- ผลหลักที่จะกินเเทนผลรอง
		SelectSubDF = {"Ice-Ice","Sand-Sand","Dark-Dark","Quake-Quake","Light-Light"}, -- ผลรองจะกินไว้ก่อนเเล้วพอผลหลักมีก้จะเปลียนไปกินผิดหลัก
		AllowEatDFInventory = true,
		StartSniper = true,
	},

	Webhook = {
		-- Webhook

		StartWebhook = false,
		WebhookURL = "",
		WebhookMode = "Send On Level Max And Every 10 min", -- "Send Every 10 min","Send On Level Max And Every 10 min"
	},

	Fps = {
		-- CPU

		FpsBoost = true,
		LockFPS = 120,
		LockFPSNow = true,
		WhiteScreen = false
	}
}
