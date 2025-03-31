---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/medusa
- ttrpg-cli/monster/type/monstrosity/retainer
statblock: inline
aliases: ["Medusa Headstrong"]
---
# [Medusa Headstrong](Misc Files\CLI\compendium\bestiary\monstrosity/medusa-headstrong-fleemortals.md)
*Source: Flee, Mortals! p. 191*  

```statblock
"name": "Medusa Headstrong (FleeMortals)"
"size": "Medium"
"type": "monstrosity"
"subtype": "medusa, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "10"
- !!int "16"
- !!int "12"
- !!int "10"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Perception": !!int "0"
  "Survival": !!int "0"
"damage_immunities": "poison"
"condition_immunities": "poison"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "Common, Elvish"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d10 plus PB piercing damage. Beginning at 7th level, the headstrong can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Snake Bite)"
- "desc": "As a bonus action, the headstrong spits venom at the eyes of a creature\
    \ within 5 feet of them. The target must succeed on a DC 10 plus PB Dexterity\
    \ saving throw or be [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded) until\
    \ the end of their next turn."
  "name": "3rd Level: Snake Spit (3/Day)"
- "desc": "When the headstrong hits a creature with a signature attack, the headstrong\
    \ injects the target with venom. The target must make a DC 10 plus PB Constitution\
    \ saving throw. On a failed save, the target takes PBd6 poison damage and is\
    \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned) until the start of\
    \ the headstrong's next turn. On a successful save, the target takes half as much\
    \ damage and isn't [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)."
  "name": "5th Level: Venomous Bite (3/Day)"
- "desc": "As an action, the headstrong fires energy beams from their eyes at a creature\
    \ they can see within 30 feet of them. The target must succeed on a DC 10 plus\
    \ PB Constitution saving throw or begin to turn to stone and be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\n\
    \nA target [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) in this\
    \ way must repeat the saving throw at the end of their next turn. On a successful\
    \ save, the effect ends. On a failed save, the creature is [petrified](Misc%20Files/CLI/rules/conditions.md#Petrified)\
    \ for 1 hour or until they are restored by a cure ailment power of 4th order or\
    \ higher, a [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell, or a similar supernatural effect."
  "name": "7th Level: Stone Gaze (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Medusa%20Headstrong.png"
```
^statblock