---
icon: npc
NoteType: NPC
AssociatedGroup: Name of Guild or Group they belong to
Gender: Female
Race: Human, Elf
Age: How old are they?
Class: Warrior or Wizard or ... 
Alignment: Are they Chaotic Neutral or Lawful Neutral
Character-Role: Are they a friend or foe?
Location: What is the name of the place they live?
---

> [!infobox]
> # `=this.file.name`
> ![[Vesperio.jpg|cover hsmall]]
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

**Vesperio** → Huésped Primal Aliatham  es una especie de vagamundo viajero manipulador encubierto.

- Guardián de los Bosques Antiguos →  nombre de leyendas
- Envía  plaga a Egipto con el objetivo de que los romanos abran la muralla y crucen la frontera para poder estar cerca del emperador y conseguir su poder

Intenciones: convencer a la party de que mate al emperador para asi liberar su energia

Pistas: 

- te engaña, te manda a robar algo a alguna casa, que en realidad es la suya y alli la party encuentra notas de loco escritas por él donde narra el Aliatham (discurso epoca oscuriodad). Quiere que te enteres de las cosas pero sin decirtelas directamente, juega con la gente
- TIene una compresion superior al hablar con animales, mas potente que hechizo de hablar con animales
- te ofrece comida que no es autoctona de la region (como si pudiera hacer crecer naranjos en el desierto)
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
