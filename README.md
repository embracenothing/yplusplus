# y++
one workout to rule them all, uwu

## why
I like yprac, I use it for my warmups and training, but there are things in the yprac client that bother me, this is a cfg that I made to improve my own experience. This is not a replacement for the yprac client, but rather a quality of life enhancement.
The main issue for me is speed and navigation, I want to be able to navigate between maps, custom workouts, and individual activities within the workout with a single keypress and without the need to alt+tab to the client. This cfg uses custom keybinds that reset back to default when leaving the map.

## installation
- make sure you have the yprac client and all the required yprac workshop maps
- copy the contents of cfg folder to the cfg folder in your csgo installation directory
- add the contents of add_to_autoexec.cfg file to your own autoexec.cfg file

This assumes that all your keybinds, crosshair and viewmodel settings are loaded with autoexec.cfg

All the workouts are created by using cfg files / aliases. Feel free to edit the preset cfg files to your liking.

You can create your own presets by using yprac client activity editor, playing them in game and then copying the contents of cfg\yprac\yprac_setting.cfg.

## general usage
- type "aim", "rcl", "bot" or "pre" in console to get started
- when loaded into the map, press keys 1, 2, 3 or 4 to start one of the workouts for that map (or navigate between maps in prefire)
- press E and Q to navigate to next/previous activity in the workout
- keys Z, X, C, and V start aim, recoil, bots and prefire, respectively
- press G to disconnect from the map and reset all keybinds to default (autoexec)

## aim
- workout 1: precision despawn taps - horizontal
- workout 2: precision despawn taps - horizontal and vertical
- workout 3: fast flicks - horizontal
- workout 4: fast flicks - horizontal and vertical

Press Z to restart current activity.

Workouts 1 and 2 are designed with the principle "slow is smooth and smooth is fast" in mind. (thanks, launders <3)

Workouts 3 and 4 spawn target after a short delay. target duration is 400ms. In the cases where the target is moving, it's speed is roughly equivalent to a head moving at deagle/smg speed.

As these workouts are all raw aim, I've disabled the viewmodel and faked the scoped weapons with a full-screen crosshair.
You can also enable the dark mode for each setting by editing y++/yaim.cfg

## recoil 
- workout 1: AK47 - 12, 15, 20, 26 and 30 bullet sprays
- workout 2: M4A4 - 10, 15, 20, 30 bullet sprays and M4A1-S - 15, 20.
- workout 3: Galil - 9, 17, 27, 35; Famas - 12, 28, 25; Krieg - 15, 30; AUG - 14, 20, 30.
- workout 4: MP9 - 12, 21, 30; MAC-10 - 12, 20, 30; MP7 - 11, 16, 30.

Every weapon in the workouts also has spam and spray transfer activities using the legacy dots feature.

Press X to change handedness.

## bots
- workout 1: strafing one taps (usp, scout, deag, awp)
- workout 2: strafing sprays (ak, m4a4, m4a1-s, galil, famas, krieg, aug)
- workout 3: peek walls (usp, scout, ak, mfa1-s, galil, famas, krieg, aug, deag, awp)
- workout 4: 1 bot rush react (usp, scout, ak, mfa1-s, galil, famas, krieg, aug, deag, awp)

Press C to restart current activity.

All of the presets have the extended arena enabled and you should be moving as much as possible, only stopping to shoot/spray. (thanks, furiousss <3)

## prefire

Entering prefire loads Anubis by default. (edit the end of y++/ypre.cfg to change this)

- map 1: Ancient
- map 2: Nuke
- map 3: Overpass
- map 4: Vertigo

(Change which maps keys 1-4 load by editing y++/binds/binds_ypre.cfg, there is also an option to specify binds for next/previous map and just cycle between them)

Keys Q and E navigate between the prefire paths.

Press V to restart current prefire path.

Prefire settings are: deag/scout, +100hp per kill, bots hostile, bot weapon is scout. I find these settings to be the most balanced, as it requires high precision but the bots aren't insta-killing you.
