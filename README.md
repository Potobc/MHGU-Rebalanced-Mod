# MHGU Rebalance mod 
 
This mod intends to balance the game in order to reduce the power gap between weapons and styles. Palicoes/Prowlers were also changed to give each bias a more defined role.  <br>

To install extract it to your mods folder if you are using ryujinx (should look like this: mods\contents\0100770008dd8000\GU rebalanced), or to the mhgu folder in atmosphere\contents if you are using a modded switch (should look like this: atmosphere\contents\0100770008dd8000\GU rebalanced), doesn’t work on yuzu. 

For the 3DS XX version, if you are using citra just extract the mod and place the romfs folder into the XX mods folder (should look like this: Citra\load\mods\0004000000197100\romfs). If you are using a modded 3DS place the romfs folder into the XX titles folder (should look like this: luma\titles\0004000000197100\romfs)

Remember to back up your save file.    <br>

If you have any suggestions leave them in the issues page, or DM me at potobc on discord.  <br>

Also available on [Gamebanana](https://gamebanana.com/mods/447835)   <br>

## All Weapons
All MV increases are also HA generation increases   <br>
Adjusted SP mode cost increase   <br>
![imagen](https://github.com/Potobc/MHGU-Rebalanced-Mod/assets/121890308/745bf5d0-9ff4-4ac9-b4fb-b5314aa0e056)   <br>

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


### Non-Weapon Specific Hunter Arts: 
Heal Gain build up reduced 830 [1196] > 570 [782]   <br>
Escape Runner duration increased 30s > 90s    <br>
Hunter's Oasis build up reduced 1330 [1796] > 860 [1055]   <br>
Frenzy Fever build up reduced 830 [1196] > 610 [819]   <br>
Castle Walls build up reduced 830 [1196] > 610 [819]   <br>
Fortress Walls build up reduced 1080 [1496] > 860 [1055]   <br>
Arisen Phoenix build up reduced 1080 [1496] > 540 [754]   <br>

## Great Sword

### Attacks:
Charge 48/65/80/100 > 58/75/90/110   <br>
Strong Charge/Valor Strong Charge 52/72/90/120 > 65/80/100/130   <br>
Jumping Slash 48 > 56   <br>
Aerial Draw Slash 48 > 60   <br>
Aerial charge 57/66/75 > 60/75/90   <br>
Adept Upswing charge 26/39/52/78 > 48/55/70/85   <br> 
Valor Draw Slash 52/62/85/115 > 52/62/70/90   <br>
Valor Charge Dash 48/65/81/112 > 52/72/90/120   <br>
Alchemy side slash 48 > 90   <br>

### Hunter Arts:
Ground Slash MVs buffed 50+20x2/50+21x3/50+22x4 > 50+20x2/60+24x3/75+28x4   <br>
Lion’s Maw multiplier buffed 1,1/1,2/1,33 > 1,2/1,4/1,6 and build up increased 290/350/500 [548/620/800] > 370/450/580 [601/672/791  <br>
Brimstone Slash MVs buffed 130/150/175/190 > 160/180/210/250, max charge time increased 8s > 12s   <br>
Moonbreaker MVs buffed 60/12+70/10+12+80 > 75/10+85/10+12+95, and build up increased 420/500/830 [704/800/1196] > 630/710/830 [838/913/1027]  <br>

### Alchemy:
Alchemy side slash 0,35  <br>
Ground Slash 1,5/1,75/2  <br>
Lion's Maw 0,15/0,3/0,5  <br>
Brimstone Slash 1 (single hit)  <br>
Moonbreaker* 1/1,5/2  <br>

## Long Sword

### Attacks: 
Side Fade Slashes 24 > 28  <br>
Spirit Roundslash 42 > 55  <br>
Rushing Spirit Slash 30 > 36  <br>
Aerial Slashes 10+25 > 15+25  <br>
Adept Spirit Reckoning 30+80 > 20+70  <br>
Valor Spirit Slash I 28 > 35  <br>
Valor Counter 51 > 28  <br>
Valor Spirit Reckoning 35+60 > 15+60  <br>

### Hunter Arts:
Sakura slash MVs reduced 100/140/160 > 80/120/140   <br>
Unhinged spirit cost increased 420/500/580 [704/800/896] > 500/580/690 [718/791/894]   <br>
Devouring demon multiplier reduced 1.1/1,2/1,3 > 1,1/1,15/1,2, and duration increased 75/60/45 > 105/90/75  <br>

### Alchemy:
Spirit Slash I 0,1  <br>
Spirit Slash II 0,15  <br>
Spirit Slash III 0,05+0,05+0,1  <br>
Spirit Roundslash 0,3  <br>
Sakura Slash 1,25/1,5/1,75  <br>
Unhinged Spirit 0,5/0,75/1  <br>
Critical Juncture 1 (single hit)  <br>

## Sword and Shield

### Oils:
Stamina Oil 8 KO > 10 KO, 10 Exh > 12 Exh  <br>
Stagger Oil stagger mod 1,2 > 1,3  <br>

### Attacks:
Rush Slash/Backstep Attack 18 > 21   <br>
Shield Combo 10+20 > 20+25   <br>
Shield Bash 8 > 21   <br>
Shield Thrust 16 > 30   <br>
Backstep Charge Attack 20+34 > 28+44, elemental mod 1+1 > 1,1+1,5   <br>
Jumping Slash 20 > 25   <br>
Aerial Rising Slash 25 > 35   <br>
Adept Backstep Counter 42 > 50, elemental mod 1 > 2   <br>
Valor Lunging Slashes 10+9+9 > 12+10+10   <br>
Valor Backflip 14 > 20   <br>
Valor Round Slashes 14+18 > 20+26   <br>
All other attacks get an MV increase of 10%   <br>
All attacks get a 1,1 elemental modifier   <br>
All shield attacks get their KO and exhaust doubled, and increased stagger mod 1 > 1,5   <br>

### Hunter Arts:

Sword Dance MVs buffed 25+14+15+15+14+15+20+7+45 > 29+19+21+21+19+21+33+22+55, level II finisher buffed 40 > 45  <br>
Round force build up increased 250/250/290 [500/500/548] > 340/400/500 [575/628/718]  <br>
Shoryugeki MVs buffed 10+60/10+35+60/10+35+60+30 > 10+70/10+45+70/10+45+70+60, stagger mod increased 1 > 1,5, and Shoryugeki III KO and exhaust increased 0+100+50+50KO > 0+100+75+75KO, 0+50+40+40ex > 0+60+45+45ex  <br>
Chaos Oil build up increased 920/1000/1000 [1304/1400/1400] > 1270/1400/1570 [1451/1577/1743], duration changed 135/180/120s > 120/150/180s, now all levels of chaos oil give you 20% affinity, 6 KO, 8 Exh,  1,15 stagger mod, and 50 sharpness, with stacking only bringing the oils back to their original value  <br>

### Alchemy:
Roundslash 0,1  <br>
Swords Dance 1,5/2/2,5  <br>
Round Force 0,25/0,5/0,75  <br>
Shoryugeki* 1/1,5/2  <br>
Chaos Oil 1 (single hit)  <br>

## Dual Blades

### Attacks:
Arch Slice I 8+12 > 10+14  <br>
Arch Slice II 7+10 > 12+16  <br>
Double Arch Slashes 10+13x2 > 12+15x2  <br>
Right Arch Side Slashes 7+10 > 11+15	  <br>
Left Arch Side Slashes 9+12 >11+15   <br>
Arch Spinning Slashes 16+6+8+18+6+10 > 19+9+11+21+9+13  <br>
Arch Hurricane Dance 8x4+20x2 > 11x4+24x2  <br>
All non-style specific attacks in archdemon mode get an increased elemental mod 1 > 1,1   <br>

### Hunter Arts:
Blood wind spin elemental modifier increased 1 > 1,1  <br>
Wolf's maw multiplier reduced 20/25/30% > 15/17,5/20%, buildup reduced 1250/1500/1670 [1700/2000/2204] > 1080/1170/1350 [1267/1354/1528]  <br>
Aerial Slam  MVs Increased 80/110/150 > 130/160/200, finisher stagger mod increased 1,5 > 2, stagger mod for spins reduced to 0 (to avoid missing due to a flinch)  <br>
Spiral slash spin MVs Increased 10 > 15, elemental modifier increased 0,5 > 1,2 for spins, and 1 > 2 for finisher, stagger modifier for spins reduced 0,9 > 0 (to avoid breaking parts before finishing), and stagger modifier for finisher increased 2/2/2 > 2/2,8/3 (to make up for the lost part damage)  <br>

### Alchemy:
Arch Hurricane Dance 0,4  <br>
Demon Dance 0,3  <br>
Blood Wind 2/2,5/3  <br>
Aerial Slam* 1,5/1,75/2  <br>
Spiral Slash 1,5/1,75/2  <br>

## Hammer

### Attacks:
Side Swing 15 > 20  <br>
Weak Pound 20 > 30  <br>
Draw Swing 20 > 30  <br>
Charge 1 20 > 30  <br>
Charge 2 40 > 50  <br>
Charge 3 Idle 15+76 > 20+90, KO 5+27 > 5+35  <br>
Charge 3 Moving 20+10x4 > 25+13x4, KO 2+2x4 > 10+8x4, Exhaust 2+2x4 > 8+4x4 (finishers stay the same)  <br>
Striker 3rd Pound 60 > 70, fixed hunter art generation 4 > 70  <br>
Striker Charge 3 19+86 > 25+95, KO 5+17 > 5+35  <br>
Aerial Charge 3 60 > 75   <br>
Aerial Smash 42 > 50   <br>
Aerial Double Down 35+50 > 35+60  <br>
Adept Charge 2 38 > 45  <br>
Adept Rushing Swing 38 > 45  <br>
Adept Idle Strong Charge 3 20+90 > 20+100, KO 10+27 > 10+40  <br>
Adept Moving Strong Charge KO 10+27 > 10+35  <br>
Valor Charge 3 15+85/20+105 > 15+85/20+115  <br>

### Hunter Arts:
Spinning Meteor MVs Increased 20x2+15+110/20x3+15+125/20x4+15+165 > 25x2+15+130/25x3+20+145/25x4+25+175, Exhaust Increased 15x2+10+30/15x3+10+30/15x4+10+40 > 18x2+10+40/18x3+15+55/18x4+20+70, and build Up increased 830/920/1100 [1196/1304/1520] >  1080/1250/1420 [1267/1354/1528]  <br>
Provoke Duration Increased 30/60/60s > 60/60/90s  <br>
Typhoon Trigger MVs Increased 5x6+20+50/60/80 > 8x6+25+50+60/70/90, KO Increased 2x6+40+60/100/125 > 5x6+50+70+100/120/140, Build Up Increased 250/330/420 [500/596/704] > 430/550/640 [654/764/847]  <br>
Impact Press Damage Increased 6 > 8, Exhaust Increased 4 > 5, HA gen 0 > 8  <br>

### Alchemy:
Charge 3 Idle 0,25  <br>
Spinning Meteor* 1,5/2/2,5  <br>
Provoke  1 (single hit)  <br>
Typhoon Trigger 1,5/1,75/2  <br>
Impact press 0,05 per hit  <br>

## Hunting Horn

### Attacks:
Draw Slam 33 > 40   <br>
Right Swing 30 > 36   <br>
Right Swing (After any attack) 27 > 35   <br>
Forward Slam 30 > 36   <br>
Forward Slam (After any attack) 27 > 35   <br>
Left Swing 30 > 36   <br>
Double Swing 12+15 > 16+20   <br>
Back Swing 45 > 53   <br>
Swing 'n Slam 15+45 > 15+50    <br>
Hilt Jab 10 > 17   <br>
Recital Right Sweep 35 > 42   <br>
Recital Kick 20 > 27   <br>
Recital Back Swing 30 > 40   <br>
Encore Backswings 40+30 > 46+40   <br>
Triple Encore Backswing 33+40+30 > 39+46+40   <br>
Encore Side Swing 35 > 42   <br>
Double Encore Side Swings 33+35 > 36+42   <br>
Jump Swing 36 > 47   <br>
Aerial Double Swings 12+22 > 26+44   <br>
Adept Triple Swings 15+20+30 > 20+30+35   <br>
Adept Recital 38 > 50   <br>
Valor Recital 30+10 > 40+13   <br>
Valor Encore 45+15 > 50+20   <br>
Regular Attacks and Recitals elemental modifier increased 1 > 1,2   <br>
Encores elemental modifier increased 1 > 1,3   <br>

### Hunter Arts:
Euphony build up increased 590/630/670 [958/956/1004] > 700/750/800 [903/951/998]   <br>
Sonic Smash wind-up elemental modifier increased 1 > 1,2, finisher damage, KO, and exhaust increased 30/35/38 > 40/60/100, 10/10/10KO > 40/60/100KO, 10/10/10ex > 60/80/120ex, and build up decreased 830/1000/1070 [1196/1400/1604] > 630/670/790 [838/875/989]    <br>
Harmonize duration buffed 60/90/120s > 90/120/150s, and build up increased 420/580/670 [704/896/1004] > 580/690/800 [791/894/998]    <br>
Invigoration duration buffed 90/120/150s > 120/150/180s, Recital MV increased 38 > 50, and build up increased 420/500/580 [704/800/896] > 500/580/690 [718/791/894]   <br>

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

## Lance

### Attacks:
Mid Thrust 20/20/25 > 25/25/30, elemental mod 1/1/1 > 1,05/1,05/1,1   <br>
High Thrust 22/22/27 > 25/25/30, elemental mod 1/1/1 > 1,05/1,05/1,1   <br>
Strong Thrust 16x3 > 22x3, elemental mod 1x3 > 1,1x3   <br>
Wide Sweep 20 > 35, elemental mod 1 > 1,15   <br>
Uncharged Counter Thrust 22 > 25   <br>
Charged Counter Thrust 50 > 60, elemental mod 1 > 1,5   <br>
Shield Bash 14 > 24, KO 27 > 45, Exhaust 27 > 25, Stagger mod 1 > 1,2   <br>
Jumping Thrust 30 > 40   <br>
Charge elemental mod 1 > 0,8   <br>
All Charge Finishers elemental mods 1 > 1,5   <br>
Striker charge finisher 67 > 60, elemental mod 1 > 1,5   <br>
Aerial triple poke 15x3 > 23x3, elemental mod 1 > 1,1   <br>
Adept Counter Swipes elemental modifier stays at 1,2+1,2   <br>
Valor shield bash 20 > 25, KO and Exhaust 27 > 35   <br>

### Hunter Arts:
Shield Assault MVs buffed, charge 10 > 15, shield Attack 30 > 60 exhaust and KO 27 > 70, Lance Attack 50 > 85  <br>
Corkscrew Jab 45x3/32x5/27x7 > 65x3/45x5/37x7, elemental mod 1/1/1 > 1,5/1,3/1,2  <br>
Enraged Guard 1.1/1.2/1.3 > 1.05/1.1/1.15  <br>

### Alchemy:
Strong Thrust 0,2  <br>
Shield Bash 0,15  <br>
Shield Assault 0,05 per shield hit, and 0,35 for both finishers  <br>
Corkscrew Jab 2/2,5/3  <br>

## Gunlance

### Attacks:
Draw attack/Running Upswing 28 > 34  <br>
Post-Shell Upswing 27 > 32  <br>
Upswing 25 > 30  <br>
Thrust 21 > 28  <br>
Slam 36 > 48  <br>
Guard Thrust 16 > 20  <br>
Jumping Thrust 22 > 27  <br>
Jumping Slam 36 > 48  <br>
Jumping Reload Slam 40 > 48  <br>
Striker 3rd Thrust 24 > 29  <br>
Aerial Slam 36 > 48  <br>
Aerial Reload Slam 40 > 48  <br>
Adept/Valor Upswing 40 > 45  <br>
Adept/Valor Reload Upswing 37 > 45  <br>
Adept Slam 50 > 55  <br>

### Shellings:
All shelling attacks now deal fixed blast status instead of fixed fire to make them better against more monsters. Blast values are 2x the previous fire damage for all shelling attacks except wide shelling where it's 4x  <br>
Normal shelling 3/4/5 damage increased 18/21/24 > 20/26/38, HA gen. increased 20 > 26  <br>
Wide shelling 3/4/5 damage increased 40/44/48 > 48/58/73, HA gen. increased 40 > 58  <br>
Long shelling 3/4/5 damage increased 28/32/36 > 34/44/60, HA gen. increased 30 > 44  <br>
Modifier order is Full burst/Charged Shelling/Wyverfire  <br>
Normal modifiers changed 1,2/1,2/1 > 1,25/1,25/1  <br>
Wide modifiers changed 0,9/1,45/1 > 1/1,5/1  <br>
Long modifiers changed 1/1,2/1,2 > 1/1,25/1,25  <br>
Wyvernsfire damage increased 25x4/30x4/35x4/40x4/45x4/ > 40x4/46x4/61x4/80x4/95x4, HA gen increased 50x4 > 80x4  <br>
Alchemy Wyvernsfire damage and HA generation increased 50% > 75% (AA Flare wyvernsfire deals full amount as always)  <br>
Removed cooldown from overheating  <br>
Valor rapid fire multiplier changed 1+1,2+1,5+2+2,6+2,6 > 0,8+1+1,2+1,4+1,8+1,8  <br>
Valor full burst modifier changed 0,8+0,9+1+1,4+1,5+1,6 > 0,8+0,9+1+1,1+1,2+,1,3  <br>

### Hunter Arts:
Dragon Blast first hit damage increased 48/49/50 > 150/200/250, repeating hits damage increased 3/6/9 > 10/15/20. Damage Formula is 1st hit x (1 + weaponRaw x 0.7/100) + 3 x (repeating hit x (1 + weaponRaw x 0.2/100)), build up increased 830/1000/1250 [1196/1400/1700] > 1180/1280/1370 [1363/1460/1548]  <br>
Blast Dash III damage increased 24+50 > 28+6, and build up increased 250/290/330 [500/548/596] > 320/360/400 [558/592/628]  <br>
Dragon breath's extra hit damage increased 10 > 15, fixed fire replaced by blast, build up increased 1080/1170/1250 [1496/1604/1700] > 1180/1280/1370 [1363/1460/1548]  <br>
AA Flare wide and long shelling deal 2x damage, normal shelling deals 1,8x damage, build up increased 400/460/520 [680/752/824] > 480/560/670 [699/773/875]  <br>

### Weapons:
Shelling buffs are applied to the final level/s  <br>
Maccao GL 3 > 4  <br>
Fiore Nulo GL 3 > 4  <br>
Fiore Nulo (G) GL 3 > 4  <br>
Fiore Nulo (R) GL 3 > 4  <br>
Baa Baa GL 3/3 > 4/5  <br>
Kamak GL 3/4 > 4/5  <br>
Teostra GL 1/1/1/1/1/1 > 1/1/2/2/3/4  <br>
Nakarkos GL 4 > 5  <br>
Worn GL 3/4 > 4/5  <br>
Giadrome GL 3/4 > 4/5  <br>
Nerscylla GL 3/4 > 4/5  <br>
Deviljho GL 3 > 4  <br>
Hyper Barroth GL 4 > 5  <br>
Dreadqueen GL 4 > 5  <br>
Drilltusk GL 3 > 4  <br>
Grimclaw GL 4 > 5, also gave dragon element 20/21/22/23/24/25/26/27/28/29/30/33/35/37/39  <br>
Nightcloak GL 4 > 5  <br>
Boltreaver GL 4 > 5  <br>
Bloodbath GL 4 > 5  <br>

### Alchemy:
Slam 0,15  <br>
Normal 0,03  <br>
Wide 0,06  <br>
Long 0,045  <br>
Wyvernsfire 0,5  <br>
Dragon Blast* 2/2,5/3  <br>
Blast Dash 0,25 for all levels, 0,5 if you end early with level III  <br>
Dragon Breath 0,04 per hit  <br>
AA Flare 1,25 for full burst (assumes load up), and 1,5 for wyvernsfire  <br>

## Switch Axe

### Axe Attacks:
Overhead Slash stagger mod 1 > 1,5  <br>
Side Slash and morphing Side slash 23 > 33  <br>
Upswing 32 > 42, stagger mod 1 > 1,3  <br>
Forward Thrust 19 > 25  <br>
Wild Swing elemental mod 1 > 0,85  <br>
Wild Sweep and Adept Wild Sweep 25+30+40 > 25+40+30, stagger mod 1+1+1 > 1,1+1,2+1,15  <br>
All the other axe attacks get a 1,1 stagger mod  <br>


### Sword Attacks:
Elemental Discharge Ticks elemental modifier 1 > 0,7   <br>
Elemental Discharge Explosion 80 > 90, elemental mod 1 > 2   <br>
Elemental Discharge Explosion (Cancel) 50 > 60, elemental mod 1 > 1,5   <br>
Jumping Downslash 30 > 40   <br>
Aerial upslash 35 > 45    <br>
Adept Slashes 25x2 > 30x2    <br>
Valor Double Discharge elemental mod 0,6+0,8 > 1+1,5   <br>
Other sword moves got +10% MVs rounded up   <br>

### Phials:
Power phial multiplier decreased 1,2 > 1,15   <br>
Elemental phial multiplier increased 1,25 > 1,85   <br>
Poison and Paralysis phials now apply double their status (basically 2/3 chance of applying previous status value)   <br>

### Hunter Arts:
Demon riot no longer buffs phials, duration increased 105/120/105s > 120/150/180s, build up reduced 1080/1170/1250 [1496/1604/1700] > 790/910/1080 [989/1103/1267]  <br>
Trance Slash damage increased (Bold numbers refer to Tempest Axe/Demon Riot extensions)  <br>
Trance Slash I 13+15+20+**16+10x3+34**+20+25+30+15x4+**70+20** > 17+20+23+**25+19x3+62**+25+28+33+20x4+**95+35**  <br>
Trance Slash II 15+17+22+**16+10x3+34**+24+29+35+25x4+**80+30** > 20+24+28+**25+19x3+62**+30+33+38+30x4+**110+50**  <br>
Trance Slash III 18+20+25+**16+10x3+34**+28+33+40+30x4+**90+40** > 24+29+34+**25+19x3+62**+36+39+44+40x4+**125+70**  <br>
Elemental modifiers increased 1 > 2  <br>
Normal Trance Slash explosions 80/90/100 > 100/110/120  <br>
Normal Trance Slash total MVs 263/332/384 > 326/403/486  <br>
Full Trance Slash total MVs 353/442/494 > 500/597/705  <br>
Trance slash build up increased 670/750/830 [1004/1100/1196] > 1250/1450/1670 [1431/1626/1841]   <br>
Tempest Axe move speed multiplier increased 2 > 3, Finisher damage increased 15+55 > 15+75, stagger mod changed 1+1,3 > 0+1,6  <br>

### Weapons:
Doubled element on all elemental phial switch axes  <br>
For switch axes with Elemental phial and status I made their swordm mode status similar to having demon Riot III active previously  <br>
Glavenus Axe: 1 Slot > 2 Slot to final level  <br>
Deviljho: Gave Power phial and dragon element (2x dragon phial)  <br>
Savage jho: gave power phial and dragon element (2x dragon phial)  <br>
Amatsu Axe: gave elemental Phial, and element multiplied by 6 instead of 2  <br>
Alatreon Axe: buffed raw 180/180/180/260/280 > 180/190/200/260/300  <br>
Kirin Axe: gave elemental Phial  <br>
Mundus altus: ele multiplied by 1,7 instead of 2  <br>
Chameleos axe: buffed raw 120/130/160/170/250/280 > 140/150/180/190/270/300  <br>
Unkalos Axe: gave power phial  <br>
Akantor Axe: gave power phial and changed raw 250/250/250/320/370 > 250/270/290/320/370  <br>
Crimson Fatalis Axe: gave power Phial and buffed raw 130/240/250 > 250/260/270  <br>
Stonefist Axe: gave power phial  <br>
Nightcloak Axe: status buffed 14/15/16/17/18 > 18/21/24/27/30 or 6/7/8/9/10 without ele phial applied (change this)  <br>
Soulseer Axe: Gave elemental phial, buffed element 24/25/26/27/28 > 62/68/72/76/82, reduced affinity from 20% > 15%   <br>
Snowbaron Axe: Gave elemental phial, buffed G rank element 22/24/26/28/30 > 60/64/68/72/80  <br>
Boltreaver Axe: buffed element 15/16/17/18/19 > 54/56/58/60/62  <br>
Grimclaw Axe: Gave elemental phial and dragon element (4x the dragon phial), Changed sharpness to same path as non G-rank (should be same as Tomb axe)  <br>
Nightcloak Axe: Status buffed 14/15/16/17/18 > 16/17/18/19/20  <br>
Elderfrost Axe: 5% > -20% affinity at all levels  <br>
Silverwind Axe: 20% > 30% affinity at max level  <br>
Bloodbath Axe: Gave power phial  <br>
Gorgonzola Axe: status buffed 3/4/5 > 15/17/20  <br>

### Alchemy:
Morph Side Slash 0,1  <br>
Elemental Discharge 0,5  <br>
Alchemy Reload 0,2  <br>
Trance Slash 3/4/5, Demon riot gives extra 1/1,5/2, Tempest axe gives extra 1,5  <br>
Energy Charge 0,25/0,5/0,75  <br>
Tempest Axe 1 for activation, 0,5 for finisher   <br>

## Charge Blade

### Shield Buff:
Non-striker red shield Buffed 15% > 20%  <br>
Yellow shield Buffed 0% > 25%  <br>

### Sword Attacks:
Draw Slash 18 > 22  <br>
Forward Slice 14 > 17  <br>
Upward Slice 15 > 18  <br>
Shield Thrust 8+12 > 12+16   <br>
Morph to Axe Attack 42 > 48  <br>
Jumping Slash 22 > 26  <br>
Jumping Morph to Axe Attack 42 > 48  <br>
Aerial Charge Slash 35 > 40  <br>

### Axe Attacks:
Upswing 33 > 38  <br>
Downswing 40 > 48  <br>
Jumping Swing 42 > 48  <br>
AED I (No Phials) 18 > 30  <br>
AED I 20 > 30  <br>
AED II (No Phials) 15+35 > 20+45  <br>
SAED (No Phials) 60 > 75  <br>
UAED (No Phials) 20+60 > 20+90  <br>
UAED 25+90 > 25+140  <br>
Aerial SAED (No Phials) 42 > 90  <br>
Aerial UAED (No Phials) 60 > 100  <br>
Aerial UAED 100 > 130  <br>
Valor UAED (No Phials) 20+55 > 20+85  <br>
Valor UAED 25+80 > 25+100  <br>

### Hunter Arts:
Energy Blade 0 Phials MVs buffed 10/20/30 > 50/60/80  <br>
Limit break III duration increased from 150s > 180s  <br>

### Weapons:
Soulseer CB: Gave element phial, reduced affinity from 20% > 15%  <br>
Soulseer CB: Element buffed 24/25/26/27/28 > 48/52/56/60/64  <br>
Grimclaw CB: Gave element phial, dragon element, and same sharpness path as non G-rank  <br>
Grimclaw CB: Element buffed 0/0/0/0/0/0/0/0/0/0/0/0/0/0/0 > 29/32/35/39/41/43/47/48/50/54/56/58/60/63/67  <br>
Boltreaver CB: Gave element phial   <br>
Boltreaver CB: Element buffed 15/16/17/18/19 > 20/30/40/50/60  <br>
ElderFrost CB: 5% > -20% affinity at all levels, element buffed 16/17/18/19/20 > 15/25/35/45/55  <br>
Old fatalis CB: Element buffed 44/47/50 > 65/75/90  <br>
Alatreon CB: Element buffed 41/42/43 > 60/71/82  <br>
Dreadking CB: Element buffed 16/17/18/19/20/21/22/23/24/25/27/28/29/30/31 > 30/33/36/40/42/45/47/49/51/55/57/59/62/65/69  <br>
Valstrax CB: Element buffed 38/40/42/44/46/48 > 45/50/60/65/70/75  <br>
G. Rathian CB: Element buffed 34/35/36/39/42 > 50/58/63/72/80  <br>
Chrono Gear CB: Element buffed 36/38/40/42/45 > 48/55/64/73/80  <br>
Seltas Queen CB: Element buffed 30/32/35/38/40 > 45/54/62/71/80  <br>
H. Zamtrios CB: Element buffed 34/35/36/39/42 > 50/58/63/72/80  <br>
K. Captain's CB: Element buffed 34/35/36/39/42 > 50/58/63/72/80  <br>
Zamtrios cb: Element buffed 25/27/30/32/34/37 > 35/42/49/56/63/70  <br>
Seltas CB: Element buffed 21/23/24/25/27/29/31 > 30/35/40/48/55/61/69  <br>
Sentinel CB: Element buffed 24/26/28/30/32/34 > 34/41/48/55/62/69  <br>
Vaik CB: Element buffed 8/10/12/14/18/22 > 20/29/38/50/60/75  <br>
Nakarkos CB: Element buffed 10/12/13/14/16/19/22 > 15/22/29/36/44/52/60  <br>
Glavenus CB: Element buffed 16/18/20/22/24/26/28/30/33 > 25/29/34/40/44/49/55/63/69  <br>
Gammoth CB: Element buffed 12/14/15/16/18/20/22/22/25 > 25/29/34/40/44/49/55/63/69  <br>
Astalos CB: Element buffed 16/18/20/22/26/28/30/32/35 > 25/29/34/40/44/49/55/63/69  <br>
Rathian CB: Element buffed 15/22/25/28/30/32/36/40 > 20/27/36/45/53/60/69/75  <br>

### Alchemy:
SAED 0,25  <br>
Phials 0,075 per explosion  <br>
Energy Blade 1 (single hit)  <br>
Healing Phial 0,15 per Explosion  <br>
Ripper Shield 1/1,25/1,5  <br>

## Insect Glaive 

### Extracts:
White 90s > 105s  <br>
Red 60s > 75s  <br>
Orange 45s > 60s  <br>
Triple up 60s > 90s  <br>

### Attacks:
All red extract attacks and style specific moves get an element mod. of 1,1  <br>
Parenthesis refer to damage of attack with red extract  <br>
Draw Slam 25 > 27  <br>
Jump slam 21 > 23  <br>
Marker Bash 10 > 15  <br>
Forward thrust 12 (15+9) > 13 (16+10)  <br>
Sweep ‘n Swipe 23+17 (25+13+15) > 25+19 (27+14+16)  <br>
Wide Sweep 23 (13+23) > 25 (14+25)  <br>
Double Lateral 15+21 (13+11+25) > 17+25 (18+16+30)  <br>
Round Slash 23 (25+27) > 25 (27+30)  <br>
Double Lunge 27 (21+35) > 30 (25+38)  <br>
Backflip 17 (13+13) > 19 (14+14)  <br>
Jumping Slash 21 (17+7) > 23 (19+9)  <br>
Aerial Spin Assault 17 > 24  <br>
Adept Slam 30 > 40  <br>
Adept Roundhouse 35 > 52  <br>

### Kinsect Attacks:
Send Kinsect 22 > 45  <br>
Charge Kinsect 60 > 80  <br>
Adept Slam Kinsect 30 > 60  <br>

### Hunter Arts:
Extract Hunter buff duration increased 30/60/90 > 60/90/120, build up increased 700/900/1000 [1040/1280/1400] >  800/980/1150 [998/1170/1334]   <br>
Swarm damage Increased 6 > 12, level 3 duration increased 60s > 90s, and now gives 12 HA charge per attack   <br>
Bug Blow finisher damage increased 80/105/120 > 90/120/150, finisher stagger mod increased 1/1/1 > 1,5/1,75/2 (same for bug blow+swarm), build up increased 580/670/750 [896/1004/1100] > 660/770/860 [866/970/1055] <br>
Bug Majeure Combo damage increased 60+25+35 > 85+50+60, build up increased 1080/1170/1250 [1496/1604/1700] > 1240/1340/1430 [1421/1519/1606]  <br>

### Weapons:
All glaives get their element increased by 1,5x  <br>

### Alchemy:
Double Lateral 0,1 (0,2)  <br>
Kinsect Spin 0,2  <br>
Extract Hunter 1 (single hit)  <br>
Swarm 0,05 per hit  <br>
Bug Blow* 1,5/1,75/2, Swarm gives an extra gauge (single hit)  <br>
Bug Majeure 0,2 per spin combo (0,4 if you count the kinsect spin)  <br>

## Bowguns

### Item and Combo Changes:
Amount probability of 1-3 combos changed 5/85/10% > 5/70/25%  <br>
Normal 2 is now made with Stone and Huskberry  <br>
Normal 3 is now made with Needleberry and Bonehusk, Needleberry capacity decreased 99 > 50  <br>
Pierce 3 now gives 1-3 shots per combo  <br>
Scatternut capacity increased 30 > 50 (Pellet 1)  <br>
Pellet 2 is now made with Popfish and Huskberry, Popfish capacity increased 40 > 50  <br>
Wyvern Claw capacity decreased 50 > 10 (Cluster 2)  <br>
Loprey and Genprey fang capacity reduced 99 > 10 (Poison 2 and Para 2 respectively)
Elemental 1 shots now have a 75% chance of giving 2-4 shots when combining with a probability of 25/50/25%, and they now use bone husk instead of huskberry  <br>
Thunder shots now require thunderbugs to make, and thunderbug capacity has been decreased 99 > 20  <br>
Dragon 1 capacity increased 3 > 6, dragonfell berry capacity increased 10 > 20  <br>
If you have any sets with items whose capacity has been reduced you’ll get that amount added to your inventory in hub, but once you enter a quest they’ll be set to the new maximum amount and you'll lose any excess so make sure to change your sets to account for that.  <br>

### Styles:
Aerial LBG Power Load duration increased 10s > 17,5s  <br>
Aerial HBG Power Load duration increased 15s > 25s  <br>
Reduced Valor HBG dodge I-frames 20 > 12 (at 60fps) so they equal a regular dodge (valor I-frames overwrite evasion +1/2 so using those won't have any effect)  <br>
Valor siege ramp up speed reduced +0,1/shot > +0,0625/shot, max speed reduced 2,5 > 1,35 (caps after the 8th shot), initial speed stays at 0,8  <br>
Valor reload gauge generation modifier reduced 3,2 > 2  <br>

### Shot Types:
Normal 6/12/10x2 > 6/11/11x2, HA gen 6/24/10x2 > 6/22/11x2   <br>
Pierce 9x3/7x4/7x5 > 7x3/7x4/7x5, HA gen 6/6/5 > 6/6/6  <br>
Pellet 5x3/5x4/5x5 > 6x3/6x4/6x5, Pellet 1 now has low rapid fire wait time, Pellet 2 now fires 3 shots with rapid fire, HA gen 5/5/5 > 6/6/6  <br>
Crag 25/30/45 fixed > 35/45/60 fixed, fire damage removed HA gen 25/30/40 > 35/45/55  <br>
Cluster 25x3/25x4/25x5 fixed > 30x3/30x4/30x5 fixed, explosion HA gen 25x3/25x4/20x5 > 30x3/30x4/25x5  <br>
Element 45/58% > 52/67%, HA gen 14/24 > 16/28  <br>
Dragon 40x5/48x5% > 45x5/58x5%, HA gen 6x5/12x5 > 7x5/14x5  <br>
Force 15/18 > 18/21, HA gen 25/35 > 30/40  <br>
Long 15/18 > 20/24, HA gen 20/40 > 35/45  <br>
Heavy 9/12 > 15/19, Stagger mod reduced 3/3,6 > 2,5/3, HA gen 18/24 > 30/38  <br>
Sting 14 > 16, HA gen 25 > 29  <br>
Stone 10 > 12, HA gen 15 > 18  <br>
Cannon 5/7 > 25/30, fixed damage removed, 10/15 KO > 30/40 KO, 5/10 Exh > 20/30 Exh, and cannonball HA gen 15/25 > 55/65  <br>
Tri-Blast 25x3 Fixed > 40x3 Fixed, fire damage removed, 10x3 Exh > 15x3 Exh, HA gen 25x3 > 35x3  <br>
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

## Palico/Prowler

### MV changes:
Jumping Spinning Slash 1st hit 5 > 8, repeating hits 5 > 6, gauge build up for 1st hit 4 > 6   <br>
Furr-ious Flurry 1st Hit  7 > 12  <br>
Furr-ious Flurry Mid 8 > 10  <br>
Furr-ious Flurry Finisher hits 1-3 6x3 > 12x3  <br>
Beast Furris Wheel 4 > 5  <br>
RoM Spike 10 > 18, and 20KO > 25KO  <br>
RoM Cannonball 8 > 12, and 0 KO > 20 KO  <br>
Stunt Cannon 35 > 65  <br>
Chestnut cannon 40 > 50  <br>
Mega Boomerang blunt 22 > 25  <br>
Iron Transpurrter throw 15 > 25, finisher 20 > 35  <br>
Claw Dance MV buffed 12x5+6x8+40=148 > 16x5+8x8+50=194  <br>
Plunderang 25 > 70   <br>

### Support cost changes:
Barrel Bombay 0 > 1  <br>
Cheer Horn gauge cost 3 > 2  <br>
Furrious gauge cost 4 > 3  <br>
Pilfer gauge cost 4 > 3  <br>
Plunderrang gauge cost 4 > 2  <br>
Poison Purr-ison gauge cost 5 > 4  <br>
True Health Horn gauge cost 3 > 2  <br>

### Skill size changes:
All elemental Boosts 2 > 1  <br>
Anger Prone 2 > 1  <br>
Attack up L 3 > 2  <br>
Attack Up S 2 > 1  <br>
Baddest Cat Ever 3 > 2  <br>
Bombay Boost 3 > 2  <br>
Crit Boost 4 > 3  <br>
Elemental Attack Up 3 > 2  <br>
Extend Beast 2 > 1  <br>
Extend Fury 2 > 1  <br>
Extend SP State 3 > 2  <br>
Extreme DEF-centric 4 > 2  <br>
Fanalis 2 > 1  <br>
Felyne Protection 2 > 1  <br>
Guard Boost 2 > 1  <br>
Guts 3 > 2  <br>
Handicraft 4 > 2  <br>
Horn Virtuoso 3 > 2  <br>
KO King 2 > 1  <br>
Land Master 3 > 2  <br>
Last Stand 3 > 2  <br>
Negate Confusion 2 > 1  <br>
Negate Wind 2 > 1  <br>
Nine Lives (Attack) 4 > 2  <br>
Nine Lives (Defense) 3 > 1  <br>
Omniresistance 3 > 2  <br>
Pilfer Boost 3 > 2  <br>
Pro Experience 4 > 2  <br>
Pro Trapper 3 > 2  <br>
Recovery Speed Up 2 > 1  <br>
Status Attack Up 4 > 2  <br>
Support Priority 3 > 2  <br>
Triforce 4 > 3  <br>
Universal 3 > 2  <br>
Weakness Exploit 2 > 3  <br>
Wind Waker 3 > 2  <br>

### Modifier Changes:
TLDR at bottom  <br>
Palico damage per level changed 15-110 > 2-100 (affects both melee and ranged)  <br>
Palico defense per level changed 1-215 > 2-100  <br>
Assist, Heal, Gather, Protect, Fighting, and beast bomb modifiers decreased to 0,5  <br>
Bomb bomb modifier Increased 1,2 > 1,5  <br>
Charisma melee modifier increased  1 > 1,25  <br>
Fight melee modifier increased  1,05 > 1,25  <br>
Guard melee modifier increased  1,05 > 1,25  <br>
Assist melee modifier increased  0,9 > 1  <br>
Heal melee modifier increased  0,9 > 1  <br>
Bomb melee modifier increased  0,95 > 1,15  <br>
Gather melee modifier increased  0,9 > 1  <br>
Beast melee modifier increased  1,1 > 1,5  <br>
Charisma ranged modifier increased 0,95 > 1,25  <br>
Guard ranged modifier increased 0,9 >1  <br>
Assist ranged modifier decreased 1,05 > 1  <br>
Heal ranged modifier increased 0,9 > 1  <br>
Bomb ranged modifier increased 1 > 1,15  <br>
Gather ranged modifier increased 1,1 > 1,5  <br>
Beast ranged modifier increased  0,85 > 1  <br>
Charisma defense modifier increased 0,95 > 2  <br>
Fight defense modifier increased 0,95 > 2  <br>
Guard defense modifier increased 1,1 > 3  <br>
Assist defense modifier increased 0,7 > 2  <br>
Heal dense modifier increased 1 > 2  <br>
Bomb defense modifier increased 0,85 > 1,5  <br>
Gather defense modifier increased 0,6 > 1  <br>
Beast defense modifier increased  1,1 > 2  <br>
Gauge modifiers order: Melee/Boomerang/Bomb/Block/gather/Passive in combat/Passive not in combat  <br>
Charisma Gauge modifiers changed 0,95/0,9/1/0,8/0,625/0,4/0,6 > 1,3/1,3/1,5/1/1/0,6/0,6  <br>
Fight Gauge modifiers changed 1,05/1/1/0,6/0,25/0,2/0,6 > 1,2/0,5/0,5/0,5/0,5/0,2/0,2  <br>
Protect Gauge modifiers changed 0,85/0,75/1,3/1,5/0,25/0,2/0,4 > 1/0,5/0,5/2/0,5/0,4/0,2  <br>
Assist Gauge modifiers changed 0,8/1,1/0,5/0,6/0,8/0,4/0,4 > 0,75/1/0,5/1/1,5/1/1,2  <br>
Heal Gauge modifiers changed 0,7/0,75/0,5/1/1/0,8/1,1 > 0,75/1/0,5/1/1,5/1/1,2  <br>
Bomb Gauge modifiers changed 0,9/1/1,6/0,25/0,25/0,2/0,4 > 0,5/0,5/2/0,25/0,5/0,2/0,2  <br>
Gather Gauge modifiers changed 0,7/1,2/0,5/0,4/1,25/0,8/0,2 > 0,5/1,2/0,5/0,25/2/0,2/0,6  <br>
Beast Gauge modifiers changed 1,1/0,75/0,75/0,25/0,25/0,2/0,2 > 1,2/0,5/0,5/0.25/0,5/0,2/0,2  <br>
TLDR:  <br>
![imagen](https://user-images.githubusercontent.com/121890308/232096553-66ba8366-9a6f-4ccb-9245-92aa6244682d.png)

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
Kurrimu2 devs. Used it to extract and replace game files. [Link](https://github.com/FanTranslatorsInternational/Kuriimu2)  <br>
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
