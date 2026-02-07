---
tags:
  - "#Adventure"
aliases:
whichParty:
completed: false
summary:
---

> [!grid | col-2 ]
> **Assigned Party:** `VIEW[{whichParty}][link]`
>
> **Status:** `INPUT[toggle:completed]`

<font color="#f7f7f7"> Scaffold at Dawn opens in 591 CY in [[Chendl]], a city trying to project strength while fear and factional ambition boil underneath. The player characters gather - each with their own connection to a condemned acquaintance - just as they are publicly executed for alleged collaboration with [[luz]]. The execution is mean to be a warning... and a political spectacle.

But the condemned was framed.

The party's immediate goal becomes personal and urgent: prove the acquaintance was innocent, expose who manufactured the accusation, and prevent the lie from hardening into "official truth". This investigation quickly pulls them into [[Chendl]]'s competing power blocs - knightly authorities, civic and noble interests, and hidden actors who thrive on panic - while the city's leaderships accelerates extraordinary "security" measures in response to the supposed threat.

As the PC's chase evidence before it's destroyed, they uncover the first threads of a larger conflict: a clandestine struggle over a city-defence initiative (the foundations of a coming "shield for [[Chendl]] and the shadowed influence of a feared figure known as [[Prince Thrommel | The Black Knight]]. What begins as a fight to clear one person's name becomes a race to stop [[Chendl]]'s defence - and its people - from being turned into weapons by those who benefit from terror, scapegoats and control.</font>

## Overview
### Quick References
> [!grid | col-3 ]
>> **Characters**
>> ```dataview
>> LIST
>> FROM outgoing([[]])
>> WHERE econtains(tags,"Character")
>> SORT file.name ASC
>> ```
>
>> **Locations**
>> ```dataview
>> LIST
>> FROM outgoing([[]])
>> WHERE econtains(tags,"Location")
>> SORT file.name ASC
>> ```
>
>> **Organisations**
>> ```dataview
>> LIST
>> FROM outgoing([[]])
>> WHERE econtains(tags,"Organisation")
>> SORT file.name ASC
>> ```

### Plot
- **A public execution ignites the story.**  
    At dawn in a crowded [[Chendl]] square, the PCs witness the execution of a person they all knew—condemned as an agent of **[[Iuz]]**. The scene is staged as civic theatre: banners, proclamations, and a crowd encouraged to treat fear as patriotism.
    
- **The condemned’s last moments reveal cracks in the story.**  
    In final words (or a final gesture), the NPC signals they were **framed** and drops a fragment of a lead—an offhand name, a coded phrase, or reference to a moved object tied to the city’s security.
    
- **An attempt is made to erase even that.**  
    Someone in the crowd (a planted “witness,” assassin, or agitator) tries to **silence** the NPC early or disrupt the moment—proving there are parties with urgent reasons to control the narrative and destroy loose ends.
    
- **The party converges and chooses a side.**  
    In the immediate aftermath—at a wake, tavern backroom, or private meeting—each PC’s personal connection to the condemned becomes the glue that binds them. They agree to act together, not as hired hands, but as people refusing to let [[Chendl]]’s justice be weaponized.
    
- **A first ally offers direction—and complications.**  
    A faction-linked NPC (often a knightly agent or principled insider) approaches with a deal: help uncover the truth, and they’ll provide resources, introductions, and protection—while also pulling the PCs into the city’s internal struggle over who controls “security.”
    
- **Evidence is hunted before it can be destroyed.**  
    The PCs race to secure tangible proof: a forged seal, a ledger page, a courier log, or a concealed message. This typically leads to a **break-in, chase, or skirmish** at a records office, warehouse, or safehouse.
    
- **The conspirators push back—fast and dirty.**  
    Hired muscle, corrupt watchmen, or faction enforcers try to intimidate, bribe, or kill witnesses. The PCs realize this isn’t a misunderstanding—it’s a coordinated frame job with institutional cover.
    
- **The larger threat is seeded: “the shield” and the [[Prince Thrommel |Black Knight]].**  
    The recovered clue points beyond the execution to a bigger plot: a covert **defence initiative** meant to protect [[Chendl]] (and a missing “keystone” component tied to it), and the ominous presence of **[[Prince Thrommel |the Black Knight]]**, glimpsed as a watcher, symbol, or whispered name—setting the direction for Act I.

## Acts
### [[The Scaffold at Dawn - Act 1]]
#### Summary
The PCs converge in the execution square to witness the public death of someone they all knew

#### Outcomes
- The party has a shared inciting trauma and motive.
    
- They gain a **first lead** (a phrase, token, name, or dropped item).
    
- They identify that someone is actively **controlling the narrative** (an early silencing attempt or planted witness).

### [[The Scaffold at Dawn - Act 2]]
#### Summary
In the execution’s aftermath (wake/tavern backroom/temple steps), the PCs share what they saw, compare personal connections to the condemned, and decide whether they’ll act—despite the risks of opposing “official justice.”

#### Outcomes
- The PCs formally **band together** with a clear purpose.
    
- They establish a **code** (what lines they won’t cross, what they’ll risk).
    
- They gain a **named ally or contact** (someone who believes the frame job is real).

### [[The Scaffold at Dawn - Act 3]]
#### Summary
The PCs race to recover a piece of evidence before it’s destroyed—records, manifests, a confession seal, or a courier log—leading to a stealthy break-in, chase, or quick fight.

#### Outcomes
- They secure **tangible proof of forgery** or procedural manipulation.
    
- They earn their first enemies: the people who sent muscle to erase evidence.
    
- They get a **map pin** (warehouse, ledger office, courier station) for the next quest.

### [[The Scaffold at Dawn - Act 4]]
#### Summary
The PCs track the “witness” or assassin connected to the execution-day manipulation. This is the first time they can put hands on the frame job’s _human machinery_.

#### Outcomes
- They learn **who paid** (directly or via intermediaries).
    
- They uncover a **faction signature** (a seal, phrase, symbol, coinage) tying the conspiracy to city politics.
    
- They gain either a prisoner, confession, or hard clue pointing toward a bigger operation.

### [[The Scaffold at Dawn - Act 5]]
#### Summary
Following the paper trail (or the captured lead), the PCs find where “the real story” was moved: a warehouse cache, transferred crate, or hidden strongbox—something connected to a broader security effort.
#### Outcomes
- They discover the plot isn’t just a frame job; it’s about **control of Chendl’s defenses**.
    
- They obtain the next-stage clue: reference to a missing **keystone component** (“Pearl” / focus gem / core).
    
- They trigger attention from a higher-tier antagonist.

### [[The Scaffold at Dawn - Act 6]]
#### Summary
A figure, symbol, or event makes the **Black Knight** feel real: a watcher in dark mail, a calling-card, or the aftermath of a precise removal.

#### Outcomes
- The campaign’s Act I antagonist force is established as _present_ in Chendl.
    
- The PCs realize their opposition isn’t only political—it’s **mythic and methodical**.
    
- Hook into Act I: the defense project can be **stolen, twisted, or weaponized**.

## Notes
By the end of these quests, the PCs should have:

- A bonded purpose: **clear the executed NPC’s name** (or prove the truth publicly).
    
- A concrete direction: pursue the **missing keystone** tied to Chendl’s defense.
    
- A living pressure: factions now see them as assets, threats, or pawns.
    
- A looming adversary: **the Black Knight** is on the board.