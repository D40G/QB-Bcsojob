# LY-Bcsojob

qb-police job edited to be a BCSO deputy edited by DrLuckyRp


Go to qb-bossmenu and add into rhe config
['bcso'] = vector3(-437.19, 5998.32, 31.72),

than go to qb-core/shaird/jobs and add

    ['bcso'] = {
		label = 'Bcso Enforcement',
		defaultDuty = true,
		offDutyPay = false,
		grades = {
            ['0'] = {
                name = 'Recruit',
                payment = 50
            },
			['1'] = {
                name = 'deputy',
                payment = 75
            },
			['2'] = {
                name = 'sirdeputy',
                payment = 100
            },
			['3'] = {
                name = 'Lieutenant',
                payment = 125
            },
			['4'] = {
                name = 'Chief',
				isboss = true,
                payment = 150
            },
        },
	},
