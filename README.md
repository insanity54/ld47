# GRID vs. Gaia Rulebook

A 2 player spell casting game made during Ludum Dare 47

Theme: Stuck in a loop

Stuck in a ... time loop?


## Lore

A great war between Magic and Science has broken out. Many low-level ESPers and mages are suddenly thrown into combat, but there's a problem. Nobody knows any spells with which to attack or defend! It is your job as either a soldier of science, or a mongering mage to destroy the enemy and preserve your faction's dogmatic way of life.


## Factions

### The Order of the GRID

  * Made up of ESPers who use advanced sciences to modify the world around them
  * Receives extra points for Metaphysics Blueprints incantations
  * Have an emphasis on electricity, light, and gravity

### Gaia Timeworn

  * Made up of Mages who use earthly magic to manipulate time and space
  * Receives extra points for Primordial Scrolls incantations
  * Have an emphasis on earth, wind, fire, air (etc)


## Game Contents

The game consists of

  * n Spell cards
  * n Word cards
  * n Chance cards
  * 2 Faction cards
  * 2 D20 dice
  * 1 D6 die

## Setup

  1. Create three stacks of shuffled cards. One each for **Spells**, **Words**, and **Chances**. (GAIA and GRID cards are shuffled together)
  2. Each player places a D20 near them which signifies the character's health. At the start of the game, each player has 16 health.
  3. Players randomly choose a faction by placing the two faction cards face down and each pointing to the card they want. Rock paper scissors settles any conflicts.
  4. Flip a coin to determine the player who goes first. The winner of the coin toss decides if they want to go first or second.
  5. Each player draws 5 cards from the **Words** stack, starting with the player who is going first.

## Game Board Layout

### Grimoire

The area which holds the three stacks of cards. **Spells**, **Words**, and **Chances**

### Hand

The cards that a player has in their possession

### Incantation Zone

The area in front of each player which holds the sequence of **Words** which have been uttered. Contains 8 numbered slots.

### Character Level Zone

The area to the right of each player which has 5 numbered card slots. The number of **Spell Cards** placed in these slots indicate player's power level.

## Win Condition

The player with the last standing character wins the game.

## Player Turn Flow

### 1. Discover

Your character's vocabulary expands as they explore the arena. The player draws one **Word** card.

### 2. Descry

Roll a 6 sided die to see if your character finds a **Science Metaphysics Blueprint** or **Magic Primordial Scroll** in the arena. If you roll a 4 or greater, draw a **Spell Card**.

### 3. Deliver

Spells can take many turns to cast. The player *may* place down one **Word Card** into their incantation zone to work towards a spell cast. **Word Cards** must be placed in the lowest numbered available **Incantation Zone** slot.

If a **Word Card** is placed which completes a spell in the player's hand, the spell is immediately cast. The effect listed on the **Spell Card** is carried out. See [Casting Spells](#casting-spells) for complete information.

### 4. Desist

The end of your turn is declared, at which point it becomes the other player's turn.

## Spells

Spells are uttered aloud over a series of turns as players cast them using word cards from their hand.

### Spell Classes

  * Damage
  * Mend
  * Utility
  * Wild
  * Eraser

Damage spells inflict damage upon the opponent. Mend spells repair damage to the character. Utility spells grant players extra cards. Wild spells have unknown effects until after they are casted. Eraser spells interfere with the opponent's spell casting.

A spell can belong to more than one class.

### Spell Cards

There are two **Spell Types,** each belonging to a **Faction**.

#### GRID Metaphysics Blueprint

A metaphysics blueprint is one of the **Spell Types** that characters can find in the arena. Blueprints have a modern appearance, blue color and contain the ordered **Words** which make up a **Spell Incantation**.

GRID Metaphysics Blueprints are most effective when used by Espers.

#### Gaia Primordial Scroll

These are aged paper scrolls which roll up and are kept together with string.

Gaia Primordial Scrolls are the other **Spell Type** that characters can find in the arena. It contains the ordered words which make up a **Spell Incantation**.

Most effective when used by mages.

### Cross-Faction Spell Usage

Each **Faction** has their own **Spell Card Type**, but a character from either faction can cast either **Spell Type**. To use a **Spell Type** from the opponent's faction to cast a **Spell** creates a **Contaminated Spell**, which is completely effective.

The side effect of **Cross-Faction Spell Usage** is that the **Contaminated Spell** does not level up the character.

## Words

Words are the building blocks of **Spells**. String **Word Cards** together in the **Incantation Zone** to successfully cast a **Spell**.

### Gaia Words

Mages prefer to use Gaia's word list to create **Pure Spells**. If a Mage casts a **Pure Spell**, the Mage will level up.

1. Absconditus
2. Aliquando
3. Castus
4. Cordeus
5. Dorime
6. Ergo
7. Ineundo
8. Pluo
9. Procedo
10. Proxy
11. Supra
12. Sylvius
13.	Tristis
14.	Varro
15.	Velius
16. Ventus

### GRID Words

Espers prefer to use GRID's word list to create **Pure Spells**. If an Esper casts a **Pure Spell**, the Esper will level up.


1. Catenary
2. Composite
3. Concave
4. Converge
5. Extremum
6. Matrix
7. Radian
8. Scalar
9. Sequence
10. Spheroid
11. Summation
12. Tau
13. Transpose
14. Variable
15. Uniform
16. Vector

### Cross-Faction Word Usage

Each **Faction** has 16 numbered **Words**. **GRID's** 8th word is functionally equivalent to **Gaia's** 8th word. This means that a player may substitute **Scalar** (GRID word #8) with **Pluo** (Gaia word #8) to complete a **Spell.**

There is nothing stopping a **Mage** from using a **GRID** word, or an **Esper** from using a **Gaia** word. To use a **Word** from the opponent's faction to cast a **Spell** creates a **Contaminated Spell**, which is completely effective.

The side effect of Cross-Faction Word Usage is that the **Contaminated Spell** does not level up the character.


## Combat

### Casting Spells

**Spells** are casted immediately when they have been completely uttered using **Word Cards** in the **Incantation Zone**.

The **Incantation Zone** is a loop, which means that a correctly ordered 4 word spell in Incantation Zone slots 7, 8, 1, and 2 is a valid spell.


Your character is only capable of casting spells listed in **Spell Cards** that you have in your **Hand**. Memorizing spells doesn't count!

You can place **Word Cards** into your **Incantation Zone** before you know what spell you are going to cast. You don't even need a **Spell Card** in your hand to place down a **Word Card**. This can be used for many purposes such as minimizing the amount of turns required to cast a spell when you eventually get a hold of a spell card. Delivering words can also be an opportunity for bluffing, by leading an opponent to believe that you are invoking a spell which you have no intention of completing.

### Pure Spells

**Pure Spells** are any spell which was cast using only words from the character's **Faction**.

### Contaminated Spells

**Contaminated Spells** are any spell which was cast using a mixture of **Gaia** and **GRID** words.

### Levelling Up

**Pure Spells** which are successfully cast level up your character by being placed in the **Character Level Zone** after the effects are carried out. **Contaminated Spells** do not level up your character, and are discarded after their effects are carried out.
