# y++
one workout to rule them all, uwu

# why
I like yprac, I use it for my warmups and training, but there are things in the yprac client that bother me, this is an attempt to fix it that I made for myself. This is not a replacement for the yprac client, but rather a quality of life enhancement.
The main issue for me is speed and navigation, I want to be able to navigate between maps, custom workouts, and individual activities within the workout with a single keypress and without the need to alt+tab to the client. This cfg uses custom keybinds that reset back to default when leaving the map.

# installation
- copy the contents of cfg folder to the cfg folder in your csgo installation directory
- add the contents of add_to_autoexec.cfg file to your own autoexec file

# general usage
- type "aim", "rcl", "bot" or "pre" in console to get started
- when loaded into the map, press keys 1, 2, 3 or 4 to start one of the workouts for that map (or navigate between maps in prefire)
- press E and Q to navigate to next/previous activity in the workout
- keys Z, X, C, and V start aim, recoil, bots and prefire, respectively
- press G to disconnect from the map and reset all keybinds to default (autoexec)

# aim
- Workout 1: precision despawn taps - horizontal
- Workout 2: precision despawn taps - horizontal and vertical
- workout 3: fast flicks - horizontal
- workout 4: fast flicks - horizontal and vertical

Workouts 1 and 2 are designed with the principle "slow is smooth and smooth is fast" in mind. Thanks, launders <3

Workouts 3 and 4 spawn target after a short delay. target duration is 400ms. In the cases where the target is moving, it's speed is roughly equivalent to a head moving at deagle/smg speed.

As these workouts are all raw aim, I've disabled the viewmodel and faked the scoped weapons with a full-screen crosshair.
You can also enable the dark mode for each setting by editing y++/yaim.cfg

# recoil 
- Workout 1: AK47 
- Workout 2: M4A4 and M4A1-S
- Workout 3: Galil, Famas, Krieg and AUG
- Workout 4: MP9, MAC-10, MP7

Every weapon in the workouts also has spam and spray transfer activities using the legacy dots feature.

# bots
- Workout 1: strafing one taps (usp, scout, deag, awp)
- Workout 2: strafing sprays (ak, m4a4, m4a1-s, galil, famas, krieg, aug)
- Workout 3: peek walls (usp, scout, ak, mfa1-s, galil, famas, krieg, aug, deag, awp)
- Workout 4: 1 bot rush react (usp, scout, ak, mfa1-s, galil, famas, krieg, aug, deag, awp)

All of the presets have the extended arena enabled and you should be moving as much as possible, only stopping to shoot/spray (thanks, furiousss <3).

# prefire

Entering prefire loads Anubis by default. (edit the end of y++/ypre.cfg to change this)

- Map 1: Ancient
- Map 2: Nuke
- Map 3: Overpass
- Map 4: Vertigo
- 
(Change which maps keys 1-4 load by editing y++/binds/binds_ypre.cfg, there is also an option to specify binds for next/previous map and just cycle between them)

Keys Q and E navigate between the prefire paths.

Prefire settings are: deag/scout, +100hp per kill, bots hostile, bot weapon is scout. I find these settings to be the most balanced, as it requires high precision but the bots aren't insta-killing you.
