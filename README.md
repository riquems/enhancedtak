# Enhanced TA:K
Adds new features and bugfixes to improve TA:K experience.

## How to install

### Manual
- Move the files you downloaded (EnhancedTAK.exe, EnhancedTAK.hpi and MonarchsFix.hpi) to your TA:K folder.
- Launch EnhancedTAK.exe (you may want to create a shortcut for it too).

Use [DXWnd](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd) to improve even more your experience.  
The reason Monarchs Fix is separated is that, when playing on different versions, your opponent monarch animation won't work. So you may want to disable it when playing multiplayer (it's just a visual thing tho).

### Auto install
- Not available yet.

## Features

* Doesn't use a wrapper for .icd file, allowing DXWnd to patch it correctly.  
  [What is DXWnd and how to use it?](http://kingdoms.catsboard.com/t1522-how-to-use-dxwnd)
* Command line params allowed  
  [More info on command line params](http://kingdoms.catsboard.com/t1257-tak-target-command-line-parameters)
* No-CD patch.
  
* PathFinding improved (raised from 12,000 to 100,000 path cycles).
  [PathFinding Study (Not available yet)]()

* Game doesn't pause anymore when minimizing during SinglePlayer games.

* Uses Extreme AI as default AI.

## Bug Fixes

### Monarchs' Fix

- All monarch's buggy animations after making ghosts, building, walking, turning and building, some would override others and result in a buggy animation (Lokken, for example), you can test that by starting building something then clicking many times into it.

- In special, Kirenna delays to attack, sometimes you would click and she wouldn't attack.

Aramon
- Fixed Mage Archer paralyze weapon.
- Fixed Knight not having frozen statue.

Taros
- Fixed Fire Demon's attack delay against flying units.
- Fixed Fire Mage first attack not hitting goblins.

Veruna
- Fixed Centaur weapon not being guided.

Zhon
- Fixed Thirsha 2nd weapon not being guided.
- Fixed Wisp attack delay.

Creon
- Fixed Gate not being targetted by units automatically.