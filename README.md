# Enhanced TA:K
Adds new features and bugfixes to improve TA:K experience.
It's totally compatible with other 4.1bb versions!

## How to install

- Simply move the files you downloaded to your TA:K root folder (i.e. C:\Cavedog\Kingdoms).
- These are the files needed:
  - Kingdoms.exe
  - EnhancedTAK.dll
  - EnhancedTAK.hpi

Use [DXWnd](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd) to improve even more your experience.  

GameRanger won't accept any file that is not called Kingdoms so I renamed it to Kingdoms.exe. You can overwrite or backup your own file. The real original executable is the .icd file anyway (you can rename it to .exe and run it).

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

## Bug Fixes

#### Engine

- The game now saves your unit limit value used in your previous multiplayer match properly.
- Some screen changes will be faster now.

#### Aramon
- Fixed Elsin wave bug where he couldn't wave for the rest of the match.
- Fixed Mage Archer paralyze weapon, adjusted for 5s stuns.
- Fixed Knight not having frozen statue.

#### Taros
- Fixed Fire Demon's attack delay against flying/moving units.
- Fixed Fire Mage first attack not hitting goblins.

#### Veruna
- Fixed Kirenna bug where she wouldn't attack unless you clicked twice.
- Fixed Centaur weapon not being guided.
- Fixed Lighthouse paralyze weapon, adjusted for 1s stuns.
- In special, Kirenna delays to attack, sometimes you would click and she wouldn't attack.
  
#### Zhon
- Fixed Thirsha 2nd weapon not being guided.
- Fixed Wisp not attacking consistently.

#### Creon
- Fixed Gate not being targetted by units automatically.
- Fixed Creon Chief paralyze weapon, adjusted for 10s stuns.