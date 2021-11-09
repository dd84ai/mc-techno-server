# dependencies for client and server:

- install docker-compose and run

- docker-compose up -d

# running client

- assumes usage with tlauncher
- ForgeOptifine 1.7.10 mode
- put mods/ and client/mods folders into your client mods folder

- Running: ./start.sh

# running server

sudo java -jar custom.jar

# in game

for logins:

- /register password password
- /login password

# Dependencies:

- teleport plugin: https://dev.bukkit.org/projects/hoams





dimensions in Tardis config

end 1|13
nether -1|5
miningworld 6
Moon -28, 1
Venus -1006, 2
Mars -29, 3
Mercury -1005, 3
asteroids -30, 4
Ceres -1007, 4
Io -1014, 5
Europa -1015, 5
Ganimede -1016, 5
barnarda C 1050, 6
Barndarda E -1051, 6
Pluto -1008, 6
Kuiper Belt -1009, 6
Enceladus -1017, 6
Miranda -1024, 6
Titan -1018
Triton -1021, 6
Calisto -1022, 6
Proxima B 1025, 6

#A comma separated list of energy cost to reach dimension
#In the form dimID|cost
#Default: 1|5000,-1|3000
Energy costs:S:1|5000,-1|3000,6|500,-28|1000,-1006|1500,-29|4000,-1005|4000,-30|4000,-1007|5000,-1014|5000,-1015|5000,-1016|5000,-1008|5000,-1009|5000,-1017|5000,-1024|5000,-1018|5000,-1021|5000,-1022|5000,-1025|8000,-1050|8000,-1051|8000

#A comma separated list of maximum heights in the form dimID|height
#E.g. -1|127 which sets the max height of the nether (dim -1) to 127
#Default: -1|127
Maximum heights:S:-1|127

#A comma separated list of minimum levels required to reach dimension
#In the form dimID|level
#Default: 1|13,-1|5
Minimum levels:S:1|13,-1|5,-28|8,-1006|12,-29|16,-1005|18,-30|20,-1007|21,-1014|23,-1015|24,-1016|25,-1008|30,-1009|31,-1017|32,-1024|33,-1018|34,-1021|35,-1022|36,-1025|36,-1050|37,-1051|38
