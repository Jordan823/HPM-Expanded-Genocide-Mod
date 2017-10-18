# HPM-Expanded-Genocide-Mod

# This mod isn't finished yet and so far only supports the genocide of North Germans, South Germans, Ashkenazi, Swiss, Swedish, Danish, Norwegian, Finnish, Sami, Icelandic, British, Irish, Basque, Spanish, Catalonian, Portugese, Galician, North Italian, South Italian, Maltese, French, Occitan, Breton, Arpitan, Picard, and the entirety of the Americas.

# It uses the same triggers as the default HPM genocide event, and will be available to trigger once those pre-requisites have been met:

	potential = {
			NOT = { has_country_flag = preparations_to_kill }
			OR = {
				government = absolute_monarchy
				government = theocracy
				government = fascist_dictatorship
				government = presidential_dictatorship
				government = proletarian_dictatorship
			}
			revolution_n_counterrevolution = 1
		}
		
		allow = {
			war = no
			NOT = { any_owned_province = { has_province_modifier = genocide } }
			invention = rhetoric_of_hate
			money = 100000
			OR = {
				government = absolute_monarchy
				government = theocracy
				government = fascist_dictatorship
				government = presidential_dictatorship
				government = proletarian_dictatorship
			}
			OR = {
				ruling_party_ideology = reactionary
				ruling_party_ideology = fascist
				ruling_party_ideology = communist
			}
		}
    
# Everything is subject to change, and suggestions are very welcome. I'm just using the default HPM pre-requisites as it's much easier while I continue to create the meat of the mod, and I will come back to the pre-requisites once all cultures have been added. I hope to port this over to vanilla by the end of it, but for now it only works with HPM.

# To install, just add it to your Victoria 2/mod folder and run it alongside HPM/HFM (make sure the version you're using corresponds with the correct genocide version!)
