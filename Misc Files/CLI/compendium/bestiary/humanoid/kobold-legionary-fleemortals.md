---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/kobold
- ttrpg-cli/monster/type/humanoid/soldier
statblock: inline
aliases: ["Kobold Legionary"]
---
# [Kobold Legionary](Misc Files\CLI\compendium\bestiary\humanoid/kobold-legionary-fleemortals.md)
*Source: Flee, Mortals! p. 174*  

```statblock
"name": "Kobold Legionary (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold, Soldier"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[chain shirt](Misc%20Files/CLI/compendium/items/chain-shirt-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "22"
"hit_dice": "4d6 + 8"
"stats":
- !!int "15"
- !!int "8"
- !!int "14"
- !!int "12"
- !!int "10"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "4"
  "Perception": !!int "2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Draconic"
"cr": "1/2"
"traits":
- "desc": "The legionary gains a +1 bonus to AC while within 5 feet of at least one\
    \ ally who also has this trait, is wielding a shield, and isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ or [prone](Misc%20Files/CLI/rules/conditions.md#Prone). To benefit from this\
    \ trait, the legionary must be wielding a shield."
  "name": "Shield? Shield!"
"actions":
- "desc": "The legionary makes two Gladius attacks. They can replace one attack with\
    \ a Shield Bash attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Gladius"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage. If the target is a Medium or smaller creature, they\
    \ must succeed on a DC 12 Strength saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Shield Bash"
"reactions":
- "desc": "When an ally within 10 feet of the legionary is targeted by an attack,\
    \ the legionary can move to the nearest unoccupied space within 5 feet of that\
    \ creature. If that creature also has the Shield? Shield! trait, they gain the\
    \ benefit of that trait against the triggering attack. To use this reaction, the\
    \ legionary must be able to see the ally and the attacker."
  "name": "Reinforce"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Kobold%20Legionary.png"
```
^statblock