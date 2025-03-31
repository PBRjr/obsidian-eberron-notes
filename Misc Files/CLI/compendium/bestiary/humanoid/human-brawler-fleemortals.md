---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/brute
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
aliases: ["Human Brawler"]
---
# [Human Brawler](Misc Files\CLI\compendium\bestiary\humanoid/human-brawler-fleemortals.md)
*Source: Flee, Mortals! p. 160*  

```statblock
"name": "Human Brawler (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Brute"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "52"
"hit_dice": "7d8 + 21"
"stats":
- !!int "17"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "3"
  "Athletics": !!int "5"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "2"
"traits":
- "desc": "When the brawler makes an attack, they have advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
"actions":
- "desc": "The brawler makes two attacks using Grab, Haymaker, or both."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one Medium or smaller\
    \ creature. Hit: 5 (1d4 + 3) bludgeoning damage, and the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 13). Until this grapple ends, the brawler can't grab another creature."
  "name": "Grab"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d4\
    \ + 3) bludgeoning damage, or 10 (3d4 + 3) bludgeoning damage against a [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ target."
  "name": "Haymaker"
- "desc": "The brawler throws one Medium or smaller creature they are grappling or\
    \ object they are holding up to 30 feet horizontally. If the thrown target is\
    \ a creature, they fall [prone](Misc%20Files/CLI/rules/conditions.md#Prone) after\
    \ this throw. If the thrown target would enter the space of a creature or solid\
    \ object that is no more than one size smaller than it, the thrown target collides\
    \ with it and stops in the nearest unoccupied space, taking 3 (1d6) bludgeoning\
    \ damage for every 10 feet it was thrown. A Large or smaller creature hit by this\
    \ thrown target must succeed on a DC 13 Dexterity saving throw or take the same\
    \ amount of damage and fall [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Throw"
"reactions":
- "desc": "When the brawler is grappling a target and is hit by a ranged attack made\
    \ by another creature the brawler can see, the brawler gains a +2 bonus to AC\
    \ against the triggering attack. If this bonus causes the attack to miss the brawler,\
    \ it hits the [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) target\
    \ instead."
  "name": "Meat Shield"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Human%20Brawler.png"
```
^statblock