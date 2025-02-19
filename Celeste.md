
```statblock
creature: Celeste
name: Celeste
layout: Basic 5e Layout
dice: true
render: true

image: [[celeste_portrait.png]]
type: Human
alignment: neutral good
cr: 5
size: medium
ac: 11
hp: 32
speed: 30
stats: [9, 10, 11, 10, 14, 14]
saves:
  - strength: -1
  - dexterity: 0
skillsaves:
  - persuasion: 5
  - arcana: 3
  - insight: 5
senses: "passive perception 10"
traits:
  - name: Skills
    desc: Persuasion, Arcana, Insight
  - name: Tools
    desc: Weaver's Tools, Herbalism Kits
languages: Common, Dwarvish

traits:
  - name: "Resourceful"
    desc: "You gain Heroic Inspiration whenever you finish a long rest."
  - name: "Lucky"
    desc: "You have a number of Luck Points equal to your proficiency bonus. You can expend 1 to give yourself advantage on a d20 test or give someone else disadvantage on an attack roll against you. You regain your Luck Points with a Long Rest."
  - name: "Prepared Spells"
    desc: "9"
  - name: "Witch's Familiar"
    desc: "it's a goat"
  - name: "Witchcraft Tokens"
    desc: "The minor results of a witch's craft - potions, salves, one-use charms, and favors - are commonly called tokens, and any given witch can expect to make countless numbers of them in their lifetime. Once created, a creature holding the token can cast the spell from it using your spell save DC, spell attack bonus, and spellcasting ability. If the spell requires Concentration, the creature must concentrate. The token then loses its magical properties, becoming a mundane item of its kind. You can maintain a number of active tokens equal to your proficiency bonus."
  - name: "Retributive Curses"
    desc: "A creature becomes a target for retribution when it transgresses against you in one of the following ways: Harm, Threat, Betrayal. Harm - The creature attacks or deals damage to you, your familiar, or a creature holding a token or talisman you created. Threat - The creature forces you to make a saving throw. Betrayal - The creature intentionally breaks a promise to you."
  - name: "Witchcraft Talismans"
    desc: "When you put your back into your craft and devote a little part of yourself to what you're making, you can weave your magic into a talisman that will last forever. Any Witch spell that doesn't require a costly Material component can be crafted into a talisman if you have an unexpected spell slot of a high enough level to cast it (you need not have the spell prepared). A creature holding the talisman can cast that spell from it, using your spell save DC, spell attack bonish, and spell casting ability. Once the talisman is used to cast its spell, it can't be used that way again until the next dawn."
  - name: "Heart's Gift"
    desc: "When you cast Spare the Dying or a spell that restores Hit Points to a creature, you can expend a number of Hit Point Dice up to your Proficiency Bonus to roll an equal number of d6s and add the total to your Hit Points one target of your spell regains."

spells:
  - Cantrips (at will, known): Cackle, Chill Touch, Guidance, Mending
  - Cantrips (at will, coven): Prestidigitation, Spare the Dying
  - 1st Level (coven): Healing Word, Sanctuary
  - 2nd Level (coven): Calm Emotions, Warding Bond
  - 3rd Level (coven): Mass Healing Word, Revivify

actions:
  - name: "Dagger Attack"
    desc: "+3 to hit, 6 (1d4 + 3) piercing damage"
  - name: "Cast Spell"
    desc: "+5 to hit, DC 13 spell save"
  - name: "Create Witchcraft Token"
    desc: "During short or long rest, use any Level 1 spell that targets one or more creatures to craft a token. You must have an unexpected spell slot and make a DC 10 + the spell's level. Once per rest."

bonus_actions:
  - name: "Curse of the Heartless"
    desc: "As a Bonus Action, you can curse a creature within 60 feet of you for 1 hour. For the duration, whenever the creature deals damage, you can rull 1d6 and reduce the damate it deals to one target by that amount. You reduce the damage by 2d6 if the target is Undead or a Fiend. Once you reduce damage in this way, you can't do so again until the start of your next turn. You can use this feature twice. You regain one expended use when you finish a Short Rest, and regain all expended uses when you finish a Long Rest."

reactions:
  - name: "Retributive Curse"
    desc: "As a reaction when a creature within 60ft of you commits such a transgression, you can place one of the following curses on it: Bloodguilt, Leaden Shoes, Uncanny Jinx, Vengeful Gleam. Bloodguilt - The first time on a turn that the target deals damage to another creature, it takes Psychic damage equal to 1d6 + your proficiency bonus. Leaden Shoes - The target's movement speed is reduced to 5 feet and it can't make Opportunity Attacks. Uncanny Jinx - Whenever the target makes a D20 Test, it must subtract 1d4 from the total. Vengeful Gleam - The target glows with a green witch-light that sheds Dim Light in a 5-foot radius. It can't benefit from the Invisible condition, and attacks against it have Advantage if the attacker can see it. The curse lasts for 1 minute. It ends early if the cursed creature dies, you apply a different Curse to the creature, or you choose to end the curse as an action. You can use this feature twice, and regain unexpended uses when you finish a Short or Long rest. If you or your allies initiated a fight with the creature, it can make a Charisma saving throw against your spell save DC. On a successful save, the curse has no effect buy you don't expend a use of this feature."
  - name: "Create Talisman"
    desc: "To craft a talisman, you must spend 24 hours of labor (this time need not be continuous) and make a DC 20 Wisdom check using Artisan's Tools. On a success, you permanently sacrifice a spell slot of the spell's level to complete the talisman."
  - name: "Use Talisman"
    desc: "As an action while you can see a talisman, you can recover the sacrificed spell slot. The talisman ceases to be a magic item, and you regain that spell slot the next time you finish a Long Rest. Similarly, if the talisman is destroyed, you regain the spell slow when you finish your next Long Rest."
```

# Prepared Spells

1. 1 - Bane
2. 1 - Command
3. 1 - Witch's Grasp
4. 1 - Inflict Wounds
5. 2 - Detect Thoughts
6. 2 - Invisibility
7. 2 - Lesser Restoration
8. 2 - Tongue Tie
9. 3 - Spellwarping Curse

# Tokens

1. Sleep
2. Disguise Self
3. Shield