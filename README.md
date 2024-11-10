# Epoch-Fallujah-Package - Version 1.0

## Epoch-Version 1.0.7.1 Map: Fallujah (1.2.1)

- Without BattlEye filter. Edit BattlEye? No way!

Have FUN!

## Used mods:

Epoch-Antihack-Admin-Tools - Compatible with DayZ Epoch 1.0.7 + | [GitHub repo](https://github.com/BigEgg17/Epoch-Antihack-Admin-Tools)

WICKED AI 2.2.7 | [GitHub repo](https://github.com/f3cuk/WICKED-AI)

## Install:

1. Copy the DayZ_Epoch_26.Fallujah folder under "MPMissions" (use "PBO tool" for packing) to your Arma2 OA\MPMissions folder

	1.1 Enabling or disableing your own settings: dayz_code\configVariables.sqf

2. Copy the dayz_server.pbo folder to your Arma 2 OA@dayz_epoch_server\addons folder (or "PBO tool" for packing)

3. Download the map ["@fallujah"](https://www.moddb.com/games/arma-2/addons/fallujah)

3. Copy the folder ["@fallujah"](https://www.moddb.com/games/arma-2/addons/fallujah) to your Serverroot

## Epoch-Antihack-Admin-Tools

1. Copy the files from "AdminTool_dll_ini.7z" to your Serverroot

2. Unpack "KFC_Array_Builder_&_AdminTool_README" and read the instructions.

2. Edit the config.sqf in your Server.pbo in "\dayz_server\antihack\"

## Starting order:

1. Client: -mod=@fallujah;@DayZ_Epoch;  (use "Steamlink" --> "Extra/optional")

2. Server: ca, @dayz_epoch, @dayz_epoch_server, @fallujah

## (WAI) Custom static missions with rewards ;-)
(dayz_server\WAI\static\default.sqf)

1. Sector FOB / Edit Lootfile "sector_fob_loot.sqf" under: @DayZ_Epoch_Server\addons\dayz_server\sector_fob\

## Extra/optional: 

Serverstart with "Steamlink":

```
steam://run/33930//-connect=99.999.999.99%20-port=2302%20-mod=EXPANSION;@fallujah;@DayZ_Epoch;%20-nosplash%20-world=empty%20-nopause
```

with password usage:

```
steam://run/33930//-connect=99.999.999.99%20-port=2302%20-PASSWORD=password%20-mod=EXPANSION;@fallujah;@DayZ_Epoch;%20-nosplash%20-world=empty%20-nopause
```

## Contact

epoch{at}posteo.de | No support for used mods! Send your Server-IP. I will visit you! ;-)

## Licences

Note the respective licenses of the files from the other GitHub Repositories. Thx to at all publishers and [EpochModTeam](https://github.com/EpochModTeam/DayZ-Epoch)