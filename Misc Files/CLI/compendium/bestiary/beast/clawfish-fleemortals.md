---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast/brute
statblock: inline
aliases: ["Clawfish"]
---
# [Clawfish](Misc Files\CLI\compendium\bestiary\beast/clawfish-fleemortals.md)
*Source: Flee, Mortals! p. 32*  

```statblock
"name": "Clawfish (FleeMortals)"
"size": "Small"
"type": "beast"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "9"
"hit_dice": "2d6 + 2"
"stats":
- !!int "15"
- !!int "13"
- !!int "12"
- !!int "4"
- !!int "10"
- !!int "5"
"speed": "30 ft., climb 30 ft., swim 40 ft."
"skillsaves":
  "Perception": !!int "2"
"damage_immunities": "lightning, poison"
"senses": "passive Perception 12"
"languages": ""
"cr": "1/8"
"traits":
- "desc": "The clawfish can hold their breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4\
    \ + 2) slashing damage, and if the target is a Small or larger creature, the\
    \ clawfish can pull themself into the target's space and attach to the target.\
    \ While attached, the clawfish moves with the target without provoking opportunity\
    \ attacks, and the clawfish can't make Claw attacks. A creature who can reach\
    \ the clawfish can use an action to make a DC 12 Strength ([Athletics](Misc%20Files/CLI/rules/skills.md#Athletics))\
    \ or Dexterity ([Acrobatics](Misc%20Files/CLI/rules/skills.md#Acrobatics)) check.\
    \ On a success, the clawfish is detached and shunted into an unoccupied space\
    \ of the clawfish's choice within 5 feet of the target. The clawfish also detaches\
    \ if they become [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled), [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated),\
    \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone), or [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained),\
    \ or if they use 5 feet of movement to detach."
  "name": "Claw"
- "desc": "Each creature touching the clawfish takes 7 (2d6) lightning damage. If\
    \ the clawfish is immersed in water, each other creature within 10 feet of the\
    \ clawfish who is touching the same body of water must succeed on a DC 11 Dexterity\
    \ saving throw or take the same damage."
  "name": "Electrocute (Recharge 6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Clawfish.png"
```
^statblock