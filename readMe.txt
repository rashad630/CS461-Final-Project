README:  (demo video here: https://www.youtube.com/watch?v=qBS4w61-JBc)
-----------------------

-Whoever wants to be player 1 should select the 5 units when the game starts. Use the right arrow key to cycle through the characters. Press Z to select a unit. Once you have selected 5, whoever is played 2 will have the remaining 5 units to use. If you want to handicap yourself, press Z on a unit that is already selected to use up a selection slot (for example, if player 1 only wants 2 units and player 2 wants 8 units, player 1 should select their 2, then press Z 3 times on either unit they selected).

-In the map, use the arrow keys to move the cursor
-If you want to move a unit, press Z on the unit, and then Z on the tile you want to move them to, provided they have enough Move to make it that many tiles away.
-If you want to deselect a unit, press Z on the unit you selected. 
-Your phase ends when all of your characters have moved, so you need to move all units to end the phase. You'll know your phase has ended when all of your characters are no longer their dark grey sprite.
-Press C on any unit in the map to check their stats screen.
-When you move next to an enemy, you can cycle through which one you want to attack (and check their forecast) by pressing the right arrow key, provided that unit is next to more than one enemy and is in proper range.
-Press A in the forecast screen when you are currently checking the forecast of the unit you want to attack. You have to attack a unit once you moved.
-To close the combat results screen, press C. You can then move the cursor like normal.

-If your animation is showing a black screen, its an issue with the BattleCam game object. Change its location to show where the battleBG game object is.

The game is over when either team loses all of their units. That's when the narrator will say the iconic "GAME!" from Smash Bros.


Here are the combat formulas used:

Atk = Wep mt + Str
Defense = def
Damage = (Atk - defense) * 3 if crit
Hit = (skill * 4 + wep hit)
Avoid = Speed * 3
Battle accuracy = hit - avoid
Crit rate = Wep crit + (skill / 2)

The game uses a 1RN system. That means the random number will only be rolled once for every "chance" that is present in the game (game-beginning level-ups, hit rolls, crit rolls)

I tried my best to make the weapons reflect how the characters play in Smash, for example Falcon Punch is an extremely risky move that, when it connects, does tons of damage.








Credits
--------------------


Super Smash Bros. Brawl -  Nintendo, Masahiro Sakurai, Sora Ltd., Monolith Soft, Toylogic, Game Arts, Paon Corporation

Fire Emblem - Developers: Nintendo, Intelligent Systems, Atlus, Koei Tecmo, MORE
Publishers: Nintendo, Intelligent Systems, Koei Tecmo, Koei, Nintendo of America Inc., Nintendo of Europe

https://coolors.co/ - gradient background

IceJkai - Map sprites for characters

Sound effects & Music -  Super Smash Bros. Brawl

Battle Background & Tileset - Fire Emblem

Cursor sprite - Fire Emblem

Character portraits - Super Smash Bros. Brawl

Mario - Nintendo, sprite ripped by A.J. Nitro 
Peach - Nintendo, sprite ripped by Atz-Chan
Donkey Kong - Chrispriter Martinez
Diddy Kong - Chrispriter Martinez
Link - GregarLink10
Samus - Nintendo, sprite ripped by unknown
Pikachu - XxAlexsmashxX
Captain Falcon - GregarLink10
Ike - nicogamer337
Sonic - Sonic Team, sprite ripped by QuadFactor
