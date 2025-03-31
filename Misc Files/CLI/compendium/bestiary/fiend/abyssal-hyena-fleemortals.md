---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/minion
statblock: inline
aliases: ["Abyssal Hyena"]
---
# [Abyssal Hyena](Misc Files\CLI\compendium\bestiary\fiend/abyssal-hyena-fleemortals.md)
*Source: Flee, Mortals! p. 121*  

```statblock
"name": "Abyssal Hyena (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "Minion"
"alignment": "typically  Chaotic Evil"
"ac": !!int "11"
"hp": !!int "8"
"stats":
- !!int "14"
- !!int "13"
- !!int "12"
- !!int "5"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "understands Abyssal but can't speak"
"cr": "1"
"traits":
- "desc": "When the hyena is reduced to 0 hit points, they can deal 1 piercing damage\
    \ to a creature within 5 feet of them (no action required), provided they weren't\
    \ [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated) before dropping\
    \ to 0 hit points."
  "name": "Death Snap"
- "desc": "If the hyena takes damage from an attack or as the result of a failed saving\
    \ throw, their hit points are reduced to 0. If the hyena takes damage from another\
    \ effect, they die if the damage equals or exceeds their hit point maximum; otherwise\
    \ they take no damage."
  "name": "Minion"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 1\
    \ piercing damage. If the target is a creature and two or more hyenas joined the\
    \ attack, the target must succeed on a Strength saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone).\
    \ The DC for this saving throw equals 10 plus the number of hyenas who joined\
    \ the attack."
  "name": "Bite (Group Attack)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Abyssal%20Hyena.png"
```
^statblock