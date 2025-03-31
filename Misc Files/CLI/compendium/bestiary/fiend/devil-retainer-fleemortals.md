---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
- ttrpg-cli/monster/type/fiend/retainer
statblock: inline
aliases: ["Devil Retainer"]
---
# [Devil Retainer](Misc Files\CLI\compendium\bestiary\fiend/devil-retainer-fleemortals.md)
*Source: Flee, Mortals! p. 72*  

```statblock
"name": "Devil Retainer (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "14"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Deception": !!int "0"
  "Persuasion": !!int "0"
"damage_resistances": "fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "Common, Infernal"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 plus PB to hit, reach 5 ft. or range\
    \ 20/60 ft. Hit: 2d4 + PB piercing damage. Beginning at 7th level, the retainer\
    \ can make this attack twice, instead of once, when they take the Attack action\
    \ on their turn."
  "name": "Signature Attack (Daggers)"
- "desc": "As an action, the retainer makes a signature attack. On a hit, the target\
    \ must use their reaction, if available, to make a weapon attack against a creature\
    \ of the retainer's choice."
  "name": "3rd Level: Misleading Strike (3/Day)"
- "desc": "As a bonus action, the retainer grants an infernal blessing to an ally\
    \ they can see within 60 feet of them. The next time that ally makes an attack\
    \ roll before the start of the retainer's next turn, the ally adds a +PB bonus\
    \ to the roll. If the attack hits, it deals an extra PB damage."
  "name": "5th Level: Adjuration (3/Day)"
- "desc": "As a bonus action, the retainer imbues their daggers with hellfire. For\
    \ 1 minute, their signature attack deals an extra PB fire damage and ignores damage\
    \ resistances."
  "name": "7th Level: Hellbitten Knives (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Devil%20Retainer.png"
```
^statblock