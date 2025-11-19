---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - ttrpg-cli/monster/cr/15
  - ttrpg-cli/monster/size/large
  - ttrpg-cli/monster/type/undead
statblock: inline
aliases:
  - Rageblight
---

```statblock
name: Vorak, the Rageblight
size: Large
type: Construct (Undead)
alignment: Chaotic Evil
ac: 18
hp: 150
hit_dice: 10d10 + 100
speed: 50 ft., climb 30 ft.
stats: [26, 16, 22, 14, 16, 10]
saves:
  Str: +13
  Con: +11
  Wis: +8
skills:
  Athletics: +13
  Intimidation: +10
  Perception: +8
  Stealth: +8
damage_resistances: "Cold, Fire, Lightning; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks"
damage_immunities: "Necrotic, Poison"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Poisoned"
senses: Darkvision 120 ft., Passive Perception 18
languages: Common, Elvish, Sibernyan (broken/muttered)
cr: 15
traits:
  - name: Reckless Engine
    desc: "At the start of his turn, Vorak can gain advantage on all melee weapon attack rolls during that turn, but attack rolls against him have advantage until the start of his next turn."
  - name: Magic Resistance
    desc: "Vorak has advantage on saving throws against spells and other magical effects."
  - name: "Phase 1: The Binding"
    desc: "He has resistance to all damage in this phase _unless_ a player successfully uses an Action on the Legacy Stone to 'Illuminate' him for one round, where he becomes vulnerable."
  - name: "Phase 2: Fractured Sigils"
    desc: "Vorak screams, shoving creatures within 30ft back 30ft (DC 18 Dex negates prone) and regaining 100hp. All Rage Pockets disperse. 4 **Sigils** appear. Vorak is **Immune to Damage** while 1+ Sigils remain."
  - name: "Phase 3: Shattered Identity"
    desc: "Vorak loses all Resistances and Immunities, and becomes **Vulnerable to Psychic Damage**. He gains the *Relentless Violence* trait (see Legendary Actions)."
actions:
  - name: Multiattack
    desc: "Vorak makes three attacks: two with his Greatsword and one with his Slam. Or he uses Unleash Fury if available."
  - name: Khyber Greatsword
    desc: "Melee Weapon Attack: +13 to hit, reach 10 ft., one target. Hit: 22 (4d6 + 8) slashing damage plus 9 (2d8) necrotic damage."
  - name: Slam
    desc: "Melee Weapon Attack: +13 to hit, reach 5 ft., one target. Hit: 17 (2d8 + 8) bludgeoning damage. Target must succeed on a DC 21 Strength save or be knocked prone."
  - name: Hurl Debris
    desc: "Ranged Weapon Attack: +13 to hit, range 60/240 ft., one target. Hit: 30 (4d10 + 8) bludgeoning damage."
  - name: Unleash Fury (Recharge 5-6)
    desc: "Vorak strikes the ground. Each creature within 10 ft must make a DC 19 Dexterity saving throw. On a failure, they take 45 (10d8) force damage, are pushed 10 ft back, and knocked prone. On a success, half damage and no push/prone."
bonus_actions:
  - name: Barbarous Leap
    desc: "Vorak jumps a distance equal to his speed toward a target without provoking opportunity attacks."
  - name: Rage Siphon (Phase 1 Only)
    desc: "Vorak consumes a nearby 'Rage Pocket' (Red Mist). He heals 11 (2d10) HP."
reactions:
  - name: Counter-Strike
    desc: "When a creature misses Vorak with a melee attack, Vorak can make one melee weapon attack against the creature."
  - name: Sigil Backlash (Phase 2 Only)
    desc: "When a Sigil is destroyed, Vorak can immediately move up to his speed and make one Greatsword attack."
legendary_actions:
  - name: Relentless Violence (Phase 3 Only)
    desc: "In Phase 3, Vorak can take 1 Legendary Action at the end of **each other creature's turn**."
  - name: Crush
    desc: "Vorak makes one Slam attack."
  - name: Mangling Step
    desc: "Vorak moves up to half his speed without provoking opportunity attacks. Any creature he moves through takes 10 necrotic damage."
lair_actions:
  - name: Rage Pockets (Phase 1 Only)
    desc: "At initiative count 20, a 10ft radius red mist spawns within 15ft of each PC. **Effect:** Moving/starting turn in mist deals 10 (3d6) psychic damage. The pockets move toward the PCs' last location at the start of rounds."
```