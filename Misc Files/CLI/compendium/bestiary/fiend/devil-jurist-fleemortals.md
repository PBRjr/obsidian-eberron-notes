---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/artillery
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
aliases: ["Devil Jurist"]
---
# [Devil Jurist](Misc Files\CLI\compendium\bestiary\fiend/devil-jurist-fleemortals.md)
*Source: Flee, Mortals! p. 67*  

```statblock
"name": "Devil Jurist (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Artillery"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "[studded leather](Misc%20Files/CLI/compendium/items/studded-leather-armor-xphb.md)"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"stats":
- !!int "11"
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "14"
- !!int "19"
"speed": "30 ft., fly 40 ft."
"saves":
  "Charisma": !!int "8"
  "Wisdom": !!int "6"
  "Intelligence": !!int "7"
"skillsaves":
  "Deception": !!int "8"
  "Perception": !!int "6"
  "Arcana": !!int "7"
  "Persuasion": !!int "8"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Common, Infernal"
"cr": "10"
"traits":
- "desc": "Fire damage dealt by the jurist ignores damage resistance."
  "name": "Hellfire"
- "desc": "If a creature the jurist can hear within 60 feet of them speaks the jurist's\
    \ true name aloud, the jurist loses their damage resistances, damage immunities,\
    \ and Devilish Charm reaction for 24 hours."
  "name": "True Name"
"actions":
- "desc": "The jurist makes two Fire and Brim stone attacks."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +8 to hit, reach 5 ft. or range 120 ft.,\
    \ one target. Hit: 17 (3d8 + 4) fire damage, and the target must succeed on\
    \ a DC 16 Constitution saving throw or gain one festering wound. A creature takes\
    \ 4 (1d8) fire damage at the start of each of their turns for each festering\
    \ wound they have. A creature who receives supernatural healing loses all festering\
    \ wounds."
  "name": "Fire and Brimstone"
- "desc": "The jurist makes one Fire and Brimstone attack against each enemy they\
    \ can see within 60 feet of them."
  "name": "Inferno (Recharge 5-6)"
"bonus_actions":
- "desc": "The jurist chooses a creature they can see within 120 feet of them who\
    \ has one or more festering wounds. One of the target's wounds ignites and they\
    \ take 9 (2d8) fire damage."
  "name": "Ashes to Ashes"
"reactions":
- "desc": "When the jurist is targeted by an attack, power, spell, or other supernatural\
    \ effect by a creature they can see within 60 feet of them, the creature must\
    \ make a DC 16 Charisma saving throw. On a failed save, the creature is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the jurist until the start of the creature's next turn, and the jurist chooses\
    \ a new target the jurist can see for the triggering effect. The new target must\
    \ be within the triggering effect's range."
  "name": "Devilish Charm (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Devil%20Jurist.png"
```
^statblock