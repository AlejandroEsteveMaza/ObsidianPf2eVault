---
icon: npc
NoteType: NPC
IsHeraldo: "true"
AssociatedGroup: Name of Guild or Group they belong to
Gender: Masculino
Race: Humano
Age: 1000
Class: Huesped 
Alignment: True Neutral
Character-Role: Neutral
Location: 
---


> [!infobox]
> # `=this.file.name`
> ![[Txun_Shu_Zu.jpg|cover hsmall]]
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

Heraldo Arcano autor de “el arte de la guerra” vive aún en casa de su madre (zu zu como le llama cariñosamente ella) está trabajando en su siguiente y controversial obra de éxito “Haz el amor y no la guerra”

- “El arte de la guerra”: famoso libro sobre estrategia militar que se escribió hace porrón de siglos y sigue siendo válido a día de  hoy


Pistas: es el autor de un libro escrito hace siglos. Tiene copias de “el arte de la guerra” en un tipo de papel muy antiguo que ya no se fabrica (papiro).

Tiene textos en idiomas que ningún player es capaz de reconocer (son idiomas que murieron hace miles de años) antes de este evento que el grupo conozca a una bibliotecaria experta en textos antiguos (si el grupo se acuerda y le lleva una copia ella sabra que estos son textos antiguos)

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
