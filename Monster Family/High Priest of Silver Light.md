```statblock
layout: Basic 5e Layout
source: MTW
name: High Priest of Silver Light
size: Medium
type: Humanoid
alignment: Chaotic Evil
ac: 14
hp: 52
hit_dice: 8d8+16
stats: [10,14,14,13,17,15]
saves:
  - WIS: 5
  - CHA: 4
skillsaves:
  - Deception: 4
  - Intimidation: 4
senses: Passive Perception 13
languages: Common, Undercommon, Abyssal
traits:
  - name: Fey Ancestry
    desc: "The High Priest has advantage on saving throws against being charmed, and magic can't put him to sleep."
  - name: Spellcasting
    desc: "The High Priest is a 5th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 15, +7 to hit with spell attacks). He has the following cleric spells prepared:\n- Cantrips (at will): guidance, sacred flame, thaumaturgy\n- 1st level (4 slots): bane, command, guiding bolt\n- 2nd level (3 slots): hold person, inflict wounds\n- 3rd level (2 slots): bestow curse, vampiric touch"
  - name: Sunlight Sensitivity
    desc: "While in sunlight, the High Priest has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight."
spells:
  - "The High Priest is a 5th-level spellcaster. His spellcasting ability is Wisdom (spell save DC 15, +7 to hit with spell attacks)."
  - "> [!info] Cantrips (At Will)"
  - "> Guidance: _Divination Cantrip_ | **Casting Time:** Action | **Components:** V, S | **Range:** Touch | **Duration:** [Concentration](https://5e.tools/conditionsdiseases.html#concentration_xphb), up to 1 minute\n>>You touch a willing creature and choose a skill. Until the spell ends, the creature adds 2 (1d4) to any ability check using the chosen skill."
  - "> **Sacred Flame**: _Evocation Cantrip_ | **Casting Time:** Action | **Components:** V, S | **Range:** 60 feet | **Duration:** Instantaneous\n>> Flame-like radiance descends on a creature that you can see within range. The target must succeed on a Dexterity saving throw or take 1d8 Radiant damage. The target gains no benefit from Half [Cover](https://5e.tools/variantrules.html#cover_xphb) or Three-Quarters [Cover](https://5e.tools/variantrules.html#cover_xphb) for this save.\n Cantrip Upgrade. The damage increases by 1d8 when you reach levels 5 (2d8), 11 (3d8), and 17 (4d8)."
  - "> **Thaumaturgy**: _Transmutation Cantrip_ | **Casting Time:** Action | **Components:** V | **Range:** 30 feet | **Duration:** 1 minute\n>> You manifest a minor wonder within range. You create one of the effects below within range. If you cast this spell multiple times, you can have up to three of its 1-minute effects active at a time.\n>> - Altered Eyes. You alter the appearance of your eyes for 1 minute.\n>> - Booming Voice. Your voice booms up to three times as loud as normal for 1 minute. For the duration, you have [Advantage](https://5e.tools/variantrules.html#advantage_xphb) on Charisma (Intimidation) checks.\n>> - Fire Play. You cause flames to flicker, brighten, dim, or change color for 1 minute.\n>> - Invisible Hand. You instantaneously cause an unlocked door or window to fly open or slam shut.\n>> - Phantom Sound. You create an instantaneous sound that originates from a point of your choice within range, such as a rumble of thunder, the cry of a raven, or ominous whispers.\n>> - Tremors. You cause harmless tremors in the ground for 1 minute."
  - "> [!info] Level 2 (3 Slots)"
  - "> **Hold Person**: _Level 2 Enchantment_ | **Casting Time:** Action | **Components:** V, S, M (a straight piece of iron) | **Range:** 60 feet | **Duration:** [Concentration](https://5e.tools/conditionsdiseases.html#concentration_xphb), up to 1 minute\n>> Choose a Humanoid that you can see within range. The target must succeed on a Wisdom saving throw or have the [Paralyzed](https://5e.tools/conditionsdiseases.html#paralyzed_xphb) condition for the duration. At the end of each of its turns, the target repeats the save, ending the spell on itself on a success.\n>> Using a Higher-Level Spell Slot. You can target one additional Humanoid for each spell slot level above 2."
  - "> **Inflict Wounds**: _Level 1 Necromancy_ | **Casting Time:** Action | **Components:** V, S | **Range:** Touch | **Duration:** Instantaneous\n>> A creature you touch makes a Constitution saving throw, taking 2d10 Necrotic damage on a failed save or half as much damage on a successful one.\n>> Using a Higher-Level Spell Slot. The damage increases by 1d10 for each spell slot level above 1."
  - "> [!info] Level 3 (2 Slots)"
  - "> **Bestow Curse**: **Casting Time:** Action | **Components:** V, S | **Range:** Touch | **Duration:** [Concentration](https://5e.tools/conditionsdiseases.html#concentration_xphb), up to 1 minute\n>> You touch a creature, which must succeed on a Wisdom saving throw or become cursed for the duration. Until the curse ends, the target suffers one of the following effects of your choice:\n>> - Choose one ability. The target has [Disadvantage](https://5e.tools/variantrules.html#disadvantage_xphb) on ability checks and saving throws made with that ability.\n>> - The target has [Disadvantage](https://5e.tools/variantrules.html#disadvantage_xphb) on attack rolls against you.\n>> - In combat, the target must succeed on a Wisdom saving throw at the start of each of its turns or be forced to take the [Dodge](https://5e.tools/actions.html#dodge_xphb) action on that turn.\n>> - If you deal damage to the target with an attack roll or a spell, the target takes an extra 1d8 Necrotic damage."
  - "**Vampiric Touch**: _Level 3 Necromancy_ | **Casting Time:** Action | **Components:** V, S | **Range:** Self | **Duration:** [Concentration](https://5e.tools/conditionsdiseases.html#concentration_xphb), up to 1 minute\n>> The touch of your shadow-wreathed hand can siphon life force from others to heal your wounds. Make a melee spell attack against one creature within reach. On a hit, the target takes 3d6 Necrotic damage, and you regain [Hit Points](https://5e.tools/variantrules.html#hit%20points_xphb) equal to half the amount of Necrotic damage dealt.\n>> Until the spell ends, you can make the attack again on each of your turns as a [Magic](https://5e.tools/actions.html#magic_xphb) action, targeting the same creature or a different one.\n>> Using a Higher-Level Spell Slot. The damage increases by 1d6 for each spell slot level above 3."
actions:
  - name: Multiattack
    desc: The High Priest makes two melee attacks.
  - name: Dagger
    desc: "_Melee Weapon Attack:_ +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage."
```