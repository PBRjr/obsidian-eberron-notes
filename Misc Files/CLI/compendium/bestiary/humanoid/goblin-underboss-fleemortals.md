---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
aliases: ["Goblin Underboss"]
---
# [Goblin Underboss](Misc Files\CLI\compendium\bestiary\humanoid/goblin-underboss-fleemortals.md)
*Source: Flee, Mortals! p. 128*  

```statblock
"name": "Goblin Underboss (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Support"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md),\
  \ [shield](Misc%20Files/CLI/compendium/items/shield-xphb.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"stats":
- !!int "10"
- !!int "16"
- !!int "13"
- !!int "12"
- !!int "12"
- !!int "10"
"speed": "30 ft., climb 20 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "3"
"skillsaves":
  "Intimidation": !!int "2"
  "Stealth": !!int "5"
  "Insight": !!int "3"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Goblin"
"cr": "2"
"traits":
- "desc": "The underboss doesn't provoke opportunity attacks when they move out of\
    \ an enemy's reach."
  "name": "Crafty"
"actions":
- "desc": "The underboss makes two Shortsword attacks or two Shortbow attacks. They\
    \ can replace one attack with a use of Command."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage."
  "name": "Shortsword"
- "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
    \ 6 (1d6 + 3) piercing damage."
  "name": "Shortbow"
- "desc": "The underboss chooses one ally they can see within 30 feet of them. If\
    \ the target can hear the underboss, the target can use their reaction to move\
    \ up to their speed or make one weapon attack."
  "name": "Command"
"bonus_actions":
- "desc": "Each willing ally within 30 feet of the underboss who can hear them becomes\
    \ reckless until the start of the underboss's next turn. While reckless, a creature\
    \ has advantage on attack rolls, and attack rolls against the creature have advantage."
  "name": "Get Reckless (Recharge 6)"
"reactions":
- "desc": "When a creature the underboss can see hits them with an attack, the underboss\
    \ chooses a willing ally within 5 feet of them. The attack hits the ally instead."
  "name": "Cowardly Commander"
"source":
- "FleeMortals"
```
^statblock