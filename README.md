# Enhanced TA:K
<<<<<<< HEAD
Adds new features and bugfixes to improve TA:K experience.
It's totally compatible with other 4.1bb versions!
=======
Adds new features and bugfixes to improve TA:K Crusades Balance experience.
It's totally compatible with other 4.1bb versions.
>>>>>>> 65114ad1cc6949d9df84b8800302ab68b43d73c8

## How to install

- Simply move the files you downloaded to your TA:K root folder (i.e. C:\Cavedog\Kingdoms).
- These are the files needed:
  - Kingdoms.exe
  - EnhancedTAK.dll
  - EnhancedTAK.hpi

Use [DXWnd](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd) to improve even more your experience.  

<<<<<<< HEAD
GameRanger won't accept any file that is not called Kingdoms so I renamed it to Kingdoms.exe. You can overwrite or backup your own file. The real original executable is the .icd file anyway (you can rename it to .exe and run it).
=======
Also, GameRanger won't accept any file that is not called Kingdoms so I renamed it to Kingdoms.exe. You can overwrite or backup your own file. The real original executable is the .icd file anyway (you can rename it to .exe and run it).
>>>>>>> 65114ad1cc6949d9df84b8800302ab68b43d73c8

## Features
* New badass icon.

* Command line params allowed.  
  [More info on command line params](http://kingdoms.catsboard.com/t1257-tak-target-command-line-parameters)
* No-CD patch.

* Increases max unit limit from 500 to 5000.

* PathFinding improved (raised from 12,000 to 100,000 path cycles).  
  [PathFinding Study (Not available yet)]()

* Game doesn't pause anymore when minimizing during SinglePlayer games.

* Uses Extreme AI as default AI.

## Game Changing Tweaks

- Rolling Towers aren't capturable.
- Knights aren't freezeable.
- Thirsha's 2nd weapon and Centaur's weapon are now guided.
- Mage Archer's 3rd weapon and Lighthouse's weapon now paralyze correctly.
- Wisps can now attack consistently.
- Fire Demon's attack delay against moving targets is gone.
- Acolyte and Weather Witch 1st and 2nd weapon have been swapped.

## Detailed Log

#### Engine

- The game now saves your unit limit value used in your previous multiplayer match properly.
- Some screen changes will be faster now.

#### Aramon
<<<<<<< HEAD
- Fixed Elsin wave bug where he couldn't wave for the rest of the match.
- Fixed Mage Archer paralyze weapon, adjusted for 5s stuns.
- Fixed Knight not having frozen statue.
=======
- Fixed Elsin wave which would stop working for the rest of the match.
- Fixed Mage Archer paralyze weapon, adjusted for 2s stuns.
- Fixed Knight being freezable.
- Swapped Acolyte 1st and 2nd weapon.
>>>>>>> 65114ad1cc6949d9df84b8800302ab68b43d73c8

#### Taros
- Fixed Fire Demon's attack delay against flying/moving units.
- Fixed Fire Mage first attack not hitting goblins.
- Swapped Weather Witch 1st and 2nd weapon.

#### Veruna
<<<<<<< HEAD
- Fixed Kirenna bug where she wouldn't attack unless you clicked twice.
- Fixed Centaur weapon not being guided.
- Fixed Lighthouse paralyze weapon, adjusted for 1s stuns.
- In special, Kirenna delays to attack, sometimes you would click and she wouldn't attack.
  
=======
- Fixed Kirenna attack delays where you needed to double click in order to her start attacking.
- Catapult now shoots faster (and moving units) but is more imprecise (like aramon catapult)
- Fixed Centaur weapon not being guided.
- Fixed Lighthouse paralyze weapon, adjusted for 0.5s stuns.

>>>>>>> 65114ad1cc6949d9df84b8800302ab68b43d73c8
#### Zhon
- Fixed Thirsha 2nd weapon not being guided.
- Adjusted Thirsha 2nd weapon velocity to match previous velocity (before being guided).
- Fixed Wisp not attacking consistently.
- Giant Orm doesn't do enourmous damage against undead units anymore.

#### Creon
- Fixed Gate not being targetted by units automatically.
- Fixed Creon Chief paralyze weapon, adjusted for 10s stuns.

#### Animals
- Fixed Deer water multiplier typo in fbi.
- Fixed Buck water multiplier typo in fbi.
- Fixed Saber Tooth Tiger road multiplier typo in fbi.

<details>
<summary>Even more detailed changes</summary>

<pre>v1.0 - Initial Release

+ Addition
- Removal
~ Modified
* Small description for complex changes.

* Badass Icon
* Command line params allowed
* No-CD
* 5000 Max Units
* Enhanced Pathfinding
* No pause when minimize or unfocus
* Extreme AI as default
* Game now saves previous unit limit used in multiplayer matches
* Some screen changes will be faster

EnhancedTAK.hpi/
scripts/

araking.cob
  * Fixed Elsin wave which would stop working for the rest of the match.
arapries.cob
  * Swapped 1st and 2nd weapon.

vermage.cob
  * Fixed Kirenna attack delays where you needed to double click in order to her start attacking.

tarmage.cob
  * Changed the piece attack is fired from.
tarwitch.cob
  * Swapped 1st and 2nd weapon.

unitscb/

araat.fbi
  + immunetoparalyzer = 1;
arabow.fbi
  weapon3
    ~ default = <s>1</s> ⇒ 57; // ~2s paralyze
aracastl.fbi
  + immunetoparalyzer = 1;
aradrag.fbi
  + immunetoparalyzer = 1;
aragod.fbi
  + immunetoparalyzer = 1;
aragren.fbi
  weapon3
    - dragon = 0;
    - factory = 0;
    - fort = 0;
    - god = 0;
    - monarch = 0;
    - naval = 0;
araking.fbi
  + immunetoparalyzer = 1;
arakeep.fbi
  - canattack = 1;
  + immunetoparalyzer = 1;
aralode.fbi
  + immunetoparalyzer = 1;
aramana.fbi
  + immunetoparalyzer = 1;
arangate.fbi
  + immunetoparalyzer = 1;
arapal.fbi
  + cantbefrozen = 1;
arapries.fbi
  * Swapped 1st and 2nd weapon
arassh.fbi
  + immunetoparalyzer = 1;
arasiege.fbi
  + cantbecaptured = 1;
  + immunetoparalyzer = 1;
aratrans.fbi
  + immunetoparalyzer = 1;
aratre.fbi
  + immunetoparalyzer = 1;
arawall.fbi
  + immunetoparalyzer = 1;
arawar.fbi
  + immunetoparalyzer = 1;

npcbotl.fbi
  + immunetoparalyzer = 1;
npcflag.fbi
  + immunetoparalyzer = 1;
npcrixx.fbi
  + immunetoparalyzer = 1;
npctemp.fbi
  + immunetoparalyzer = 1;
npctemp2.fbi
  + immunetoparalyzer = 1;
npcthesh.fbi
  + immunetoparalyzer = 1;

tarcage.fbi
  + immunetoparalyzer = 1;
tarcastl.fbi
  + immunetoparalyzer = 1;
tardrag.fbi
  + immunetoparalyzer = 1;
tardung.fbi
  + immunetoparalyzer = 1;
targod.fbi
  + immunetoparalyzer = 1;
tarhell.fbi
  + immunetoparalyzer = 1;
tarlode.fbi
  + immunetoparalyzer = 1;
tarmana.fbi
  + immunetoparalyzer = 1;
tarnecro.fbi
  + immunetoparalyzer = 1;
tarngate.fbi
  + immunetoparalyzer = 1;
tarsh.fbi
  + immunetoparalyzer = 1;
tarwall.fbi
  + immunetoparalyzer = 1;
tarwitch.fbi
  * Swapped 1st and 2nd weapon

verasy.fbi
  + immunetoparalyzer = 1;
verat.fbi
  + immunetoparalyzer = 1;
vercastl.fbi
  + immunetoparalyzer = 1;
vercen.fbi
  weapon1
    + turnrate = 180;
verdrag.fbi
  + immunetoparalyzer = 1;
verflag.fbi
  + immunetoparalyzer = 1;
verfltwr.fbi
  + immunetoparalyzer = 1;
vergod.fbi
  + immunetoparalyzer = 1;
verharp.fbi
  + immunetoparalyzer = 1;
verkeep.fbi
  + immunetoparalyzer = 1;
verlight.fbi
  + immunetoparalyzer = 1;
  weapon1
    ~ default = <s>1</s> ⇒ 15; // ~0.5s paralyze
verlode.fbi
  + immunetoparalyzer = 1;
vermage.fbi
  + immunetoparalyzer = 1;
verman.fbi
  + immunetoparalyzer = 1;
vermana.fbi
  + immunetoparalyzer = 1;
vermort.fbi
  + immunetoparalyzer = 1;
verngate.fbi
  + immunetoparalyzer = 1;
verpill.fbi
  + immunetoparalyzer = 1;
verpult.fbi
  weapon1
    + aimtolerance = 1024;
verscout.fbi
  + immunetoparalyzer = 1;
vertower.fbi
  + immunetoparalyzer = 1;
vertrans.fbi
  + immunetoparalyzer = 1;
vertre.fbi
  + immunetoparalyzer = 1;
verwall.fbi
  + immunetoparalyzer = 1;

zondrag.fbi
  + immunetoparalyzer = 1;
zonfire.fbi
  + immunetoparalyzer = 1;
zonflies.fbi
  weapon1
    + aimtolerance = 1024;
zonamoe.fbi
  weapon1
    + undead = 0.04;
zonglyph.fbi
  + immunetoparalyzer = 1;
zongod.fbi
  + immunetoparalyzer = 1;
zonhunt.fbi
  + immunetoparalyzer = 1;
  weapon2
    + turnrate = 180;
    ~ weaponvelocity = <s>500</s> ⇒ 480;
zonhurt.fbi
  + immunetoparalyzer = 1;
  weapon2
    + turnrate = 180;
    ~ weaponvelocity = <s>500</s> ⇒ 480;
zonlode.fbi
  + immunetoparalyzer = 1;
zonmana.fbi
  + immunetoparalyzer = 1;

creacad.fbi
  + immunetoparalyzer = 1;
creaeri.fbi
  + immunetoparalyzer = 1;
crebomb.fbi
  + immunetoparalyzer = 1;
crechie.fbi
  weapon3
    ~ default = <s>1</s> ⇒ 286; // ~10s
cregate.fbi
  + immunetoparalyzer = 1;
  + shootme = 1; 
cregatl.fbi
  + immunetoparalyzer = 1;
cregod.fbi
  + immunetoparalyzer = 1;
creiron.fbi
  + immunetoparalyzer = 1;
crelode.fbi
  + immunetoparalyzer = 1;
cremana.fbi
  + immunetoparalyzer = 1;
crenavy.fbi
  + immunetoparalyzer = 1;
crepris.fbi
  + immunetoparalyzer = 1;
cresage.fbi
  + immunetoparalyzer = 1;
cresmit.fbi
  + immunetoparalyzer = 1;
crester.fbi
  + immunetoparalyzer = 1;
cresubm.fbi
  + immunetoparalyzer = 1;
crewall.fbi
  + immunetoparalyzer = 1;

lifdeer.fbi
  ~ <s>watermultipliser</s> ⇒ watermultiplier
lifdeer2.fbi
  ~ <s>watermultipliser</s> ⇒ watermultiplier
lifsaber.fbi
  ~ <s>admultiplier</s> ⇒ roadmultiplier
</pre>
</details>
<br/>

## Credits

Paladin for many findings and ideas. Most of his contributions can be found here: https://kingdoms.catsboard.com/t1445-patch-bugs-balance-improvements  
WhiteHammer for ExtremeAI  
WL- Albino for tests and time.  