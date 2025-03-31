---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity/companion
statblock: inline
aliases: ["Owlbear Companion"]
---
# [Owlbear Companion](Misc Files\CLI\compendium\bestiary\monstrosity/owlbear-companion-fleemortals.md)
*Source: Flee, Mortals! p. 223*  

```statblock
"name": "Owlbear Companion (FleeMortals)"
"size": "Large"
"type": "monstrosity"
"subtype": "Companion"
"alignment": "Unaligned"
"ac_class": "13 plus PB (natural armor)"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "5"
- !!int "12"
- !!int "10"
"speed": "40 ft."
"saves":
  "Strength": !!int "0"
  "Constitution": !!int "0"
"skillsaves":
  "Athletics": !!int "0"
  "Perception": !!int "0"
"senses": "darkvision 60 ft., passive Perception 0"
"languages": ""
"traits":
- "desc": "The owlbear has advantage on Wisdom ([Perception](Misc%20Files/CLI/rules/skills.md#Perception))\
    \ checks that rely on sight or smell."
  "name": "Keen Sight and Smell"
"actions":
- "desc": "Melee Weapon Attack: +3 plus PB to hit, reach 5 ft., one target. Hit:\
    \ 1d6 plus PB slashing damage."
  "name": "Signature Attack (Claw)"
- "desc": "The owlbear makes a signature attack. On a hit, the attack deals an extra\
    \ PB damage, and the owlbear can move the target 5 feet in any direction."
  "name": "1st Level: Violent Attack (2 Ferocity)"
- "desc": "The owlbear leaps up to half their speed without provoking opportunity\
    \ attacks. When they land, each creature within 5 feet of them must succeed on\
    \ a DC 10 plus PB Strength saving throw or be knocked [prone](Misc%20Files/CLI/rules/conditions.md#Prone)."
  "name": "3rd Level: Owlie Oop (5 Ferocity)"
- "desc": "The owlbear attempts to grab and crush a creature they can see within 5\
    \ feet of them. The target must make a DC 10 plus PB Dexterity saving throw. On\
    \ a failed save, the target takes PBd10 bludgeoning damage and is [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ (escape DC 10 plus PB). On a successful save, the target takes half as much\
    \ damage and is not [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled).\
    \ Until this grapple ends, the target is also [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained).\
    \ The grapple ends if the owlbear uses Bear Hug on another target or makes a signature\
    \ attack against another target."
  "name": "5th Level: Bear Hug (8 Ferocity)"
"bonus_actions":
- "desc": "The owlbear lets loose a unique battle hoot. If the owlbear's caregiver\
    \ can hear the owlbear, the caregiver gains 5 × PB temporary hit points."
  "name": "Give a Hoot (Recharges after a Long Rest)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Owlbear%20Companion.png"
```
^statblock