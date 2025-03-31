---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fleemortals
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration/solo
statblock: inline
aliases: ["Ithu'rath"]
---
# [Ithu'rath](Misc Files\CLI\compendium\bestiary\npc/ithurath-fleemortals.md)
*Source: Flee, Mortals! p. 202*  

```statblock
"name": "Ithu'rath (FleeMortals)"
"size": "Large"
"type": "aberration"
"subtype": "Solo"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "255"
"hit_dice": "30d10 + 90"
"stats":
- !!int "23"
- !!int "9"
- !!int "16"
- !!int "23"
- !!int "14"
- !!int "18"
"speed": "30 ft., fly 60 ft. (hover), swim 60 ft."
"saves":
  "Charisma": !!int "9"
  "Wisdom": !!int "7"
  "Intelligence": !!int "11"
  "Constitution": !!int "8"
"skillsaves":
  "Intimidation": !!int "9"
  "Insight": !!int "12"
  "Perception": !!int "12"
  "History": !!int "11"
"condition_immunities": "[charmed](Misc%20Files/CLI/rules/conditions.md#Charmed),\
  \ [flanked](Misc%20Files/CLI/rules/conditions.md#Flanked), [frightened](Misc%20Files/CLI/rules/conditions.md#Frightened),\
  \ [prone](Misc%20Files/CLI/rules/conditions.md#Prone)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 22"
"languages": "Common, Deep Speech, Undercommon, telepathy 120 ft."
"cr": "16"
"traits":
- "desc": "Ithu'rath can breathe air and water."
  "name": "Amphibious"
- "desc": "Ithu'rath is immune to any power, spell, or effect that would alter their\
    \ form."
  "name": "Immutable Form"
- "desc": "When Ithu'rath fails a saving throw, they can succeed on the save by channeling\
    \ the power of their protective slime. Until the end of Ithu'rath's next turn,\
    \ creatures have advantage on the saving throw for Ithu'rath's Devolving Tentacle\
    \ attack."
  "name": "Slimy Resistance (3/Day)"
- "desc": "Ithu'rath has advantage on saving throws against powers, spells, and other\
    \ supernatural effects."
  "name": "Supernatural Resistance"
"actions":
- "desc": "Ithu'rath makes six Devolving Tentacle attacks and uses Piscine Transformation."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 20 ft., one target. Hit: 16\
    \ (3d6 + 6) piercing damage. The first time a creature is hit with this attack\
    \ on a turn, they must succeed on a DC 19 Constitution saving throw or be injected\
    \ with a degenerative psionic slime (save ends at end of turn). While slimed,\
    \ each time the creature makes an attack roll or an ability check, they must roll\
    \ a d4 and subtract the number rolled from the d20 roll. At the end of a slimed\
    \ creature's turn, the size of the subtracted die increases by one: the d4 becomes\
    \ a d6, the d6 becomes a d8, and so on, to a maximum of d12. The cure\
    \ ailment power or [lesser restoration](Misc%20Files/CLI/compendium/spells/lesser-restoration-xphb.md)\
    \ spell also ends this effect."
  "name": "Devolving Tentacle"
- "desc": "Ithu'rath targets a creature with a head, legs, or torso they can see within\
    \ 60 feet of them, blasting them with a pulse of transformational energy. The\
    \ target must succeed on a DC 19 Wisdom saving throw or undergo one of the following\
    \ transformations of the Ithu'rath's choice:\n\n- Head. The target's head\
    \ transforms into the head of a fish, proportionately sized for their body. They\
    \ can't speak.  \n- Legs. The target's legs become fins. Their walking speed\
    \ is reduced to 10 feet (unless their walking speed is slower), and they gain\
    \ a swimming speed of 30 feet.  \n- Torso. The target's torso becomes the\
    \ body of a fish with gills. They can only breathe water and can hold their breath\
    \ for 1 hour. If the target isn't underwater when this transformation takes effect,\
    \ they begin suffocating.  \n\nThe transformation lasts until a cure ailment power\
    \ of 4th order or higher or the [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md)\
    \ spell affects the target. A target who suffers all three transformations at\
    \ once is permanently transformed into a hybrid fishlike creature and can only\
    \ be returned to their original form by a [wish](Misc%20Files/CLI/compendium/spells/wish-xphb.md)\
    \ spell or similar supernatural effects."
  "name": "Piscine Transformation (3rd-Order Power)"
"bonus_actions":
- "desc": "Ithu'rath teleports 30 feet to an unoccupied space they can see."
  "name": "Jaunt (3rd-Order Power)"
"reactions":
- "desc": "When a creature within 30 feet of Ithu'rath hits them with an attack, Ithu'rath\
    \ can psionically barrage that creature. That creature must succeed on a DC 19\
    \ Constitution saving throw or be pushed 5 feet away from Ithu'rath and be [restrained](Misc%20Files/CLI/rules/conditions.md#Restrained)\
    \ until the end of the creature's next turn, as their lower body temporarily melts\
    \ into an immovable goo."
  "name": "Liquefy (3rd-Order Power)"
"legendary_actions":
- "desc": "Ithu'rath has three villain actions. They can take each action once during\
    \ an encounter after an enemy's turn. They can take these actions in any order\
    \ but can use only one per round."
  "name": ""
- "desc": "Ithu'rath targets one or more creatures with a skeleton within 60 feet\
    \ of them, attempting to temporarily melt their ligaments. Each target must succeed\
    \ on a DC 19 Constitution saving throw or take 18 (4d8) necrotic damage and\
    \ have disadvantage on Strength- and Dexterity-based ability checks, attack rolls,\
    \ and saving throws for 1 minute (save ends at end of turn)."
  "name": "Action 1: Skeletal Collapse"
- "desc": "Ithu'rath channels a pulse of telekinetic energy to scour and harry their\
    \ foes. Each enemy within 60 feet of Ithu'rath must succeed on a DC 19 Strength\
    \ saving throw or take 18 (4d8) force damage and be moved up to 30 feet in any\
    \ direction."
  "name": "Action 2: Psychic Pulse"
- "desc": "Ithu'rath unleashes a cloud of transformative slime. Each creature within\
    \ 60 feet of Ithu'rath who isn't an olothec or a slime servant must make a DC\
    \ 19 Constitution saving throw. On a failed save, a target takes 45 (10d8) piercing\
    \ damage and is [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded) until\
    \ the end of their next turn as their eyes temporarily turn into insectoid feelers.\
    \ On a successful save, a target takes half as much damage and isn't [blinded](Misc%20Files/CLI/rules/conditions.md#Blinded)."
  "name": "Action 3: Slime Storm"
"source":
- "FleeMortals"
"image": "https://raw.githubusercontent.com/TheGiddyLimit/homebrew/master/_img/FleeMortals/token/Ithu%27rath.png"
```
^statblock