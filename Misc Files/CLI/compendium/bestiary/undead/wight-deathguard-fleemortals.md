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
aliases: ["Wight Deathguard"]
---
# [Wight Deathguard](Misc Files\CLI\compendium\bestiary\undead/wight-deathguard-fleemortals.md)
*Source: Flee, Mortals! p. 256*  

```statblock
"name": "Wight Deathguard (FleeMortals)"
"size": "Medium"
"type": "undead"
"subtype": "undead, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "10"
- !!int "12"
"speed": "30 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Intimidation": !!int "0"
  "Perception": !!int "0"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](Misc%20Files/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": "the languages they knew in life"
"actions":
- "desc": "Melee Attack Roll: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d8 plus PB slashing damage. Beginning at 7th level, the deathguard can make\
    \ this attack twice, instead of once, when they take the Attack action on their\
    \ turn."
  "name": "Signature Attack (Longsword)"
- "desc": "As a reaction to an ally the deathguard can see within 5 feet of them being\
    \ hit with an attack, the deathguard redirects the attack to themself, potentially\
    \ causing the attack to miss. If the attacker is within 5 feet of the deathguard,\
    \ the deathguard can make a signature attack against the attacker."
  "name": "3rd Level: Blood for Blood (3/Day)"
- "desc": "As an action, the deathguard shrouds themself in dark energy. The deathguard\
    \ regains PBd6 hit points, and each enemy within 5 feet of the deathguard must\
    \ make a DC 10 plus PB Wisdom saving throw. On a failed save, a target takes PBd6\
    \ necrotic damage. On a successful save, a target takes half as much damage."
  "name": "5th Level: Soul Thief (3/Day)"
- "desc": "As an action, the deathguard moves up to their speed without provoking\
    \ opportunity attacks. Each ally the deathguard passes within 5 feet of during\
    \ the move can use a reaction to move up to their speed in the same direction\
    \ as the deathguard without provoking opportunity attacks. Until the start of\
    \ the deathguard's next turn, attacks against these allies have disadvantage."
  "name": "7th Level: This Way! (3/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Wight%20Deathguard.png"
```
^statblock