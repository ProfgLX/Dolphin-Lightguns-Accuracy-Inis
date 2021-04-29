# Sinden-Dolphin-Accuracy-Inis
Collection of inis to get 1:1 (close) aim accuracy with the Sinden Lightgun in the Dolphin emulator (Made by PiperCalls and Prof_gLX). Also included is a pack to remove crosshairs from games by PiperCalls.

# Sinden Accuracy Pack #1 (Made by PiperCalls and Prof_gLX)

This pack is mostly the "Rail" type shooters that do not require any character movement in-game. I have to figure out button assignments on the the rest & then I will release Pack #2 that will include all the rest of the Wii games that can be played with the Sinden. I have included a few of the non-"Rail" type shooters in this pack that I have been able to get the button assignments on the Sinden correct though.

The aim/crosshair has been dialed in on all these games. All aiming is pretty close to perfect for these games on my cabinet. When Prof_gLX and I were testing these games, there was some slight variations in "perfect" aim for me vs. what he was getting. If you experience any slight offset, reach out to me on Discord and I'll tell you how to make the minor adjustments for your setup.

To install the inis to dial in the aim just do the following:
1. Copy all the ini files in the zip into your User/Config/Profiles/Wiimote/ folder
2. Open Dolphin and for each of these games Right-Click on the game, Click Properties, Select the Editor sub-tab and in the User Config field type the following:
	[Controls]
	WiimoteProfile1 = {name of the ini file}
So for example, for House of the Dead: Overkill would be :
	[Controls]
	WiimoteProfile1 = HOTDOverkill_P1

There's probably a more automated way to share the game profile settings so you don't have to do this for each game but I haven't explored it yet. I haven't played with setting the buttons too much, just enough to test each game a bit so you might have to set some additional buttons to proceed further into some of the games. To see the buttons I've assigned or change them, just open the controller profile ini in Dolphin for that particular game.


# Dolphin crosshair removal (By PiperCalls) (crosshairs are for wimps!)

It is recommended to first test that your crosshair is dead on in the games before removing the crosshairs. Make any minor adjustments before removing them. You'll need your aim dead-on accurate to play without crosshairs.

So, to remove the crosshairs from the game:
1. Copy the folders with the Crosshair removal textures into your User/Load/Textures/ folder. Leave the textures in their individual game folders.
2. In Dolphin, click on Graphics, click on the Advanced Tab & under the Utility field select Load Custom Textures box.

The Crosshairs are completely removed in most of the games, there are a few games that I haven't been able to track down all the Crosshair textures. Once I get these tracked down I'll include them in the Pack #2. If anyone wants to help track these down, please share. Some of the non-Rail games I've just left the crosshairs as these are just an early preview of Pack #2.

Here are the games "patches" i've included with this pack (total of 45 games) along with some notes as needed. Buttons are mapped what worked for me, feel free to change button assignments.
 
Arcade Shooting Gallery
Attack of the Movies 3D
Big Buck Hunter Pro
Cabela's Monster Buck Hunter
Chicken Blaster
Chicken Riot
Chicken Shoot - this game has issues, you have to use dpad up to move your aim up and even with crosshair on and directly lined up with the target it 		still doesn't register hits all the time.
Cocoto Magic Circus
The Conduit - non Rail type, will def require some more buttons setup, haven't removed the crosshairs yet
Conduit 2 - non Rail type, will def require some more buttons setup, haven't removed the crosshairs yet
Deer Drive Legends - aiming is very slow on this game, maybe some Dolphin settings to speed it up?
Dead Space Extraction - aim is on but going to need to setup more buttons to progress through the game
Dino Strike
Eco Shooter: Plant 530
Fast Draw Showdown - Hold DPAD Down to holster gun
Ghost Squad
Gunblade NY & LA Machineguns: Arcade Hits Pack - haven't been able to locate the crosshair texture to remove it yet
Gunslingers
Heavy Fire Afghanistan - DPAD to hide
Heavy Fire Black Arms
Heavy Fire Special Operations
The House of the Dead 2 & 3 Returns
The House of the Dead: Overkill
Jurassic the Hunted
Link's Crossbow Training
Mad Dog McCree Gunslinger Pack
Martian Panic
NERF N-Strike Elite
Pirate Blast
Reload
Remington Great American Bird Hunt
Remington Super Slam Hunting: Africa
Remington Super Slam Hunting: Alaska
Remington Super Slam Hunting: North America
Resident Evil: The Darkside Chronicles
Resident Evil: The Umbrella Chronicles
Sin & Punishment: Star Successor
Sniper Elite
Target Terror
Top Shot Arcade
Top Shot Dinosaur Hunter
Wii Play
Wild West Guns
Wild West Shootout
Zombie Panic in Wonderland
