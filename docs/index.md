# SCPF Area-14 Change Log
All changes to Area-14 will be documented here.
This web page is managed and updated by the Manufacturing Department. 
## Quick Links
* [Detailed Weapon Statistics](https://docs.google.com/spreadsheets/d/17A-Qn2cw7yGLl_R0BbsM4ODvLzdZUj_Z9p6ZllokMis/edit?usp=sharing)

## April 18th, 2021
This update was worked on by Spearritt

### Changed
- D Class bodies can no longer be searched
- Stolen Access Card/Hostile Access Card can no longer be picked up from body searching

### Fixed
- Body search interaction should now stay with the body (lol)

## April 17th, 2021
This update was worked on by Spearritt

### Added
- Body Searching Feature

## April 10th, 2021
This update was worked on by Spearritt and TheeDeer

### Added
- MD Lolipops
- New SCP-409 script

### Changed
- Honey Badger Sound

### Fixed
- Back-end issue with the load screen


## April 9th, 2021
This update was worked on by Spearritt

### Added
- SCAR-H (See detailed weapon stats)
- Honey Badger (See detailed weapon stats)

### Removed
- Ability to skip the loading screen, was causing back-end issues.
- Disabled kick on "Echo" failure.

## April 8th, 2021
This update was worked on by Spearritt

### Added
- O5-9 in game identifier

### Fixed
- Performance related improvements to the menu

## April 6th, 2021
This update was worked on by Spearritt

### Changed
- Reversed change which blocks death-screen camera movement

## April 5th, 2021
This update was worked on by Spearritt

### Changed
- Reduced CZ scanner alarm volume by 50%
- Updated Wall of ESiD

### Fixed
- Airlock vents being audible across site.

### Removed
- CES Easter Event stuff

## April 3rd, 2021
This update was worked on by Spearritt

### Changed
- Players can no longer rotate their camera when dead
- Radio is now hidden when dead
- Red Fox Alarm
- TSC Cells no longer close during a lockdown

### Fixed
- TOC Permissions
-Activity logger for TOC

## March 18th, 2021
This update was worked on by Christbru01

### Added
- Raiders no longer need to rejoin to select the hostile team

### Fixed
- Outside spawns for hostiles repaired and moved closer to the exterior breach point

### Changed
- General maintenance regarding access control

## March 10th, 2021
This update was worked on by Spearritt and Christbru01

### Added
- Vehicles will now despawn if the player who spawned it leaves the game.
- "motor destroy-all" to despawn all vehicles on the map.
- CD Request system now properly factors in and updates assigned SD's last time chosen for testing.

### Changed
- You must now hold a class of C or above to use the 'motor' commands on terminals. (D Class naughty bois)
- "motor destroy" will now only destroy vehicles you spawned.
- Info screens no longer count users in the menu towards their department's count

### Fixed
- No longer assigns multiple additional CDs if some deny the request.
- CDs replaced in the CD request system are no longer required to progress the request

## March 8th, 2021
This update was worked on by Christbru01

### Fixed
- Patched soda affect duplication issue (hopefully)

## March 7th, 2021
This update was worked on by Christbru01

### Changed
- Added "sd2" and "sru" private servers and updated admin permissions to reflect this

## March 6th, 2021
This update was worked on by Christbru01

### Changed
- Removed hostile card access to most swing doors in TSA due to CDs locking other CDs in/out
- CD Request system made viewable by non-CD/CE/Hostiles. Only L3+ and MaD members can initiate requests
- Fixed soda buff duplication method

## March 5th, 2021
This update was worked on by Christbru01

### Changed
- Fixed numerous bugs with the new update and server degradation issues

## February 26th, 2021
This update was worked on by Spearritt

### Changed

- Disabled Clicker on MaD "WIP Lock" doors

## February 25th, 2021
This update was worked on by Christbru01

### Added
- Improvements to the teleport preventions

### Fixed
- Weird error with billboardgui and accessorys named "Head"

## February 16th, 2021
This update was worked on by Christbru01

### Fixed
- 1208 + tool bug where you get teleported back to the chamber patched
- 034 no longer able to affect those in spawn. (Exploiters smh)
- 1230 no longer removes the player's clothes after returning from the dream world
- 002 no longer breaks if the player lost their hands from 330
- 330 no longer gives infinitely

### Added
- Reimplemented teleport exploit prevention code now that most forms of false positives have been removed. Be sure to watch for any false positives and report them if found.
- Exploit prevention client sanity checks

## February 15th, 2021
This update was worked on by Spearritt and Christbru01

### Fixed

- SD/MTF lag root cause by dummy client bogging down FPS with dummy movement replication on characters with large numbers of parts (such as those with extensions)
- Dummy no longer falls apart or has parts falling through the map occassionally in the menu
- Dummy no longer has hat duplication issues
- God mode issues where a player's health goes negative and never triggers .Died fixed

### Added

- Check to damage to prevent applying damage to those inside the pending spawn (No more exploiters shooting you while you're in the menu)

## February 10th, 2021
This update was worked on by Spearritt

### Removed

- Trello connection for MTF roles (Bye bye Trello, we hate you!)

### Fixed

- MTF Join issues

## February 9th, 2021
This update was worked on by Spearritt

### Added

- 2 new skin tones (https://scpf.nolt.io/5822)

## February 7th, 2021
This update was worked on by Christbru01

### Changed

- Shield swap reworked to take 0.5 seconds to equip from selection and 1.5 seconds after equip before being able to switch to anything else but no longer blocks from swapping from the shield to other items.
- P90 recoil reduced by about 50% due to recoil being way too high for it (It was 150% of the glock recoil). (Real life P90s are well known to have minimal recoil compared to most weapons of it's class)

## February 6th, 2021
This update was worked on by Spearritt

### Added

- Vulcan

### Changed

- ESiD Office permissions to allow A-1 access

## February 3rd, 2021
This update was worked on by Christbru01

### Changed

- Shield swap nerf reduction to now take 0.25 seconds from beginning to equip before shield comes to hand with a 0.75 second after before player can unequip as well as a 0.75 second delay after beginning to unquip the shield followed by a 0.25 second delay before they can equip anything else
- Taser draw time reduced to 0.15 seconds

### Fixed

- Taser randomly stopped being able to fire due to a firerate issue
- Tasing someone while they hold a shield no longer breaks their inventory

## February 2nd, 2021
This update was worked on by Spearritt and Christbru01

### Added

- TOC loadout changes during authorized riots
- Shield swap prevention. If you equip a shield you must deequip it before you can equip anything else (Draw/Stow delay also added so you can't change quickly when using a shield. Animations coming soon to visually show this)

### Changed

- Gate A is now on new door system
- M1911 buffed
- Guns now have a 0.3 second delay once equipped before they are ready to fire (May increase for some weapons and animations coming soon to visually show this)
- AK-12 burst firerate significantly reduced
- Taser range increased by 50% to a maximum effective range of 75 studs

### Fixed

- TimeGive and 034 will no longer give suppressors by default
- 261 causing cheat prevention trigger when using healing items while having increased walkspeed
- Updated the weapon statistics page to be accurate again

## February 1st, 2021
This update was worked on by Christbru01 and Spearritt

### Added

- Autoclicker spam prevention when equipping/unequipping tools (Now a 0.2 second delay when toggling a tool)
- Announcement reverberation

### Changed

- SD and MTF can now access and blow/repair the breach holes in private servers
- SD seniors+ can now access the G18
- SD LTs can now access any area SRU can access
- Improvements to alert lights
- ~~Alert lights now turn on while an announcement is playing rather than after~~ [REVERTED]

### Fixed

- Added additional checks to try and prevent 034 god mode

### Removed

- O5-9's in-game identifier and permissions

## January 31, 2021
This update was worked on by Christbru01 and Spearritt

### Added

- O5-12's in game permissions and identifier
- SCP-939 [CLOSED BETA: NOT YET ACCESSIBLE]

### Changed

- Internal improvements to stability for object protection system.
- ESiD office decor
- Unused AD offices have been MaD locked

### Fixed

- Issue where MD curtains caused server-wide kick
- Players getting stuck in loading screen when initializing the security system (Pending stress testing/confirmation)
- Crash-level spam from 989 triggers script

## January 30, 2021
This update was worked on by Spearritt and Christbru01

### Changed

- Knife hit boxing
- ESiD office decor at O5 request
- Object protection system reworked to reduce lag and increase stability

### Fixed

- Further gun system hit registration fixes

## January 29, 2021
This update was worked on by Spearritt

### Changed

- Slightly buffed Glock 17

### Fixed

- 999 Reset
- NVG Fix
- Medkit client error fix

### Removed

- CES Event Images

## January 28, 2021
This update was worked on by Spearritt

### Changed

- Balanced out gun stats. See quick links for further details.
- 173 scan 

### Fixed

- Hit Registration fixed! (Finally)

## January 27, 2021
This update was worked on by Spearritt

### Added

- New SCP-999 (with added snores and screams)

### Changed

- Modified back-end security to better performance

### Fixed

- SCP-173 performance issues

## Janury 26, 2021
This update was worked on by Spearritt

### Added

- Improved SCP-266

### Changed

- 173 Pathfinding

### Fixed

- Internal performance and security updates
- CMDR Permission bugs
- Stopped 457 and 173 being able to sit

## January 24, 2021
This update was worked on by Spearritt, specialforcest and Dr_D3stiny

### Added

- New 173!
- New Scanners at CZ's (Pending)
- Cmdr Management permission
- Height Measure in MD wing

### Changed

- Department Command can now access team command within reserved servers

## January 23, 2021
This update was worked on by Spearritt

### Notices

- SCP-173 has been temporarily disabled and locked while we migrate over to a new version of it. 173 will be back in a couple of days.

### Added

- Retractable Walls in 606 CC

### Changed

- Slightly buffed 606 kill

### Fixed

- 606 Delay Glitch
- 606 Insta-Killing/Sniping

### Removed

- CZ Stripe loading on server start-up. (Pointless)

## January 22, 2021
This update was worked on by Spearritt

### Changed

- Re-Written SCP-606. It's now more efficient and less of a server resource sponge.
- Restricted some tools being given using EventGive (Staff, Remote)
- SCP-606 now grows as it kills more players, awh it's so cute.

### Fixed

- 606 being too fast

## January 21, 2021
This update was worked on by Spearritt

### Changed

- DEA ToggleServerPublic permission
- DEA ReservedServer permission
- Spectate tool permission [to reflect request made by DEA HC]

## January 19, 2021
This update was worked on by Spearritt

### Added

- Radio now supports RichText. 
     - ``<b>Oh my god!</b> A <font color="#eb8934">D Class</font> is in Zone A!``

### Changed

- Removed CES 250,000 event content
- SD now have access to SCP-409
- Re-enabled the Level 0 Quiz

## January 18, 2021
This update was worked on by Spearritt

~~Some menu features may be temporarily unavailable due to on-going latency investigations.~~

### Added

- ~~Additional security to SCP-989~~

### Changed

- Closed vending machine door in staff cafeteria (SCP-173-J has gone back to bed.)
- Disabled and locked SCP-989 temporarily due to security concerns. 

## January 17, 2021
This update was worked on by Spearritt

### Added

- NVG mode for hostile agent and leader
- Added EventWinner permission node

### Changed

- Hostile Radio Permissions. L4+ and DEA Adviser + now have access to hostile channel during raids. (APPROVED BY O5-5)
- Hostile Leader Extension permissions

## January 16, 2021
This update was worked on by Spearritt and specialforcest

### Added

- CES Spawn
- CES event banners/posters

## Changed

- Changes to game credits
- DEA Level 4 Office

## Fixed

- Issue where 173-J could be moved and taken out of the vending machine
- Fixed knife blocks
- Fixed fire extinguishers

## January 15, 2021
This update was worked on by Spearritt

### Added
- SCP-173-J for 250,000 members events

## January 13, 2021

### Added

- Starling statue to SD spawn
- 289's touch part to bullet blacklist

### Fixed

- Fixed issue where cuffed SCed players would get cuffed in laggy servers

## January 12, 2021

### Fixed

- Fixed tablet UI issue

## January 9, 2021

### Added

- Event give command to CBRS
- CES1,2,3 to reserved servers

### Fixed

- Patched auto clicking struggle mini-game on cuffs

## January 7, 2021

### Added

- Better user interface for auto solitary
- Disabled players in solitary from being able to fire a gun (Wall-shooting prevention)

### Changed

- D Class will now have "SC-" on their rank tag when confined to solitary
- SC escape timer no longer considers dead players

### Fixed

- Exploit patches, details redacted.
- Fixed issue where players confined to solitary wouldn't be automatically released if they were still cuffed

## January 6, 2021
 
### Added

- Cuff struggle system
- Auto Solitary Confinement
- Ability to start/stop a cuffed player following you (binded to E key)

### Changed

- SCP-261 healing items now have a delay based on the amount of damage a player takes.

### Fixed

- General bug fixes, details redacted.

## January 3, 2021

### Added

- ToggleServerPublic command to foundation terminals

### Changed

- Activity logger logos are now centrally controlled
- Permissions for containment chamber viewing area doors are now correctly implemented

### Fixed

- Exploit patches, details redacted.
- SCP-034 duplication
- SCP-038 invisible brick blocking gun pellets

## January 2, 2021
 
### Changed

- SCP-034 now times out if not used within 5 minutes.

### Fixed

- Exploit patches, details redacted.

## January 1, 2021
🥳 Happy New Year! 🥳
 
### Fixed

- Multiple SCP exploit related patches
- SCP-038 cloning bug
- SCP-457 spreading fire to OBS windows
- Spinning light activation kicking everyone in the server

## December 30, 2020
 
### Added

- New interaction involving SCP-034: Who said cheaters never win?
- New interaction involving SCP-034: Mother desires ritual sacrifice.

### Fixed

- Routine bug patches relating to game security
- Exploit patches, details redacted.

## December 27, 2020
 
### Added

- Additional security checks on SCP-034

### Changed

- Updated various permissions regarding MTF spawn

### Fixed

- SCP 034 naming issue fixed relating to [REDACTED]
- SCP-[REDACTED] no longer gets stuck on chairs
- Hit registration fixes [REVERTED: December 28, 2020]
 
## December 25, 2020
 
### Added

- Fire extinguisher permissions added
- Developer alts now load their main account character appearances

### Changed

- SCP-034 revamped
- TSiD permissions updated to reflect change of office
 
### Fixed

- Handcuff patch preventing cuffed players from interacting with objects
- Vials permissions fixed
- Fixed critical map issues

## Prior Updates
Updates prior to what is listed on this web page can be found [here](https://devforum.roblox.com/t/scpf-area-14-update-notes/753213/104?u=spearritt).
