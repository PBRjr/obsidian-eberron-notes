---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/solo
statblock: inline
aliases: ["Xorannox"]
---
# [Xorannox](Misc Files\CLI\compendium\bestiary\npc/xorannox-fleemortals.md)
*Source: Flee, Mortals! p. 220*  

```statblock
"name": "Xorannox (FleeMortals)"
"size": "Large"
"type": "aberration"
"subtype": "Solo"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "228"
"hit_dice": "24d10 + 96"
"stats":
- !!int "10"
- !!int "16"
- !!int "18"
- !!int "19"
- !!int "14"
- !!int "18"
"speed": "0 ft., fly 20 ft. (hover)"
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
  "Intelligence": !!int "9"
"skillsaves":
  "Intimidation": !!int "9"
  "Deception": !!int "9"
  "Insight": !!int "7"
  "Perception": !!int "7"
  "Arcana": !!int "9"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [flanked](Misc%20Files/CLI/rules/conditions.md#Flanked), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Common, Deep Speech, Undercommon"
"cr": "14"
"traits":
- "desc": "Eight eyes float around Xorannox and create his Eye Psionics. If Xorannox\
    \ fails a saving throw, he can destroy a random floating eye (chosen by rolling\
    \ a d8) and succeed instead. If an eye is destroyed, a new eye pops of out of\
    \ Xorannox's face to replace it 24 hours later."
  "name": "Painful Resistance (3/Day)"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 14\
    \ (4d6) piercing damage."
  "name": "Bite"
- "desc": "Xorannox creates three of the following psionic eye effects. Unless otherwise\
    \ stated, each eye targets a creature who he can see within 120 feet of him. He\
    \ can't use the same effect twice on a turn.\n\n- 1. Charm Beam. The targeted\
    \ creature must succeed on a DC 17 Wisdom saving throw or be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by Xorannox for 1 hour, or until he harms the creature or one of their allies.\
    \  \n- 2. Compulsion Beam. The targeted creature must succeed on a DC 17 Intelligence\
    \ saving throw or use their reaction, if available, to move up to their speed\
    \ toward the closest ally they can see and make one weapon attack against them.\
    \ Creatures who can't be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ are unaffected.  \n- 3. Memory Beam. The targeted creature must make a DC\
    \ 17 Intelligence saving throw. On a failed save, if the creature has unexpended\
    \ spell slots, they expend a spell slot of their highest remaining level, with\
    \ no effect. If they don't have unexpended spell slots, they instead lose proficiency\
    \ with a weapon they're holding or carrying for 1 minute (save ends at end of\
    \ turn).  \n- 4. Toxic Vapors. Xorannox chooses a point he can see within\
    \ 120 feet of him. Each creature within 10 feet of the point must succeed on a\
    \ DC 17 Constitution saving throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute (save ends at end of turn).  \n- 5. Telekinetic Field. Xorannox\
    \ chooses a point he can see within 120 feet of him. Each enemy within 10 feet\
    \ of the point must succeed on a DC 17 Strength saving throw or be moved up to\
    \ 30 feet in any direction and take 7 (2d6) force damage at the end of the move.\
    \ Additionally, Xorannox can target any object within 10 feet of the point that\
    \ weighs 300 pounds or less and isn't being worn or carried, moving it up to 30\
    \ feet in any direction. Xorannox can also exert fine control on objects with\
    \ this effect, such as manipulating a simple tool or opening a door or a container.\
    \  \n- 6. Lightning Bolt. Xorannox shoots a 5-foot-wide, 60-foot-long line\
    \ of lightning. Each creature in the line must succeed on a DC 17 Dexterity saving\
    \ throw, taking 36 (8d8) lightning damage on a failed save, or half as much\
    \ damage on a successful one.  \n- 7. Explosion. Xorannox chooses a point\
    \ he can see within 120 feet of him. Each creature within 10 feet of the point\
    \ must make a DC 17 Dexterity saving throw, taking 36 (8d8) fire damage on a\
    \ failed save, or half as much damage on a successful one.  \n- 8. Necrosis\
    \ Beam. The targeted creature must succeed on a DC 17 Constitution saving throw\
    \ or immediately take 55 (10d10) necrotic damage and lose 7 (2d6) hit points\
    \ at the start of each of their turns. If this effect reduces a target's hit points\
    \ to 0, they die. The effect ends if Xorannox dies or can't see the target. This\
    \ psionic effect can't be used again while this effect persists.  "
  "name": "Eye Psionics"
"bonus_actions":
- "desc": "Xorannox's central eye turns solid black and projects a 150-foot cone of\
    \ energy. If Xorannox or any creature in that area is affected by a spell, the\
    \ spell's effects immediately end for that creature."
  "name": "The Great Eye (Recharge 6)"
"reactions":
- "desc": "When a creature hits Xorannox with an attack, he shoots a psionic fear\
    \ beam at them. The creature must succeed on a DC 17 Wisdom saving throw or take\
    \ 21 (6d6) psychic damage and be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ of Xorannox for 1 minute (save ends at end of turn)."
  "name": "Cower!"
"legendary_actions":
- "desc": "Xorannox has three villain actions. He can take each action once during\
    \ an encounter after an enemy's turn. He can take these actions in any order but\
    \ can use only one per round."
  "name": ""
- "desc": "Xorannox shoots a psionic disruption beam at three creatures he can see\
    \ within 120 feet of him. Each target must make a DC 17 Wisdom saving throw. On\
    \ a failed save, whenever the target makes more than one weapon attack on a turn\
    \ or casts a spell that isn't a cantrip, they take 14 (4d6) psychic damage.\
    \ This effect lasts for 1 minute (save ends at end of turn)."
  "name": "Action 1: Disruption Beams"
- "desc": "Xorannox turns [invisible](Misc%20Files/CLI/rules/conditions.md#Invisible)\
    \ until the end of his next turn and teleports up to 120 feet to an unoccupied\
    \ space he can see."
  "name": "Action 2: Disappearing Act"
- "desc": "Xorannox unleashes the effects of all of his remaining psionic eyes at\
    \ once in a 20-foot-wide, 120-foot-long line. Each creature in that area must\
    \ make a save against two random eye effects from Xorannox's Eye"
  "name": "Action 3: Megabeam"
- "desc": "If the effect usually affects an area, it instead only affects individual\
    \ creatures."
  "name": "Psionics (reroll duplicates for each target)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Xorannox.webp"
```
^statblock