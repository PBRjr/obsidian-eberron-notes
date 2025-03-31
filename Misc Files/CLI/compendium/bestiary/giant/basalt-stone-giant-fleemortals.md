---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/giant/controller
statblock: inline
aliases: ["Basalt Stone Giant"]
---
# [Basalt Stone Giant](Misc Files\CLI\compendium\bestiary\giant/basalt-stone-giant-fleemortals.md)
*Source: Flee, Mortals! p. 111*  

```statblock
"name": "Basalt Stone Giant (FleeMortals)"
"size": "Huge"
"type": "giant"
"subtype": "Controller"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "12d12 + 72"
"stats":
- !!int "24"
- !!int "15"
- !!int "22"
- !!int "13"
- !!int "15"
- !!int "12"
"speed": "40 ft."
"saves":
  "Wisdom": !!int "5"
  "Constitution": !!int "9"
"skillsaves":
  "Athletics": !!int "10"
  "Perception": !!int "5"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks that aren't\
  \ adamantine"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Giant"
"cr": "8"
"traits":
- "desc": "While motionless, the giant is indistinguishable from a statue."
  "name": "False Appearance"
- "desc": "When a creature attacks the giant with a melee weapon that isn't adamantine\
    \ and rolls a 1 on the d20 for that attack, that weapon is destroyed if it is\
    \ mundane. If that weapon is supernatural, it loses all supernatural properties\
    \ for 1 hour."
  "name": "Stone Flesh"
"actions":
- "desc": "The giant makes two Rune-Signed Blade attacks. They can replace one attack\
    \ with a Forked Knives attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +10 to hit, reach 10 ft., one target. Hit: 25\
    \ (4d8 + 7) slashing damage. If the target is a creature, each time they are\
    \ hit by this attack, their movement speed is reduced by a cumulative 10 feet\
    \ (to a minimum speed of 5 feet) until they regain at least 1 hit point."
  "name": "Rune-Signed Blade"
- "desc": "Melee or Ranged Weapon Attack: +10 to hit, reach 10 ft. or range 60/240\
    \ ft., one target. Hit: 17 (3d6 + 7) piercing damage, and if the target is\
    \ a Medium or smaller creature on the ground, they are knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)\
    \ and [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) as they are\
    \ pinned by the knife. The target or a creature who can reach the knife can use\
    \ an action to make a DC 18 Strength ([Athletics](Misc%20Files/CLI/rules/skills.md#Athletics))\
    \ check to try to dislodge the knife, freeing the pinned target and ending the\
    \ [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained) condition on a\
    \ success."
  "name": "Forked Knives"
"reactions":
- "desc": "When the giant is hit by a melee attack, each creature within 10 feet of\
    \ them must succeed on a DC 17 Strength saving throw or be pushed up to 10 feet\
    \ away from the giant."
  "name": "Resonate Rune"
"source":
- "FleeMortals"
```
^statblock