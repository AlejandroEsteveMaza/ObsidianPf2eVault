


| ![[mapa_v1.jpg\|hsmall+wsmall+center]] | ![[ImagePlaceholder.jpg\|hsmall+wsmall+center]] | ![[ImagePlaceholder.jpg\|hsmall+wsmall+center]] | ![[ImagePlaceholder.jpg\|hsmall+wsmall+center]]            |
| -------------------------------------- | ----------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------- |
| [[Mapa del Mundo]]                     | [[Tablero de viaje.canvas\|Tablero de viaje]]   | [[Acto 1]]                                      | [[3. The Party/Nombre Aventura/Nombre Aventura\|El grupo]] |


# Notas modificadas recientemente
```dataview  
TABLE WITHOUT ID  
link(file.path, file.folder + " / " + file.name) AS "Note",  
file.mtime AS "Last modified"  
FROM "/"  
WHERE file.mtime >= date(today) - dur(30 days)  
AND file.name != this.file.name  
AND !contains(file.path, "z_Assets")  
AND !contains(file.path, "Inline Scripts")  
AND !contains(file.path, "z_Templates")  
AND !contains(file.path, "daily notes")  
AND !contains(file.path, "BRAT")  
SORT file.mtime DESC  
LIMIT 10  
```

# Diario de sesiones

```dataview
TABLE WITHOUT ID link(file.name) AS "Session Date", Status, players, OneLiner
from "4. Session Journals/Nombre Aventura"
where (type = "Session Journal")
SORT file.name DESC
```

# NPCs modificados recientemente
```dataview  
TABLE WITHOUT ID link(file.name) AS "NPC Name", Gender, Race, Age, Location, AssociatedGroup  
FROM "2. The World/NPCs"
WHERE (NoteType = "NPC") 
SORT file.mtime DESC
LIMIT 10
```

# Localizaciones modificadas recientemente
```dataview  
TABLE WITHOUT ID link(file.name) AS "Location Name", type, Government, Community-Size, size, population  
FROM "2. The World/Localizaciones"
WHERE (NoteType = "Localizacion")  
SORT file.mtime DESC
LIMIT 10
```