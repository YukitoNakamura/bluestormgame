# Bluestorm
Even though this is a repository, this is only for bug tracking purposes.

*This game is a work in progress and may have bugs or crash sometimes. Please report all bugs and crashes [here](https://github.com/YukitoNakamura/bluestormgame/issues).*

## Game Information
Bluestorm is a RPG Game set in a near-future world(2076):
> During a heist at a big bank corporation, the intrusion system detects invasion and promptly sounds the alarm, causing the building to go into lockdown. Unable to escape normally, you fight the guards and escape, also leaving the city. Three years later, you return and see everything changed, so you promise to unravel all secrets the city hides, alongside your long time best friends.

[DOWNLOAD](https://ouo.io/7t8elh)
[More info](https://yukitoscorner.com/bluestorm) 
[To report issues and mistranslations](https://github.com/YukitoNakamura/bluestormgame/issues)


## Changelog
---
### Build 2025-07-19
#### Added:
- Text above events. Characters or objects that provide quests will have a QUEST AVAILABLE text above them. Characters that are somehow important or interactable will have their names above them.
- Text signs to doors. Whenever a door leads somewhere, there will be a sign above it.
- Switched the menu to a "Kingdom Hearts" style with new features.
- Ratt and Thrax as party members, exclusive to THIS build.
#### Fixed:
- Cracked walls in East Area, which were wrongly passable in the last build;
- Buggy counters. Now you can interact with the barman and the Skytech clerk.
#### Returning:
- The Complex is finally back, with an added Trophy Room(unlockable via sidequests). Each cell has an energy door. The complex also has a sign above the gate.
- Cells: Basic cells are now available. In the Administration office, there will be a door with a Hallways sign above it, interact with that door to go to the hallways, then, go right to the first door marked Basement Level 1.
- Transport Helicopter is back, free for now. Push Page Down(RB/R1) and select **Call Transport**.
- Screen tinting now working again.

#### Bugs identified and not fixed
- Hide message window. For now, the message window cannot be hidden via keyboard or controller, only works with right mouse button. I'll see if I can get the plugin dev to fix it or fix it myself. Bluestorm.txt has been updated to reflect this.
#### Bugs identified and working on:
- When you switch party member positions around, the graphics will not update unless you leave and come back to the menu. This happens because the graphics are kinda independent from the menu itself;
- Character menu graphics simply appear instead of sliding in with the menu. Working on it;
- Quest Journal(Journal in the menu) lacks a description. I'm looking into a way to add it.
#### To do
- Rework the Subdue skill. For now, it will be disabled;
- Rework the damsels.

---
### Build 2025-07-05

#### Added
- Town Hall map added with first floor. Contains the basic services you'd find in a common town hall.
- Town Hall receptionist now has a information role. In case you don't remember where things are, you can go to him and ask where each department is. Some of his options are still locked, as they will be redone with more updates.
- Town Hall receptionist now has a Taxes menu. Yes, I plan to maybe add taxes to the game, but I need to check how to work out the battle prizes into the taxes. Taxes will be paid in a season basis once the system is fully implemented.
- Ratt's flat has been readded to the game, but it's not enterable yet.
- Some places now have openable doors, like the town hall and the protagonist's flat.
- Phone menu readded.
#### Removed:
- Call Transport, Status and PassTime choices on the phone menu. 
#### Reworks
- Reworked the property menu, to show options in plural instead of singular.
#### To do for July 12
- Work out quests 1 to 3;
- Readd the complex;
- Readd day-night cycle.
#### To do for the future updates:
- Readd the damsels;
- Readd the scenes;
- Readd the chopper feature;
- Work out story quests.
---
### Build 2025-06-21
#### Changed:
- The 20+ outside city maps have been condensed to 5(8 with the beach and additional housing complex maps). The city is now formed of north, south, east, west and downtown areas.
- Tilesets have changed from the default RPG Maker tilesets to Rinober's Futuristic City tilesets.
- The game contains only the Cypress Flats interior, with the rest coming next week.
- Protag's walking sprite is a placeholder, while I do the definitive sprites.
- No quests, they will be reimplemented in the July 5 update.

---
### Build 2025-03-15
#### Fixed
- Some bugs regarding the map and such;
- Some untranslated bits that have been reported.

---
### Build 2025-02-08
#### Added
- **Tech Revive** skill for our IT Specialist(Kaelyn). Uses 20TP, revives an ally and restores 15% of his/her HP. Warms up for 1 turn and has a 3-turn cooldown;
- Quit option under Phone Menu>Options. Read **bluestorm.txt**'s section 2.2 for more info. The file is in your game's root directory;
- Added info on how to start the story in the game to **bluestorm.txt**. Read section 2.3 for more info.
#### Disabled
- Kidnapping disabled for Nathalia. As of now, it won't work for her.
#### Updated
- Retuned Kaelyn's stats as an enemy. Now she hits harder, has more defense, more HP and is more agile.
#### To do
- Nathalia's battler spritesheet. Probably by a midweek emergency update;
- Spritesheets for Ratt and Thrax;

---

### Build 2025-01-25
#### Added
 - More quests, still not playable.
#### Fixed
- Fixed a crash caused by the **Ashland Way Gym** door. Now the game should allow you to enter it without crashing;
- Removed some buggy events;
#### Updated
- Bar dialog. Translated the bartender's lines to english;
- Now you can order a beer, which will replenish your party's health by 90HP. Instant use, though;
- Kung Fu Man's dialog. Most of his lines are now translated to english.
#### Remaining Bugs
- Random freeze happening sometimes. Haven't been able to track this thing down. Please report it in the [issues page](https://github.com/YukitoNakamura/bluestormgame/issues) if it happens with you.
### Todo
- Add the beer as a consumible item(probably by Feb 8th).
- Add more barfly variants. They are all stock RPG Maker characters right now;

---
### Build 2025-01-11

#### Added:
- A few more quests, but unplayable right now.

#### Fixed
- Some leftover bugs from the dec 28th build.
---
### Build 2024-12-28
#### Added:

- Main quests 1 through 3, all translated.

#### Fixed

- A few translation mistakes.

---
### Build 2024-12-14
#### Fixed
- After subduing Kaelyn, her image didn't vanish from the screen. Now it should;
- Battle with **Kaelyn** not ending after tying her up. The battle should now end properly;
- Fixed some typos regarding Kaelyn's kidnapping battle.

#### To do
- Work out some of the character's battle sprites. Nathalia's and Ratt's are unfinished right now.

These may go to the next build

---
### Build 2024-12-11
#### Fixed:
- Not able to sleep to pass time. Now added a feature for it on the bed;
- Music fixed in the reported locations.

#### Added
- Added **Pass Time** feature to the phone menu.
---
### Build 2024-12-02
#### Added
- Personal transport. Will work only if outside. Right now, it only teleports you to your home or your complex. In the future, it will be reworked to detect where is your effective home, once more player houses are unlocked;

---
### Build 2024-11-23

#### Added
- **Tie Damsel to bed** feature;
- Art for the **tie damsel to bed feature**;

#### To do
- Add more storage bondage pics;
- Fix the **bride damsel on bed code**.

#### Removed:
- **Marriage Necklace** from the cabinet in the apartment.
*Bride damsel on bed, which requires the marriage necklace, is buggy. I'll see if I can fix that bug for the **November 25th emergency update**.*
---

### Build 2024-10-12 beta

#### Changed
- Nathalia now has **tied up to chair** art.

#### To do
- Add pics and bed tie functionality;
- Add pics to storage bondage.

---

### Build 2024-09-28

#### Changed:
- Added high resolution pics for Nathalia during talk.
- Added the Forced Marriage system back;
You can find the necklace in the cabinet right beside the computer desk. Just press action on it.
---

### Build 2024-09-14
#### Fixed
- Character display bug in battle, that persisted since the new battlers were introduced.

---

### Build 2024-08-09
#### Added
- Kaelyn to the storage area.

#### Fixed
- A few mistakes I spotted, along with version mistakes.

---
### Build 2024-07-26

#### Added
- New damsel: Kaelyn Summers, a pretty, dark haired girl, who lives in Buckinstone Ridge. She is the second damsel and will be the second female party member in the future. She can be found either in the Plaza Square(south of government plaza) or in her apartment;
- New class: IT Specialist, Kaelyn's exclusive class. IT Specialists can inflict confusion upon enemies, through their Digital Scramble skill, along with other skills;
- Generic animation for the **Subdue** skill;
- Row Formation now available;
- Credits screen.

#### Fixed?
- Nathalia's chat graphics now have a higher resolution.

#### Changed
- Battle mode is back to **Side View**;
- Battle Engine Core's functionality is back to the game, with better AI and much better battles;
- Nathalia's class changed to Fighter;
- Battles now light up to normal colors after the emerge message, even if they happen during the night. Only a few specific battles will have environment colors;
- Game now runs in 1920x1080;
- Battle command and battle status windows now have a transparent background.

#### Removed
- Nathalia's old sprites, since the game is now in side view, her front view sprites were removed from the game.

---

### Build 2024-07-15

#### Fixed
- Nathalia could not be kidnapped after her battle in build 2024-07-12. Now, you're able to abduct her after battle;

#### Changed
- Paralysis after Barrage now remains for 2 turns. It varied from 1 to 2 before;

---

### Build 2024-07-12

#### Added
- Ability to upgrade the Complex with one extra floor that has five captive spots;
#### Fixed
- Nathalia's timetable, left blank in **build 2024-07-05**(oops?);
- Nathalia's graphics. Now the graphics will show up correctly;
#### Removed
- **Storeroom**. Feature moved to the **Complex** in **Duke Lane**, with 3 initial spots and 5 more per upgrade, closing on 2 upgrades;

*The complex can be obtained for free during the beta, but will cost a lot of money in the final game.*

[Download](https://www.patreon.com/posts/bluestorm-v2024-108011693)

---

### Build 2024-07-05

#### Added
- Added a kidnapping battle for Nathalia. Now you can't simply take her like in build **2024-07-01**, you have to fight and capture her before she is added to your team;
- Added **GabWindows**, dialogues that show up in the upper area of the screen and don't stop gameplay;
- Added a **crime timer**.
#### Fixed
- Screen tinting feature. Now the screen will tint according to the hour of day;
- Tuned the time control function. Each game minute now corresponds to 2 real life seconds instead of 3;
- Some mistranslations in the skills.
#### Updated
- Updated some of Nathalia's dialogs, added a few and fixed some;
- Added some expressions for Nathalia's dialogs in the Skytech Store. Her storeroom graphics will come later;
- Nathalia's statistics as an enemy. She has more HP and hits harder. May be retuned in the future;
- Ratt's **Barrage** cooldown reduced from 4 turns to 3;
- Protag's **Military Training** cooldown increased to 1 turn from 0.

#### Changed
- Battle View is now Front View;
---

### Build 2024-07-01

**Added**
- Nathalia as a kidnappable girl;
- Plaques to indicate locations in the main map;
- Day of week to the clock menu(page down>status);

**Fixed**
- Some untranslated bits;
- Reimplemented character schedules;
- Location opening times(not all);
- KeyboardConfig menu now shows up on Options;


---
### Build 2024-06-28
**Added**
- Translations from portuguese to english;

- Closed off a few features, as they are not needed;

**Fixed**

- Cypress Flats receptionist moving to wall block;

- Ratt's Flat causing the protagonist to be frozen;

**Temporary fixes**

- Shop and location opening times;

- Some character schedules;

**Unsolved bugs**

- Screen tinting doesn't work;

- Untranslated bits;

- Keyboard Config not showing up(will be fixed in the next version)

*Temporary fixes: Need to wait for a plugin to be fixed before I can permanently fix it.
