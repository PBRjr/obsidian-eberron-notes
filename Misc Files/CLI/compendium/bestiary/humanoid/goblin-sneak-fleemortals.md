---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/retainer
statblock: inline
aliases: ["Goblin Sneak"]
---
# [Goblin Sneak](Misc Files\CLI\compendium\bestiary\humanoid/goblin-sneak-fleemortals.md)
*Source: Flee, Mortals! p. 132*  

```statblock
"name": "Goblin Sneak (FleeMortals)"
"size": "Small"
"type": "humanoid"
"subtype": "goblin, Retainer"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "medium armor"
"stats":
- !!int "10"
- !!int "16"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "10"
"speed": "30 ft., climb 20 ft."
"saves":
  "Charisma": !!int "0"
  "Dexterity": !!int "0"
  "Wisdom": !!int "0"
  "Intelligence": !!int "0"
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Stealth": !!int "0"
  "Acrobatics": !!int "0"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Common, Goblin"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +3 plus PB to hit, reach 5 ft. or range\
    \ 20/60 ft., one target. Hit: 2d4 plus PB piercing damage. Beginning at 7th\
    \ level, the sneak can make this attack twice, instead of once, when they take\
    \ the Attack action on their turn."
  "name": "Signature Attack (Daggers)"
- "desc": "As an action, the sneak moves up to their speed without provoking opportunity\
    \ attacks. Before, during, or after the move, they can make two signature attacks."
  "name": "3rd Level: Weaving Knives (3/Day)"
- "desc": "As a bonus action, the sneak takes the Hide action. If the sneak hits a\
    \ creature they are hidden from with an attack on the same turn, the creature\
    \ takes an extra PBd10 piercing damage, and the sneak can immediately take the\
    \ Hide action (no action required)."
  "name": "5th Level: Sneak and Stab (3/Day)"
- "desc": "As a bonus action, the sneak covers a dagger in a special poison, which\
    \ lasts for 1 hour or until the sneak hits a creature with a signature attack.\
    \ A creature hit with the [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ dagger must make a DC 10 plus PB Constitution saving throw. On a failed save,\
    \ the target takes PBd12 poison damage and is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute (save ends at the end of turn). On a successful save, the target\
    \ takes only half as much damage and isn't [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)."
  "name": "7th Level: Poisoned Blade (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Goblin%20Sneak.webp"
```
^statblock