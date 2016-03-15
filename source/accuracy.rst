Accuracy
========

To understand how combat works in Pillars of Eternity it’s important to understand Accuracy. Whenever an offensive ability is used by a party member or an enemy it will target one of four Defenses: Deflection, Fortitude, Reflex or Will. Melee weapons target Deflection; physical attacks (such as Knockbacks but also Poisons) typically target Fortitude; Area of Effect abilities target Reflexes and “spiritual” abilities (like Paralyze, fear-inducing abilities and many Ciphers powers) target Will.

Regardless of the targeted Defense, the same calculation is always computed:

((Attacker Accuracy) – (Defender Defense)) + random(1,100).

In words, this means that the attacker’s Accuracy is subtracted to the appropriate defender’s Defense, then a random number between 1 and 100 is rolled. The final score determines the kind of hit: Miss, Graze, Hit or Critical Hit.

* 0-15 is a Miss (no damage done, or spell is resisted)
* 16-50 is a Graze (50% is done, and lasting effects’ duration is halved as well)
* 51-100 is a Hit (normal damage and effect duration)
* 101+ is a Critical Hit (150% damage and effect duration)

It’s therefore quite important to not neglect Accuracy as it plays a big (but not the only) part of the overall damage output. If a character keeps Missing or Grazing, its damage output will be low (which may or may not matter depending on its purpose).

Examples
^^^^^^^^

Let’s give an example with an attacker of an Accuracy of 50 targeting a defender with a Deflection of 50 as well. In that case, the attacker has a 15% miss chance, 35 of graze, 50% to hit and 0% to critically hit.

((accuracy: 50) – (deflection: 50) = 0
(random(0-100)) = 0-100
Total = 0-100

15% chance to be between 1 and 15, 35% chance to be between 16 and 50, 50% of chance to be between 51 and 100. Even if the attacker rolls a 100, since the added remainder is 0, the total will still be 100, so the attack cannot critically hit.

Now if the attacker has got 100 Accuracy, things change a lot:

100 – 10 = 50
random(0-100) = 0-100
Total = 50-150

This is a 0% chance to miss or graze, a 50% chance to Hit and 50% chance to Critically Hit.

It’s therefore important to keep one rule in mind: the larger the difference between the attacker’s Accuracy and the defender’s Defense, the bigger the damage output of the attacker. In the course of the game this means boosting the player-controlled characters Accuracy has much as possible while decreasing the enemies’ Defenses as much as possible.

Boosting Accuracy
^^^^^^^^^^^^^^^^^

Perception is an attribute that increases the character’s Accuracy (`“Natural Accuracy”`) by 1 for each point above 10 that is allocated in it. This means that a character with 20 Perception will benefit of 10 points of Accuracy. Decreasing Perception has the exact same effect (-1 Natural Accuracy per point below 10).

Another way to increase Accuracy is by the way of Weapon Enchantments:
* Fine and “Accurate 1” will provide 5 Accuracy
* Exceptional and “Accurate 2” will provide 15 Accuracy
* Superb and “Accurate 3” provides 30 Accuracy
* Legendary provides 45 Accuracy
* Mythic provides 55 Accuracy

It’s important to note that enchantments are only available to Weapons. It’s not possible to enchant Spells and unarmed weapons (like a monk’s Fists).

Spell casters (and monks?) have options. Spells typically come with an Accuracy bonus to the targeted Defense. This varies from spell to spell, and is never has high as Superb-enchanted or above weapons. This is probably for balancing reasons: a spell is usually more impactful than a weapon attack so it’s not a bad thing that they benefit from less Accuracy.

Monks first get accuracy bonuses as they level up (check this).

Another way to boost Accuracy is through Buff spells. : 

* Priests
    ** Blessing (rank 1) : Allies +5 Accuracy, +10% Damage for 20 sec
    ** Devotions for the Faithful (rank 4) : Allies +4 Might, +20 Melee Accuracy, +20 Ranged Accuracy for 30 sec
    ** Champion's Boon (rank 5) : Single targeted ally gains +10 Might, +10 Perception, +5 Damage Reduction for 30 sec (the Perception part of this buff increases Accuracy by 30)
    ** Crowns for the Faithful (rank 6) : Allies +6 Perception, +25 Resolve, +6 Intellect for 30 sec
    ** Minor Avatar (rank 7) : Self +20% Melee Damage, +20% Ranged Damage, +8 Might, +8 Dexterity, +8 Constitution, +8 Perception, +40 Max Endurance, +8 Resolve, +8 Intellect for 30 sec
* Wizards
    ** Something something (rank 1) : Increase Caster's Accuracy by 10 (?)
    ** (complete the list)
* More classes

Some Talents also provide an Accuracy bonus. (link to something else here probably?)

Finally, some items provide an Accuracy bonus. Sometimes it’s very wide and benefits all type of attacks. In some cases the effect explicitly list what kind of attacks the effect will benefit (for instance Unarmed Damage or Ranged Weapons only).

Decreasing anemies Accuracy
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Priests
    ** Despondent Blows (rank 3) : Enemies -15 Melee Accuracy, +15% Crits converted to Hits for 30 sec

Stacking Accuracy
^^^^^^^^^^^^^^^^^

There are rules for stacking accuracy. For instance, it's not possible to get an Accuracy bonus from two different spells (the spell providing the highest of the two bonuses suppresses the other one). Here's a list of all the possible ways to stack Accuracy

* Perception (provides the Natural Bonus)
* Weapon Enchantments (in the case of two weapon fighting, each Weapon has got a different Accuracy score)
* Buffing spell or modal effect, but only one. For instance, a Paladin Aura (being a considered as a spell by the game) will not stack with any Spell providing a strictly Accuracy bonus. It ``will`` stack if the spell provides a more specific bonus (for instance only to Ranged Weapons). It must just not be described as simply "Accuracy."
* Item effects. Similarly to spells, only the item providing the highest Accuracy bonus will be taken into account - others will be Supressed. Again as with the spells, if the actual effect description is different, then the Accuracy will add up.
* Talents. Some talents provide an Accuracy bonus, to a specific situation (a specific group of weapons in the case of Weapon Specializations, a special kind of weapons in the case of Marskman, etc.)
* Racial bonuses. For instance, a Wood Elf has a +4 Accuracy bonus to enemies more than 4 meters away.
 
