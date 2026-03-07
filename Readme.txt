Harry Potter Potions Knowledge Base

This is a naive implementation created in addition to the OpenCyc Knowledge Base that adds potions as they are understood from the Harry Potter universe.


Implemented Potions

There are five potions implemented:

- Cure Boils
- Polyjuice
- The Draught of Living Death
- Shrinking Solution
- The Draught of Peace


Potion Validity

We consider the steps and ingredients it takes to create each potion to determine if a potion is "valid", meaning that it should have its intended effect on its drinker.


Potion Effects

We also consider the state of the person drinking a "valid" potion.

(In the case that a person drinks an "invalid" potion, we assume no effect will take place.)

For each potion, we consider if a person must be in an altered state for the potion to have an effect.
Example: A person must have boils for the Cure Boils Potion to have an effect.


State Outcomes

If the person is not in the correct altered or unaltered state for a "valid" potion to have its effect, the person's state remains unchanged from their original state.

If the person is in the correct state and the potion is "valid", the intended effects of the potion will occur to its drinker.