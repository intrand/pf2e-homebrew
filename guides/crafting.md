<style>
body {
  background-color: #111111;
  color: #dddddd;
}

h1,h2,h3,h4,h5 {
    /* color: #ffffff; */
    color: lightgreen;
}

tbody tr:nth-child(odd){
    background-color: #4C8BF5;
    color: #fff;
}
tbody tr:nth-child(even){
    background-color: #111111;
    color: #cccccc;
}
</style>

# About

This will guide you through crafting an item in Pathfinder 2nd Edition. It's astounding that a guide is needed for this, but, until Paizo makes crafting better, this is what we have.

> Boxes like these contain text quoted from the official source(s).

# Requirements[^reqs]

> [Core Rulebook page 244](https://2e.aonprd.com/Actions.aspx?ID=43)

To Craft an item, you must meet the following requirements:

1. **The item is your level or lower**

    > An item that doesn't list a level is level 0.
    
2. **You must be proficient**

    > If the item is 9th level or higher, you must be a master in Crafting, and if it's 16th or higher, you must be legendary.

    | Item Level | Required Skill Proficiency[^skill] |
    | - | - |
    | 0-8 | Trained |
    | 9-15 | Master |
    | 16+ | Legendary |

3. **You may need the appropriate feat(s)**

    > You need the Alchemical Crafting skill feat to create alchemical items, the Magical Crafting skill feat to create magic items, and the Snare Crafting feat to create snares.

4. **You have the formula for the item**

    > You can gain access to the formulas for all common items in Chapter 6: Equipment by purchasing a basic crafter's book (page 287). See Formulas for information on how to acquire other formulas.

5. **You have an appropriate set of tools and, in many cases, a workshop**

    > For example, you need access to a smithy to forge a metal shield, or an alchemist's lab to produce alchemical items.

6. **You must supply raw materials worth at least half the item's Price**

    > You always expend at least that amount of raw materials when you Craft successfully. If you're in a settlement, you can usuallysend currency to get the amount of raw materials you need, except in the case of rarer precious materials.

7. **GM: Set the crafting DC**

    > [Core Rulebook page 503](https://2e.aonprd.com/Rules.aspx?ID=554)

    **This is based on item level, *not character level***.

    > Table 10-5: DCs by Level

    <!-- | Level | DC | &nbsp; | Level | DC | &nbsp; | Level | DC | -->
    | Level | DC | &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; | &nbsp; |
    | - | - | - | - | - | - | - | - |
    | **0** | *14* |
    | **1** | *15* | &nbsp; | **11** | *28* | &nbsp; | **21** | *42* |
    | **2** | *16* | &nbsp; | **12** | *30* | &nbsp; | **22** | *44* |
    | **3** | *18* | &nbsp; | **13** | *31* | &nbsp; | **23** | *46* |
    | **4** | *19* | &nbsp; | **14** | *32* | &nbsp; | **24** | *48* |
    | **5** | *20* | &nbsp; | **15** | *34* | &nbsp; | **25** | *50* |
    | **6** | *22* | &nbsp; | **16** | *35* |
    | **7** | *23* | &nbsp; | **17** | *36* |
    | **8** | *24* | &nbsp; | **18** | *38* |
    | **9** | *26* | &nbsp; | **19** | *39* |
    | **10** | *27* | &nbsp; | **20** | *40* |


8. **Modify the crafting DC based on rarity here**

    > [Core Rulebook page 503](https://2e.aonprd.com/Rules.aspx?ID=555)

    > Table 10-6: DC Adjustments

    | Difficulty | Adjustment | Rarity |
    | - | - | - |
    | Incredibly easy | -10 | - |
    | Very easy | -5 | - |
    | Easy | -2 | - |
    | Hard | +2 | Uncommon |
    | Very hard | +5 | Rare |
    | Incredibly hard | +10 | Unique |

9. **You must spend 4 days at work, at which point you attempt a Crafting[^skill] check.**

    > The GM determines the DC to Craft the item based on its level, rarity, and other circumstances.

    GM: DC is determined as above. Make any adjustments to the DC and establish the skill needed[^skill] to craft the item *before* the player rolls their skill check.

    > **Critical Success** Your attempt is successful. Each additional daysent Crafting reduces the materials needed to complete the item by an amount based on your level + 1 and your proficiency rank in Crafting.
    >
    > **Success** Your attempt is successful. Each additional daysent Crafting reduces the materials needed to complete the item by an amount based on your level and your proficiency rank.
    >
    > **Failure** You fail to complete the item. You can salvage the raw materials you supplied for their full value. If you want to try again, you must start over.
    >
    > **Critical Failure** You fail to complete the item. You ruin 10% of the raw materials you supplied, but you can salvage the rest. If you want to try again, you must start over.

10. **Reduce cost, if you choose**

    Use the table below to determine how much each extra day would reduce the cost of finishing the item. The longer you work, the cheaper the item is to craft.

    **Use *character level* and your proficiency in the appropriate skill[^skill] (usually Crafting)**

    > [Core Rulebook page 236](https://2e.aonprd.com/Actions.aspx?ID=23)

    > Table 4-2: Income Earned

    Level | DC | Failed | Trained | Expert | Master | Legendary |
    | - | - | - | - | - | - | - |
    | 0 | 14 | 1c | 5c | 5c | 5c | 5c |
    | 1 | 15 | 2c | 2s | 2s | 2s | 2s |
    | 2 | 16 | 4c | 3s | 3s | 3s | 3s |
    | 3 | 18 | 8c | 5s | 5s | 5s | 5s |
    | 4 | 19 | 1s | 7s | 8s | 8s | 8s |
    | 5 | 20 | 2s | 9s | 1g | 1g | 1g |
    | 6 | 22 | 3s | 1.5g | 2g | 2g | 2g |
    | 7 | 23 | 4s | 2g | 2.5g | 2.5g | 2.5g |
    | 8 | 24 | 5s | 2.5g | 3g | 3g | 3g |
    | 9 | 26 | 6s | 3g | 4g | 4g | 4g |
    | 10 | 27 | 7s | 4g | 5g | 6g | 6g |
    | 11 | 28 | 8s | 5g | 6g | 8g | 8g |
    | 12 | 30 | 9s | 6g | 8g | 10g | 10g |
    | 13 | 31 | 1g | 7g | 10g | 15g | 15g |
    | 14 | 32 | 1.5g | 8g | 15g | 20g | 20g |
    | 15 | 34 | 2g | 10g | 20g | 28g | 28g |
    | 16 | 35 | 2.5g | 13g | 25g | 36g | 40g |
    | 17 | 36 | 3g | 15g | 30g | 45g | 55g |
    | 18 | 38 | 4g | 20g | 45g | 70g | 90g |
    | 19 | 39 | 6g | 30g | 60g | 100g | 130g |
    | 20 | 40 | 8g | 40g | 75g | 150g | 200g |
    | 20 (critical success) | — | — | 50g | 90g | 175g | 300g |

    > **Critical Success** You do outstanding work. Gain the amount of currency listed for the task level + 1 and your proficiency rank.
    Success You do competent work. Gain the amount of currency listed for the task level and your proficiency rank.
    >
    > **Failure** You do shoddy work and get paid the bare minimum for your time. Gain the amount of currency listed in the failure column for the task level. The GM will likely reduce how long you can continue at the task.
    >
    > **Critical Failure** You earn nothing for your work and are fired immediately. You can’t continue at the task. Your reputation suffers, potentially making it difficult for you to find rewarding jobs in that community in the future.



[^reqs]: Feats such as [Craft Anything](https://2e.aonprd.com/Feats.aspx?ID=773) may allow you to change or bypass item crafting requirements.
[^skill]: Feats may change the skill required to craft an item, such as the [Medical Researcher](https://2e.aonprd.com/Feats.aspx?ID=2170) skill feat.
