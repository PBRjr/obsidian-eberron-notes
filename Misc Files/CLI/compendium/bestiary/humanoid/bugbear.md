---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/environment/forest
- ttrpg-cli/monster/environment/grassland
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Bugbear"]
---
# [Bugbear](Misc Files\CLI\compendium\bestiary\humanoid/bugbear.md)
*Source: Monster Manual p. 33, Eberron: Rising from the Last War. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Bugbears are born for battle and mayhem. Surviving by raiding and hunting, they bully the weak and despise being bossed around, but their love of carnage means they will fight for powerful masters if bloodshed and treasure are assured.

## Goblinoids

Bugbears are often found in the company of their cousins, hobgoblins and goblins. Bugbears usually enslave goblins they encounter, and they bully hobgoblins into giving them gold and food in return for serving as scouts and shock troops. Even when paid, bugbears are at best unreliable allies, yet goblins and hobgoblins understand that no matter how much bugbears might drain a tribe of resources, these creatures are a potent force.

## Followers of Hruggek

Bugbears worship Hruggek, a lesser god who dwells on the plane of Acheron. In the absence of their goblinoid kin, bugbears form loose war bands, each one led by its fiercest member. Bugbears believe that when they die, their spirits have a chance to fight at Hruggek's side. They try to prove themselves worthy by defeating as many foes as possible.

## Venal Ambushers

Despite their intimidating builds, bugbears move with surprising stealth. They are fond of setting ambushes and flee when outmatched. They are dependable mercenaries as long as they are supplied food, drink, and treasure, but a bugbear forgets any bond when its life is on the line. A wounded member of a bugbear band might be left behind to help the rest of the band escape. Afterward, that bugbear might help pursuers track down its former companions if doing so saves its life.

```statblock
"name": "Bugbear"
"size": "Medium"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "[hide armor](Misc%20Files/CLI/compendium/items/hide-armor-xphb.md), [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "15"
- !!int "14"
- !!int "13"
- !!int "8"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"skillsaves":
  "Stealth": !!int "6"
  "Survival": !!int "2"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"cr": "1"
"traits":
- "desc": "A melee weapon deals one extra die of its damage when the bugbear hits\
    \ with it (included in the attack)."
  "name": "Brute"
- "desc": "If the bugbear surprises a creature and hits it with an attack during the\
    \ first round of combat, the target takes an extra 7 (2d6) damage from the attack."
  "name": "Surprise Attack"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 11\
    \ (2d8 + 2) piercing damage."
  "name": "Morningstar"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 9 (2d6 + 2) piercing damage in melee or 5 (1d6 +\
    \ 2) piercing damage at range."
  "name": "Javelin"
"source":
- "MM"
- "ERLW"
"image": "Misc%20Files/CLI/compendium/bestiary/humanoid/token/bugbear.webp"
```
^statblock

## Environment

underdark, grassland, forest