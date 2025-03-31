---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/retainer
- ttrpg-cli/monster/type/undead/undead
statblock: inline
aliases: ["Vampire Neophyte"]
---
# [Vampire Neophyte](Misc Files\CLI\compendium\bestiary\undead/vampire-neophyte-fleemortals.md)
*Source: Flee, Mortals! p. 274*  

```statblock
"name": "Vampire Neophyte (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "undead, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "12"
- !!int "16"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "12"
"speed": "30 ft., climb 30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Acrobatics": !!int "0"
  "Persuasion": !!int "0"
"damage_vulnerabilities": "radiant"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, any two languages they knew in life"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d8 plus PB slashing damage. Beginning at 7th level, the neophyte can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Claws)"
- "desc": "When the neophyte hits a creature with a signature attack, the neophyte\
    \ grabs the target. The target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB), and the neophyte moves up to their speed without provoking\
    \ attacks of opportunity (no action required). If the [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ creature is Medium or smaller, they don't cost the neophyte extra movement."
  "name": "3rd Level: Take Away (3/Day)"
- "desc": "As an action, the neophyte moves up to their speed toward a creature they\
    \ can see within 60 feet of them. If the neophyte ends their movement within 5\
    \ feet of the creature, the target must succeed on a DC 10 plus PB Dexterity saving\
    \ throw or be [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) (escape\
    \ DC 10 plus PB) and take 1d4 piercing damage plus PBd8 necrotic damage. The\
    \ neophyte regains hit points equal to half the necrotic damage dealt."
  "name": "5th Level: Blood Seeker (3/Day)"
- "desc": "As a reaction to taking damage, the neophyte disappears in a cloud of bats\
    \ and insects. Every enemy within 10 feet of the neophyte must make a DC 10 plus\
    \ PB Dexterity saving throw. On a failed save, a creature takes PBd4 piercing\
    \ damage plus PBd4 slashing damage. On a successful save, a creature takes half\
    \ as much damage. At the end of the turn, the neophyte reforms in an unoccupied\
    \ space within 30 feet of where they disappeared."
  "name": "7th Level: Child of the Night (3/Day)"
"source":
- "FleeMortals"
```
^statblock