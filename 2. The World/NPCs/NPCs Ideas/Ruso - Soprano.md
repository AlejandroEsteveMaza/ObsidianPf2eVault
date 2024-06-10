---
icon: npc
NoteType: NPC
AssociatedGroup: Name of Guild or Group they belong to
Gender: Male or Female or... 
Race: Human, Dwarf, Elf, etc
Age: How old are they?
Class: Warrior or Wizard or ... 
Alignment: Are they Chaotic Neutral or Lawful Neutral
Character-Role: Are they a friend or foe?
Location: What is the name of the place they live?
---

> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/ImagePlaceholder.jpg|cover hsmall]]
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

Los Soprano
Los protas lo matan y tienen que desahacerse del cadáver en un sitio lejano pero este escapa y resulta ser alguien de las fuerzas especiales.
Cuando los protas vuelven ya no estan sus caballos ¿se los ha llevadoe l ruso?

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
