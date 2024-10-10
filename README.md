# MHGU Rebalance mod 
 
This mod intends to balance the game in order to reduce the power gap between weapons and styles, and to make element a better option for most weapons.  <br>

Palicoes/Prowlers were changed to give each bias a more defined role, with Gather, Fighter, and Beast being damage cats, Bomb and Guard being safer alternatives since they have adept dodge/guard but losing a bit of damage due to that, Charisma being a generalist, and Heal and Assist being support.   <br>

To install extract it to your mods folder if you are using ryujinx (should look like this: mods\contents\0100770008dd8000\GU rebalanced), or to the mhgu folder in atmosphere\contents if you are using a modded switch (should look like this: atmosphere\contents\0100770008dd8000\GU rebalanced).  <br>

If you downloaded the HD mod compatible version you just have to replace the resident.arc file (located in: GU rebalanced\romfs\nativeNX\loc\arc) with the appropriate one depending on your preferred button layout (you still need the appropriate layout from the HD mod as this only has the shared file, not all of them). As for language the file you replace has very few words in english which don't affect your ability to play the game so I didn't make one for every language (will probably make one for every language after the final update of this mod though)  <br>

For the XX version, if you are using citra just extract the mod and place the romfs folder into the XX mods folder (should look like this: Citra\load\mods\0004000000197100\romfs). If you are using a modded 3DS place the romfs folder into the XX title folder (should look like this: luma\titles\0004000000197100\romfs)  <br>

To make sure the mod works check if any of the weapon changes have applied  <br>

If you have any suggestions leave them in the issues page, or DM me at potobc on discord.  <br>

Also available on [Gamebanana](https://gamebanana.com/mods/447835)   <br>

## All Weapons
All blademaster MV changes are also HA generation changes.   <br>
Shots have their HA generation changes specified with their respective moves due to them not being 1:1 with MVs like with blademaster attacks.   <br>
Ailment modifier refers to both element and status as it affects both of them.   <br>
Adjusted SP mode cost increase   <br>
![imagen](https://github.com/Potobc/MHGU-Rebalanced-Mod/assets/121890308/745bf5d0-9ff4-4ac9-b4fb-b5314aa0e056)   <br>

### Deviant weapons:
Did a few changes to some deviant weapons that I thought I should point out
For the weapons that don't have access to Snowbaron weapons the Elderfrost ones were changed to be more elementally inclined (340 raw instead of 370 and access to purple, still more raw oriented but they have more element this way)
Gave Grimclaw weapons dragon element since its SA had a dragon phial and all weapons can use it except IG
DB lacks a fire deviant weapon so I changed Deadeye’s stats to match Dreadking, and I replaced their model with the Twin Star Blades
IG lacks both a fire and dragon deviant weapon. For fire I changed Stonefist to match Dreadking stats (since Soulseer already exists as a water option), and for dragon I changed Bloodbath to match Grimclaw stats. I know they don’t use the element I gave them but IG does not have a lot of deviant weapons for me to choose from (literally has the least amount of deviant weapons in the game)

### Valor Rebalance:
Valor generation has been changed to allow for players to have 100% uptime with valor state provided they are aggressive enough  <br>
Getting to valor mode has been made a bit harder to give more incentive to staying in valor mode  <br>
Valor sheath damage reduction reduced for blademaster 70% > 50%, and gunner 85% > 65%  <br>
Moves only accessible in valor mode and Hunter Arts have been given increased valor generation which allows for 100% uptime, these are specified in the Valor section of the weapon. Regular Attacks also got small valor generation increases.  <br>

### Alchemy Rework:
Alchemy gain is now MV based (used to be arbitrary from the looks of it), with 1 MV giving 6 Alchemy charge for blademaster, and each Alchemy gauge being 3000 so 500MVs equal 1 gauge.   <br>
Formula for shots is (Mod MV) x (Base Alchemy Gen)/(Base MV) x 1,5/2/3 (1,5 for regular shots, 2 for Internal shots, and 3 for all elemental/status shots since they had lower base alchemy gen than other shots)   <br>
Hunter Arts and some attacks get a larger increase in Alchemy generation specified in the Alchemy section of the weapon as the number of gauges they give you, for example if it says 0,5 it means you get half a gauge. Gauge gain of multi-hit attacks is based on what % of the total MVs they do.    <br>
There are some exceptions to the above since there isn't any overflow so all single hit HA are only able to give 1 gauge, and HA where the damage is focused on a single or few attacks (marked with *) will have a more even spread while still giving higher MV moves more gauge gen.   <br>
Due to the increase in alchemy gauge generation the numbers of bars you have to spend in order to increase SP Arts level has increased 2/5/12 > 3/8/18   <br>
Alchemy Fireball fixed damage increased 60 > 150, stagger mod increased 1,3 > 1,6   <br>
Alchemy Sonic Bomb and Remedy cook time removed.   <br>
Alchemy Item changes    <br>
![imagen](https://github.com/Potobc/MHGU-Rebalanced-Mod/assets/121890308/182f643b-fd8f-44f8-a51e-21a748aecba5)

### Move Speed:
Move speed was measured in how long it took weapons to cross the arena starting area
Not gonna put the actual speed values because they aren't 1:1 between weapons (base SA Axe mode has 360 in speed and LBG has 350 but SA is still slower)
GS/Lance/GL/SA Sword/CB Axe 11,8s > 10,8s 
SA Axe 8,2s > 6,2s 
CB Sword 7,2s > 6,6s 
LBG 6,8s > 5,9s 
LS/Hammer 6,5s > 6,2s
SnS 5,9s > 5,65s 
DB 5,65s > 5,0s 

All Move Speeds:
Running: 3,80s
Bow (Haster Rain): 4,40s
SA (Tempest Axe): 4,70s
DB/HH (SI)/IG (White): 5,00s
SnS: 5,65s
LBG: 5,90s
Walking/LS/Hammer/SA Axe: 6,20s
IG/Bow: 6,40s 
CB Sword: 6,60s
HH (No SI): 8,40s
GS/Lance/GL/SA Sword/CB Axe: 10,80s
HBG: 11,40s

### Non-Weapon Specific Hunter Arts: 
Heal Gain build up reduced 830 [1196] > 570 [782]   <br>
Hunter's Oasis build up reduced 1330 [1796] > 860 [1055]   <br>
Frenzy Fever build up reduced 830 [1196] > 610 [819]   <br>
Castle Walls build up reduced 830 [1196] > 610 [819]   <br>
Fortress Walls build up reduced 1080 [1496] > 860 [1055]   <br>
Arisen Phoenix build up reduced 1080 [1496] > 540 [754]   <br>

## Great Sword

### Attacks:
Side Slap ailment modifier 1 > 0,7   <br>
Side Slash 32 > 38    <br>
Charge 48/65/80/100 > 48/75/90/115, ailment modifier 1/1/1/1 > 1,25/1,6/1,8/2,1    <br>
Strong Charge 52/72/90/120 > 65/85/100/130, ailment modifier 1/1/1/1 > 1,6/1,8/2/2,3   <br>
Strong Side Slash 42/50/60/80 > 40/50/60/70 ailment modifier 1/1/1/1 > 1,4/1,5/1,6/1,8   <br>
Aerial Draw Slash 48 > 58, ailment modifier 1,5   <br>
Aerial charge 48/57/66/75 > 50/65/75/90, ailment modifier 1/1/1 > 1,3/1,5/1,7/1,9   <br>
Adept Upswing charge 26/39/52/78 > 42/55/62/75, ailment modifier 1/1/1/1 > 1,2/1,35/1,5/1,7   <br>
Valor Draw Slash 52/65/81/112 > 52/65/80/100, ailment modifier 1,3/1,5/1,7/2   <br>
Valor Charge Dash 52/61/85/115 > 60/80/95/120, ailment modifier 1/1/1/1 > 1,5/1,7/1,9/2,2    <br>
Alchemy side slash 48 > 90, ailment modifier 1 > 2   <br>
All other attacks get a 1,2 ailment modifier   <br>

### Hunter Arts:
Ground Slash 50+20x2/50+21x3/50+22x4 > 80+20x2/100+20x3/130+20x4, ailment modifier 1+1x2/1+1x3/1+1x4 > 1,8+1x2/2,1+1x3/2,4+1x4, and build up increased 630/670/830 [838/875/1027] > 650/780/920 [857/979/1113]   <br>
Lion’s Maw multiplier buffed 1,1/1,2/1,33 > 1,2/1,35/1,5, ailment modifier 1/1/1 > 1,4/1,5/1,6, and build up increased 290/350/500 [548/620/800] > 370/450/580 [601/672/791]    <br>
Brimstone Slash 130/150/175/190 > 170/200/230/270, max charge time increased 8s > 12s, ailment modifier 1/1/1/1 > 2,5/3,5/4,5/6   <br>
Moonbreaker 60/12+70/10+12+80 > 75/10+95/10+12+125, ailment modifier 1/1+1/1+1+1 > 1,6/1+1,9/1+1+2,2, stagger modifiers 1,5/0,9+2/0,9+0,9+2,5 > 2/0,9+2,25/0,9+0,9+2,5, and build up increased 420/500/830 [704/800/1196] > 630/710/830 [838/913/1027]    <br>

### Alchemy:
Alchemy side slash 0,35  <br>
Ground Slash 1,5/1,75/2  <br>
Lion's Maw 0,15/0,3/0,5  <br>
Brimstone Slash 1 (single hit)  <br>
Moonbreaker* 1/1,5/2  <br>

### Valor:
Regular Attacks 1s  <br>
Valor Draw Charge 3/4/5/6s  <br>
Valor Strong Charge 5/6/7/8s  <br>
Valor Charge Dash 4/5/6/7s  <br>
Valor Side Slash 2/3/4/5s  <br>
Ground Slash 8/9/10s  <br>
Lion's Maw 4/4,5/5s  <br>
Brimstone Slash 9/10/12/15s (refers to charge level)  <br>
Moonbreaker 4,5/6/7,5s  <br>

## Long Sword

### Attacks: 
Thrust 14 > 15   <br>
Rising Slash 18 > 21   <br>
Spirit Slash I 28 > 30   <br>
Mid-Spirit Thrust 14 > 16   <br>
Spirit Slash II 30 > 34    <br>
Spirit Rising Slash 18 > 23   <br>
Spirit Slash III ailment modifier 1+1+1 > 1+1+1,3   <br>
Spirit Roundslash 42 > 52, ailment modifier 1 > 1,7   <br>
Red Aura Spirit Roundslash 42 > 60, ailment modifier 1 > 2   <br>
Rushing Spirit Slash 30 > 32   <br>
Aerial Slashes 10+25 > 16+25    <br>
Aerial Spirit Slash III ailment modifier 1+1+1 > 1+1+1,3   <br>
Adept Spirit Reckoning 30+80 > 20+75, ailment modifier 1+1 > 0,5+2,5   <br>
Valor Spirit Slash I 28 > 34   <br>
Valor Spirit Slash II 30 > 34   <br>
Valor Counter 51 > 42   <br>
Valor Spirit Reckoning 35+60 > 20+60, ailment modifier 1+1 > 0,5+2   <br>
All other Regular attacks get a 1,1 ailment modifier   <br>
All other Spirit Slashes get a 1,3 ailment modifier   <br>

### Hunter Arts:
Sakura Slash ailment modifiers for blade attacks 1 > 1,5  <br>
Unhinged Spirit build up increased 420/500/580 [704/800/896] > 580/650/760 [718/791/894]  <br>
Critical Juncture ailment modifiers 1/1/1 > 3/4/5  <br>
Devouring Demon multiplier reduced 1,1/1,2/1,3 > 1,1/1,15/1,2, and duration increased 75/60/45 > 105/90/75  <br>

### Alchemy:
Spirit Slash I 0,1  <br>
Spirit Slash II 0,1  <br>
Spirit Slash III 0,05+0,05+0,1  <br>
Spirit Roundslash 0,2  <br>
Red Spirit Roundslash 0,3  <br>
Sakura Slash 1,25/1,5/1,75  <br>
Unhinged Spirit 0,5/0,75/1  <br>
Critical Juncture 1 (single hit)  <br>

### Valor:
Regular Attacks 0,6s  <br>
Jumping Valor Spirit Slash II 2s  <br>
Valor Spirit Slash I 3s  <br>
Valor Spirit Slash II 3s  <br>
Valor Spirit Slash III 3s  <br>
Valor Spirit Reckoning 6s  <br>
Valor Counter 4s  <br>
Sakura Slash 6/7,5/9s  <br>
Critical Juncture 7,5/9/10,5s  <br>
Unhinged Spirit 4s  <br>

## Sword and Shield

### Oils:
Stamina Oil 8 KO > 10 KO, 10 Exh > 12 Exh  <br>
Stagger Oil stagger mod 1,2 > 1,3  <br>

### Attacks:
Shield Combo 10+20 > 16+23, KO/Exh 15/15 > 20/30, stagger modifier 1+1 > 0,6+1,3   <br>
Strong Side Slash 21 > 24, ailment modifier 1 > 1,2   <br>
Strong Up Slash 19 > 21, ailment modifier 1 > 1,2   <br>
Shield Bash 8 > 23, KO/Exh 10/15 > 20/20, stagger modifier 1 > 1,2   <br>
Shield Thrust 16 > 28, KO/Exh 15/25 > 25/35, stagger modifier 1 > 1,2   <br>
Roundslash 24 > 30, ailment modifier 1 > 1,3   <br>
Backstep Charge Attack 20+34 > 29+40, ailment modifiers 1+1 > 1,2+1,5, KO/Exh 15/25 > 30/40, stagger modifier 1+1 > 0,6+1,3   <br>
Aerial Rising Slash 25 > 35   <br>
Adept Backstep Counter ailment modifier 1 > 1,6   <br>
Valor Backflip 14 > 20   <br>
Backflip Followup 16 > 30, ailment modifier 1> 1,3   <br>
Valor Rushing Slashes 10+9+9 > 21+15+16, KO/Exh 15/25 > 30/40   <br>
Valor Round Slashes 14+18 > 24+30, ailment modifier 1+1 > 1,2+1,3   <br>
All other attacks get a 1,1 ailment modifier   <br>
Attacks not mentioned get +10% MV   <br>

### Hunter Arts:

Sword Dance 25+14+15+15+14+15+20+7+45 > 35+19+21+21+19+21+30+12+55, level I/II finisher 40 > 45, ailment modifiers 1 > 1,2, finisher ailment modifier 1 > 2, build up decreased 830/920/1250 [1196/1304/1700] > 830/920/1080 [1027/1113/1267]  <br>
Round force III no longer sends you flying (will still affect other people not using the mod), build up increased 250/250/290 [500/500/548] > 340/400/500 [575/628/718]  <br>
Shoryugeki 10+60/10+35+60/10+35+60+30 > 10+85/10+35+75/10+35+70+35, stagger modifier increased 1 > 1,5, KO changed 100/100+50/100+50+50KO > 100/50+100/50+100+50KO, and exhaust increased 70/50+40/50+40+40ex > 80/50+70/55+80+65ex   <br>
Chaos Oil build up increased 920/1000/1000 [1304/1400/1400] > 950/1080/1250 [1141/1267/1431], duration changed 135/180/120s > 120/150/180s, now all levels of chaos oil give you 20% affinity, 6 KO, 8 Exh,  1,15 stagger mod, and 50 sharpness, with stacking only bringing the oils back to their original value  <br>

### Alchemy:
Roundslash 0,15  <br>
Swords Dance 1,5/2/2,5  <br>
Round Force 0,25/0,5/0,75  <br>
Shoryugeki* 1/1,5/2  <br>
Chaos Oil 1 (single hit)  <br>

### Valor:
Regular attacks 0,27s  <br>
Valor Backflip 2s  <br>
Backflip Followup 3s  <br>
Valor Rushing Slashes 4s  <br>
Valor Round Slashes 5s  <br>
Sword Dance 7,5/9/10,5s  <br>
Round Force 2,5/3/3,5s  <br>
Shoryugeki 6/7,5/9s  <br>
Chaos Oil 4,5/6/7,5s  <br>

## Dual Blades

### Attacks:
Arch Slice I 8+12 > 11+14   <br>
Arch Slice II 7+10 > 13+16   <br>
Circle Slash 10+13x2 > 13+15x2   <br>
Left/Right Arch Side Slashes 9+12/7+10 > 14+18/14+18   <br>
Arch Double Jumping Slashes 16+6+8+18+6+10 > 19+9+11+21+11+13, ailment modifier 1 > 1,2   <br>
Arch Hurricane Dance 8x4+20x2 > 10x4+23x2, ailment modifier 1x4+1x2 > 1,2x4+1,4x2   <br>
Demon Six-Way Slash 4+8+4+8+12x2 > 6+10+6+10+14x2   <br>
Demon Double Jumping Slashes 16+6+8+18+6+10 > 16+7+9+18+9+11   <br>
Demon Dance ailment modifiers 1+1x8+1+1x2 > 1,3+0,85x8+0,9+1,5x2   <br>
Spinning Slashes ailment modifier 1x4+1x2 > 0,8x4+0,9x2   <br>
Adept/Valor Spinning Slashes 5x4+10x2 > 5x4+8x2 ailment modifier 1x4+1x2 > 0,7x4+0,8x2   <br>
Adept Demon/Arch Slashes ailment modifiers 1+1+1x2 > 0,9+1+0,8x2   <br>
Valor Demon Dance first hits ailment modifier 1+1 > 1,3+1,3 (rest is the same as Demon Dance)   <br>
Valor Counter 10x2+7x2 > 12x2+10x2, ailment modifier 1x2+1x2 > 1,2x2+1x2   <br>
All other attacks in archdemon mode get an ailment modifier of 1,1   <br>
Valor shares MVs with archdemon and demon mode so all their changes apply to it as wel   <br>

### Hunter Arts:
Blood wind spin ailment modifier increased 1 > 1,1, build up increased 670/750/830 [1004/1100/1196] > 960/1080/1170 [1151/1267/1354]   <br>
Wolf's maw multiplier reduced 20/25/30% > 20/20/20%, buildup reduced 1250/1500/1670 [1700/2000/2204] > 1170/1280/1400 [1354/1460/1577]   <br>
Aerial Slam 80/110/150 > 130/160/200, finisher stagger modifier increased 1,5 > 2, stagger modifier for spins reduced to 0 (to avoid missing due to a flinch)   <br>
Spiral slash spin 10 > 12, ailment modifiers 0,5 > 1, and stagger modifier 0,9 > 0 (to avoid missing due to a flinch), and finisher ailment modifier 1 > 1,5, and stagger modifier 2/2/2 > 2/2,8/3 (to make up for the lost part damage)   <br>


### Alchemy:
Arch Hurricane Dance 0,25  <br>
Demon Dance 0,3  <br>
Blood Wind 2/2,5/3  <br>
Aerial Slam* 1,5/1,75/2  <br>
Spiral Slash 1,5/1,75/2  <br>

### Valor:
Regular attacks 0,17s per hit  <br>
Valor Six-Way Slash 6s  <br>
Valor Double Jumping Slashes 6s   <br>
Valor Spinning Slashes 3s  <br>
Valor Dash Counter 5s  <br>
True Demon Dance 12s  <br>
Blood Wind 9/11/13s  <br>
Aerial Slam 6/7,5/9s  <br>
Spiral Slash 6/7,5/9s  <br>

## Hammer

### Attacks:
Draw Swing/Charge 1 Followup 20 > 25   <br>
Strong Pound 42 > 45   <br>
Weak Pound 20 > 25   <br>
Side Swing 15 > 20, KO 22 > 30   <br>
Golf Swing ailment modifier 1 > 2   <br>
Charge 1 25 > 30   <br>
Charge 2 40 > 55, ailment modifier 1 > 1,6   <br>
Charge 3 idle 15+76 > 15+90, KO 5+27 > 5+35, ailment modifier 1+1 > 0,5+2    <br>
Charge 3 moving spin 20+10x4 > 25+13x4, KO 2+2x4 > 10+8x4, Exhaust 2+2x4 > 8+4x4, ailment modifiers 1+1x4 > 1+0,8x4, stagger modifiers 1+1x4 > 1+0,5x4 finishers ailment modifier 1/1 > 1,6/2   <br>
Striker 3rd Pound 60 > 70   <br>
Striker Charge 3 19+86 > 20+95, KO 5+17 > 5+35, ailment modifier 1+1 > 0,6+2   <br>
Aerial Charge 3 60 > 65   <br>
Aerial Smash 42 > 45, KO 15 > 25   <br>
Adept Idle Strong Charge 3 20+90 > 20+105, KO 10+27 > 10+40, ailment modifier 1+1 > 0,6+2,2   <br>
Adept Moving Strong Charge KO 10+27 > 10+35, ailment modifier 1+1 > 0,5+1,9    <br>
Valor Charge 2 ailment modifier 1/1 > 1,4/1,7   <br>
Valor Charge 3 15+85/20+105 > 15+85/20+110, KO 10+50/10+60 > 10+50/10+65, ailment modifier 1+1/1+1 > 0,5+1,9/0,6+2,2   <br>
Stagger modifier for all 3rd charges changed 1+1 > 0,5+1,1   <br>
All other attacks get +0,1 ailment modifier for every 10MVs   <br>

### Hunter Arts:
Spinning Meteor MVs Increased 20 > 25 for spins, 15 > 20 for setup spin, and 110/125/165 > 130/145/175 for finishers, exhaust Increased 15 > 18 for spins, 10 > 15 for setup spin, and 30/30/40 > 40/55/70 for finishers, ailment modifiers increased 1 > 1,2 for spins and setup spin, 1/1/1 > 2,5/3/3,5 for finishers, and build up increased 830/920/1100 [1196/1304/1520] >  1080/1250/1420 [1267/1354/1528]   <br>
Provoke Duration increased 30/60/60s > 60/60/90s   <br>
Typhoon Trigger MVs increased 5x6+20+50/60/80 > 8x6+25+60/70/90, KO increased 2x6+40+60/100/125 > 5x6+50+100/120/140, finisher ailment modifiers increased 1/1/1 > 1,5/1,75/2, and build up Increased 250/330/420 [500/596/704] > 430/550/640 [654/764/847]
Impact Press MVs increased 6 > 8, Exhaust increased 4 > 5, HA gen increased 0 > 8, duration increased 80/100/120s > 90/120/150s   <br>

### Alchemy:
Golf Swing 0,25   <br>
Charge 1 0,1   <br>
Charge 2 0,2   <br>
Charge 3 Idle 0,3   <br>
Spinning Meteor* 1,5/2/2,5   <br>
Provoke  1 (single hit)   <br>
Typhoon Trigger 1,5/1,75/2   <br>
Impact press 0,05 per hit   <br>

### Valor:
Regular Attacks 1s   <br>
Valor Charge 1 2/4s   <br>
Valor Charge 2 3/5s   <br>
Valor Charge 3 5/8s    <br>
Same values for Valor Charge Aerial Attacks   <br>
Spinning Meteor 9/10,5/12s   <br>
Provoke 3/4,5/6s   <br>
Typhoon Trigger 6/7,5/9s   <br>
Impact press 0,25s per hit   <br>

## Hunting Horn

### Attacks:
Forward Slam 33 > 41   <br>
Right Swing 30 > 37   <br>
Left Swing 30 > 37   <br>
Flourish 12+22 > 18+26    <br>
Back Swing 45 > 48    <br>
Swing 'n Slam 15+45 > 15+50   <br>
Hilt Jab 10 > 17   <br>
Recital Right Sweep 35 > 48   <br> 
Recital Kick 20 > 32   <br>
Recital Upswing 25 > 34   <br>
Recital Backswing 30 > 40    <br>
Encore Backswings 40+30 > 52+40   <br>
Triple Encore Backswing 33+40+30 > 43+52+40   <br>
Left/Right Encore Side Swing 35/35 > 47/56   <br>
Left/Right Double Encore Side Swings 33+35/33+35 > 43+47/43+56 (right is a bit slower so it's a bit stronger)   <br>
Jump Swing 36 > 47   <br>
Aerial Flourish 12+22 > 26+44   <br>
Adept Triple Swings 15+20+30 > 20+25+35   <br>
Adept Recital 38 > 42   <br>
Valor Recital ailment modifier 1+1 > 1,2+1,2   <br>
Valor Encore 45+15 > 40+15   <br>
Regular Attacks ailment modifier increased 1 > 1,2   <br>
Recitals ailment modifier increased 1 > 1,4   <br>

### Hunter Arts:
Euphony build up increased 590/630/670 [958/956/1004] > 700/750/800 [903/951/998]   <br>
Sonic Smash wind-up MVs increased 5x2/5x2/5x4 > 12x2/12x2/12x4, ailment modifier increased 1 > 1,2, finisher MVs, KO, and exhaust increased 30/35/38 > 40/60/100, 10/10/10KO > 40/60/100KO, 10/10/10ex > 60/80/120ex, damage formula for finisher fixed damage is MV x (1 + (TrueRaw x 0,016)),  and build up decreased 830/1000/1070 [1196/1400/1604] > 630/670/790 [838/875/989]    <br>
Harmonize duration buffed 60/90/120s > 90/120/150s, and build up increased 420/580/670 [704/896/1004] > 580/690/800 [791/894/998]    <br>
Invigoration duration buffed 90/120/150s > 120/150/180s, Recital MV increased 38 > 42, and build up increased 420/500/580 [704/800/896] > 500/580/690 [718/791/894]   <br>

### Alchemy:
Recital Right Sweep 0,15    <br>
Recital Kick 0,1   <br>
Recital Back Swing 0,15   <br>
Encore Backswings 0,3   <br>
Triple Encore Backswing 0,4   <br>
Encore Side Swings 0,15   <br>
Double Encore Side Swings 0,25   <br>
Sonic Smash 1/1,5/2   <br>
Invigoration 0,2 per hit   <br>

### Weapons
![imagen](https://github.com/user-attachments/assets/341916a6-bb6a-4ced-bbef-26124cb67d61)



### Valor:
Regular Attacks 1s  <br>
Flourish 3s  <br>
Recital Right Sweep 2s  <br>
Recital Kick 2s  <br>
Recital Back Swing 2s   <br>
Encore Backswings 4s  <br>
Triple Encore Backswing 6s  <br>
Left/Right Encore Side Swings 2/3s  <br>
Left/Right Double Encore Side Swings 4/5s  <br> 
Valor Recital 5s  <br>
Valor Encore 8s  <br>
Sonic Smash 7,5/9/12s  <br>
Invigoration 4,5s per hit  <br>

## Lance

### Attacks:
Mid Thrust 20/20/25 > 27/27/32   <br>
High Thrust 22/22/27 > 27/27/32   <br>
Strong Thrust 16x3 > 27x3, ailment modifier 1x3 > 1,25x3   <br>
Wide Sweep 20 > 40   <br>
Uncharged Counter Thrust 22 > 24, ailment mod 1 > 1,15   <br>
Charged Counter Thrust 50 > 60, ailment modifier 1 > 1,7   <br>
Shield Bash 14 > 35, KO/Exh 27/27 > 40/35, Stagger modifier 1 > 1,3   <br>
Jumping Thrust 30 > 40   <br>
Charge ailment modifier 1 > 0,8   <br>
All Charge Finishers ailment mods 1 > 1,6   <br>
Striker charge finisher 67 > 55, ailment modifier 1 > 1,6   <br>
Aerial triple poke 15x3 > 23x3   <br>
Adept Counter Sweeps 41+36 > 40+30   <br>
Valor Shield Bash 20 > 26   <br>
All other attacks get +0,1 ailment modifier for every 10MVs   <br>

### Hunter Arts:
Shield Assault charge 10 > 15, Shield Attack 30 > 45, KO/Exh 27/27 > 70/70, Stagger modifier 1 > 1,5, Lance Attack 50 > 60, ailment modifier 1 > 1,8, build up increased 250/330/420 [500/596/704]> 340/420/500 [575/628/718]    <br>
Corkscrew Jab 45x3/32x5/27x7 > 65x3/48x5/40x7, ailment modifier 1/1/1 > 1,6/1,45/1,3    <br>
Enraged Guard raw modifiers reduced 1,1/1,2/1,3 > 1,1/1,125/1,15    <br>

### Alchemy:
Strong Thrust 0,25  <br>
Shield Bash 0,15  <br>
Shield Assault 0,05 per shield hit, and 0,35 for both finishers  <br>
Corkscrew Jab 2/2,5/3  <br>

### Valor:
Regular Attacks 0,66s  <br>
Strong thrust 1,5s  <br>
Charge 0,2s  <br>
Charge Finishers 2s   <br>
Valor Shield Bash 2,5s  <br>
Uncharged Counter Thrust 1,5s  <br>
Charged Counter Thrust 5s  <br>
Shield Assault 1,5s per shield hit, 3s for finishers  <br>
Corkscrew Jab 6/7,5/9s  <br>

## Gunlance

### Attacks:
Thrust 21 > 29, ailment modifier 1 > 1,2   <br>
3rd Thrust 24 > 34, ailment modifier 1 > 1,3   <br>
Running Upswing 28 > 35, ailment modifier 1 > 1,3   <br>
Upswing 25 > 35, ailment modifier 1 > 1,3   <br>
Slam/Valor Slam 38 > 50, ailment modifier 1 > 1,6   <br>
Guard Thrust 16 > 24, ailment modifier 1 > 1,1   <br>
Jumping Thrust 22 > 30, ailment modifier 1 > 1,3   <br>
Jumping Slam 40 > 55, ailment modifier 1 > 1,6   <br>
Adept/Valor Reload Upswing 36 > 40 ailment modifier 1 > 1,4   <br>
Adept Slam ailment modifier 1 > 1,6   <br>

### Shellings:
Normal shelling 3/4/5 damage increased 18/21/24 > 24/30/37, HA gen 20 > 22    <br>
Wide shelling 3/4/5 damage increased 40/44/48 > 49/62/75, HA gen 40 > 44    <br>
Long shelling 3/4/5 damage increased 28/32/36 > 37/46/57, HA gen 30 > 33   <br> 
Modifier changed for Full Burst/Charged Shelling/Wyvernsfire   <br>
Normal modifiers 1,2/1,2/1 > 1,2/1,6/1   <br>
Wide modifiers 0,9/1,45/1 > 0,85/1,8/1   <br>
Long modifiers 1/1,2/1,2 > 1/1,6/1,3   <br>
Wyvernsfire damage increased 25x4/30x4/35x4/40x4/45x4/ > 43x4/50x4/67x4/88x4/105x4, HA gen increased 50x4 > 80x4   <br>
Removed all fire damage from Shellings and Wyvernsfire    <br>
Alchemy Wyvernsfire damage and HA generation increased 50% > 65% (AA Flare Wyvernsfire deals full amount)   <br>
Removed cooldown from overheating   <br>
Valor Reload now fully reloads shells   <br>
Valor rapid fire modifier reduced 1+1,2+1,5+2+2,6+2,6 > 0,8+1+1,2+1,4+1,5+1,5   <br>
Valor full burst modifier reduced 0,8+0,9+1+1,4+1,5+1,6 > 0,8+0,9+1+1,1+1,2+1,3   <br>
Reduced stagger from shellings and wyvernsfire so they no longer send you flying (only affects you, teammates that don't have the mod will still be sent flying)   <br>

### Hunter Arts:
Dragon Blast first hit damage increased 48/49/50 > 150/200/250, repeating hits damage increased 3/6/9 > 10/15/20. Damage Formula is (1st hit) x (1 + weaponRaw x 0.7/100) + (repeating hits)  x (10 x (1 + weaponRaw x 0.2/100)), build up increased 830/1000/1250 [1196/1400/1700] > 1180/1280/1370 [1363/1460/1548]  <br>
Blast Dash III MVs increased 24+50 > 28+60, and build up increased 250/290/330 [500/548/596] > 320/360/400 [558/592/628]
Dragon breath extra hit damage increased 10 > 15, fixed fire replaced by blast, build up increased 1080/1170/1250 [1496/1604/1700] > 1180/1280/1370 [1363/1460/1548]  <br>
AA Flare wide and long shelling deal 2x damage, normal shelling deals 1,8x damage, build up increased 400/460/520 [680/752/824] > 480/560/670 [699/773/875]  <br>

### Weapons:
Changed GL shelling type depending on the amount of sharpness they have, with normal getting the most and wide the least
Level 4 and 5 GLs are about the same in terms of damage, with lvl4 focusing more on the lance part and level 5 on the gun part
![imagen](https://github.com/user-attachments/assets/e91f48a2-0ac9-4dbc-a805-3a382710d43c)

### Alchemy:
Slam 0,2  <br>
Normal 0,02  <br>
Wide 0,04  <br>
Long 0,03  <br>
Wyvernsfire 0,5  <br>
Dragon Blast* 2/2,5/3  <br>
Blast Dash 0,25 for all levels, 0,5 if you end early with level III  <br>
Dragon Breath 0,04 per hit  <br>
AA Flare 1,25 for full burst (assumes load up), 1,5 for wyvernsfire  <br>

### Valor:
Regular Attacks 0,6s  <br>
Valor Slam 3s  <br>
Valor Wyvernsfire 13s  <br>
Full Burst 0,8/1,6/1,2s per shelling  <br>
Rapid Shelling 1,5/3/2,25s per shelling  <br>
Dragon Blast 8/9/10s  <br>
Blast Dash 3/3/4,5s  <br>
Dragon Breath 0,35s per hit  <br>
AA Flare 7,5s for full burst (assumes load up), 10s for wyvern's fire  <br>

## Switch Axe

### Phials:
Power phial multiplier decreased 1,2 > 1,07  <br>
ailment phial multiplier increased 1,25 > 1,5  <br>

### Axe Attacks:
Overhead Slash stagger modifier 1 > 1,3   <br>
Side Slash 23 > 33   <br>
Upswing 32 > 40, stagger modifier 1 > 1,2   <br>
Forward Thrust 19 > 26   <br>
Wild Swing hits 1/2/3+ 22/22/22 > 19/21/24, ailment modifier 1/1/1 > 0,9/0,95/1   <br>
Wild Sweep 25+30+40 > 25+35+30, stagger modifier 1+1+1 > 1,1+1,2+1,15   <br>
Jumping Swing 40 > 48, stagger modifier 1 > 1,2   <br>
All other attacks get a stagger modifier of 1,1    <br>

### Sword Attacks:
Side Slash 28 > 33   <br>
Double Slash 28+36 > 31+40   <br>
Jumping Downslash 30 > 37   <br>
Adept Double Upslash 25+25 > 30+26   <br>
Valor Double Slash after dodge 22+30 > 27+34   <br>
Elemental Discharge Ticks ailment modifier 1 > 0,8   <br>
Power Phial ED Explosion (cancel) 80 (50) > 90 (60), ailment modifier 1 (1) > 2 (1,5)   <br>
Element/Status Phial ED Explosion (cancel) ailment modifier 1,5 (1,15) > 3 (1,5)   <br>
Exhaust Phial ED Explosion (cancel) 80 (50) > 90 (60), ailment modifier 2 (1,3) > 3 (2)   <br>
Power Phial Valor Double ED Explosion 40+60 > 40+50, ailment modifiers 0,6+0,8 > 1+1   <br>
Element/Status Phial Valor Double ED Explosion 40+60 > 30+40 ailment modifiers 0,8+1 > 1+1,5   <br>
Exhaust Phial Valor Double ED Explosion 40+60 > 40+50, ailment modifiers 1+1,4 > 1+1   <br>
All other Sword attacks get +10% MVs   <br>
All Sword attacks get a 1,2 ailment modifier   <br>

### Hunter Arts:
Demon riot phial buff reduced 5/10/20% > 10/10/10%, duration increased 105/120/105s > 90/105/120s   <br>
Trance Slash (Underlined numbers refer to Tempest Axe/Demon Riot extensions)   <br>
Trance Slash I 13+15+20+16+10x3+34+20+25+30+15x4+70+20 > 17+20+23+25+19x3+75+25+28+33+20x4+95+35   <br>
Trance Slash II 15+17+22+16+10x3+34+24+29+35+25x4+80+30 > 20+24+28+25+19x3+75+30+33+38+30x4+110+50   <br>
Trance Slash III 18+20+25+16+10x3+34+28+33+40+30x4+90+40 > 24+29+34+25+19x3+75+36+39+44+40x4+125+70   <br>
Increased ailment modifiers for normal hits 1 > 2, elemental ticks 1 > 1,5, and elemental explosion 1 > 4   <br>
Normal Trance Slash explosions 80/90/100 > 100/110/120   <br>
Normal Trance Slash total MVs 263/332/384 > 326/403/486   <br>
Full Trance Slash total MVs 353/442/494 > 513/610/718   <br>
Trance slash build up increased 670/750/830 [1004/1100/1196] > 1250/1450/1670 [1431/1626/1841]    <br>
Energy Charge build up increased 500/650/850 [1004/1100/1196] > 650/780/920 [857/979/1113]   <br>
Tempest Axe move speed multiplier increased 2 > 2,4, Finisher MVs increased 15+55 > 15+75, ailment modifiers increased 1+1 > 0,5+1,8 stagger modifiers changed 1+1,3 > 0+1,6, and build up increased 420/500/580 [704/800/896] > 580/650/760 [718/791/894]   <br>

### Weapons:
Status SA with element phial got their status reduced to account for the increase in ailment modifiers   <br>
SAs given Power phial: Kecha, Zamtrios, Uragaan, Lagiacrus, Deviljho, Unkalos, Akantor, Skeletal Nakarkos, Crimson Fatalis, Stonefist, Nightcloak, and Bloodbath   <br>
SA given Elemental phial: Silverlos, Agnaktor, Savage, Shagaru, Kirin, Soulseer, Snowbaron, and Grimclaw   <br>
Power phial SAs with <330 raw got an increase so they rely more on raw htz for damage (otherwise they would have been better as Ele phial SAs and I wanted there to be a similar number of phial types)   <br>
Gorgonzola Axe: status buffed 3/4/5 > 11/13/15   <br>

### Alchemy:
Elemental Discharge 0,5  <br>
Alchemy Reload 0,2  <br>
Trance Slash 3/4/5, Demon riot gives extra 1/1,5/2, Tempest axe gives extra 1,5  <br>
Energy Charge 0,25/0,5/0,75  <br>
Tempest Axe 1 for activation, 0,5 for finisher   <br>

### Valor:
Regular Axe attacks 0,65s   <br>
Regular Sword Attacks 0,45s    <br>
Wild Swing 0,5s per hit   <br>
Double Slash 3s   <br>
Double Slash after dodge 2s   <br>
Wild Sweep 6s   <br>
Double Discharge 6s   <br>
Trance Slash 15s/16,5s/18s, Demon riot gives extra 3s/4,5s/6s, Tempest axe gives extra 6s   <br>
Energy Charge 1,5/3/4,5s   <br>
Tempest Axe 4s for activation, 4s for finisher   <br>

## Charge Blade

### Shield Buff:
Yellow shield buff 0% > 25%   <br>
Yellow shield also buffs phials (confirmed by “Fallen Feces”) so now its better for damage than red shield, however you do lose the phial explosion when guarding, and you still lose sharpness when guarding, so red shield is better for defence and sharpness management   <br>

### Sword Attacks:
Draw Slash 18 > 20    <br>
Forward Slice 14 > 22   <br>
Upward Slice 15 > 17   <br>
Shield Thrust ailment modifiers 1+1 > 0,5+0,6   <br>
Jumping Slash 22 > 26   <br>
Aerial Charge Slash 35 > 40   <br>
Due to the element buffs all attacks get a 0,85 ailment modifier   <br>

### Axe Attacks:
Upswing 33 > 38   <br>
Downswing 40 > 48   <br>
Forward Downsing 42 > 48   <br> 
ED I 20 > 27   <br>
ED II 20+45 > 20+50    <br>
AED (No Phials) 42 > 75, ailment modifier increased 1 > 1,5   <br>
AED ailment modifier increased 1 > 2   <br>
SAED (No Phials) 20+60 > 20+90,  ailment modifiers increased 1+1 > 0,5+2   <br>
SAED 25+90 > 25+120,  ailment modifiers increased 1+1 > 0,5+3   <br>
Aerial AED (No Phials) 42 > 90, ailment modifier increased 1 > 1,5   <br>
Aerial AED ailment modifier increased 1 > 2   <br>
Aerial SAED (No Phials) 60 > 100,  ailment modifier increased 1 > 2   <br>
Aerial SAED 100 > 130,  ailment modifier increased 1 > 3   <br>
Valor ED III (No Phials) 15+35 > 15+40   <br>
Valor ED III 15+70 > 20+55    <br>
Valor SAED (No Phials) 20+55 > 20+75,  ailment modifiers increased 1+1 > 0,5+1,5   <br>
Valor SAED 25+80 > 25+90,  ailment modifiers increased 1+1 > 0,5+2   <br>

### Phials:
Mini Phials HA gen 0 > 5   <br>
ED Phials impact MV 5 > 7, HA gen 0 > 10   <br>
AED Phials HA gen 0 > 10   <br>
SAED Explosion HA gen 0 > 40   <br>

### Hunter Arts:
Energy Blade 0 Phials 10/20/30 > 50/60/80, ailment modifier for 0 phials 1/1/1 > 1/1/2, 1-3 phial 1/1/1 > 2/3/4, 4-6 phials 1/1/1 > 4/5/6, 7-9 phials 1/1/1 > 6/7/8, and 10 phials 1/1/1 > 8/9/10   <br>
Limit break III duration increased 150s > 180s   <br>

### Weapons:
CBs given Impact phial: Seltas Queen, Rathian, Zamtrios, Gammoth, Glavenus, Sentinel Blade, Skeletal Nakarkos   <br>
CBs given Elemental phial: Silverlos, Charge Fox, Mandible Blade, Kushala, Shagaru, Astral Nakarkos, Soulseer, Boltreaver, Elderfrost   <br>
Impact phial CBs with <320 raw got a raw increase (same reasoning as for power phial SAs)   <br>

### Alchemy:
SAED 0,3  <br>
Mini Phials 0,03 per explosion  <br>
Phials 0,075 per explosion  <br>
Energy Blade 1 (single hit)  <br>
Healing Phial 0,15 per Explosion  <br>
Ripper Shield 1/1,25/1,5  <br>

### Valor:
Regular Sword Attacks 0,4s  <br>
Regular Axe Attacks 0,8s  <br>
ED III 5s  <br>
Valor AED 5s  <br>
Valor SAED 7s  <br>
Phials 0,5s per explosion   <br>
SAED Explosion 4s  <br>
Energy Blade 3/4,5/6s for 0 phials, 6/7,5/9s for 1-3 phials, and 9/10,5/12s for 4-6 phials  <br>
Ripper Shield 4,5/6/7,5s  <br>

## Insect Glaive 

### Extracts:
White 90s > 75s  <br>
Red 60s > 90s  <br>
Orange 45s > 105s  <br>
Triple up 60s > 120s  <br>

### Attacks:
Parenthesis refer to MVs of attacks with red extract  <br>
Draw Slam 25 > 27  <br>
Jump Slam 21 > 27  <br>
Marker Bash 10 > 20  <br>
Thrust 12 (15+9) > 13 (16+12)  <br>
Rising Slash 23+17 (25+13+15) > 23+19 (21+16+18)  <br>
Reaping Slash  23 (13+23) > 25 (17+22)  <br>
Double Slash 15+21 (13+11+25) > 18+27 (18+16+28)  <br>
Wide Sweep 23 (15+27) > 25 (16+28)  <br>
Tornado Slash 21+35 > 18+42, ailment modifier 1+1 > 1,2+1,4  <br>
Backflip 17 (13+13) > 19 (19+19)  <br>
Jumping Slash 21 (17+7) > 23 (19+9), ailment modifier 1 (1+1) > 1 (1,4+1,2)  <br>
Aerial Spin Assault 17+7xn > 24+9xn, ailment modifier 1+1xn > 1,4+1,2xn  <br>
Adept Roundhouse 35 > 42, ailment modifier 1 > 1,4  <br>
All attacks while having red extract get an ailment modifier of 1,2  <br>

### Kinsect Attacks:
All Kinsects were changed to be blunt so they can apply KO  <br>
Send Kinsect 22 > 45, KO 16 > 25  <br>
Charge Kinsect/Kinsect Spin 60 > 80, KO 40 > 50  <br>
Adept Kinsect Slam 30 (40) > 45 (60), KO 16 (16) > 25 (35)  <br>
Valor Kinsect Attack 22 (28) > 35 (50), KO 16 (16) > 20 (30)  <br>
Valor Kinsect Spin 50 > 80, KO 40 > 50   <br>

### Kinsect Changes:
![imagen](https://github.com/Potobc/MHGU-Rebalanced-Mod/assets/121890308/ebe2ff02-19e0-4d4f-aceb-be00e7c23417)  <br>

### Hunter Arts:
Extract Hunter buff duration increased 30/60/90 > 60/90/120, KO 16 > 80, and increased build up increased 700/900/1000 [1040/1280/1400] > 800/980/1150 [998/1170/1334]   <br>
Swarm fixed damage increased 6 > 10 (12 with red extract?), level 3 duration increased 60s > 90s, and HA generation 0 > 10   <br>
Bug Blow finisher MVs increased 80/105/120 > 90/120/150, ailment modifiers increased 1/1/1 > 2/3/4, stagger modifier increased 1/1/1 > 1,5/1,75/2, the extra attack from Swarm has the same properties depending on Swarm's level, and build up increased 580/670/750 [896/1004/1100] > 660/770/860 [866/970/1055]   <br>
Bug Majeure Combo MVs increased 20x3 > 60x3, KO 6 > 40, and build up increased 1080/1170/1250 [1496/1604/1700] > 1240/1340/1430 [1421/1519/1606]   <br>

### Alchemy:
Double Lateral 0,1 (0,15)  <br>
Kinsect Spin 0,2  <br>
Extract Hunter 1 (single hit)  <br>
Swarm 0,05 per hit  <br>
Bug Blow* 1,5/1,75/2, Swarm gives an extra gauge (single hit)  <br>
Bug Majeure 0,2 per spin combo (0,4 if you count the kinsect spin)  <br>

### Valor:
Regular Attacks 0,21s per hit  <br>
Marker Bash 1s  <br>
Triple Roundhouse 2s (4s)  <br>
Double Jumping Strikes 3s (5s)  <br>
Kinsect Regular Attack 1s  <br>
Kinsect Charge Attack 2s  <br>
Kinsect Valor Attack 4s  <br>
Extract Hunter 4,5/6/7,5s  <br>
Swarm 0,5s per hit  <br>
Bug Blow 6/7,5/9s  <br>
Bug Majeure 6s per spin combo  <br>

## Bowguns

### Item and Combo Changes:
Amount probability of 1-3 combos changed 5/85/10% > 5/70/25%  <br>
Normal 2 is now made with Stone and Huskberry  <br>
Normal 3 is now made with Needleberry and Bonehusk, Needleberry capacity decreased 99 > 50  <br>
Pierce 3 now gives 1-3 shots per combo  <br>
Scatternut capacity increased 30 > 50 (Pellet 1)  <br>
Pellet 2 is now made with Popfish and Huskberry, Popfish capacity increased 40 > 50  <br>
Wyvern Claw capacity decreased 50 > 10 (Cluster 2)  <br>
Loprey and Genprey fang capacity reduced 99 > 10 (Poison 2 and Para 2 respectively)  <br>
Elemental 1 shots now have a 75% chance of giving 2-4 shots when combining with a probability of 25/50/25%, and they now use bone husk instead of huskberry  <br>
Thunder shots now require thunderbugs to make, and thunderbug capacity has been decreased 99 > 20  <br>
Dragon 1 capacity increased 3 > 12, dragonfell berry capacity increased 10 > 30  <br>
Doubled Dragon 2 shot amount for all bowguns  <br>
If you have any sets with items whose capacity has been reduced you’ll get that amount added to your inventory in hub, but once you enter a quest they’ll be set to the new maximum amount and you'll lose any excess so make sure to change your sets to account for that.  <br>

### Styles:
Aerial LBG Power Load duration increased 10s > 17,5s  <br>
Aerial HBG Power Load duration increased 15s > 25s  <br>
Reduced Valor HBG dodge I-frames 20 > 12 (at 60fps) so they equal a regular dodge (valor I-frames overwrite evasion +1/2 so using those won't have any effect)  <br>
Valor siege ramp up speed reduced +0,1/shot > +0,08/shot, max speed reduced 2,5 > 1,35, initial speed stays at 0,8  <br>
LBG/HBG Valor reload gauge generation modifier increased 3,2/3,2 > 3,6/4,5, both of these modify the valor gauge values mentioned in the valor section  <br>
HBG Valor reload duration increased 24s > 30s  <br>

### Shot Types:
Pierce 9x3/7x4/7x5 > 7x3/7x4/7x5, HA gen 6/6/5 > 6/6/6   <br>
Pellet 5x3/5x4/5x5 > 7x3/7x4/7x5, Pellet 1 now has low rapid fire wait time, Pellet 2 now fires 3 shots with rapid fire, HA gen 5/5/5 > 6/6/6  <br>
Crag 25/30/45 fixed > 35/45/60 fixed, fire damage removed HA gen 25/30/40 > 35/45/55  <br>
Cluster 25x3/25x4/25x5 fixed > 30x3/30x4/30x5 fixed, explosion HA gen 25x3/25x4/20x5 > 30x3/30x4/25x5  <br>
Element 45/58% > 57/73%, HA gen 14/24 > 16/28  <br>
P. Element 20x3/23x5 > 27x3/25x5  <br>
Dragon 40x5/48x5% > 52x5/67x5%, HA gen 6x5/12x5 > 7x5/14x5  <br>
Force 15/18 > 18/21, HA gen 25/35 > 30/40  <br>
Long 15/18 > 20/24, HA gen 20/40 > 35/45  <br>
Heavy 9/12 > 15/19, Stagger modifier reduced 3/3,6 > 2,5/3, HA gen 18/24 > 30/38  <br>
Sting 14 > 16, HA gen 25 > 29  <br>
Stone 10 > 12, HA gen 15 > 18  <br>
Cannon 5/7 > 25/30, fixed damage removed, 10/15 KO > 30/40 KO, 5/10 Exh > 20/30 Exh, and cannonball HA gen 15/25 > 55/65  <br>
Tri-Blast 25x3 Fixed > 40x3 Fixed, fire damage removed, 10x3 Exh > 15x3 Exh, HA gen 25x3 > 35x3  <br>
Shrapnel 8x3 > 12x3, HA gen 8x3 > 12x3  <br>
Wyvern 25x2 > 37x2, fire damage removed, HA gen 25x2 > 37x2  <br>
Blast 25/50 Blast > 50/75 Blast  <br>
Poison Smoke 35 Poison > 75 Poison  <br>
LBG Valor dodge shot 10 KO/Exh > 15 KO/Exh  <br>
LBG Valor dodge double shot 7x2 KO/Exh > 9x2 KO/Exh  <br> 
Alchemy 10 > 12, HA gen 27 > 30  <br>

### Light Bowgun Hunter Arts:
Bullet Geyser build up reduced 300/500/650 [560/800/980] > 270/310/360 [516/549/592]  <br>
Full House increased build up 250/310/650 [500/570/980] > 500/620/750 [718/828/951]  <br>
Rapid Fire rain MVs per shot increased 6 > 12, build up increased 300/500/650 [560/800/980] > 950/1080/1200 [1141/1267/1431]  <br>
Charge Shot number of shots increased at level 3 10 > 15  <br>

### Heavy Bowgun Hunter Arts:
Super Nova center damage increased 40/40/45 > 80/90/100, grazing damage increased 36/15/5 > 40/45/50, and build up increased 420/500/830 [704/800/1196] > 1080/1170/1250 [1267/1354/1431]. Formula for damage is (Center/Grazing) + (Center/Grazing) x (weaponRaw / 100 * 0,75/1,5/2)  <br>
Guns Blazing duration increased 40/60/90s > 60/90/120s  <br>
Gunpowder Infusion damage buff reduced 10% > 7,5%, amount of shots given at level 3 increased 22 > 25  <br>
Void piercer MVs increased 90/120/170 > 130/160/200, stagger mod increased 1,1/1,15/1,2 > 1,2/1,3/1,4, build up increased 830/1000/1070 [1196/1400/1604] > 1030/1270/1450 [1218/1451/1626]   <br>

### Alchemy:
Bullet Geyser 0,1/0,2/0,3  <br>
Rapid Fire Rain 0,15 per shot, 2,25/2,7/3,15 if you hit all shots  <br>
Charge Shot 0,1/0,15/0,2 (refers to shot level)  <br>
Super Nova* 2 (1 for shot and 1 for explosion)  <br>
Void Piercer 1 (single hit)  <br>

### Valor:
Normal 0,24/0,4/0,4s  <br>
Pierce 0,13/0,1/0,09s per hit  <br>
Pellet 0,14/0,12/0,1s per hit  <br>
Element 0,56/0,7s  <br>
Pierce Element 0,27/0,23 per hit  <br>
Dragon 0,25/0,3s per hit  <br>
Crag 1,25/1,35/1,45s  <br>
Clust 1,25/1,35/1,45s  <br>
Status 0,7/0,85s  <br>
Force 0,55/0,7s  <br>
Long 0,6/0,76s  <br>
Dazzling 0,55  <br>
Heavy 0,6/0,76s  <br>
Sting 0,55  <br>
Stone 0,55  <br>
Cannon 1/1,2s  <br>
Triblast 0,36 per hit  <br>
Slicing 0,26/0,2s per hit  <br>
Shrapnel 0,32s per hit  <br>
Wyvern 2s  <br>
Valor Shot 0,48s  <br>
Bullet Geyser 0,8/1/1,3s  <br>
Rapid Fire Rain 0,2s per shot, 3/3,6/4,2s if you hit all shots  <br>
Charge Shot 0,15/0,3/0,5s per shot level  <br>
Super Nova 1,5/1,75/2s  <br>
Void Piercer 1,5/1,75/2s  <br>

## Bow

### Coatings:
Element Coating 1 and 2 capacity increased 20 > 50  <br>

### Modifiers:
Alchemy Gauge 0,4/1/1,5/1,7 > 0,4/0,8/1/1,25 (this applies to the Alchemy generation of arrows)  <br>
Valor Gauge 1/1,2/2/2,5 > 0,8/1/1,3/1,5 (this applies to the Valor generation of arrows)  <br>
Arc Shot Raw 0,7/0,85/0,95 > 1/1,2/1,4  <br>
Valor Power Shots 1+1,3 > 0,6+0,8  <br>

### Arc Shots:
Focus 3x5, 7x5 KO, 8x5 Exh > 6x5, 12x6KO, 10x6Exh  <br>
Wide 3x5, 7x5 KO, 8x5 Exh > 6x5, 12x6KO, 10x6Exh  <br>
Blast 18 fixed, 20 KO, 27 Exh > 60 fixed, 60KO, 40Exh  <br>

### Hunter Arts:
Triple Volley MVs increased 7x3+7x3+17x5/10x3+10x3+20x5/14x3+14x3+23x5 > 15x3+15x3+26x5/19x3+19x3+31x5/22x3+22x3+36x5, and build up increased 500/600/700 [800/920/1040] > 1080/1170/1250 [1267/1354/1431]  <br>
Tactical Retreat build up reduced 250/330/420 [500/596/704] > 250/300/360 [500/541/592]  <br>
Blade Wire MVs increased 9x3/11x3/13x3/15x3 > 12x3/14x3/16x3/18x3  <br>

### Weapons:
The bows below have been changed to give every shot/element combination a viable option  <br>
All bows changed that had the Blast Arc Shot where given either wide or focus since those are better at applying element  <br>
Thunder, Water, and Dragon bows get power 2, and element 1/2 coatings  <br>
Fire, and Ice bows get power 1/2, and element 2 coatings  <br>
![imagen](https://github.com/Potobc/MHGU-Rebalanced-Mod/assets/121890308/ba59ee88-d815-4d47-9ebd-cd3734b5a1bb)  <br>


### Alchemy:
Arrows 0,01/0,02/0,05/0,08/0,1 depending on shot level  <br>
Arc Shot 0,15  <br>
Triple Volley 1,5/2/2,5  <br>
Blade Wire 0,02/0,05/0,1/0,15 per hit  <br>

### Valor:
Arrows 1,1/1,8/2,3/2,7/3s depending on shot level  <br>
Triple Volley 7,5/9/10,5s  <br>
Blade Wire 1,2/1,5/1,8/2,25s per hit   <br>

## Palico/Prowler

### Melee Attacks:
Draw Attack/Right Slash 12 > 17, ailment modifier 0,7 > 1   <br>
Left Slash 14 > 19, ailment modifier 0,7 > 1,1   <br>
Overhead Slash 16 > 24, ailment modifier 0,7 > 1,2   <br>
Rising Slash 18 > 27, ailment modifier 1 > 1,3   <br>
Jumping Spinning Slash first hit 5 > 12, and ailment modifier 0,4 > 1, repeating hits 5xn > 7xn, ailment modifier 0,4xn > 0,6xn   <br>
Furr-ious Flurry repeating Hits 7xn > 16xn, ailment modifier 0,5xn > 1xn   <br>
Furr-ious Flurry Finisher 8x3+30 > 18x3+35, ailment modifier 0,5x3+1 > 1,2x3+1,5   <br>
Furris Wheel 5xn > 6xn,  ailment modifier 0,4xn > 0,6xn   <br>

### Boomerang Attacks:
Boomerang 1 9 > 12   <br>
Boomerang 2 7 > 14   <br>
Boomerang 3 6+13 > 6+17   <br>
Big Boomerang 1 12 > 15   <br>
Big Boomerang 2 10 > 18   <br>
Big Boomerang 3 9+17 > 9+20   <br>
Piercing Boomerang 1 9+2x3 > 12+2x3   <br>
Piercing Boomerang 2 7+2x3 > 14+3x3   <br>
Piercing Boomerang 3 6x3+13+3x3 > 6x3+17+4x3   <br>
Big + Piercing 1 12+3x3 > 15+3x3   <br>
Big + Piercing 2 10+3x3 > 18+4x3   <br>
Big + Piercing 3 9x3+17+4x3 > 9x3+20+5x3   <br>
Boomerush 24+4 > 18+9, ailment modifier 1+0,5 > 1,2+0,7   <br>
Big Boomerush 24+6 > 18+12, ailment modifier 1+0,5 > 1,2+0,8x3   <br>
Piercing Boomerush 24+4x3 > 18+9x3, ailment modifier 1+0,5x3 > 1,2+0,7x3   <br>
Big + Piercing Boomerush 24+6x3 > 18+12x3, ailment modifier 1+0,5x3 > 1,2+0,8x3   <br>
Charged Boomerang raw modifier increased 1,15 > 1,3   <br>
Piercing Boomerangs ailment modifier increased 0,4xn > 0,6xn    <br>

### Beast Attacks:
Forward Slashes 10x2 > 13x2, ailment modifier 0,7x2 >  0,9x2   <br>
Jumping Slashes 12x2 > 16x2 ailment modifier 0,7x2 > 1,1x2   <br>
Triple Slashes 8x3 > 19x3, ailment modifier 0,5x3 > 1,2x3   <br>
Back Slashes 11x2 > 15x2, ailment modifier 0,7x2 > 1x2   <br>
Rushing Slashes 5x2+7x2 > 7x2+9x2, ailment modifier 0,5x2+0,5x2 > 0,8x2+0,9x2   <br>
Charged Rushing Slashes 6x2+9x2 >9x2+13x2, ailment modifier 0,8x2+0,8x2 > 1x2+1,2x2   <br>
Beast Finisher 10x4 > 22x4, ailment modifier 1x4 > 1,5x4   <br>
Beast Furris Wheel 4xn > 6xn, ailment modifier 0,4xn > 0,6xn   <br>

### Weapons:
I really wanted to change all weapons but I’m already taking too long on the update, so I decided to just change the elemental deviant weapons, though as a consolation I also changed status deviants. I also gave them each a server and blunt version (X/XX version respectively)    <br>

### Support Moves Cost:
Barrel Bombay 0 > 1   <br>
Cheer Horn gauge cost 3 > 2   <br>
Furrious gauge cost 4 > 3   <br>
Pilfer gauge cost 4 > 3   <br>
Plunderrang gauge cost 4 > 2   <br>
Poison Purr-ison gauge cost 5 > 4   <br>
True Health Horn gauge cost 3 > 2   <br>

### Skill Size:
Changed palico skill slots progression so you now get 10 slots at max level. You get the 8th slot at level 70 (was 75), the 9th at level 85, and the 10th at level 99. The game doesn't show your skill slots once you have 9+ but they still work, you just won't see them.   <br> 
All Elemental Boosts 2 > 1   <br>
Anger Prone 2 > 1   <br>
Attack up L 3 > 2   <br>
Attack Up S 2 > 1   <br>
Baddest Cat Ever 3 > 2   <br>
Bombay Boost 3 > 2   <br>
Crit Boost 4 > 3   <br>
Elemental Attack Up 3 > 2   <br>
Extend Beast 2 > 1   <br>
Extend Fury 2 > 1   <br>
Extend SP State 3 > 2   <br>
Extreme DEF-centric 4 > 2   <br>
Fanalis 2 > 1   <br>
Felyne Protection 2 > 1   <br>
Guard Boost 2 > 1   <br>
Guts 3 > 2   <br>
Horn Virtuoso 3 > 2   <br>
KO King 2 > 1   <br>
Land Master 3 > 2   <br>
Last Stand 3 > 2   <br>
Negate Confusion 2 > 1   <br>
Negate Wind 2 > 1   <br>
Nine Lives (Attack) 4 > 2   <br>
Nine Lives (Defense) 3 > 1   <br>
Omniresistance 3 > 2   <br>
Pilfer Boost 3 > 2   <br>
Pro Experience 4 > 2   <br>
Pro Trapper 3 > 2   <br>
Recovery Speed Up 2 > 1   <br>
Status Attack Up 4 > 2   <br>
Support Priority 3 > 2   <br>
Triforce 4 > 3   <br>
Universal 3 > 2   <br>
Weakness Exploit 2 > 3   <br>
Wind Waker 3 > 2   <br>

### Modifier Changes:
Palico damage per level changed 15-110 > 2-100 (affects both melee and ranged)   <br>
Palico defense per level changed 1-215 > 2-100   <br>
Charisma bomb modifier increased to 1,5  <br>
Assist, Heal, Gather, Protect, Fighting, and beast bomb modifiers changed to 1  <br>
Bomb bomb modifier increased to 2  <br>
Charisma melee modifier increased 1 > 1,25   <br>
Fight melee modifier increased 1,05 > 1,5   <br>
Guard melee modifier increased 1,05 > 1,25   <br>
Assist melee modifier increased 0,9 > 1   <br>
Heal melee modifier increased 0,9 > 1   <br>
Bomb melee modifier increased 0,95 > 1   <br>
Gather melee modifier increased 0,9 > 1   <br>
Beast melee modifier increased 1,1 > 1,5   <br>
Charisma ranged modifier increased 0,95 > 1,25   <br>
Guard ranged modifier increased 0,9 >1   <br>
Assist ranged modifier decreased 1,05 > 1   <br>
Heal ranged modifier increased 0,9 > 1   <br>
Bomb ranged modifier increased 1 > 1,25   <br>
Gather ranged modifier increased 1,1 > 1,5   <br>
Beast ranged modifier increased 0,85 > 1   <br>
Charisma defense modifier increased 0,95 > 2,5   <br>
Fight defense modifier increased 0,95 > 2,5   <br>
Guard defense modifier increased 1,1 > 3,5   <br>
Assist defense modifier increased 0,7 > 2,5   <br>
Heal defense modifier increased 1 > 2,5   <br>
Bomb defense modifier increased 0,85 > 2   <br>
Gather defense modifier increased 0,6 > 1,5   <br>
Beast defense modifier increased 1,1 > 2,5   <br>
Gauge modifiers order: Melee/Boomerang/Bomb/Blocks/gather/Passive in combat/Passive not in combat   <br>
Charisma Gauge modifiers changed 0,95/0,9/1/0,8/0,625/0,4/0,6 > 1,3/1,3/1,5/1/1/0,6/0,6   <br>
Fight Gauge modifiers changed 1,05/1/1/0,6/0,25/0,2/0,6 > 1,2/0,5/0,5/0,5/0,5/0,2/0,2   <br>
Protect Gauge modifiers changed 0,85/0,75/1,3/1,5/0,25/0,2/0,4 > 1/0,5/0,5/2/0,5/0,4/0,2   <br>
Assist Gauge modifiers changed 0,8/1,1/0,5/0,6/0,8/0,4/0,4 > 0,75/1/0,5/1/1,5/1/1,2   <br>
Heal Gauge modifiers changed 0,7/0,75/0,5/1/1/0,8/1,1 > 0,75/1/0,5/1/1,5/1/1,2   <br>
Bomb Gauge modifiers changed 0,9/1/1,6/0,25/0,25/0,2/0,4 > 0,5/0,5/2/0,25/0,5/0,2/0,2   <br>
Gather Gauge modifiers changed 0,7/1,2/0,5/0,4/1,25/0,8/0,2 > 0,5/1,2/0,5/0,25/2/0,2/0,6   <br>
Beast Gauge modifiers changed 1,1/0,75/0,75/0,25/0,25/0,2/0,2 > 1,2/0,5/0,5/0.25/0,5/0,2/0,2   <br>
![imagen](https://github.com/user-attachments/assets/c1550b0b-2781-4cf9-99e3-f59035dc2993)   <br>


## Optional Palico Changes:

### Moves:
Assist: emergency retreat > piercing Boomerang   <br>
Fighting: piercing Boomerang > emergency retreat  <br>
Switched those two since I wanted to keep the 2 bias per move rule and fighting is melee focus so emergency retreat gives it a good and inherent healing move. (same reasoning for giving Assist piercing since it's ranged focused)  <br>
Bomb: Mega Barrel Bombay > Giga Barrel Bombay (Mega replaces Giga in A tier skills, doesn't make sense for Bomb to not have innate access to the best Bomb move)  <br>

### Skills:
Charisma: Slacker slap > weakness exploit (slacker slap wasn't useful so this way you can get wex without the save editor or XX exclusive cats)  <br>
Fighting: Attack up S > Extend Fury (Attack Up is now a C tier skil replacing tremos res., with the it taking extend fury place in B tier)  <br>
Beast: Recovery Speed Up > Extend Beast (Recovery Speed Up replace biology in C tier)  <br>
Replaced Goldenfish Catcher, Negate Confusion and wind, Stamina Drain, and Non-stick fur, with an elemental boost skill (ice, water, and dragon boost, megaflare, and nagatobimaru), and made them 1 cost.   <br>

Optional since the game does have a sanity check and will unequip moves/skills if you have any illegal ones, so you will have to use a save editor or grind if you want to use these changes.  <br>
To install it, download the optional changes and replace the resident.arc file inside GU rebalanced\romfs\nativeNX\loc\arc, or luma\titles\0004000000179800\romfs\arc with the one from the optional changes folder.  <br>

# Credits:  <br>
Marie • マリー. Responsible for basically all the palico changes not taken from cope.  <br>
NeoChozo. Tester for blademaster weapons and helped with balancing them.  <br>
SnowxNexus for helping with testing prowlers, Bows, and the Valor rework.  <br>
Kurrimu2 devs. Used it to extract and replace game files. [Link](https://github.com/FanTranslatorsInternational/Kuriimu2)  <br>
Fabius_Flynn for helping test the valor rework. [Link](https://www.twitch.tv/Fabius_Flynn)
FallenFeces for testing out the CB yellow shield and general help.
Rhendryo for testing the valor changes.
Darkclem for help with Prowler.
Aradi and everyone who worked on the cope mod. Used their files to know where stuff was, and ~~stole~~ got a lot of changes from them. [Link](https://github.com/Aradi147/MHGUCope)  <br>
Everyone who worked on the mhxx and mhgu modding wiki. Showed where to find and how to edit weapons base stats. [Link](https://github.com/GReinoso96/XXModding/wiki/Weapons)  <br>
Awesomeosity. Used their guides to know attacks MVs and names. [Link](https://drive.google.com/drive/folders/117JR73W79j0ToZ0TyVFRPNm_hFGX44Hj)  <br>
Rage Burner for the XX port  <br>
RoxSin for helping with balance and testing of bowguns.  <br>
Klark231, Crosshex, and everyone who worked on the XX translation project, since I used some of their files to have the game in english. [Link](https://gbatemp.net/threads/mhxx-complete-english-patch.609362/)  <br>
Everyone who worked on Kiranico. Used for finding IDs when editing weapons. [Link](https://mhgu.kiranico.com/)  <br>
iSharingan. Used their spreadsheet to know palico gauge modifiers. [Link](https://docs.google.com/spreadsheets/d/1D7IaRnsc3Jv3ce-RGHB0tJV-ArvNZbrHP-w9ZRIBBAQ/edit)  <br>
Monkbreh (github: Monkbreh). Helped with move identification and told me where to find valor style changes [Link](https://github.com/Monkbreh)  <br>
aJiJi123. Helped with shot type IDing  <br>
