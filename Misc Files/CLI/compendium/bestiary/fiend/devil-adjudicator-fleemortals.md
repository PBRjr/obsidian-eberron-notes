---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/controller
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Devil Adjudicator"]
---
# [Devil Adjudicator](Misc Files\CLI\compendium\bestiary\fiend/devil-adjudicator-fleemortals.md)
*Source: Flee, Mortals! p. 66*  

```statblock
"name": "Devil Adjudicator (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Controller"
"alignment": "typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"stats":
- !!int "12"
- !!int "16"
- !!int "18"
- !!int "16"
- !!int "14"
- !!int "20"
"speed": "30 ft., fly 40 ft."
"saves":
  "Charisma": !!int "10"
  "Wisdom": !!int "7"
  "Constitution": !!int "9"
"skillsaves":
  "Deception": !!int "10"
  "Religion": !!int "8"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Persuasion": !!int "10"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Common, Infernal"
"cr": "14"
"traits":
- "desc": "If a creature the adjudicator can hear within 60 feet of them speaks the\
    \ adjudicator's true name aloud, the adjudicator loses their damage resistances,\
    \ damage immunities, and Devilish Charm reaction for 24 hours."
  "name": "True Name"
"actions":
- "desc": "The adjudicator makes two Infernal Injunction attacks and uses Adjudicator's\
    \ Interdiction, if available."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +10 to hit, reach 5 ft. or range 120\
    \ ft., one target. Hit: 27 (5d8 + 5) fire damage, and the target must make\
    \ a DC 18 Wisdom saving throw. On a failed save, the adjudicator chooses for the\
    \ target to become either [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by or [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened) of them\
    \ until the end of the target's next turn."
  "name": "Infernal Injunction"
- "desc": "The adjudicator places an infernal seal on one creature they can see within\
    \ 120 feet of them. The target must succeed on a DC 18 Charisma saving throw or\
    \ be interdicted until the adjudicator dies. While interdicted, a creature's speed\
    \ is halved, they can't take reactions, and they can't regain hit points. A cure\
    \ ailment power, a [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md)\
    \ or [remove curse](Misc%20Files/CLI/compendium/spells/remove-curse-xphb.md) spell,\
    \ or a similar supernatural effect ends the effect early."
  "name": "Adjudicator's Interdiction (Recharge 5-6)"
- "desc": "Three creatures the adjudicator can see within 60 feet of them must make\
    \ a DC 18 Charisma saving throw. On a failed save, a target must choose to either\
    \ take a -5 penalty to AC or a -5 penalty to ability checks and attack rolls.\
    \ This penalty lasts for 10 minutes (save ends at end of turn)."
  "name": "Bad Deal (1/Day)"
"reactions":
- "desc": "When the adjudicator is targeted by an attack, power, spell, or other supernatural\
    \ effect by a creature they can see within 60 feet of them, the creature must\
    \ make a DC 18 Charisma saving throw. On a failed save, the creature is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the adjudicator until the start of the creature's next turn, and the adjudicator\
    \ chooses a new target the adjudicator can see for the triggering effect. The\
    \ new target must be within the triggering effect's range."
  "name": "Devilish Charm (2/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Devil%20Adjudicator.png"
```
^statblock