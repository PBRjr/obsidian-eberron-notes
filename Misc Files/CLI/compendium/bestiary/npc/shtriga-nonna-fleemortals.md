---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey/solo
statblock: inline
aliases: ["Shtriga Nonna"]
---
# [Shtriga Nonna](Misc Files\CLI\compendium\bestiary\npc/shtriga-nonna-fleemortals.md)
*Source: Flee, Mortals! p. 140*  

```statblock
"name": "Shtriga Nonna (FleeMortals)"
"size": "Medium"
"type": "fey"
"subtype": "Solo"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d8 + 56"
"stats":
- !!int "18"
- !!int "16"
- !!int "18"
- !!int "14"
- !!int "15"
- !!int "19"
"speed": "30 ft., fly 30 ft."
"saves":
  "Wisdom": !!int "5"
"skillsaves":
  "Deception": !!int "7"
  "Stealth": !!int "6"
  "Perception": !!int "5"
  "Survival": !!int "5"
"damage_resistances": "thunder; bludgeoning, piercing, slashing from mundane attacks"
"damage_immunities": "cold, fire"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Giant, Infernal, Sylvan"
"cr": "6"
"traits":
- "desc": "In addition to any other spells in this stat block, Shtriga Nonna can cast\
    \ the following spells, using Charisma as the spellcasting ability (spell save\
    \ DC 15):\n\nAt will: [alter self](Misc%20Files/CLI/compendium/spells/alter-self-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
    \ [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md)<sup>[A](#^superscript-casting-time)</sup>,\
    \ [thaumaturgy](Misc%20Files/CLI/compendium/spells/thaumaturgy-xphb.md)<sup>[A](#^superscript-casting-time)</sup>\n\
    \n1/day: [scrying](Misc%20Files/CLI/compendium/spells/scrying-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
    \n3/day each: [fabricate](Misc%20Files/CLI/compendium/spells/fabricate-xphb.md)<sup>[+](#^superscript-casting-time)</sup>,\
    \ [legend lore](Misc%20Files/CLI/compendium/spells/legend-lore-xphb.md)<sup>[+](#^superscript-casting-time)</sup>\n\
    \n| Superscript | Casting Time |\n|-------------|--------------|\n| A | 1 action\
    \ |\n| B | 1 bonus action |\n| R | 1 reaction |\n| + | Longer than 1 action (see\
    \ spell description) |\n^superscript-casting-time"
  "name": "Spellcasting (Utility)"
- "desc": "When Shtriga Nonna fails a saving throw, she can immediately turn into\
    \ a cat of her size (Medium in her normal form, Large while under the effect of\
    \ Grow) and succeed instead. While in cat form, Shtriga Nonna retains her game\
    \ statistics and ability to speak, except she can't cast spells or use Soul Steal.\
    \ She reverts to her previous form at the end of her next turn."
  "name": "Feline Resilience (3/Day)"
- "desc": "Shtriga Nonna has advantage on saving throws against powers, spells, and\
    \ other supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "Shtriga Nonna makes two Corrosive Claw attacks. She can replace one attack\
    \ with a use of Soul Steal, if available."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +7 to hit, reach 5 ft. (10 ft. with Grow), one\
    \ target. Hit: 11 (2d6 + 4) slashing damage, or 14 (3d6 + 4) slashing damage\
    \ while under the effect of Grow. If the target is wearing mundane metal armor,\
    \ they must succeed on a DC 15 Dexterity throw or their armor takes a permanent\
    \ and cumulative -1 penalty to the AC it offers. If the armor is reduced to an\
    \ AC of 10, it is destroyed."
  "name": "Corrosive Claw"
- "desc": "Shtriga Nonna inhales deeply in a 30-foot cone. Each creature in that area\
    \ must make a DC 15 Constitution saving throw, taking 16 (3d10) necrotic damage\
    \ on a failed save, or half as much damage on a successful one. Shtriga Nonna\
    \ regains 10 hit points for each creature who fails this saving throw."
  "name": "Soul Steal (Recharge 5-6)"
"bonus_actions":
- "desc": "For 1 minute, Shtriga Nonna magically increases in size, along with anything\
    \ she is wearing or carrying. While enlarged, she is Large, her reach becomes\
    \ 10 feet, she deals an extra 3 (1d6) damage on Strength-based weapon attacks\
    \ (included in the attacks), and she makes Strength checks and Strength saving\
    \ throws with advantage. If Shtriga Nonna lacks the room to become Large, she\
    \ attains the maximum size possible in the space available."
  "name": "Grow (2/Day; 3rd-Level Spell)"
- "desc": "Shtriga Nonna feeds on the body of an [unconscious](Misc%20Files/CLI/rules/conditions.md#Unconscious)\
    \ creature within 5 feet of her. The target takes 10 (3d6) piercing damage,\
    \ and Shtriga Nonna recharges her Soul Steal action."
  "name": "Gobble You Up"
"reactions":
- "desc": "When a creature hits Shtriga Nonna with a melee attack, she magically reverses\
    \ gravity around her. Each creature within 5 feet of her must succeed on a DC\
    \ 15 Strength saving throw or rise vertically 10 feet into the air. A creature\
    \ levitating in this way remains suspended until the end of their next turn, then\
    \ falls unless they have an ability that keeps them aloft."
  "name": "Turned Upside Down"
"legendary_actions":
- "desc": "Shtriga Nonna has three villain actions. She can take each action once\
    \ during an encounter after an enemy's turn. She can take these actions in any\
    \ order but can use only one per round."
  "name": ""
- "desc": "The air within 30 feet of Shtriga Nonna magically fills with the scent\
    \ of rotten food. Each other creature in that area must succeed on a DC 15 Wisdom\
    \ saving throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute (save ends at end of turn). Creatures are affected even if they\
    \ hold their breath or don't need to breathe."
  "name": "Action 1: Snackies for Sweeties"
- "desc": "Shtriga Nonna grows four cat legs in a burst of magical energy. Each creature\
    \ within 5 feet of her must make a DC 15 Dexterity saving throw. On a failed save,\
    \ a creature takes 10 (4d4) force damage and is pushed 10 feet away from her.\
    \ On a successful save, a creature takes half as much damage and isn't pushed.\
    \ Shtriga Nonna can then move up to twice her speed, after which the extra cat\
    \ legs disappear."
  "name": "Action 2: Feline Felicity"
- "desc": "Shtriga Nonna opens a portal to her massive oven in the palms of her hands,\
    \ creating a blast of heat and noise in a 30-foot cone. Each creature in that\
    \ area must make a DC 15 Dexterity saving throw, taking 13 (3d8) fire damage\
    \ plus 13 (3d8) thunder damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Action 3: Open the Oven"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew-img/main/img/FleeMortals/monsterToken/Shtriga%20Nonna.webp"
```
^statblock