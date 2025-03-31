---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Skitterling Companion"]
---
# [Skitterling Companion](Misc Files\CLI\compendium\bestiary\beast/skitterling-companion-fleemortals.md)
*Source: Flee, Mortals! p. 132*  

```statblock
"name": "Skitterling Companion (FleeMortals)"
"size": "Tiny"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "15 plus PB (natural armor)"
"stats":
- !!int "6"
- !!int "16"
- !!int "12"
- !!int "5"
- !!int "14"
- !!int "10"
"speed": "30 ft., fly 50 ft."
"saves":
  "Dexterity": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Sleight of Hand": !!int "0"
  "Perception": !!int "0"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB slashing damage."
  "name": "Signature Attack (Claws)"
- "desc": "The skitterling makes a signature attack. On a hit, the target also has\
    \ disadvantage on the next attack roll they make before the start of the skitterling's\
    \ next turn."
  "name": "1st Level: Destabilizing Attack (2 Ferocity)"
- "desc": "The skitterling moves up to their speed without provoking opportunity attacks\
    \ and makes a signature attack. On a hit, if the target is a Medium or smaller\
    \ creature, they are also knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ and [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) by the skitterling\
    \ (escape DC 10 plus PB)."
  "name": "3rd Level: Ankle Biter (5 Ferocity)"
- "desc": "The skitterling chaotically bounces around, smearing toxin on each enemy\
    \ within 5 feet of them.\n\nEach target must succeed on a DC 10 plus PB Constitution\
    \ saving throw or take 1d6 plus PB poison damage and be [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)\
    \ until the end of the skitterling's next turn. A creature within 5 feet of a\
    \ target [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded) in this way can\
    \ use their action to wipe the toxin off them, ending the condition for that target."
  "name": "5th Level: In All Your Faces! (8 Ferocity)"
"bonus_actions":
- "desc": "The skitterling flutters and screeches distractingly, allowing their caregiver\
    \ an opportunity to reposition. The caregiver can use a reaction to move up to\
    \ their speed without provoking opportunity attacks."
  "name": "Crafty Distraction (Recharges after a Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Skitterling.webp"
```
^statblock