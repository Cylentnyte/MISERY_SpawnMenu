MISERY Spawn Menu
By Cylentnyte

This is a port of the Spawn Menu Mod by Skidz to work with MISERY 1.2

All vanilla and MISERY objects can be spawned through the spawn menu, accessible from the
pause screen during any single player game. Starting a new game is not needed, this is
compatible with current saves.

Objects are listed by their variable name and may need some trial and error to sort out what is what.

Install:
- Make sure you are running STALKER CoP 1.6.02
- Install MISERY 1.2 (MISERY 1.0 + Patch 2)
- Drag and drop the gamedata folder into your main CoP directory, overwriting when asked.
- Open "fsgame.ltx" in Notepad and find the line:

$game_data$             = true  | false | $fs_root$       | gamedata\

- Change it to:

$game_data$             = true  | true  | $fs_root$       | gamedata\

A "Vanilla only" version has been added under the "CoP MISERY Spawn Menu 1.0 Vanila Only" folder.
This only lists vanilla items in the spawn menu, leaving the rest of MISERY to be explored normally.
If you would prefer this, drag and drop the gamedata from that folder into your CoP folder instead.

Version notes:

1.0:
- Mod created

----------------------------------------------------------

Credits:

Spawn Menu Mod, by Skidz
MISERY, by the MISERY team
