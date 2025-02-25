### 2024-01-18

- Updated to Hearthstone version 28.4.0.192412 (contributed by Endefx)
- Fixed an issue where multi-class cards would be read as neutral in some contexts (contributed by Endefx)
- Added a shortcut (T) to quickly access tavern brawl from the main menu (contributed by Endefx)

### 2023-12-24

- Updated HearthstoneAccess to support the new player experience (contributed by Endefx)
- Added support for the new catchup packs (contributed by Endefx)
- Fixed an issue that prevented players from entering the arena for the first time (contributed by Endefx)
- Added partial support for the tavern brawl mode (contributed by Endefx)

Known issue: HearthstoneAccess may lock up just after completing the apprenticeship. Restart the client to resolve this.

### 2023-12-09

- Updated the shop implementation for Hearthstone 28.2. Note that the shop layout has been completely redesigned, and now reflects the tabbed structure shown on- screen. (contributed by Endefx)

### 2023-12-06

- Updated to Hearthstone version 28.2.0.190416 (contributed by Endefx)
- Added support for the tavern spells mechanic in Battlegrounds (contributed by Endefx)

Warning! This update has introduced several major changes to the game. As a result, the shop will be temporarily inaccessible until we can account for the redesign.
In addition, the new player experience has been completely revamped. If you are still in the apprentice ranks, we recommend not to install this mod version as none of the new ui is accessible at this time.

### 2023-11-13

- Implemented the mass pack opening feature. To start, select a pack on the pack opening screen and press space. (contributed by Endefx)
- Fixed an issue where trying to open a pack that is locked, for example when it is part of a preorder, would cause a nonsensical string to be spoken (contributed by Endefx)
- The pack opening screen will once again automatically close after all packs have been opened (contributed by Endefx)


### 2023-11-09 (2)

- Updated to Hearthstone version 28.0.0.189384 (contributed by Endefx)

### 2023-11-09

- Disabled an inaccessible class unlock popup that recently started appearing for some players (contributed by Endefx)

### 2023-11-07

- Updated to Hearthstone version 28.0.0.189017 (contributed by Endefx)
- When reading your opponent's mana during gameplay, their current mana count will now be read along with the total amount (contributed by KeyWasFull)

### 2023-10-30

- Added accessibility for the new Hearthstone tutorial (contributed by Endefx)

Note: the skip tutorial button is currently inaccessible.

### 2023-10-17

- Updated to Hearthstone version 27.6.0.187190 (contributed by Endefx)
- Fixed an issue with choose one rewards where it was possible to claim an item that was already part of the player's collection, leading to unpredictable behavior (contributed by Endefx)

Warning! Blizzard has completely rewritten the Hearthstone tutorial in this version. If you are a new player, please wait for us to make it accessible with the mod.

### 2023-09-19 (2)

- Fixed a regression in Battlegrounds where pressing the O key would erroniously announce that there are no anomalies (contributed by Endefx)

### 2023-09-19

- Updated to Hearthstone version 27.4.0.185749 (contributed by Endefx)
- Added support for anomalies in traditional Hearthstone modes. The O key can be used to read them during gameplay. (contributed by Endefx)
- Added accessibility for the Battlegrounds collection manager. This currently supports hero skins, bartenders and strikes. (contributed by Endefx)

### 2023-09-06

- Updated to Hearthstone version 27.2.2.185054

### 2023-09-02
- When editing a deck in the collection manager, it is now possible to craft or disenchant the currently focused card by pressing Shift+Enter (contributed by Endefx)
- Restored the ability to change the format of a deck in the collection manager (contributed by Endefx)
- Fixed an issue in Battlegrounds where your final place would not be read in friendly matches and while spectating (contributed by Endefx)

### 2023-08-22

- Updated to Hearthstone version 27.2.0.183876 (contributed by Endefx)
- When using the T key to forge a card, this will now be correctly announced as forging (contributed by Yncat)
- When discovering a card, it is now possible to hide the discover interface using the tab key and inspect the game board (contributed by Endefx)
- Added an option to record textual logs of traditional Hearthstone games. Once enabled, the logs will be saved in a directory called "battle logs" found in the main Hearthstone directory (contributed by KeyWasFull)
- Added support for the new anomaly mechanic in Battlegrounds. They will be read along with the available tribes at the start of the game and when pressing the O key. (contributed by Endefx)

### 2023-08-01

- It is now possible to view multiple related cards in the collection manager (contributed by Endefx)
- Fixed an issue where pressing shift+F could cause a location such as Prison of Yogg-Saron to activate and target the enemy hero (contributed by Endefx)
- Twist will no longer be shown in the format picker menu when it is inactive (contributed by Endefx)

### 2023-07-25

- Updated to Hearthstone version 27.0.0.181554 (contributed by Endefx)
- Fixed an issue causing multi-target cards to erroniously present the discover interface in some cases (contributed by Endefx)
- Fixed an issue preventing the "Choose a target" prompt from being announced for additional targets of multi-target cards (contributed by Endefx)
- Fixed an issue where pressing the up and down arrow keys while choosing a target could skip over lines of the card being read (contributed by Endefx)


### 2023-07-11

- Fixed an issue causing a hang and reconnect in Battlegrounds on the 6 gold turn when quests are enabled (contributed by Endefx)
- Fixed an issue causing placeholders in Battlegrounds quest reward text to be read incorrectly (contributed by Endefx)

### 2023-06-28

- Updated to Hearthstone version 26.6.0.179020 (contributed by Endefx)
- Heroic duels are now accessible (contributed by Endefx)
- The new Twist mode is now accessible. See below for a known issue (contributed by Endefx)
- Arena and Duels will no longer appear in the modes menu if you haven't unlocked all classes (contributed by Endefx)

There are the following known issues in this version. They will be addressed in later updates:

- It is not currently possible to read the season rules for the Twist mode. For now, refer to the Twist announcement at <https://hearthstone.blizzard.com/en-us/news/23968054/introducing-hearthstone-s-new-mode-twist>.
- The ability to change the format of a deck in the collection manager has been temporarily disabled.

### 2023-06-10

- Added a workaround to prevent the mod from playing the wrong card in some rare cases (contributed by KeyWasFull)
- The Japanese language is now available (contributed by Yncat)

### 2023-05-31
- Updated to Hearthstone version 26.4.0.175913 (contributed by Endefx)

### 2023-05-22
- Various bug fixes and minor improvements for duels (contributed by Seva Popov, Nahana and Endefx)

### 2023-05-16
- The duels mode is now accessible. At the moment only casual duels are supported. (contributed by Seva Popov, Nahana and Endefx)

### 2023-05-10
- Updated to Hearthstone version 26.2.0.174258 (contributed by Endefx)
- It is now possible to read the list of members in a battlegrounds party (contributed by Endefx)
- Minions destroyed by Patchwerk in the hand will now be read (contributed by Endefx)


### 2023-04-10

- While opening a pack, the spacebar can now be used to reveal a random hidden card. This allows players to open packs much more quickly. (contributed by Endefx)
- It is now possible to change the format (standard/wild) of a deck while editing it in the collection manager. (contributed by Endefx)
- It is now possible to purchase packs in bulk with gold in the ingame shop (contributed by Endefx)

### 2023-04-04

- Updated to Hearthstone version 26.0.0.170824 (contributed by Endefx)
- Added an option to change the speed of minion attacks with shift+f. You will need to experiment with the different values to determine the one that is most suitable for your hardware and network. (contributed by KeyWasFull)
- Fixed an issue where pressing the escape key while in the sound options menu would erroniously open the game menu on top of it (contributed by Endefx)

### 2023-03-16

- It is now possible to read the quests on the event tab (contributed by KeyWasFull)
- Added a potential fix for the issue in Battlegrounds where the buddy button would not be read correctly in some cases (conttributed by Endefx)
- In battlegrounds, the minion type of buddies will now be read on the hero choice screen and the buddy button (contributed by Endefx)

### 2023-03-15 (2)

- Added initial accessibility support for the event tab of the journal (contributed by KeyWasFull)
Fixed some issues with the adventure chooser (contributed by KeyWasFull)


### 2023-03-15

- Updated to Hearthstone version 25.6.0.168788 (contributed by Endefx)
- Buddies have returned to Battlegrounds! Press D to see the stats and current cost of your buddy, and enter to buy.
- The sideboard mechanic used by cards such as E.T.C., Band Manager is fully accessible. When editing your deck, focus on E.T.C. and press spacebar to see his band! (contributed by Endefx)
- The Knights of the Frozen Throne adventure is now accessible (contributed by KeyWasFull)
- Known issue: It is currently not possible to start the new event using the mod. We are working hard and hope to resolve this soon.

### 2023-03-11

- In option menus, the current value of checkboxes and dropdown controlls will now be read (contributed by Endefx)
- Scrolling has been implemented in the social pannel. You will now be able to interract with all of your friends. (contributed by Endefx)
- Fixed an issue that allowed the crafting button to be pressed even if there was not enough dust to craft the card (contributed by Endefx)
- Changed the reading of minion enchantments to be more reliable (contributed by Endefx)

### 2023-02-26

- Fixed an issue that caused the haunting of cards during gameplay to be read incorrectly (contributed by KeyWasFull)
- Fixed an issue with the accessibility of the new free deck claiming experience (contributed by Endefx)
- In the collection, the expansion or set that a card belongs to will now be read (contributed by Endefx)
- Modified the corpse counter to bring it in line with the changes in patch 25.4. See the Hearthstone patch notes for more information. (contributed by Endefx)
- It is now possible to replay and skip the traditional Hearthstone tutorial (contributed by Endefx)
- The new sound options menu is now accessible. Note that all options related to sound have moved into this menu. (contributed by Endefx)

### 2023-02-14

- Updated to Hearthstone version 25.4.0.165029 (contributed by Endefx)
- The revamped free deck experience for new and returning players is now accessible. You will be able to play with your loaner decks and claim them once the trial period expires. (contributed by Endefx)
- Cards haunted by the card "Haunting nightmare" will now be announced (contributed by KeyWasFull)
- In the options menu, it is now possible to disable speech while Hearthstone is in the background (contributed by KeyWasFull)

### 2023-01-29

- It is now possible to interact with missing and invalid cards while editing a deck (contributed by Endefx)
- Restored the original behavior of the tab key in some horizontal menus (contributed by KeyWasFull)
- Added three new shortcut keys to the main menu: R to play ranked, A to play casual and O to open packs (contributed by Saladeuh)
- Fixed an issue preventing players from starting their first arena run (contributed by KeyWasFull)

### 2023-01-23

- Updated translations
- Added a "Enable debug logging for this run" item to options. Developers may
  ask you to use this if you are reporting an issue. (contributed by KeyWasFull)
- Fixed an issue related to browsing coins in your collection (contributed by
  KeyWasFull)

### 2023-01-17

- Updated to Hearthstone version 25.2.0.162867 (contributed by Endefx)

### 2023-01-15

- Achievement fixes (contributed by  KeyWasFull)

### 2023-01-13

- It is now possible to view and claim achievements in the journal (contributed by  KeyWasFull)

### 2023-01-05

- Updated to Hearthstone version 25.0.4.162171 (contributed by Endefx)

### 2022-12-30

- Support for purchasing arena tickets with gold (contributed by  KeyWasFull)
- Support for reading of darkmoon tickets in Battlegrounds (contributed by  KeyWasFull)

### 2022-12-26

- Fixed a bug where increases to spell damage were being reported incorrectly (contributed
  by  Endefx)
- Updated translations
- Various improvements (contributed by  HLLF)

### 2022-12-23

- Fixed a bug where a popup dialogue related to the event rewards track prevented
  Hearthstone Access from working correctly (contributed by  Endefx)

### 2023-12-22

- Support for the arena mode (contributed by  KeyWasFull)
- Internal changes in how modifier keys (ctrl, shift, alt) are handled
  (contributed by  HLLF)
- f14 and f15 can be used to disable and enable accessibility (contributed by
  HLLF)

### 2022-12-17

- Updated translations
- It is no longer possible to access the emote menu when spectating (contributed by Mazen)
- More fixes to multi-target cards (contributed by  KeyWasFull)

### 2022-12-15

- Battlegrounds party announcements (contributed by  KeyWasFull)
- multi-target card fix (contributed by  KeyWasFull)
- It is now possible to purchase items in the ingame shop with runestones (contributed by  LordLuceus)

### 2022-12-12

- Battlegrounds invite changes  (contributed by  KeyWasFull)
- When choosing a deck to play, it is now possible to read the number of ranked wins with its class (contributed by  KeyWasFull)

### 2023-12-10

- Signature cards are now properly read as such (contributed by  HLLF)
- code cleanup (contributed by  HLLF)
- Added support for challenging friends to battlegrounds (contributed by
  KeyWasFull)

### 2022-12-09

- Restored the reading of rewards track XP (contributed by  Endefx)
- The card reroll popup is now accessible (contributed by  Endefx)

### 2022-12-08

- Reverted the quicker shift +f attack since it was unreliable for some users (contributed by
  Endefx)
- Made the Death Knight and Demon Hunter prologues accessible (contributed by
  KeyWasFull)
- Updated translations
- When reading your level in the rewards track, it is now possible to find out your current xp and the amount required for the next level (contributed by  Mazen)

### 2022-12-06

- Improved the Death Knight corpse counter (contributed by Alex19EP)

### 2022-12-04

- The attack speed when using shift +f is now faster (contributed by  KeyWasFull)
- Fixes to the end of game screen (contributed by  JScholes and HLLF)
- Fixed the handling of choose one hero powers used in some solo adventures (contributed by  KeyWasFull)
- Fixed the tracking of unlocked classes (contributed by  Endefx)

### 2022-12-02

- Fixed the spectate button in the social panel (contributed by  KeyWasFull)
- It is now possible to read the runes on Death Knight cards in the collection (contributed
  by Endefx)
- Updated translations

### 2022-12-01

- Updated to Hearthstone Version 25.0.0.159202 (contributed by Endefx)

### 2022-11-30

- Added the Death Knight corpse counter (contributed by Endefx)
- Updated to Hearthstone version 25.0.0.158725 (contributed by Endefx)
