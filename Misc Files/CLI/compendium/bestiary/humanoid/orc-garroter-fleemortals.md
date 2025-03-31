---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/ambusher
- ttrpg-cli/monster/type/humanoid/orc
statblock: inline
aliases: ["Orc Garroter"]
---
# [Orc Garroter](Misc Files\CLI\compendium\bestiary\humanoid/orc-garroter-fleemortals.md)
*Source: Flee, Mortals! p. 208*  

```statblock
"name": "Orc Garroter (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "orc, Ambusher"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "30"
"hit_dice": "4d8 + 12"
"stats":
- !!int "15"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "9"
"speed": "35 ft."
"saves":
  "Dexterity": !!int "4"
"skillsaves":
  "Athletics": !!int "4"
  "Stealth": !!int "6"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Orc"
"cr": "1"
"traits":
- "desc": "When the garroter isn't [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated)\
    \ and they are reduced to 0 hit points but not killed outright, they can make\
    \ an attack against an enemy (no action required) before the hit point reduction\
    \ is resolved. If the attack hits and its damage reduces the target to 0 hit points,\
    \ the garroter drops to 1 hit point instead of 0 hit points."
  "name": "Relentless (1/Turn)"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) bludgeoning damage, and the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 12). Until the grapple ends, the target can't speak intelligibly\
    \ or cast spells with verbal components. If the attack was made with advantage,\
    \ the target must make a DC 12 Constitution saving throw. On a failed save, the\
    \ target falls [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)\
    \ for 1 minute (save ends at start of turn) or until they take damage. A creature\
    \ can use an action to shake another creature awake who falls [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)\
    \ in this way."
  "name": "Strangle"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage. If the attack was made\
    \ with advantage, the target takes an extra 7 (2d6) piercing damage."
  "name": "Dagger"
"bonus_actions":
- "desc": "The garroter magically turns [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ for 1 minute. Any equipment the garroter wears or carries is [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ with them. While [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible),\
    \ the garroter's movements make no sound. If the garroter hits a creature with\
    \ an attack, casts a spell, or takes damage, the effect ends."
  "name": "Cloak (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Orc%20Garroter.png"
```
^statblock