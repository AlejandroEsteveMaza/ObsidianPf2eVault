---
icon: npc
NoteType: NPC
alias: Lift
IsHeraldo: "true"
AssociatedGroup: Name of Guild or Group they belong to
Gender: Female 
Race: Elf
Age: 10
Class: Druid
Alignment: Neutral Good
Character-Role: Friend
Location: -
---

> [!infobox]
> # `=this.file.name`
> ![[lift.jpg|cover hsmall]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Home | `=this.Location` |
> Group | `=this.AssociatedGroup` |
> Sex | `=this.gender` |
> Race | `=this.race` |
> Age | `=this.age` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Alignment | `=this.alignment` |
> Class | `=this.class` |
> Character Role | `=this.character-role` |

# `=this.file.name`
## Perfil

druida convencida que es un animal que puede transformarse en persona.
Muy cachonda.

---
> [!info] Statblock
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> ```

```encounter-table
name: Individual
creatures:
 - 1: Commoner
```
