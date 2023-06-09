---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Changelog

{% tabs %}
{% tab title="v1.1.3" %}
## General

* Updated spark texture.
* Improvements for Bright atmosphere.
* Player won't receive the crystallization effect if wearing SCP-427 and touching SCP-409.
* Added Sanity timer to the Debug Hud 2.

## Rooms

* The door to SCP-005's containment chamber will be opened if SCP-005 appears inside SCP-409's containment chamber.
* Some design improvements.

## Items

* Added varinats of SCP-714 from SCP-914.

## Bug Fixes

* Fixed NVG and SCRAMBLE not increasing the brightness of the rooms.
* Fixed quick loading image.
* Fixed and optimized arrow images.
* Fixed an ability to open wooden doors in "cont2\_1123" event.
* Fixed MAV in the Pocket Dimension throne room.
* Fixed an issue where SCP-049 achievement couldn't be obtained when using SCP-268.
* Fixed Stamina cap not draining exactly where it needs to.
{% endtab %}

{% tab title="v1.1.2" %}
## General

* Added "Camera render interval" option.
* Added Voice Volume slider.
* Reduced chances of obtaining Key Card Omni from SCP-914 with Level 6 Key Card.
* The Heavy Ballistic Vest can be modified by SCP-914.

## Rooms

* Added SCP-066's containment chamber.
* Added an intermediate door to bypass elevators in "room3\_storage".
* Updated lightmaps.
* Updated texture for alcohol hand gel.
* Some design improvements.

## Items

* Added SCP-268.
* Renamed "Small First Aid Kit" to "Compact First Aid Kit".
* Tiny improvement for Compact First Aid Kit.
* Tiny improvement for Ballistic Vests.
* SCP-714 and Heavy equipment can be used to protect the player from Pocket Dimension bird planes in the trenches.

## NPCs

* NPCs that deal damage now have their damage scale with difficulty.
* SCP-008-1's walk speed is slower than their chase speed.

## Bug Fixes

* Fixed MAV after playing intro sequence.
* Fixed saves.
* Fixed downloaded languages cannot be deleted.
* Fixed default language not setting correctly.
* Fixes for Map Creator:
  * Fixed the English version of Map Creator doesn't show the text correctly.
  * Fixed the localize font unable to load.
* Fixed MTF step sounds.

## Map Creator

* Increased width of tab above the grid.
* Changed Manual link.
{% endtab %}

{% tab title="v1.1.1" %}
## General

* Tiny optimizations.

## Bug Fixes

* Fixed a bug with incorrect description of SCP-005 in Map Creator.
* Fixed SCP-860-1 dimension and all related MAVs.
* Fixed downloaded languages cannot be deleted.
* Fixed Map Creator events cannot be localized.
* Some fixes for event descriptions in Map Creator.
{% endtab %}

{% tab title="v1.1.0" %}
## Launcher

* Aligned resolution list.

## General

* Added a new feature that allows the player name a savegame with non-latin characters, like chinese, russian and etc.
* Added "Home" key, "End" key, "Delete" key and "Insert" key to switch insert mode. Abilty to hold left/right arrow to fast move cursor. Implement of Ctrl+C and Ctrl+V.
* Added a hitbox in "room2\_servers\_hcz" room preventing SCP-096 to be triggered through the bloody windows.
* Added some folders organization.
* Added language selection.
* Added SCP-066 achievement.
* Added "PRESS ANY KEY TO CONTINUE" string while playing startup videos.
* Added escape time.
* Added sound volume for dropping the items, so NPCs can hear your activity. Increased crouch and picking up sound volumes.
* Added more parameters for debug menu.
* Added text shadow option.
* Removed "playmusic" console command.
* Removed SCP-106 from SCP-005's containment chamber event.
* Improved fluid step sounds.
* Changed color of the decal created in SCP-914 on "ROUGH" mode.
* Converted .ini files to UTF-8 format.
* Finally made the "Bright mode" similar to original game.
* Optimized game a lot.

## Mechanics and effects

* Added a small chance to accidentally drop an item when trying to use it.
* Added dropping items without closing inventory with right click.
* Added a blood decal after killing the player.
* Added new color effects depending on player zone.
* Added a smooth stamina reducing effect while wearing the Hazmat Suit or SCP-714.
* Can no longer save inside the gate elevators, the Pocket Dimension, inside elevators and when SCP-914 is refining items.
* Every document, note and chatscreen has it's own texture.
* Some improvements for player's room detection. Might fix some problems with custom maps and new optimization system.

## Rooms

* Added buttons for containment door in SCP-049's containment chamber.
* "room3\_storage" changes:
  * Added Level 1 Keycard inside the "room3\_storage" area.
  * Added death message when falling down the elevator shaft.
* Added missing chatscreen in "room2\_office\_3" room.
* Changed type of door button being used in the Heavy Containment Zone's deadend checkpoint rooms.
* Improved SCP-205's containment chamber.
* Improved SCP-096's containment chamber design.
* Improved some rooms design.
* Tiny corrections for rooms description.
* Batteries on the map are now randomized.
* Dr. L's office harm player like inside the Pocket Dimension.
* Returned "Pipes\_NoRust" texture.
* Level 3 Keycard located in SCP-895's containment chamber now drops from a fallen guard.
* Increased SCP-005's spawnrate in the containment chamber.

## Items

* Renamed some console item names.
* Renamed Severed Hand to White/Yellow Severed Hand.
* SCRAMBLE Gear changes:
  * Added SCRAMBLE Gear variation without batteries.
  * Tiny battery rebalance for SCRAMBLE Gear.
  * The SCRAMBLE Gear a bit distances camera fog now. Also made a SCRAMBLE Gear's HUD a bit brighter.
* S-NAV 310 and blue NVG require now an 18V Battery.
* Nerfed NVG fog distance from 30 to 17.
* The white pill now cures the "Common Cold".
* Hazmat Suit/Gas mask changes:
  * Added a new Gas Mask/Hazmat Suit variation: Gas Mask/Hazmat Suit without fogging.
  * Players wearing Hazmat Suit are now able to pick up and drop items.
  * You can use items while wearing the Hazmat Suit with exceptions being similar to that of the Gas mask plus no First Aid Kit and no Syringes.
  * The Hazmat Suit now fogs up.
  * Very fine variations of these items no longer grant infinite stamina. Stamina is doubled.
  * You can now wear SCP-714 and the Hazmat Suit at the same time, but only if SCP-714 was worn before the hazmat suit.
  * Reduced defense time against SCP-049, but added for Hazmat Suit combined with SCP-148.
* SCP-714 can be put into the wallet.
* SCP-427 and SCP-714 cannot be dropped anymore without taking it off.
* Origami can be added to the clipboard.
* Night vision doesn't work inside the Pocket Dimension. If you'll use it, you'll get more damage.

## Menu

* Added degree symbol for FOV value.
* Added "PRESS ANY KEY TO WAKE UP" string for CWM loading screen.
* Added additional options menu. This was done in order to free up some space for settings.
  * Added in-game versions of the "Use launcher", "Subtitles", "Startup videos" and "Smooth bars" settings.
* Added highlight effect for slidebars.
* Tiny improvement for difficulties color.
* Removed extra spacing in credits.
* The subtitles setting has been moved to the "AUDIO" category.
* Remade options menu.

## NPCs

* Hazmat suit and SCP-714 now fall to the ground when removed by SCP-049.
* Reduces how long the Hazmat Suit protects the player from SCP-049 from 12 seconds down to 5 seconds. The Heavy Hazmat Suit changed from indefinite to 12 seconds.
* SCP-035's victim now slowly hurts player.
* Increased the spawn timer for SCP-106 when using SCP-914.
* Reduced SCP-096's speed.
* The MTF Units and SCP-049 now open linked doors in the same way as the player.
* SCP-066 is now visible on the S-NAV Ultimate.

## Map Creator

* Made the Map Creator to be compatible with latest BlitzPlus version.

## Bug Fixes

* Fixed a bug with Ulgrin not triggering on the player when he is reading a document.
* Fixed a bug with console bind.
* Fixed SCP-096 triggering while his face is hidden by fog.
* Fixed SCP-106 animation when getting hit by the Tesla Gate.
* Fixed windows textures for some rooms.
* Fixed the office door appearing to freeze in weird ways when leaving the room instantly.
* Fixed non-latin characters in loading screens not showing correctly.
* Fixed checkpoint monitors not turning at all.
* Fixed wrong textures for Class-D model in "room2\_nuke" and "room3\_2\_hcz".
* Fixed grammar a little bit.
* Fixed an ability to pick up items when you died.
* Fixed SCP-049 removing hazmat suit and SCP-714 at the same time.
* Fixed SCP-1499 not being taken off when the hazmat suit was equipped in the 1499 dimension.
* Fixed position of the SCP-895 pivot attracting player's camera while wearing night vision goggles.
* Fixed "ACCESS CODE" string going out of button image on different resolutions.
* Fixed autosave option text color when option is disabled.
* Fixed an issue caused SCP-106's collider to linger while using "disable106" command.
* Fixed "disable/enable966" console command not hiding/showing all SCP-966 instances.
* Fixed "ThreatAnnouncPossession.ogg" not playing at all.
* Fixed battery messages and sounds playing even if the game is paused.
* Fixed SCP-1025 not being in player's focus while reading (no darkness effect).
* Fixed light flash appearing ahead of time in Gate A area.
* Fixed SCP-106 collider not being teleported correctly.
* Fixed sound path for some SCP-294 drinks.
* Fixed the framelimit not working properly.
* Fixed a wrong sound of the wooden doors.
* Fixed a loading text's color timer getting out of sync.
* Fixed images disappearing after using ALT+TAB.
* Fixed a white pill not being be put in the wallet.
* Fixed cutscene in SCP-049's containment chamber not working at all.
* Fixed monitor overlay not hiding after turning off the security cam.
* Fixed an issue with wearable items of the same type not dropping when one of the items was equipped.
* Fixed height of NPCs teleportation.
* Fixed center coordinates of some rooms correcting player's/SCP-049's/MTF's teleportation.
* Fixed open door SFX for the forest door.
* Fixed SCP-096's idle ambient sound playing even if player teleported far away.
* Fixed an issue that caused SCP-008's container to get a closed state after loading a save.
* Fixed "STOP HIDING!" string not working while using pause menu.
* Tiny fix for dead guard position in the starting location.
* Tiny fix for map generation.
* Tiny fix for keypad slots.
* Tiny fix for S-NAV image position.
* Tiny fix for console.
* Minor bugfixes...
{% endtab %}

{% tab title="v1.0.3" %}
## General

* Added sound volume for crouching and picking the items up, so NPCs can hear your activity.
* Added smoke particles for all NPCs hit by the Tesla Gate.
* Improved gas mask fogging overlay.
* Updated TSS startup video.
* The HUD will be hidden when the player dies.
* SCP-005 can no longer be placed into the wallet.
* The player must use SCP-513 to get an achievement.
* SCP-914 changes:
  * Added new refinement for SCP-500.
  * SCP-914 is now slightly rebalanced.
* Optimized game.

## Menu

* Added "Master volume" and "Invert mouse by X-axis" options.
* Added "CONTROL CONFIGURATION" button.
* Renamed "Enable room lights" option to "Advanced room lighting".
* Made capitalization for buttons text.

## Mechanics and effects

* Blinking reduces blur.

## NPCs

* Added new messages when SCP-049 destroys the hazmat suit or removes the ring from the player.
* Changed SCP-049 eyes glow to blue.
* Tiny rebalance for MTF's shooting.
* Decreased detect distance for MTF.

## Rooms

* Added new death message for "room3\_storage" area.
* Added new room in the Entrance Zone.
* Tiny improvement for "cabient\_c.b3d" and "garbage\_bin.b3d" models.
* Made the rooms a bit brighter.
* Reduced SCP-005 spawnrate inside containment chamber.
* O5 Council Room code is now randomized.

## Bug Fixes

* Fixed "IsDead" parameter for guard.
* Fixes for SCP-966:
  * Fixed messages while using echo sound.
  * Fixed an issue where SCP-966 had one extra frame of idle animation while chasing the player.
* Fixes for SCP-294:
  * Fixed wrong color of the drinks refined in SCP-914.
  * Fixed multipliers for drinks effects.
  * Fixed blink and stamina multipliers that were reducing player stats on Fine and Very Fine settings.
  * Fixed a bug where SCP-294 didn't remove a master card from inventory while using.
  * Fixed SCP-008 and SCP-409 cups resetting their effects.
  * Fixed SCP-294 sometimes giving the wrong drink.
* Fixed an issue where Dr. Maynard's code could be the same as Dr. Harp's.
* Fixed the first aid kit that deals damage to the player if injuries are less than 0.5.
* Fixed a bug where fog color was stored in memory every time.
* Fixed ticket model.
* Fixes for SCP-860-1:
  * Fixed missing dark fog color.
  * Fixed Izumi sprite shifting one pixel to the left when blinking.
  * Fixed incorrect position of Izumi logs.
  * Fixed calculation of previous EventState3 value to prevent SCP-860-2's spawn from being skipped.
  * Fixed SCP-860-1 branches wrapping around the grid border and creating unreachable tiles.
  * Fixed a bug causing Logs inside SCP-860-1 to have a wrong scale after loading the game.
* Fixes for SCP-1162-ARC:
  * Fixed ability to use SCP-1162-ARC while using inventory.
  * Fixed SCP-1162-ARC that kills the player even if he has any item.
* Fixed non-facility rooms contributing to "Rooms found" parameter.
* Fixed untitled save files not correctly being named after the second one.
* Fixed "EscortTerminated" sound not working mos of the time.
* Fixed a bug due to which the pause didn't stop some timers and effects.
* Fixed incorrect sound volumes for sprinting and walking.
* Fixed certain NPCs sometimes appearing on the navigator and the blue night vision goggles' interface when they're not supposed to.
* Fixes for SCP-970:
  * Fixed items dropped from clipboards or wallets into the main hallway not creating clones.
  * Fixed clones not inheriting many of the properties of the cloned item (e.g. clipboard inventory).
  * Fixed "clones" of main hallway items seemingly vanishing after SCP-970 teleports the player (e.g. clipboards losing their items).
  * Fixed cloned items not removing after teleporing by SCP-970.
  * Fixed Strange Note from SCP-970 falling through floor when dropped.
  * Fixed glitched doors movement.
* Fixed removal voice lines being spammable by repeatedly approaching and backing away from SCP-049.
* Fixed an ability to move the head after death.
* Fixed 4th blood drop sound not playing.
* Fixes for pause menu:
  * Fixed "YOU DIED" screen sometimes appearing in place of "THE END" screen.
  * Fixed being able to unpause for one frame while dead.
  * Fixed mouse click not working in credits.
  * Fixed credits lines moves too fast and not smoothly.
  * Fixed the wrong menu would appear for one frame when switching menus, or components of one menu would stay on the screen for one frame when switching menus.
  * Fixed drawing a white or black texture on menu assets.
* Fixed MAVs:
  * Fixed MAV after deleting saved game.
  * Fixed MAV while playing in "NO SAVE" mode.
  * Fixed MAV after using "disable/enable049" commands.
  * Fixed MAV while trying to use a clipboard or wallet.
  * Fixed MAV on the forest created by the Map Creator.
  * Fixed MAV after killing SCP-035's tentacle.
  * Fixed MAV in the Pocket Dimension.
* Fixed normal step sounds not working after steepping on decals in the ending areas.
* Fixed an invisible collider being left wherever the player last fell or died.
* Fixed fonts in Map Creator.
* Fixed a bug where SCP-1048 event is applied for Dr. L.'s office.
* Fixed "room2\_js" overlapping with adjacent rooms.
* Fixed a console input box that is rendered through pause menu.
* Fixed upgraded NVG killing earlier around SCP-895.
* Fixed empty sound in "DoorBudge1.ogg".
* Fixed NPCs AI not being able to find correct waypoint on stairs.
* Fixed Burnt Note scaling.
* Fixed wrong SCP-409 texture.
* Fixed an ability to select a book.
* Fixed "RedVision" eyedrops texture saying "ReVision".
* Fixed "Stream channel not found" error spamming in console.
* Fixed Gate A that is visible from Gate B.
* Fixed an ability to press on the "BACK" button while deleting save game.
* Tiny fix for SCP-372's AI.
* Tiny fixes for location of the pause menu buttons.
* Tiny fix for heavy hazmat suit icon.
* Tiny fix for SCP-106 decals deceleration speed.
* Tiny fixes for some rooms.
* Tiny fix for slider highlight detection.
{% endtab %}

{% tab title="v1.0.2" %}
## General

* Improved SCP-939's texture.
* Tiny code optimizations.
* Nerfed SCP-005's chamber event.

## Mechanics and effects

* Added fluid step sounds.
* Added slow effect for SCP-106's decals.
* Added player's cough sounds in "room3\_storage" area.
  * Also the green gas kills the player.
* Improved SCP-106's retreat animation in the tesla gate.
* The tesla gate stops NPCs.

## Rooms

* Opened two doors in "cont2\_427\_714\_860\_1025".

## Bug Fixes

* Fixed button positions in "room2C\_gw\_2\_lcz".
* Fixed MAV while entering the SCP-970 loop again.
* Fixed MAV in SCP-914's containment chamber (the bug manifests itself while entering the "room2\_nuke" for some reason).
* Fixed electric box collision and ventilation grate lighting in "room2\_6\_hcz".
* Fixed SCP-500-01 amount in SCP-500.
* Fixed wrong zone sections for Map Creator.
* Fixed custom map shows a random seed in the menu.
* Fixed elevator door in "room2\_ic".
* Fixed GodMode doesn't protect from the Pocket Dimension flying columns.
* Hopefully fixed mouse movement.
* Tiny fixes for re-scaling.
{% endtab %}

{% tab title="v1.0.1" %}
General

* Added death message for guard.
* Improved auto save system. If you saved badly, you can return to the previous save.
* Renamed "Smooth HUD" option to "Smooth Bars".
* Reworked bright atmosphere mode.
* Optimized the game while using 100% of gamma.
* Optimized some rooms a little bit.
* Hopyfully optimized game on different resolutions.
* Tiny overlay optimization.
* Finished «SL\_monitors.png» file.
* Unlocked all difficulties.
* Decreased colored fog brightness.
* The fog began to change more smoothly.

## Menu

* Improved input boxes design.

## Rooms

* Removed "room2\_7\_hcz".
* Removed "room2\_3\_ez" event.
* Improved SCP-1123's event.
* Changed "096\_spawn" event rooms (from "room2\_2\_hcz" to "room2\_3\_hcz").
* Separated "room2\_elevator" and "room2\_elevator\_2" events.
* Some props are brighter now.

## Map Creator

* Sorted rooms list.

## Bug Fixes

* Fixed save screen in the SCP-1123's containment chamber.
* Fixed SCP-1123 is pickable through the window.
* Fixed a bug where SCP-895 spawns in LCZ.
* Fixed elevator panel positions in "room3\_storage" and "room2\_mt".
* Fixed "room2\_ic" can't be spawned on the map.
* Fixed SCP-173's AI.
* Fixed SCP-409's achievement can't be reached by interacting with crystallized Class-D.
* Fixed MAVs:
  * Fixed MAV while entering the SCP-970 loop.
  * Fixed MAV in SCP-035's containment chamber.
  * Fixed MAV in SCP-1499's dimension.
* Fixed missing door in "room2\_checkpoint\_lcz\_hcz" and "room2\_checkpoint\_hcz\_ez" rooms.
* Fixed a bug where SCP-714 and hazmat suit sometimes don't defend the player from SCP-049.
* Fixed a bug where you can't exit from SCP-294's overlay.
* Fixed SCP-008-1's attack AI.
* Fixed SCP-049-2 positions in SCP-049's containment chamber.
* Fixed missing door frame in "room2\_4\_hcz" room.
* Fixed SCP-106's decal on the wall in SCP-005's containment chamber.
* Fixed inventory slots amount after loading the game with another difficulty type.
* Fixed SCP-035's texture in "room2\_ez\_035" event.
* Fixed a bug where SCP-173 can stuck inside an office seat in SCP-008's containment chamber.
* Fixed "room2\_3\_ez" room design.
* Fixed missing ambient sound in "room2\_ez" and "room2\_2\_ez" rooms.
* Fixed electric box collision in SCP-008, SCP-096 and SCP-205's containment chambers.
* Fixed blood decal position under guard in SCP-895's containment chamber.
* Fixed blood decal position under player in SCP-1123's containment chamber.
* Fixed ability to save the game on endings.
* Fixes for SCP-1499's dimension:
  * Fixed double first chunk.
    * Fixed chunk objects spawn.
* Fixed the game doesn't load door positions properly.
* Fixed doors in "room2\_servers\_hcz".
* Fixed SCP-1048's paper texture.
* Fixed refinements for clipboard and wallet.
* Fixed wrong interface scaling.
* Fixes for SCP-294: - Fixed keypad isn't accurate. - Fixed duplicate buttons.
* Fixed keypad button interface isn't accurate.
* Fixed items in the wallet/clipboard aren't clickable/hard to click.
* Fixed ticket model.
* Fixed missing textures in "room3\_storage".
* Fixed SCP-1162's label wasn't renamed to SCP-1162-ARC.
* Fixed crouching in NoClip mode.
* Fixed doors in SCP-173's containment chamber.
* Tiny fix for "room2\_shaft", "cont1\_914", "room2\_ic" and "room2\_js" rooms.
* Tiny fix for item positions in "room2\_3\_ez" room.
* Tiny fixes for 4K resolutions.
* Tiny fix for monitor saving.
* Tiny fix for selected items.
* Tiny fix for credits.
{% endtab %}

{% tab title="v1.0.0" %}
_This version continues original game._

## Launcher

* Added YouTube, Discord and ModDB icons.
* Added Resolution Selection button.
* Added "REPORT A BUG!" and "SEE CHANGELOG" buttons.
* Removed Check for updates feature.
* Removed 16-Bit mode.
* Removed Graphics Driver Selection, which did not actually change anything anyways.
* Improved game icon.

## General

* Added anisotropic filtering.
* Added support for resolutions of up to 4k.
* Added Unicode support.
* Added subtitles feature.
* Added FOV option.
* Added warning startup video.
* Added "Apollyon" difficulty.
* Added extreme difficulty factor.
* Added screenshot key.
* Added auto save option.
* Added more easter eggs.
* Added frame to hint messages.
* Added ability to erase words faster.
* Added inventory size scaling with difficulty and custom inventory options.
* Removed Antialiased Text feature.
* Renamed most files.
* Optimized game.
* Converted most files to `.PNG`.
* Converted most `.X` files to `.B3D`.
* To obtain a new difficulty, the previous one must be completed.
* The Keter difficulty achievement will be saved after beating the one.
* Anti-aliasing option is automatically disabled for non-fullscreen modes.
* Loading screen images now scaled correctly.
* Combined room converters.

## Menu

* Added delete button for custom maps menu.
* Added option to (re)enable/disable the launcher and startup videos in-game.
* Added a sound when clicking on disabled checkboxes or buttons in menus.
* Added gray color for locked checkboxes and buttons.
* Added some space between the page indicator and the next/previous page buttons on the load game screen.
* Added button to restore all settings to standard values.
* Added new loading screen images:
  * Keycard.
  * HID Turret.
  * Radio Transceiver.
  * HK G36.
  * Anomalyous ducks.
  * Locking devices.
  * SCP-008, SCP-148, SCP-1048, SCP-1048-A.
* Improved console:
  * Added new console commands:
    * `106retreat`.
    * `money` or `rich`.
    * `doorcontrol`.
    * `unlockcheckpoints`.
    * `resetfunds`.
    * `newyear`.
    * `noblink` or `nb`.
    * `debughud` ( `game` / `player` / `scps` ).
    * `clear` or `cls`.
    * `codes`.
  * Added more names for NPCs.
  * Added short names for some commands.
  * Removed unnecessary console commands.
  * Improved font.
  * Renamed some item names (each item has own ID now).
  * Reworked `asd` console command.
* Removed unnecesary files.
* Improved SCP-682 and Night Vision Goggles loading screens.
* Improved loading screen itself.
* Changed the name of the "Custom" difficulty to "Esoteric".
* Using the "ESC" button has "BACK" button effect.

## NPCs

* Added new SCP-1048 drawings.
* Added two new diseases to SCP-1025: "Secondary Polycythemia" and the "Cannibal Plague".
  * Also overhauled the design of its pages.
* Added SCP-205's document.
* Added new SCP-035's emotion.
* Many changes to SCP-914:
  * Added SCP-1025 refinements.
  * Added a very special book.
  * Added Blank Document.
  * Added ability to downgrade Keycards.
  * Added a bad and a super battery.
  * Added ability to get electronics via Electronical Components.
  * Added worse and better clipboards and wallets.
  * Added a new sound for knob.
  * Added corrosive vest.
  * Added another hand.
  * Removed paper strips.
  * Improved image.
  * Replaced the doors by one-sided ones.
* Added bloody SCP-096 texture after killing someone.
  * Added own containment chamber.
  * Also improved chase theme.
* Added SCP-005 and SCP-409.
* Added SCP-500.
* Added new SCP-294 drinks.
* Added new achievment image for SCP-1048.
* Added 4th SCP-939 on the area.
* Added breath sound for SCP-008-1.
* Added orange healing duck.
* Added new janitor, scientist and body textures.
* Added bullet miss sound.
* Added badges for personnel.
* Added earphones for guard listening to music.
* (Re-)Added SCP-173's head rotating.
* Improved SCP-049-2 AI.
* Improved SCP-106's texture and animations.
* Improved anomalyous ducks texture.
* Improved D-Class animations.
* Improved MTF AI.
* Improved guard and SCP-049-2 helmet texture.
* Improved CI model.
* Changed SCP-049's model.
  * Also changed eyes to blue.
* Changed SCP-372's model.
* Renamed SCP-1162 to SCP-1162-ARC.
* Combined SCP-1048 and SCP-1048 Pen models.
* Combined texture for SCP-173's cell.
* Nerfed SCP-500-01.
* SCP-1123 can be picked up.

## Rooms

* Added glow to buttons.
  * Also added red ones.
* Added new bump textures.
* Added unique elevator buttons.
* Added elevator panels showing the floor that you are going to.
* Added O5 Council office.
* Added Entrance Zone endroom.
* Added one-sided and office doors.
* Added music for SCP-106's containment chamber and Maintenance Tunnels.
* Removed light cones.
* Removed quick loading from the Surveillance Room, SCP-939 area and SCP-966's containment chamber.
* Improved bump textures.
* Improved rooms design.
  * Added new props:
    * System unit.
    * Yucca bush.
    * Computer mouse.
    * Water cooler.
  * Added observation room for SCP-914's containment chamber.
  * Added observation room signs.
  * Added more interactable doors.
  * Added new textures.
  * Added elevator to SCP-008, SCP-079 and SCP-106's containment chambers.
  * Added vehicle in the intro sequence.
  * Added save monitor in the Surveillance Room.
  * Added checkpoint monitor in «room4\_ic».
  * Added Light Containment Zone medical bay.
  * Added new Heavy Containment Zone tunnel.
  * Added new Entrance Zone offices.
  * Improved SCP-895's model and image.
  * Improved office seat model.
  * Changed some rooms to Heavy Containment Zone style.
* Renamed all rooms.
* Rebalanced some keycard buttons.

## Items

* Added 3D models for SCP-860, Lost Key and coins.
* Added rusty texture for memorable coin.
* Added SCRAMBLE Gear.
* Added low battery sound for S-NAV, Radio Transceiver and Night Vision Goggles.
* Added Ballistic Helmet.
* Added bloody texture for papers and notes.
* Added infected syringes.
* Added Level 0 Key Card and Level 6 Key Card.
* Added new sounds for Night Vision Goggles.
* Added messages for eye drops.
* Rebalanced the S-NAVs.
* The Master Card can be used in SCP-294.
* The Hazmat Suit is now hunched over when put off.
  * Also added unique overlay.
* All electronics has a random charge.
* Ballistic vest reduces damage from NPCs.
* Equipping a wearable item is now delayed by a timer.
* Keys, badges and SCP-500-01 can be put in a wallet.

## Mechanics and effects

* Added dust effect while player's camera is shaking.
* Added spreading effect for blood decals.
* Added spark effect for broken buttons.
* Added bullet decals.
* Added new SCP-079 face images.
* Added crouch sound.
* Added walk and closed eye icons.
* Added smoothed HUD bars.
* Gasmask changes:
  * Added idle breathing.
  * Added wet effect.
* Added ability to swap items in inventory.
* Added green indicator for positive effects and more negative indicators.
* Added slightly blackout while reading a document or note and etc.
* Added bloody overlay.
* Added more D-9341 sounds into the intro sequence. Also added tiny blur.
* Added miss sound for NPCs.
* Added a colored fog depending on the player's area.
* Improved glass break and elevator beep sounds.
* Improved white smoke texture.
* Inventory, save screens, code doors and SCP-294 don't stop the game anymore.
* Crouching reduces stamina.
* Battery charges are now randomized.
* The tesla gate lights up the surrounding rooms.
* NVG protects eyes from the gas.

## Map Creator

* Sorted rooms by zones.

## Bug Fixes

* Fixed a sound for big containment doors locked by SCP-079.
* Fixed appearing of the gas from SCP-035's containment chamber in Maintenance Tunnels.
* Fixes for SCP-1048-A:
  * Fixed SCP-1048-A's scream being able to be heard anywhere.
  * Fixed double texture.
* Fixed SCP-049 spam-closing the door behind it, if the player tries to open it.
* Fixed SCP-106's eyes glowing in the dark and flying in midair while he is emerging.
* Fixes for SCP-173:
  * Fixed head poking out of its box when recontained by the MTFs.
  * Fixed distance on S-NAV Ultimate.
  * Fixed SCP-173 not breaking the glass in the Light Containment Zone test room event if the player looked away.
* Fixed breath sound while using "noclip" console command.
* Fixed button sound not working when not using launcher.
* Fixed annoying secondary lighting lever in the Electrical Center.
* Fixed messages being visible in the pause menu or console.
* Fixed elevators don't move decals.
* Fixed room lights not working most of the time.
* Fixed launcher options not saving when quitting.
* Fixed security camera bases rotating with the cameras.
* Fixed inventory not being fully centered while using clipboard/wallet.
* Fixed positions of some buttons.
* Fixed message being moved down if selecting a document, while a clipboard/wallet is open.
* Fixed brightness of the buttons guarded by 4-digit pass code.
* Fixed door types in HCZ checkpoints-endrooms.
* Fixed SCP-1162-ARC doesn't remove overlays.
* Fixed SCP-860-1 generation.
* Fixed the Gate A bug where SCP-106 spawns constantly.
* Fixed light rendering through wooden doors.
* Fixed time not being bound to FPS correctly.
* Fixed input boxes displaying too many characters for a frame, if too many characters are entered.
* Fixes for SCP-1025:
  * Fixed an exploit allowing the player to avoid SCP-1025 resetting by opening the inventory.
  * Fixed SCP-1025's appendicitis messages not showing up.
* Fixed multiple items appearing to be worn, when multiple items of the same type are held.
* Fixes for SCP-966:
  * Fixed SCP-966's walking animations.
  * Fixed echo sound spamming.
* Fixed being able to see SCP-1048 disappearing in Heavy Containment Zone test room when using the scanner.
* Fixed inventory single clicks being recognized as double clicks.
* Fixes for NVG:
  * Fixed SCP-895 and NVG interaction.
  * Fixed NVG not working against temporary blackouts.
* Fixed refined items of which the base version requires batteries being broken when spawned via command and removed the commands that acted as workarounds.
* Fixed Right and Down movement always overriding Left and Up movement.
* Fixes for intro sequence:
  * Fixed being able to walk/run while getting up from bed in the intro sequence.
  * Fixed decals disappearing after the intro sequence.
  * Fixed animation of balcony guard.
  * Fixed gurads not shooting at the player if the music guard has been triggered.
  * Cell door in the intro now closes, fixing a bug where the guards could get stuck in it.
  * Fixed Agent Ulgrin gets stuck after giving SCP-173 document.
* Fixes for MTF:
  * Fixed the MTFs not closing the door after recontaining SCP-173.
  * Fixed MTFs not announcing blinking or the presence of SCP-049-2.
  * Fixed missing P90 texture on the scope.
  * Fixed MTF SCP-049-2 voicelines not having a radio filter.
  * Fixed MTF spawning triggers outside Entrance Zone.
  * Fixed "stopsound" or "stfu" console command not stopping the MTF announcements.
* Fixed keycard, origami, SCP-513-1 models.
* Fixed breath sound while wearing SCP-714.
* Fixed and reworked the "revive" console command.
* Fixed tentacles, SCP-205, SCP-966, SCP-1048-A, SCP-066, SCP-860-2, SCP-049, the Pocket Dimension plane and guards at some points not respecting the "notarget" command.
* Fixed wrong paper texture on the props.
* Fixed SCP-079 door sound in the Surveillance Room.
* Fixed step sounds not being recognized correctly.
* Fixed flying models in the center of the world.
* Fixed ability to open menu and inventory while cutscenes.
* Fixed SCP-096 can't be triggered through the glass.
* Fixed missing waypoints.
* Fixed MAVs in SCP-1499 dimension and SCP-205's containment chamber after loading a save file.
* Fixed blink and stamina timers not being saved.
* Fixed positions of some items.
* Fixed paper texture on the spawned clipboard.
* Fixed broken textures, missing room props and lights.
* Fixed decontamination gateway triggers.
* Fixed severed hand scale.
* Fixed descriptions of some rooms.
* Fixed decals size not being saved correctly.
* Fixed double corrosion decal in the Emily Ross event.
* Fixed menu buttons have wrong width and height.
* Fixed Omni Key Card achievement image.
* Fixed text font for Burnt Note with Dr. Maynard's access code.
* Fixed smoke doesn't interact with fog.
* Fixed wrong decal blend in the Pocket Dimension.
* Fixed a bug where auto closing is applied for locked doors.
* Fixed ability to select an item without any effect.
{% endtab %}
{% endtabs %}
