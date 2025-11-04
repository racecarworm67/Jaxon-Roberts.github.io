# Projects

## Case Study: Redesigning Sundered Sky
**From a "Mandatory Tax" to a Strategic Teamfight Item**

---

### 1. The Problem: Sundered Sky's Design Conflict
As a Diamond 2 peak player, I identified a core design conflict with the item Sundered Sky. It exists in a problematic state that is both unhealthy for build diversity and unsatisfying to use long-term.

The item's identity is split, leading to four major flaws:

    The "Dueling Tax": The combination of a 175% AD crit and a significant missing-health heal is so powerful in 1v1s that it becomes a must-buy ASAP for most bruisers. This stifles build diversity and makes early-game skirmishes a simple stat-check of who has the item and who doesn't. I feel that other items should be options for bruisers whose goals are to impact the game through their classes' design goals in fights, being primary engage tools and wreaking havoc with damage, disruption, and utility on the enemy team. Sundered Sky currently has no place outside of the first 15-20 minutes of the game and does not fulfill the intention of the bruiser class.

    The "Scaling Trap": While dominant early, the item's value scales terribly. In late-game 5v5s, the self-heal is often too small to matter before you are bursted down, and the single-target damage is less valuable than team-wide utility. For example, a Xin Zhao who dashes in and isolates the enemy Caitlyn will be able to get a Sundered Sky proc off, but will still likely be bursted down through said heal. Other bruiser items like Sterak’s Gage and Death’s Dance guarantee Xin Zhao’s disruption for longer, but he is forced to build into Sundered Sky in its current state.

    The "Selfish Slot": Bruisers are often the team's primary initiators. Committing a full item slot to a purely "selfish" 1v1 item feels counter-intuitive to the role's late-game objective, which is to soak damage, disrupt, and enable carries. Other current bruiser items like Black Cleaver and Sterak’s Gage allow champions to either provide extra support to their carries or be alive longer during fights to ensure their carries are able to deal more damage. Sundered Sky in its current state provides none of that.

    The "Binary Counter": The item's entire defensive value is tied to healing. This makes it extremely vulnerable to an 800 gold Grievous Wounds component, making its power unreliable and frustrating. Bruisers as a class are designed to have high uptime in fights; building a lot of Ability Haste and Health allow champions to get multiple rotations of spells off. However, when the entirety of a legendary item’s worth is counterable by an epic item, yet the item is currently required to be built every game, there must be an inherent design flaw in said item.


### 2. The Design Goals
Based on this analysis, my goal was to redesign the item to solve these problems. The new design must:

    Break 1v1 Dominance: Intentionally weaken the item in isolated duels to remove its "mandatory buy" status.

    Create a Teamfight Identity: Shift its power from 1v1 skirmishing to 5v5 teamfight initiation. I still wanted it to have power in the early game, but I didn’t want it to be a “must-buy or lose” type of item.

    Reward Proactive Skill: The item's reward should be controlled by the user and scale based on their ability to find a good engagement.

    Improve Reliability: Remove the "Grievous Wounds" counterplay and provide a consistent, understandable defensive reward. Although Serpent’s Fang does exist, having the sole function of the item be countered by an equally matched legendary item feels more comfortable for its new power level.


### 3. The Proposal: "Aspect's Aegis"
To achieve these goals, I propose replacing Sundered Sky with a new item that rewards a player's courage and fulfills the "initiator" fantasy. The name is inspired by the celestial Aspects of Targon, who face overwhelming odds.

    Aspect's Aegis

    Stats: 450 Health, 55 AD, 20 Ability Haste

    Passive - Unbreakable Will: On first basic attack against an enemy champion, gain a shield for 100-300 (scales with level 1-18) for 3 seconds.

    This shield is increased by 50% for each other enemy champion (within 800 units) present when the effect triggers. (12-second cooldown).


### 4. Technical Prototype & Code
To prove the concept, I built a simple Java calculator to model the shield's scaling. This allows for rapid iteration and balancing.

[View the 'AegisCalculator' Java prototype on GitHub](https://github.com/jaxon-roberts/AegisCalculator)



# TFT Target Selection Simulator
* **What it is:** A Java app that simulates how AI units select targets on a battlefield.
* **Core Concept:** Uses a `PriorityQueue` to manage a list of potential attackers. This ensures that the highest-priority unit (like a 5-cost carry) gets to attack a "Target Dummy" as soon as it's free. This is a direct prototype of AI task-scheduling and resource management in a game engine.
* **[View the `TFT-Target-Simulator` on GitHub](https://github.com/racecarworm67/TFT-Target-Simulator)**


#2. TFT Shop & Champion Pool Simulator
* **What it is:** A Java backend that models the entire *Teamfight Tactics* champion pool and shop-rolling logic.
* **Core Concept:** An Object-Oriented system that "deals" champions from a "shuffled" pool. This project demonstrates how OOP, data structures, and secure randomization are used to build a core gameplay system.
* **[View the `TFT-Shop-Simulator` on GitHub](https://github.com/racecarworm67/TFT-Shop-Simulator)**
