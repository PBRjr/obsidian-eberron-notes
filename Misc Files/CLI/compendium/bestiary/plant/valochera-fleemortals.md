---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant/controller
- ttrpg-cli/monster/type/plant/fungus
statblock: inline
aliases: ["Valochera"]
---
# [Valochera](Misc Files\CLI\compendium\bestiary\plant/valochera-fleemortals.md)
*Source: Flee, Mortals! p. 329*  

```statblock
"name": "Valochera (FleeMortals)"
"size": "Large"
"type": "plant"
"subtype": "fungus, Controller"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "180"
"hit_dice": "19d10 + 76"
"stats":
- !!int "20"
- !!int "10"
- !!int "18"
- !!int "5"
- !!int "10"
- !!int "5"
"speed": "30 ft., swim 20 ft."
"saves":
  "Dexterity": !!int "4"
  "Strength": !!int "9"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "4"
"damage_resistances": "cold, fire"
"damage_immunities": "acid, lightning, poison"
"condition_immunities": "[blinded](Misc%20Files/CLI/rules/conditions.md#Blinded),\
  \ [deafened](Misc%20Files/CLI/rules/conditions.md#Deafened), [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 14"
"languages": ""
"cr": "9"
"traits":
- "desc": "Whenever the valochera is subjected to acid damage, they take no damage\
    \ and instead regain a number of hit points equal to the acid damage dealt."
  "name": "Acid Absorption"
- "desc": "Any creature who starts their turn within 5 feet of the valochera must\
    \ succeed on a DC 16 Constitution saving throw or be [poisoned](Misc%20Files/CLI/rules/conditions.md#Poisoned)\
    \ for 1 minute (save ends at end of turn)."
  "name": "Unbearable Stench"
"actions":
- "desc": "The valochera makes two Mycelium attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 18\
    \ (3d8 + 5) bludgeoning damage. If the target is Large or smaller, they are\
    \ [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled) (escape DC 15).\n\n\
    Until this grapple ends, the target is [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)."
  "name": "Mycelium"
- "desc": "The valochera douses a creature they have [grappled](Misc%20Files/CLI/rules/conditions.md#Grappled)\
    \ with acid and then takes a bite. The target must make a DC 16 Dexterity saving\
    \ throw, taking 22 (4d10) acid damage plus 14 (2d8 + 5) piercing damage on\
    \ a failed save, or half as much damage on a successful one."
  "name": "Chow Time"
- "desc": "The valochera spits a glob of noxious sludge at a point they can see within\
    \ 30 feet of them.\n\nEach creature in a 5-foot-radius sphere centered on that\
    \ point must make a DC 16 Constitution saving throw, taking 33 (6d10) poison\
    \ damage on a failed save, or half as much damage on a successful one."
  "name": "Poison Glob (Recharge 5-6)"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Valochera.png"
```
^statblock