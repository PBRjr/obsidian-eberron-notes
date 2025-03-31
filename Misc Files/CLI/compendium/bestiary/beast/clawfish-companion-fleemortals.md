---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast/companion
statblock: inline
aliases: ["Clawfish Companion"]
---
# [Clawfish Companion](Misc Files\CLI\compendium\bestiary\beast/clawfish-companion-fleemortals.md)
*Source: Flee, Mortals! p. 33*  

```statblock
"name": "Clawfish Companion (FleeMortals)"
"size": "Small"
"type": "beast"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "13"
- !!int "12"
- !!int "4"
- !!int "10"
- !!int "5"
"speed": "30 ft., climb 30 ft., swim 40 ft."
"saves":
  "Dexterity": !!int "0"
  "Strength": !!int "0"
"skillsaves":
  "Stealth": !!int "0"
  "Perception": !!int "0"
"senses": "passive Perception 0"
"languages": ""
"traits":
- "desc": "The clawfish can hold their breath for 15 minutes."
  "name": "Hold Breath"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Bite)"
- "desc": "The clawfish makes a signature attack. On a hit, the attack deals an extra\
    \ PB lightning damage, and the target can't take reactions until the start of\
    \ the clawfish's next turn."
  "name": "1st Level: Overwhelming Attack (2 Ferocity)"
- "desc": "The clawfish makes a signature attack against a Medium or smaller creature.\
    \ On a hit, the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). Until this grapple ends, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ and the clawfish can't make a signature attack against another target."
  "name": "3rd Level: Coiling Claws (5 Ferocity)"
- "desc": "Each creature within 10 feet of the clawfish must make a DC 10 plus PB\
    \ Dexterity saving throw, taking PBd8 lightning damage on a failed save, or\
    \ half as much damage on a successful one."
  "name": "5th Level: Lightning Bomb (8 Ferocity)"
"reactions":
- "desc": "When the clawfish or their caregiver is attacked by a creature the clawfish\
    \ can see within 5 feet of them, the clawfish shocks the attacker. The attacker\
    \ must make a DC 10 plus PB Dexterity saving throw, taking PBd6 lightning damage\
    \ on a failed save, or half as much damage on a successful one."
  "name": "Lightning Retaliation (Recharges after a Short or Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Clawfish%20Companion.png"
```
^statblock