# Casually Competitive Script for TF2

This repo contains my scripts for TF2 and a copy of my autoexec file. The best bits include a togglable script
to hide only primary weapon viewmodels, a bind to vote for the next map when it's bugged and quick shortcuts for
common engie and spy things.

https://ko-fi.com/squidfysh (not required at all, but much appreciated).

## Installation
To install the scripts, paste each file into the TF2 cfg folder in your Steam installation folder:
%steam install folder%\steamapps\common\Team Fortress 2\tf\cfg

If you just want to use the script for one class, you must also have a reset.cfg file and a %class%.cfg file
for each class with the line "exec reset.cfg" otherwise the class specific scripts will be bound to all classes.

The [Default](https://github.com/Squidfysh/casually-competitive-script/tree/main/Default) folder contains the
files that must be preset for classes you don't wish to have custom scripts for and a reset.cfg file with the
default TF2 bindings. You can replace the default class files with the ones you would like to use. Be aware
that it may not function properly if only some scripts are used.

## Ok cool but what does it do?
This script adds a few significant features:
- MWHEEL UP = primary, MWHEEL DOWN = melee and Q = secondary (MWHEEL UP and Q and switched on medic)
- LEFT ARROW = Spy!
- DOWN ARROW = Thanks!
- RIGHT ARROW = kill
- UP ARROW = toggle a script that hides your primary weapon's viewmodel only (for spy it hides when you shoot)
  - ^ Compatible with using 1-5 for switching weapons!
- HOME = hud_reloadscheme
- END = set up tr_walkway (sv_cheats 1 & sv_allow_point_servercommand always)
- 7, 8, 9, 0 select loadouts 1-4 when CTRL is held
- Holding CTRL while pressing E asks for uber (masks uber when on medic)
- Holding CTRL while pressing z, x or c votes for the corresponding map, even when it's bugged
- NUMPAD 1-9 auto-switch you to play the corresponding class (CAPS must be held on spy)
- R to Eureka teleport to spawn on engie (hold CTRL to switch to tele exit)
- 1-4 instant-build corresponding buildings on engie (hold CTRL to destroy and hold CAPS to switch weapons)
- MIDDLE MOUSE BUTTON to instantly replace your sentry on engie
- NUM PAD to instantly diguise as the corresponding class on spy (hold CTRL for friendly disguises and CAPS to switch class)
- MIDDLE MOUSE BUTTON to reuse last disguise/change disguise weapon on spy

## Known Issues
- When enabling invisible primary viewmodels, you need to reselect your primary weapon for it to take effect
- While dead as the spy with invisible primary viewmodels enabled and your primary weapon selected you cannot
cycle between spectated players
  - To fix this; simply select your melee or secondary weapon (while dead, it still works)
