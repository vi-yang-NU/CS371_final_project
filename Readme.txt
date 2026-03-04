This is a naive implementation created in addition to the OpenCyc Knowledge Base that adds potions as they are understood from the Harry Potter Universe.

There are five potions implemented: Cure Boils, Polyjuice, The Draught of Living Death, Shrinking Solution, and The Draught of Peace.
We consider the steps and ingredients it takes to create each potion to determine if a potion is "valid", meaning that it should have its intended effect on its drinker.
We also consider the state of the person drinking a "valid" potion. (In the case that a person drinks an "invalid" potion, we assume no effect will take place.)
    For each potion, we consider if a person must be in an altered state for the potion to have an effect (i.e. a person must have boils for the Cure Boils Potion to have an effect.) 
        If they are not in the correct altered or unaltered state for a "valid" potion to have its effect, the person's state is unchanged from their original state.
        If they are in the correct state and the potion is "valid", the intended effects of the potion will occur to its drinker.