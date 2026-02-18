##############################################################################
##############################################################################
###              DISCLAIMER: I DID NOT MAKE THE ORIGINAL GAME              ###
###                (AKA. BALDI'S BASICS CLASSIC REMASTERED)                ###
###               THE ORIGINAL GAME WAS CREATED BY MYSTMAN12               ###
###                    (http://basically-games.itch.io)                    ###
##############################################################################
##############################################################################

Baldi's Basics Classic Remastered ModMenu v1.3.0 by Fasguy
Compatible Game Version: v1.1

INFO:
IF YOU WANT TO USE THE MOD, THEN YOU NEED TO HAVE THE ORIGINAL GAME ALREADY INSTALLED.

############################### HOW TO INSTALL ###############################
Video Tutorial: https://youtu.be/vAZmy1_ktlk
1. Download and Install BepInEx 5 (https://docs.bepinex.dev/articles/user_guide/installation/index.html)
2. Go into the "BepInEx" folder.
3. Go into the "plugins" folder.
4. Put the entire "ModMenu" folder into the "plugins" folder.
5. Start the game.
6. Press TAB in-game to open the ModMenu.


################################# HOW TO USE #################################
TAB:				Open/Close ModMenu


################################# CHANGELOG ##################################
v1.3.0 (Game v1.1)
+ The ModMenu can now be localized.
+ Added error handler, for when the ModMenu can't patch parts of the game.
+ New modifier to allow the Portal Poster on any wall.
+ Characters with a party variant can now be spawned as said variant.
+ Added customizable hotkeys.
+ Presets can now be deleted directly from the ModMenu.
+ Added Pitch, Speed and Loop MIDI modifiers.
+ New option to toggle Music corruption.
+ "Tutor Baldi" and "Slender Tutor" have been reimplemented as "Happy Baldi" and "Slender Baldi" respectively.
+ Music can now be played/stopped directly through the ModMenu.
* General performance improvements.
* Ending the party event early no longer throws an error, when the event is naturally supposed to end.
* Changing the clown vomit swap time now resets the currently running iterations to prevent high-value deadlocks.
* Fixed Baldi hearing the player and the secret ending triggering in YCTP behaviour "skip with all correct, expect impossible question".
* Fixed Cloudy Copter's Wind force value not being applied to newly spawned instances.
* The Free Run option in the Fun Settings modifiers now only enforces it on the main menu, instead of toggling it during an active session.
* The scene list is now split into modes and labeled properly.
* Fliparoo now works properly together with Mirror Mode.
* Fixed a coroutine error, when passing through one of Arts and Crafters' triggers while he's disabled.
* The main menu fun settings buttons are synchronized in real time.
* The main menu NULL and Glitch game mode buttons are synchronized in real time.
* Rules in Principal's Rules modifier can now be restored from presets.
* Collecting Notebooks through the ModMenu now properly plays the Schoolhouse Escape song, when reaching the required total.
* Exits no longer break when collecting all Notebooks, while still standing inside the spawn area.
* The "Collect Notebooks" option is now influenced by the "YCTP Behaviour" modifier.
* The game now uses a custom save file while using the ModMenu, to prevent the NULL achievement from being granted after uninstalling.
* The ModMenu no longer disappears when opening a dropdown field in the launcher.
* The color selector now gets revalidated, when using the sliders.
* "Jump Anywhere" no longer stacks with Playtime's jumprope.
* The "Lights Out" modifiers of the player and Principal no longer reset between scenes.
* Teleporting to exits with noclip enabled no longer places the player in the ground.
* Beans' "Lethal Touch on Gum Wad" modifier now works independently of Beans' "Lethal Touch" modifier.
* Secret codes from the YCTP can now be toggled directly through the ModMenu.

------------------------------------------------------------------------------

v1.2.0 (Game v1.1)
+ You can now spawn multiple instances of a character at the same time.
+ You can now despawn individual instances of a character.
+ The character teleporter has been extended to allow the teleportation of individual instances.
+ Notebooks can now be collected directly through the ModMenu.
+ New modifier to skip the YCTP.
+ New modifier force the critical error screen chance to be 100%.
+ New modifier to prevent game-ending deaths from quitting the game.
+ New modifier that allows the user to change the game's MIDI SoundFont.
+ New modifier for manipulating Mrs. Pomp's reset time.
+ New modifier to adjust Cloudy Copter's wind force.
+ New modifier to adjust how long Beans' gum gets stuck on characters.
+ New modifier for manipulating how long Chalkles will wait before locking a room.
+ New modifier to adjust how long Chalkles locks a room.
+ Re-Implemented "Activate in Spoop-Mode" into the "Classic, Yet Again" plugin.
+ New modifier to adjust the min and max amount of whirlpools for the flood event.
+ New modifier to adjust the max height and rising speed of the water for the flood event.
+ New modifier to adjust the flood event's movement multiplier.
+ New modifier to adjust the min and max amount of flippers for the gravity event.
+ New modifier to adjust the initial flipper spawn delay for the gravity event.
+ New modifier to adjust the gravity event's min and max amount of time to respawn flippers.
+ New modifier to spawn Null in the glitch balloon variant.
+ Characters can now be assigned as a light source, for the lights out event.
+ Lights out light colors can now be adjusted by the player.
+ The strength of light sources during the lights out event can now be adjusted.
+ Beans' gum movement multipliers can now be adjusted.
* Corrupted config files don't prevent the ModMenu from starting anymore.
* Almost all values can now be adjusted without already being in a game scene.
* Enabling the "Hard mode" fun setting while in the YCTP no longer softlocks the game.
* Fixed "Lethal Touch" not working on chalkles.
* Fixed an issue that prevented Null from breaking windows, when "Ignores player trigger" is active.
* Camera positions are now persistent through in-game sessions.
* Fixed an issue that caused Principal to infinitely send the player to detention.
* Dropdown fields no longer expand outside of the usable UI area.
* The UI now properly refreshes, when elements get added/removed.

------------------------------------------------------------------------------

v1.1.0 (Game v1.1)
+ The ModMenu now has a starting page, which shows some general information about the ModMenu.
+ "Vanilla" and "Classic, Yet Again" now have individual plugin icons.
+ The reference resolution of the ModMenu can now be controlled through the settings.
+ Added new option that allows the game's Fun Settings to work while playing Endless mode.
+ Added new option that allows the game's Fun Settings to work while playing Null/Glitch style.
+ The Fun Setting "Mirrored" can now be toggled directly through the ModMenu.
+ The Fun Setting "Lights Out" can now be toggled directly through the ModMenu.
+ The Fun Setting "Hard Mode" can now be toggled directly through the ModMenu.
+ The Fun Setting "Free Run" can now be toggled directly through the ModMenu.
+ Lethal touch can now be enabled for Beans' gum wad.
+ Baldi's appraisal time can now be changed through the ModMenu.
+ ModMenu values can now be reset to default, wherever a default value exists.
* Setting a custom jump amount for Playtime now requires enabling "Override Jumprope values".
* Switching from Null/Glitch style to another scene no longer breaks the "Quit" button in the pause menu.
* Null no longer tries to make lights flicker, while the "Lights out" Fun setting is enabled.
* Highscores can no longer be saved, while the ModMenu is installed.
* FourtyTwo balloons no longer break in hard mode.
* Fliparoo doesn't potentially invert the horizontal mouse movement anymore, when loading a preset.
* Sprites no longer cull too early, when manipulating the camera fov.
* Switching to a Free Run scene will now automatically enable the "Free Run" Fun Setting.
* Fixed some general issues with loading presets from the main menu.
* The character modifier "Enabled" can now changed through the bulk editor.
* The bulk editor menu now gets properly updated when values change.

------------------------------------------------------------------------------

v1.0.1 (Game v1.1)
* Audio Vomit now works even when the in-game launcher is disabled.
* Mrs. Pomp can properly play her "Zero" audio again.
* Entering one of Chalkles' rooms while it's disabled no longer causes the room to lock anyways.
* Null is no longer affected by Baldi's slap speed randomizer setting.
* The game no longer softlocks, when opening the ModMenu during a Menu->Game or YCTP->Game transition.
* Fixed an issue that caused Null projectiles to be tethered to the player camera's rotation.
* The default "Character activation distance" value has been lowered from 10 to 5.

------------------------------------------------------------------------------

v1.0.0 (Game v1.1)
* Initial release.