---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
aliases: ["Scyza"]
---
# [Scyza](Misc Files\CLI\compendium\bestiary\monstrosity/scyza-fleemortals.md)
*Source: Flee, Mortals! p. 212*  

```statblock
"name": "Scyza (FleeMortals)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "108"
"hit_dice": "8d20 + 24"
"stats":
- !!int "21"
- !!int "9"
- !!int "17"
- !!int "5"
- !!int "11"
- !!int "7"
"speed": "40 ft."
"saves":
  "Strength": !!int "7"
  "Constitution": !!int "5"
"condition_immunities": "[frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "4"
"traits":
- "desc": "The scyza deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "While wearing a war harness, the scyza can carry up to thirty-six Medium\
    \ or smaller creatures."
  "name": "War Harness"
"actions":
- "desc": "The scyza makes two Claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage, and the target is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +7 to hit, reach 20 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage. If the target is on top of the scyza, the target\
    \ falls off and lands [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Tail Whip"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 23\
    \ (4d8 + 5) bludgeoning damage, and if the target is a creature who can hear,\
    \ they are [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed) until the end of\
    \ their next turn by the crest's deep ringing."
  "name": "Head Crest"
- "desc": "The scyza claws at the ground in a flurry. Each creature of the scyza's\
    \ choice within 5 feet of them must make a DC 15 Dexterity saving throw. On a\
    \ failed save, a creature takes 13 (3d8) slashing damage, is knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone),\
    \ and is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded) by a cloud of\
    \ dust until the start of the scyza's next turn. On a successful save, a creature\
    \ takes half as much damage and isn't knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ or [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)."
  "name": "Claw Twister (Recharge 6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Scyza.png"
```
^statblock