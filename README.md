# Casually Competitive v1.0.1
## TF2 Script by Squidfysh

This repo contains my scripts for TF2 and a copy of my autoexec file. The best bits include a togglable script
to hide only primary weapon viewmodels, a bind to vote for the next map when it's bugged and quick shortcuts for
common engie and spy things.

The scripts are quite easily modifiable as almost every key is only bound in one location.

If your keyboard doesn't have a NUMPAD, the quick class changing, quick spy disguising and "technical" things
(eg. hud_reloadscheme) wont be avaliable to you.

https://ko-fi.com/squidfysh (not required, but much appreciated).

## Installation
The [zip folder](https://github.com/Squidfysh/casually-competitive-script/blob/main/casually-competitive-v1.0.1.zip) contains all script files, including the default ones.

To install the scripts, paste each cfg file into the TF2 cfg folder in your Steam installation folder:
%steam install folder%\steamapps\common\Team Fortress 2\tf\cfg

If you just want to use the script for one class, you must also have a reset.cfg file and a %class%.cfg file
for each class with the line "exec reset.cfg" otherwise the class specific scripts will be bound to all classes.

The [Default](https://github.com/Squidfysh/casually-competitive-script/tree/main/Default) folder contains the
files that must be present for classes you don't wish to have custom scripts for and a reset.cfg file with the
default TF2 bindings. You can replace the default class files with the ones you would like to use. Be aware
that it may not function properly if only some scripts are used (toggles for engie/spy are bound in reset.cfg).

## Ok cool but what does it do?
### Basic
- MWHEEL UP = primary, MWHEEL DOWN = melee and Q = secondary (MWHEEL UP and Q and switched on medic)
  - 1-5 still work for switching weapons (CAPSLOCK must be held on engineer for them to work)
- F = **action slot item** (spells, power-up canteen, etc), H = **inspect**
- LEFT ARROW = Spy!
- DOWN ARROW = Thanks!
- RIGHT ARROW = kill bind
- 7, 8, 9, 0 **select loadouts** 1-4 when CTRL is held
- Holding CTRL while pressing E **asks for uber** (masks uber when on medic)
- Holding CTRL while pressing z, x or c **votes for the corresponding map**, even when it's bugged

### Class Specific
- NUMPAD 1-9 auto-switch you to play the corresponding class (CAPS must be held on spy)
- R to **Eureka teleport to spawn** on engie (hold CTRL to **switch to tele exit**)
- 1-4 **instant-build** corresponding buildings on engie (hold CTRL to destroy and hold CAPS to switch weapons)
- MIDDLE MOUSE BUTTON to **instantly replace your sentry** on engie
- NUM PAD to **instantly diguise** as the corresponding class on spy (**hold CTRL for friendly disguises** and CAPS to switch class)
- MIDDLE MOUSE BUTTON to reuse last disguise and **change disguise weapon** on spy

### Toggle Invis Primary Viewmodels
- UP ARROW = toggle a script that **hides your primary weapon's viewmodel** only (for spy it hides when you shoot)
  - Compatible with using 1-5 for switching weapons!
  - Primary viewmodel for spy returns when cloaking

### Technical
- HOME = hud_reloadscheme
- END = **set up tr_walkway** (sv_cheats 1 & sv_allow_point_servercommand always)
- DELETE = open vgui tree for HUD editing (sv_cheats 1 & vgui_drawtree 1)

## Known Issues
- When enabling invisible primary viewmodels, you need to reselect your primary weapon for it to take effect
- While dead as the spy with invisible primary viewmodels enabled and your primary weapon selected you cannot
cycle between spectated players
  - To fix this; simply select your melee or secondary weapon (while dead, it still works)

## To-Do List
- Add toggleable script to unbind the scoreboard (for when you care too much about the stats)
- Add toggleable script to disable the voice and text chat (for when some asshole is ruining the game or you wanna stream)
- Fix Engie's weapons being invisible after placing a building

## Version History
### v1.0.1
- Fixed class quickswitch not rebinding after playing spy
