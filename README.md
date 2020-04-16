# Enhanced TA:K
Adds new features and bugfixes to improve TA:K experience.
It's totally compatible with other 4.1bb versions (with the small exception of Monarch fixes, which will bug opponent monarch animation if his version is different).

## How to install

- Simply move the files you downloaded to your TA:K root folder (i.e. C:\Cavedog\Kingdoms).
- These are the files needed:
  - Kingdoms.exe
  - EnhancedTAK.hpi
  - MonarchsFix.hpi

Use [DXWnd](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd) to improve even more your experience.  

The reason Monarchs Fix is separated is that, when playing on different versions, your opponent monarch animation won't work. So you may want to disable it when playing multiplayer by moving it out of the folder (it's just a visual thing tho).  

Also, GameRanger won't accept any file that is not called Kingdoms so I renamed it to Kingdoms.exe. You can overwrite or backup your own file. The real original executable is the .icd file anyway (you can rename it to .exe and run it).

## Features

* Doesn't use a wrapper for .icd file, allowing DXWnd to patch it correctly.  
  [What is DXWnd and how to use it?](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd)
* Command line params allowed.  
  [More info on command line params](http://kingdoms.catsboard.com/t1257-tak-target-command-line-parameters)
* No-CD patch.

* Increases max unit limit from 500 to 5000.

* PathFinding improved (raised from 12,000 to 100,000 path cycles).  
  [PathFinding Study (Not available yet)]()

* Game doesn't pause anymore when minimizing during SinglePlayer games.

* Uses Extreme AI as default AI.

## Bug Fixes

#### Engine

- The game now saves your unit limit value used in your previous multiplayer match properly.

#### Monarchs' Fix

- All monarch's buggy animations after making ghosts, building, walking, turning and building, some would override others and result in a buggy animation (Lokken, for example), you can test that by starting building something then clicking many times into it.

- In special, Kirenna delays to attack, sometimes you would click and she wouldn't attack.

#### Aramon
- Fixed Mage Archer paralyze weapon.
- Fixed Knight not having frozen statue.

#### Taros
- Fixed Fire Demon's attack delay against flying units.
- Fixed Fire Mage first attack not hitting goblins.

#### Veruna
- Fixed Centaur weapon not being guided.

#### Zhon
- Fixed Thirsha 2nd weapon not being guided.
- Fixed Wisp not attacking consistently.

#### Creon
- Fixed Gate not being targetted by units automatically.