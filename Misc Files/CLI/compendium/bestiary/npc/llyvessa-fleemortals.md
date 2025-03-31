---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/artillery
- ttrpg-cli/monster/type/humanoid/elf
statblock: inline
aliases: ["Llyvessa"]
---
# [Llyvessa](Misc Files\CLI\compendium\bestiary\npc/llyvessa-fleemortals.md)
*Source: Flee, Mortals! p. 376*  

```statblock
"name": "Llyvessa (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf, Artillery"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "[studded leather armor](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"stats":
- !!int "10"
- !!int "22"
- !!int "13"
- !!int "15"
- !!int "17"
- !!int "12"
"speed": "35 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "6"
"skillsaves":
  "Nature": !!int "5"
  "Stealth": !!int "9"
  "Perception": !!int "6"
  "Acrobatics": !!int "9"
  "Survival": !!int "6"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Elvish, telepathy 120 ft."
"cr": "5"
"traits":
- "desc": "Attacking at long range with a ranged weapon doesn't impose disadvantage\
    \ on Llyvessa's attack rolls."
  "name": "Deadly Sharpshooter"
- "desc": "When a creature targets Llyvessa with an attack, power, or spell, the creature\
    \ must succeed on a DC 14 Wisdom saving throw or be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by her until the end of her next turn (no action required)."
  "name": "Elf Glamour (1/Day)"
- "desc": "Llyvessa can communicate telepathically with any Amethyst Knife boss regardless\
    \ of distance, provided they are on the same plane of existence."
  "name": "Mind Link"
"actions":
- "desc": "Llyvessa makes two Scimitar or Longbow attacks. Alternatively, she makes\
    \ one Longbow attack and uses Psychic Shot, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d6\
    \ + 6) slashing damage."
  "name": "Scimitar"
- "desc": "Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. Hit:\
    \ 15 (2d8 + 6) piercing damage."
  "name": "Longbow"
- "desc": "Llyvessa makes a Longbow attack that ignores cover, and which can pass\
    \ through mundane solid objects up to 5 feet thick that aren't being worn or carried."
  "name": "Psychic Shot (Recharge 5-6)"
"bonus_actions":
- "desc": "Llyvessa or one willing creature within 5 feet of her teleports to an unoccupied\
    \ space Llyvessa can see within 30 feet of her."
  "name": "Jaunt (1/Day; 3rd-Order Power)"
"reactions":
- "desc": "When a creature Llyvessa can see within 60 feet of her makes a ranged weapon\
    \ attack, she gives the creature advantage or disadvantage on the attack roll\
    \ (her choice)."
  "name": "*Control Projectiles (3/Day; 2nd-Order Power)"
- "desc": "When Llyvessa is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [paralyzed](Misc%20Files/CLI/rules/conditions.md#Paralyzed), or [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned),\
    \ she chooses a willing Amethyst Knife boss within 60 feet of her who doesn't\
    \ already have the condition or is immune to it. The chosen creature then gains\
    \ the condition for the duration, and Llyvessa loses the condition. She can use\
    \ this reaction even while [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)."
  "name": "Shared Condition"
"source":
- "FleeMortals"
```
^statblock