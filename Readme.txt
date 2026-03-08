Harry Potter Potions Knowledge Base

/////////////////////////////////////////////////
@Authors: Vincent Yang, Claire Metcalf, Victoria Ng, Faith Do 
@Date: March 8th 
@Description: 
This is a naive implementation created in addition to the OpenCyc Knowledge Base that adds potions as they are understood from the Harry Potter universe.
/////////////////////////////////////////////////

----------------------------------------------------- 
Implemented Potions and Methodology Reasoning: 
-----------------------------------------------------

There are five potions implemented:

1. Cure Boils                    - Cures the boils of the drinker 
2. Polyjuice                     - Allows you to transform into the hair of whatever person you put into the potion 
3. The Draught of Living Death   - Puts you into a deep deep slumber 
4. Shrinking Solution            - Ages you younger (effectively shrinking you)
5. The Draught of Peace          - Gives the drinker an emmense sense of peace 

The reasoning behind choosing these potions mainly comes from the avaible sources we can find on how to make these potions, 
as the individual steps to making these potions are quite complex and involve 
a variety of steps and procedures. 

Additionally individual ingredients may have certain reactions if specific actions are performed on it (for example if you heat procupine quills it results in an explosion)

We also want to consdier that it is possible to fail to make potions, which can result form 1. not haing all the ingredients or 2. processing ingredients in the wrong steps. 
For the scope of this project and due to limited time, we will only focus on the first, however we will make some headway into encoding the latter. 

This leads us to potion effects, which will tell us if a potion will have the desired effect on the drinker, depending on the state of the drinker. 

----------------------------------------------------- 
HOW TO RUN 
-----------------------------------------------------
1. Upload a total of 8 files (
    1. cureboilPotionrules.krf 
    2. draughtofLivingDeathPotionRules.krf
    3. draughtofPeacePotionrules.krf
    4. ingredients_rules.krf
    5. PolyjuicePotionrules.krf 
    6. potion_rules.krf 
    7. shrinkingPotionrules.krf. 
    8. shrinkingPotionruleskrf. 
    )