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

<font color="#f7f7f7"> Summarise the overarching adventure, outlining its main premise, goals, and the central conflicts or journey that drives it. </font>

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
<font color="#f7f7f7">Summarise the key events that occurred during the quest or a major story point.</font>

## Acts
### [[ ! Template - Quest ]]
#### Summary
<font color="#7f7f7f">Summarize the key events that occurred during the quest or a major story point.</font>

#### Outcomes
<font color="#7f7f7f">Summarise the outcomes of the quest or major story point, noting how it advances or resolves this adventure.</font>


### [[ ! Template - Quest]]
#### Summary
<font color="#7f7f7f">Summarize the key events that occurred during the quest or a major story point.</font>

#### Outcomes
<font color="#7f7f7f">Summarise the outcomes of the quest or major story point, noting how it advances or resolves this adventure.</font>

## Notes