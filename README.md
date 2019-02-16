# Emulatrix

JavaScript Emulator based on RetroArch - Sega Genesis, Nintendo, Super Nintendo, GameBoy, GameBoy Color, GameBoy Advance, MAME32, PlayStation and DOSBox.

## Web:

https://emulatrix.lrusso.com.ar

## IMPORTANT: After clicking in 'Open ROM'

| PLATFORM  | HOW TO PLAY A GAME?  | FILE FORMAT | NOTE |
| :------------ |:---------------:| :-----:| :-----:|
| Nintendo | Select the game file from your hard drive. | NES | --- |
| Super Nintendo | Select the game file from your hard drive. | SMC | --- |
| GameBoy | Select the game file from your hard drive. | GB | --- |
| GameBoy Color | Select the game file from your hard drive. | GBC | --- |
| GameBoy Advance | Select the game file from your hard drive. | GBA | --- |
| Sega Genesis | Select the game file from your hard drive. | BIN | --- |
| MAME32 | Select the game file from your hard drive. | ZIP | Do not rename the file. |
| PlayStation | Select the game file from your hard drive. | BIN | --- |
| DOS | Select the game file from your hard drive. | ZIP | Will try to run AUTORUN.BAT |

## DOSBox useful commands:

| TYPE IN THE PROMPT  | RESULT  |
| :------------ |:---------------:|
| config -set "cycles=4000" | Default emulation speed |
| config -set "cycles=10000" | Faster emulation speed |
| config -set "cycles=15000" | Faster emulation speed |
| config -set "cycles=20000" | Fastest emulation speed |
| config -set "sbtype=none" | Sound Blaster disabled |

## Core files:

| PLATFORM  | URL  | CORE |
| :------------ |:---------------:| :-----:|
| Nintendo | https://buildbot.libretro.com/stable | fceumm |
| Super Nintendo | https://buildbot.libretro.com/stable | snes9x2010 |
| GameBoy | https://buildbot.libretro.com/stable | gambatte |
| GameBoy Color | https://buildbot.libretro.com/stable | gambatte |
| GameBoy Advance | https://buildbot.libretro.com/stable | vba_next |
| Sega Genesis | https://buildbot.libretro.com/stable | genesis_plus_gx |
| MAME32 | https://buildbot.libretro.com/stable | fbalpha2012 |
| Commodore 64 |https://github.com/rjanicek/vice.js | --- |
| PlayStation | https://github.com/tjwei/pcsxjs | --- |
| DOS | --- | --- |
