---
icon: npc
NoteType: NPC
AssociatedGroup: Name of Guild or Group they belong to
Gender: Male or Female or...
Race: Human, Dwarf, Elf, etc
Age: How old are they?
Class: Warrior or Wizard or ...
Alignment: Lawful Good
Character-Role: Friend
Location: W?
---
> [!infobox]
> # `=this.file.name`
> ![[Darinor.jpg|cover hsmall]]
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

Viaja acompañado de dos caballos 🐴:
- Brisa 
- Lucas

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
