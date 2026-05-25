---
tags:
  - Character
  - Player
art: "[[PlaceholderCharacter.png]]"
playedBy: Kim
aliases:
titles:
ancestry: Human
heritage:
gender: Female
pronouns: She/Her
sexuality:
languages:
  - Common
  - Common Sign Language
  - Orc
occupation:
affiliations: "[[Temple of Heironeous]]"
religions: "[[Heironeous]]"
condition:
  - Healthy
located: "[[Chendl]]"
whichParty: party1
fc-date:
  year: "[-*]"
birthday: -28
year:
age: 25
---

> [!infobox | no-blending black]+ <font color="#ffffff">Infobox</font>
> 
> `VIEW[!{art}][text(renderMarkdown)]`
> 
> ### <font color="#d8d8d8">Played By:</font> <font color="#ffc000">`VIEW[playedBy]`</font>
> 
> # Profile
> | | |
> |---|---|
> | **Aliases** | `VIEW[{aliases}][text]` |
> | **Titles** | `VIEW[{titles}][text]` |
> | **Ancestry** | `VIEW[{ancestry}][link]` |
> | **Heritage** | `VIEW[{heritage}][link]` |
> | **Gender** | `VIEW[{gender}]` _(`VIEW[{pronouns}]`)_ |
> | **Sexuality** | `VIEW[{sexuality}]` |
> | **Age** | `VIEW[floor(({Vault Hub#time}-{birthday})/{Vault Hub#dpy})][:age]` yrs |
> 
> # Information
> | | |
> |---|---|
> | **Languages** | `VIEW[{languages}][link]` |
> | **Occupations** | `VIEW[{occupation}][text]` |
> | **Affiliations** | `VIEW[{affiliations}][link]` |
> | **Religions** | `VIEW[{religions}][link]` |
> | **Condition** | `VIEW[{condition}]` |
> | **Located** | `VIEW[{located}][link]` |

~~~meta-bind-button
label: Insert Pronounced
style: primary
action:
  type: replaceSelf
  templater: true
  replacement: "z_Templates/Markdown/Template Inserts/Template - Pronounced.md"
~~~

> [!poem|directory]- Directory
> ![[Database - Character Manager.base]]

<font color="#7f7f7f">A short overview that introduces who this Character and what makes them unique.</font>

## Description
### Appearance
<font color="#7f7f7f">What does this character look like?</font>
- **Build**
	- <font color="#7f7f7f">Details</font>
- **Features**
	- <font color="#7f7f7f">Details</font>

## Aspects
### Ideals
<font color="#7f7f7f">What is this characters's core beliefes?</font>
- **Loves**
	- <font color="#7f7f7f">Details</font>
- **Hates**
	- <font color="#7f7f7f">Details</font>

### Traits
<font color="#7f7f7f">What are this character’s defining behaviors?</font>
- **Perks**
	- <font color="#7f7f7f">Details</font>
- **Flaws**
	- <font color="#7f7f7f">Details</font>

## Current
### Motivations
<font color="#7f7f7f">What drives this character’s actions and decisions?</font>
- **Short-Term**
	- <font color="#7f7f7f">Details</font>
- **Long-Term**
	- <font color="#7f7f7f">Details</font>

### Worship
<font color="#7f7f7f">Does this character follow a god, faith, or belief system, and why?</font>
- <font color="#7f7f7f">TBD</font>
	- <font color="#7f7f7f">Details</font>

### Relationships
<font color="#7f7f7f">Who does this character know or what factions are they connected to? What are their relationship like and how did the meet?</font>
- <font color="#7f7f7f">TBD</font>, _Debt Owed_
	- <font color="#7f7f7f">Details</font>
- <font color="#7f7f7f">TBD</font>, _Mother_
	- <font color="#7f7f7f">Details</font>
- <font color="#7f7f7f">TBD</font>, _Father_
	- <font color="#7f7f7f">Details</font>

## Lore
### Birth
**Birth Location:** <font color="#5f497a">Example Link</font>

**Day** `INPUT[inlineSelect(option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20), option(21), option(22), option(23), option(24), option(25), option(26), option(27), option(28)):fc-date.day]` **Month** `INPUT[inlineSelect(option(1, Aurora),option(2, Novus), option(3, Iter), option(4, Florera), option(5, Tersus), option(6, Solis), option(7, Calor), option(8, Caelum), option(9, Visus), option(10, Messis), option(11, Cedrus), option(12, Tornu), option(13, Parago)):fc-date.month]` **Year** `INPUT[number(class(nb-mb-55)):year]` `VIEW[\[{year}-*\]][text(hidden):fc-date.year]` `VIEW[{Vault Hub#dpy}*{year}+{Vault Hub#dpm}*({fc-date.month}-1)+{fc-date.day}][math(hidden):birthday]`

### Childhood
<font color="#7f7f7f">What happened during this character's childhood?</font>
- <font color="#7f7f7f">TBD</font>
	- <font color="#7f7f7f">Details</font>

### Chapter #1
<font color="#7f7f7f">What happened during this chapter of this character's life?</font>
- <font color="#7f7f7f">TBD</font>
	- <font color="#7f7f7f">Details</font>

## Notes
<font color="#7f7f7f">If you player doesn't use Obsidian and needs help creating their character, feel free to send them this handout. It will then keep their formatting close to yours:</font>
[Player Handout](https://docs.google.com/document/d/1_eFTuK3teRJSAVbd2QSZxjDTgE_RZH54zZg-3Eoo4Hk/edit?usp=sharing)

