# ActiveResponseTraining

![Image](https://i.imgur.com/WAEzk68.png)

Update of James76543s mod
https://steamcommunity.com/sharedfiles/filedetails/?id=1228227243

![Image](https://i.imgur.com/7Gzt3Rg.png)

	
![Image](https://i.imgur.com/NOW7jU1.png)

Combat threats are the biggest risk to your colony&apos;s survival!  Shooting and Melee proficiency is no joking matter, and now you have a place to hone your shooting and melee skills to keep in tip top shape when the next raider, mechanoid, or ravaging horde of bloodthirsty squirrels comes looking for trouble.
	
     This mod adds a modular shooting range and melee dummy to train combat skills.  They utilise the bill system and give experience (skill gain) comparable but higher than manually training combat and other typical activities like smithing or sculpting.

     Only colonists set as hunters will train at these new buildings.

     This update is carefully balanced so that it takes a reasonable amount of time to gain skill and maintain that skill.  A colonist at max skill should expect to spend about 2-3 hours a day training to maintain that max skill.  This is comparable but higher than other skills.  The bill system can be used wisely to keep your shooters sharp. 
 Set a bill to train forever and limit only those with skill 19 to use it.  When their skills degrade to 19, they will go to train until they&apos;re above 20 again.  If the bills are set right, they should spend their time wisely without any manual intervention and be ready when you need them.

     Training is free for melee, but if you&apos;re at the shooting range, expect to use some ammo (steel) and bring your own target (wood log).  Since I added a cost to training in an attempt to add balance, I modelled the price per skill point to be about 10% of what a neurotrainer would cost per skill point.  Let me know what you think of that, and I might add something like a laser training simulator that uses electricity instead of ammo.

This mod was created by ItchyFlea, but it hasn&apos;t been updated in a while.  I made updates to it and have been using it myself, so I thought I would upload it because I haven&apos;t seen any comparable mods and defense is such an important part of the game.  I took the most recent update and added a few features that I felt it needed:

 1) Training for battle is serious, so no more joy from training.  Previously I had people not capable of combat come and shoot a gun just for joy.
 2) Dummy is uninstallable (minifiable).
 3) More options for construction, and changed the textures slightly to pick up the &apos;stuff&apos; colors.
 4) Dummy can be made of any leather + hay, this picks up leathers from other mods.
 5) Shooting range can be made of any woody, stony, or metallic stuff.  This picks up materials from other mods too.
 6) Added a cost to training shooting, and very carefully balanced the cost per skill point, work amount, and skill points per hour to roughly 10% of the cost per skill point from a Neurotrainer.

     Lastly, this mod is super easy to customize if anyone wants to increase the skill gain rate.  Navigate to the mod folder, and go to \Defs\RecipeDefs\AR-Recipe.xml and edit the file with NotePad++ (or equivalent editor).  The &lt;workSkillLearnFactor&gt; and  &lt;workAmount&gt; is what you want to change.  The skill points gained per job = &lt;workAmount&gt; * .11 * &lt;workSkillLearnFactor&gt;.  So the default number should be about 1144 skill points per job, which is about 1144 skill points per hour.  If you want to decrease the time to complete a training job, decrease &lt;workAmount&gt; and you&apos;ll see a proportional decrease in the time.  2000 is about an hour, 1000 is about half an hour.  My intention is to possibly add this as a scale bar in the mod options menu.  If you want to remove the cost for the shooting range, remove the lines in AR-Recipe.xml from &lt;ingredients&gt; to &lt;/ingredients&gt; (Should be lines 15 through 32).

     If anyone wants to contribute new art, please feel free to pm me.  Art isn&apos;t my strong point!


Credits:
============
ItchyFlea:	Mod Creator
Shinzy:		Texture Artist
James76543:	Updater

![Image](https://i.imgur.com/Rs6T6cr.png)



-  See if the the error persists if you just have this mod and its requirements active.
-  If not, try adding your other mods until it happens again.
-  Post your error-log using https://steamcommunity.com/workshop/filedetails/?id=818773962]HugsLib and command Ctrl+F12
-  For best support, please use the Discord-channel for error-reporting.
-  Do not report errors by making a discussion-thread, I get no notification of that.
-  If you have the solution for a problem, please post it to the GitHub repository.



