---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/brute
statblock: inline
aliases: ["Marsh Hydra"]
---
# [Marsh Hydra](Misc Files\CLI\compendium\bestiary\monstrosity/marsh-hydra-fleemortals.md)
*Source: Flee, Mortals! p. 334*  

```statblock
"name": "Marsh Hydra (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Brute"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "126"
"hit_dice": "12d10 + 60"
"stats":
- !!int "20"
- !!int "10"
- !!int "20"
- !!int "3"
- !!int "12"
- !!int "3"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "8"
  "Perception": !!int "7"
"condition_immunities": "flanked, [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned),\
  \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": ""
"cr": "7"
"traits":
- "desc": "The marsh hydra has advantage on saving throws against being [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
    \ [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed), [dazed](Misc%20Files/CLI/rules/conditions.md#Dazed),\
    \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
    \ [stunned](Misc%20Files/CLI/rules/conditions.md#Stunned), and knocked [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)."
  "name": "Multiple Heads"
- "desc": "If the marsh hydra moves at least 20 feet straight toward a creature and\
    \ then hits them with an Entangling Serpents attack on the same turn, that target\
    \ must succeed on a DC 16 Strength saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "Roll Over"
"actions":
- "desc": "The marsh hydra makes two Entangling Serpents attacks. They can replace\
    \ one attack with a Many Bites attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 14\
    \ (2d8 + 5) bludgeoning damage, and the target is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 16)."
  "name": "Entangling Serpents"
- "desc": "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 9\
    \ (1d8 + 5) piercing damage, and the target must make a DC 16 Constitution saving\
    \ throw. On a failed save, the target takes 18 (4d8) poison damage and is [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ until the end of the marsh hydra's next turn. On a successful save, the target\
    \ takes half as much damage and isn't [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)."
  "name": "Many Bites"
"bonus_actions":
- "desc": "The marsh hydra activates one of the following effects; if the effect targets\
    \ another creature, the marsh hydra targets one creature they can see within 30\
    \ feet of them:\n\n- 1. Poison Spit. The targeted creature must succeed on\
    \ a DC 16 Dexterity saving throw or take 9 (2d8) poison damage and be [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)\
    \ until the end of the marsh hydra's next turn.  \n- 2. Entrancing Gaze. The\
    \ targeted creature must succeed on a DC 16 Wisdom saving throw or be [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed)\
    \ by the marsh hydra for 1 minute or until the marsh hydra harms the target (save\
    \ ends at end of turn).  \n- 3. Terrifying Rattle. The targeted creature must\
    \ succeed on a DC 16 Wisdom saving throw or be [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)\
    \ by the marsh hydra for 1 minute (save ends at end of turn).  \n- 4. Reinforcements.\
    \ The marsh hydra shuffles which heads are on the outside of their body and regains\
    \ 10 (3d6) hit points.  "
  "name": "Serpent Surprise"
"source":
- "FleeMortals"
```
^statblock