# DFU-Mod_Armor-Reduces-Damage-Taken-Instead-Of-Avoiding-Overhaul
Second Mod I Made for the Daggerfall Unity Project.

WHAT DOES THIS MOD CHANGE AND WHY?

Armor has been changed from having the D&D "Armor Class" rule-set, where better armor would give the wearer a better AC, which would make them harder to hit. This mod changes this entire system, now better armor now instead REDUCES how much damage is taken when hit by a physical attack. Similar to more modern Elder Scrolls games, such as Oblivion, this has more detail than that system though.

Skills are now what determines your odds of avoiding an attack completely or not. Armor is there to help protect you when you are unable to avoid an attack. 
With this, the dodge skills has a MUCH higher factor in your avoidance chances, double from classic values. This also works the same for all enemies as well.

With the theme of wanting skills and innate traits and abilities having more impact on a characters ability to fight well, weapons have had their Hit Bonus 
nerfed massively. That daedric sword will now give +14 to the wielders hit chance, instead of the classic +60. With this chance, skills now have a far larger 
impact on a characters ability to hit things. Weapon skills now scale 150% with your skill, instead of 100%.

Combat focused racials have been buffed. The Adrenaline Rush special advantage has been buffed, and also triggers at a higher threshold of health than before.

Critical Strike has been reworked completely. When you or an enemies lands a critical strike, the damage of that hit will be multiplied, this value increases 
as the critical strike skill increases, as well as the classic effect of having an increased hit-chance on that strike as well. With this much more powerful 
version of the critical strike skill, it now has a much more rare chance of happening, which is determined by the skill as well, the luck attribute now also 
increases the odds of landing a critical strike. So with 100 CS skill and 50 luck, your chance to land a crit is 25%, and with 100 CS and 100 luck, chance is 50%. The damage multiplier goes up to 200% for the player, and 150% for monsters.

Damage reduction does not just occur for those using armor. Willpower, Strength, and Endurance all have an effect on the "Natural" physical damage resistance of the player and enemies. Endurance has double the effect that Willpower and Strength have. This natural damage reduction is capped at 20%, both negative and positive. This effect also stacks additively when wearing armor and shields, so it always benefits your, whether naked or armored like a tank.

Some monsters also have an innate damage reduction as well, this is to simulate them having armor, that they clearly are wearing in their sprite, but not actually being able to wear armor. This includes many enemies such as the Skeletal Warrior, Daedroths, and Daedra Lord, just to list a few.

Shields now serve a much more effective purpose than before. Shields work the same way in that they protect a few parts of a characters body, but instead of adding a meager AC score like in classic, they now add a very significant damage reduction for the parts of the body they protect, and this damage reduction gets better and better as the MATERIAL of the shield improves. So you won't want to just use that leather tower-shield for long, because it will be vastly out-classed in terms of protection and durability by the higher tier materials. Now those Daedric shields actually have a purpose!

Since shields are now much more powerful. It also seemed like a good idea to give 2-handed weapons a reason to be used. You now benefit double from the strength modifier for damage while using any 2-handed weapons that are not bows. Hand to Hand also gets this benefit.

With the focus on skills and attributes effecting hit-chance in mind. Luck now has a slightly higher impact on avoiding being hit. Speed is now taken into account for both hitting and being hit, but at half the effect that agility now has.

More enemies have been added to the previously exclusive to the Skeletal Warrior club of "Takes double damage from silver". This now includes enemies that would make sense to also have this "weakness". Werewolf, Wereboar, Ghost, Wraith, Vampire, and Mummy.

This mod also has my previous mod "Believable Equipment Characteristics And Durability" built in as well, which you can find more info on its main mod page.

The "Roleplay Realism" Archery Module has been baked into this mod as well, as it would otherwise be overridden, it can be toggled on and off in the options.

Finally, a big addition for the "balance" of this mod is a custom for this overhaul edit of Ralzar's "Meaner Monsters" mod, which changes the primary combat 
stats of many enemies in the game, with the intention of making them more of a challenge overall. My edit of Meaner Monsters is specifically for this mod, but can be toggled on and off, if you wish. ALL off the vanilla monsters in Daggerfall have been changed in some way, most of them being much more powerful than their original forms.


SPOILERS/MORE DETAILS/INDIVIDUAL MODULE INFO:

If you want EXACT numbers and information on how some mechanics and formula work in this mod, under the hood. You can look at the source code yourself from the github linked lower down. You can also email/post a thread on the parent forum post linked below and I would be happy to ask any questions.


OPTIONS:

Equipment Damage Enhanced
Fixed Strength Damage Modifier
Armor Hit Formula Redone
Critical Strikes Increase Damage
Roleplay Realism Archery Module
Ralzar Meaner Monsters Edit

Sorry for how verbose this mod description is. I feel that's it's necessary to detail how it works in this way, otherwise many of the changes would be very difficult to observe in a short test, since all of this is going on in the background. If you have an questions feel free to contact me on the forums:(https://forums.dfworkshop.net/index.php)

My Forum Account Name Is: Magicono43

Main Forum Post: https://forums.dfworkshop.net/viewtopic.php?f=14&t=3506

Github Repository: https://github.com/magicono43/DFU-Mod_Believable-Equipment-Characteristics-And-Durability

I hope to make more mods in this vein, "smaller" ones, as well as eventually larger ones as well.


COMPATIBILITY:

There can potentially be some conflict between this mod and others that modify similar things. The main issues would arise if another mod also alters 

the "DamageEquipment" method in the "FormulaHelper.cs" script. As of now, mods such as "RoleplayRealism" should be compatible, as a separate method 

is overridden. The best bet would be to have this lower in the load-order if you happen to be experiencing some issues. I.E. Make my mod load 5th, and 

the possibly likely incompatible mod load as 4th, etc.


INSTALLATION:

Unzip and open the folder that matches your operating system (Windows/OSX/Linux)

Copy the "ArmorReducesDamageTakenInsteadOfAvoidingOverhaul.dfmod" into your DaggerfallUnity_Data\StreamingAssets\Mods folder

Make sure the mod is enabled and "Mod system" is enabled in the starting menu under "Advanced -> Enhancements"

UNINSTALL:

Remove "ArmorReducesDamageTakenInsteadOfAvoidingOverhaul.dfmod" from the "StreamingAssets/Mods" folder.
