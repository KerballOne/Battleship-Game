Setup:
	Install mods from modlist.txt
	Extract BATTLESHIP folder into GameData
	Recommended changes: 
		change Scatterer ocean swells - Alt-10 in flight > Oceans > reduce windspeed from 7 to 4)
		change PhysicsRange Extender from 100m to 1000m)
		change Camera Tools continued to not auto-enable with BDA
	Copy craft files from _CRAFT_FILES into saves/<savename>/Ships/SPH/
	Copy spawn_templates.cfg into GameData\BDArmory\PluginData
		Optional:  Find/Replace CraftURL locations to your savename (or when loaded the crafts will be blank, and you will need to manually give each team one of each craft)
	
	
Running a game:
	Spawn all ships
		In BDA Vessel Spawner 
		Spawn Options:  menu, set Spawn Options > Teams to Custom Templates
		Spawn Template options: Load "Battleship!"
		Spawn Only
	Launching Aircraft
		Select a Carrier from BDA Vessel Switcher
		Stage!  (a newly created F-14 Fighter will release and lock into the launch catapult)
		Select the F-14 Fighter from the BDA Vessel Switcher
		Press "b" to release the brake (the catapult will launch the aircraft)
		Enable PilotAI just as the aircraft reaches the end of the catapult
		... repeat for both Carriers and both aircraft
	Start Competition
