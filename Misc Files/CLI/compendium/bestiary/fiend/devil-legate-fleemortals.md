---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
- ttrpg-cli/monster/type/fiend/soldier
statblock: inline
aliases: ["Devil Legate"]
---
# [Devil Legate](Misc Files\CLI\compendium\bestiary\fiend/devil-legate-fleemortals.md)
*Source: Flee, Mortals! p. 68*  

```statblock
"name": "Devil Legate (FleeMortals)"
"size": "Medium"
"type": "fiend"
"subtype": "devil, Soldier"
"alignment": "typically  Lawful Evil"
"ac": !!int "17"
"ac_class": "[half plate](Misc%20Files/CLI/compendium/items/half-plate-armor-xphb.md)"
"hp": !!int "127"
"hit_dice": "15d8 + 60"
"stats":
- !!int "18"
- !!int "15"
- !!int "18"
- !!int "11"
- !!int "14"
- !!int "18"
"speed": "30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "5"
  "Strength": !!int "7"
"skillsaves":
  "Athletics": !!int "7"
  "Deception": !!int "7"
  "Persuasion": !!int "7"
"damage_resistances": "bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)"
"senses": "darkvision 120 ft., passive Perception 12"
"languages": "Common, Infernal"
"cr": "8"
"traits":
- "desc": "While in Hell or within 60 feet of a devil with a challenge rating of 9\
    \ or higher, the legate has advantage on saving throws against powers, spells,\
    \ and other supernatural effects."
  "name": "Hellish Resistance"
- "desc": "If a creature the legate can hear within 60 feet of them speaks the legate's\
    \ true name aloud, the legate loses their damage resistances, damage immunities,\
    \ and Devilish Charm reaction for 24 hours."
  "name": "True Name"
"actions":
- "desc": "The legate makes two Infernal Pike attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d10 + 4) piercing damage plus 11 (2d10) fire damage, and the legate chooses\
    \ one of the following effects:\n\n- Focused Hate. The target has disadvantage\
    \ on attack rolls made against creatures other than the legate until the end of\
    \ the legate's next turn.  \n- Hellbite. The target takes an extra 5 (2d4)\
    \ fire damage.  \n- Skewer. The legate deals 5 (1d10) piercing damage plus\
    \ 5 (1d10) fire damage to another creature within 5 feet of the target.  "
  "name": "Infernal Pike"
"reactions":
- "desc": "When the legate is targeted by an attack, power, spell, or other supernatural\
    \ effect by a creature they can see within 60 feet of them, the creature must\
    \ make a DC 15 Charisma saving throw. On a failed save, the creature is [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the legate until the start of the creature's next turn, and the legate chooses\
    \ a new target the legate can see for the triggering effect. The new target must\
    \ be within the triggering effect's range."
  "name": "Devilish Charm (1/Day)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Devil%20Legate.png"
```
^statblock