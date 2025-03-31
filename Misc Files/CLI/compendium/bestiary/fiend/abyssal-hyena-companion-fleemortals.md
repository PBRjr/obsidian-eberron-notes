---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/companion
statblock: inline
aliases: ["Abyssal Hyena Companion"]
---
# [Abyssal Hyena Companion](Misc Files\CLI\compendium\bestiary\fiend/abyssal-hyena-companion-fleemortals.md)
*Source: Flee, Mortals! p. 123*  

```statblock
"name": "Abyssal Hyena Companion (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "14"
- !!int "12"
- !!int "5"
- !!int "12"
- !!int "8"
"speed": "50 ft."
"saves":
  "Dexterity": !!int "0"
  "Strength": !!int "0"
"skillsaves":
  "Perception": !!int "0"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB piercing damage."
  "name": "Signature Attack (Bite)"
- "desc": "The hyena makes a signature attack. On a hit, the target also has disadvantage\
    \ on the next Strength or Dexterity saving throw they make before the start of\
    \ their next turn."
  "name": "1st Level: Unbalancing Attack (2 Ferocity)"
- "desc": "The hyena makes a signature attack with advantage. On a hit, the attack\
    \ deals an extra PB necrotic damage, and the hyena regains hit points equal to\
    \ the necrotic damage dealt."
  "name": "3rd Level: Gobbling Bite (5 Ferocity)"
- "desc": "Each enemy within 30 feet of the hyena who can hear them must succeed on\
    \ a DC 10 plus PB Wisdom saving throw or take PBd4 psychic damage and be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of the hyena until the start of the hyena's next turn."
  "name": "5th Level: Cackle (8 Ferocity)"
"reactions":
- "desc": "When the hyena's caregiver is hit with an attack and the hyena is within\
    \ 5 feet of the attacker, the hyena can make a signature attack against the attacker."
  "name": "Blood Frenzy (Recharges after a Short or Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Abyssal%20Hyena.png"
```
^statblock