---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/support
statblock: inline
aliases: ["Jedar Pike"]
---
# [Jedar Pike](Misc Files\CLI\compendium\bestiary\npc/jedar-pike-fleemortals.md)
*Source: Flee, Mortals! p. 352*  

```statblock
"name": "Jedar Pike (FleeMortals)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, Support"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "[half plate](Misc%20Files/CLI/compendium/items/half-plate-armor-xphb.md)"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "14"
- !!int "10"
- !!int "12"
- !!int "10"
- !!int "15"
- !!int "14"
"speed": "30 ft."
"saves":
  "Charisma": !!int "4"
  "Wisdom": !!int "4"
"skillsaves":
  "Religion": !!int "2"
  "Insight": !!int "4"
  "Perception": !!int "4"
"senses": "passive Perception 14"
"languages": "Celestial, Common"
"cr": "1"
"traits":
- "desc": "In addition to any other spells in this stat block, Jedar can cast the\
    \ following spells, using Wisdom as the spellcasting ability (spell save DC 12):\n\
    \nAt will: [light](Misc%20Files/CLI/compendium/spells/light-xphb.md) <sup>[A](#^superscript-casting-time)</sup>,\
    \ [thaumaturgy](Misc%20Files/CLI/compendium/spells/thaumaturgy-xphb.md) <sup>[A](#^superscript-casting-time)</sup>\n\
    \n1/day: [augury](Misc%20Files/CLI/compendium/spells/augury-xphb.md) <sup>[+](#^superscript-casting-time)</sup>\n\
    \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
    \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action (see\
    \ spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When Jedar makes an attack, he has advantage on the attack roll."
  "name": "Exploit Opening (3/Day)"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage plus 2 (1d4) necrotic damage."
  "name": "Warhammer"
- "desc": "Ranged Spell Attack: +4 to hit, range 120 ft., one target. Hit: 14\
    \ (4d6) necrotic damage, and the next attack roll made against this target before\
    \ the end of Jedar's next turn has advantage."
  "name": "Nameless Reach (2/Day; 1st-Level Spell)"
- "desc": "Jedar animates three [decrepit skeleton](Misc%20Files/CLI/compendium/bestiary/undead/decrepit-skeleton-fleemortals.md)s,\
    \ who appear in unoccupied spaces Jedar can see within 30 feet of him. The skeletons\
    \ act immediately after Jedar on the same initiative count and follow his verbal\
    \ orders.\n\nIf Jedar dies, the skeletons are destroyed."
  "name": "Animate Bones (1/Day)"
"bonus_actions":
- "desc": "Jedar destroys a decrepit skeleton under his control and chooses a creature\
    \ he can see within 60 feet of him. The target gains 7 (2d6) temporary hit points."
  "name": "Bone Shield"
"source":
- "FleeMortals"
```
^statblock