---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/shapechanger
statblock: inline
aliases: ["Death Slaad"]
---
# [Death Slaad](Misc Files\CLI\compendium\bestiary\aberration/death-slaad.md)
*Source: Monster Manual p. 278*  

Death slaadi are suffused with energy from the Negative Energy Plane and exemplify evil's corruption of chaos, and they take sadistic pleasure in bringing harm to others. They propagate their race by dragooning mobs of red and blue slaadi and invading other planes. Humanoids who survive the incursion become incubators for new slaadi.

## Slaadi

In the Ever-Changing Chaos of Limbo, bits of forest and meadow, ruined castles, and isolated islands drift through a tumult of fire, water, earth, and wind. The foremost inhabitants of this inhospitable plane are the toad-like slaadi. Slaadi are undisciplined and have no formal hierarchy, although weaker slaadi obey stronger ones under threat of annihilation.

### The Spawning Stone

Long ago, Primus, overlord of the modrons, created a gigantic, geometrically complex stone imbued with the power of law. He then cast it adrift in Limbo, believing that the stone would bring order to the chaos of that plane and halt the spread of chaos to other planes. As the stone's power grew, it became possible for creatures with ordered minds, such as modrons and githzerai, to create enclaves in Limbo. However, Primus's creation had an unforeseen side effect: the chaotic energy absorbed by the stone spawned the horrors that came to be known as slaadi. Sages refer to Primus's massive creation as the Spawning Stone for this reason.

The slaadi wiped out every last modron enclave in Limbo. As creatures of utter chaos, slaadi loathe modrons and attack them on sight. Nonetheless, Primus stands by his creation and either doesn't perceive the slaadi as threats or chooses to ignore them.

### Birth and Transformation

Slaadi have horrific cycles of reproduction. Slaadi reproduce either by implanting humanoid hosts with eggs or by infecting them with a transformative disease called chaos phage. Each color of slaad reproduces or transforms in a different way, with red slaadi spawning blue and green slaadi, and blue slaadi spawning red and green. Each green slaad undergoes a lifelong cycle of transformation into the more powerful gray and death slaadi. With each transformation, the slaad retains its memories.

### Shapechangers

Some slaadi can transform into the humanoid creatures from which they were originally spawned. These slaadi return to the Material Plane to sow discord in the guise of their former selves.

> [!note] Variant: Slaad Control Gems
> 
> As a slaad emerges from the Spawning Stone, the stone magically implants a fragment of itself in the slaad's brain. This fragment takes the form of a magic gem roughly the size and shape of a human child's fist. The gem is the same color as the slaad. Another creature can use magic to draw forth a slaad's gem and use it to subjugate the slaad. The slaad must obey whoever possesses its gem. If a slaad's gem is destroyed, the slaad can no longer be controlled in this way.
> 
> A slaad born from something other than the Spawning Stone has no gem in its brain, but it gains one if it ever comes into contact with the Spawning Stone. Slaadi on Limbo are attracted to the Spawning Stone, so most end up with a gem. A slaad with a control gem in its brain has the following additional trait.
> 
> **Control Gem.** Implanted in the slaad's brain is a magic control gem. The slaad must obey whoever possesses the gem and is immune to being [charmed](Misc%20Files/CLI/rules/conditions.md#Charmed) while so controlled.
> 
> Certain spells can be used to acquire the gem. If the slaad fails its saving throw against imprisonment, the spell can transfer the gem to the spellcaster's open hand, instead of imprisoning the slaad. A [wish](Misc%20Files/CLI/compendium/spells/wish-xphb.md) spell, if cast in the slaad's presence, can be worded to acquire the gem.
> 
> A [greater restoration](Misc%20Files/CLI/compendium/spells/greater-restoration-xphb.md) spell cast on the slaad destroys the gem without harming the slaad.
> 
> Someone who is proficient in Wisdom ([Medicine](Misc%20Files/CLI/rules/skills.md#Medicine)) can remove the gem from an [incapacitated](Misc%20Files/CLI/rules/conditions.md#Incapacitated) slaad. Each try requires 1 minute of uninterrupted work and a successful DC 20 Wisdom ([Medicine](Misc%20Files/CLI/rules/skills.md#Medicine)) check. Each failed attempt deals 22 (`4d10`) psychic damage to the slaad.
^variant-slaad-control-gems

> [!quote]  
> 
> Embedded in a slaad's brain is a magic gem. Acquire it, and the slaad is yours to command.


```statblock
"name": "Death Slaad"
"size": "Medium"
"type": "aberration"
"subtype": "shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"stats":
- !!int "20"
- !!int "15"
- !!int "19"
- !!int "15"
- !!int "10"
- !!int "16"
"speed": "30 ft."
"skillsaves":
  "Perception": !!int "8"
  "Arcana": !!int "6"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "blindsight 60 ft., darkvision 60 ft., passive Perception 18"
"languages": "Slaad, telepathy 60 ft."
"cr": "10"
"traits":
- "desc": "The slaad's innate spellcasting ability is Charisma (spell save DC 15,\
    \ +7 to hit with spell attacks). The slaad can innately cast the following spells,\
    \ requiring no material components:\n\nAt will: [detect magic](Misc%20Files/CLI/compendium/spells/detect-magic-xphb.md),\
    \ [detect thoughts](Misc%20Files/CLI/compendium/spells/detect-thoughts-xphb.md),\
    \ [invisibility](Misc%20Files/CLI/compendium/spells/invisibility-xphb.md) (self\
    \ only), [mage hand](Misc%20Files/CLI/compendium/spells/mage-hand-xphb.md), [major\
    \ image](Misc%20Files/CLI/compendium/spells/major-image-xphb.md)\n\n1/day each:\
    \ [cloudkill](Misc%20Files/CLI/compendium/spells/cloudkill-xphb.md), [plane shift](Misc%20Files/CLI/compendium/spells/plane-shift-xphb.md)\n\
    \n2/day each: [fear](Misc%20Files/CLI/compendium/spells/fear-xphb.md), [fireball](Misc%20Files/CLI/compendium/spells/fireball-xphb.md),\
    \ [fly](Misc%20Files/CLI/compendium/spells/fly-xphb.md), [tongues](Misc%20Files/CLI/compendium/spells/tongues-xphb.md)"
  "name": "Innate Spellcasting"
- "desc": "The slaad can use its action to polymorph into a Small or Medium humanoid,\
    \ or back into its true form. Its statistics, other than its size, are the same\
    \ in each form. Any equipment it is wearing or carrying isn't transformed. It\
    \ reverts to its true form if it dies."
  "name": "Shapechanger"
- "desc": "The slaad has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "The slaad's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "The slaad regains 10 hit points at the start of its turn if it has at least\
    \ 1 hit point."
  "name": "Regeneration"
"actions":
- "desc": "The slaad makes three attacks: one with its bite and two with its claws\
    \ or greatsword."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 9 (1d8\
    \ + 5) piercing damage plus 7 (2d6) necrotic damage."
  "name": "Bite (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 10\
    \ (1d10 + 5) slashing damage plus 7 (2d6) necrotic damage."
  "name": "Claws (Slaad Form Only)"
- "desc": "Melee Weapon Attack: +9 to hit, reach 5 ft., one target. Hit: 12\
    \ (2d6 + 5) slashing damage plus 7 (2d6) necrotic damage."
  "name": "Greatsword"
"source":
- "MM"
"image": "Misc%20Files/CLI/compendium/bestiary/aberration/token/death-slaad.webp"
```
^statblock