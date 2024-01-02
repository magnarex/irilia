---
alias: []
tags: [clan-oscuro]
---
```RpgManagerData
data: 
  synopsis: "Ciudad capital del Clan Obscuro. Se alza sobre un saliente en las montañas centrales de Irilia, en la cara oscura donde el sol no da nunca, y es por eso que siempre parece que esté sumida en un contante crepúsculo. Un monumental puente de oscuridad la comunica con la red de caminos de Irilia."
  complete: false
  address: 
relationships: 
  - type: "bidirectional"
    path: "NonPlayerCharacters/Chelen.md"
    description: 
  - type: "child"
    path: "Locations/Irilia/Clan Oscuro/La Nocturna/Barrio Alto/Barrio Alto.md"
    description: 
  - type: "child"
    path: "Locations/Irilia/Clan Oscuro/La Nocturna/Barrio de los Mercaderes/Barrio de los Mercaderes.md"
    description: 
  - type: "child"
    path: "Locations/Irilia/Clan Oscuro/La Nocturna/Barrio Bajo/Barrio Bajo.md"
    description: 
```
```RpgManager
models: 
  header: true
  lists: 
    pcs: 
    npcs: 
    events: 
    clues: 
    locations: 
      - relationship: "parent"
        title: "Inside"
      - relationship: "child"
        title: "Contains"
      - relationship: 
        title: "Related Locations"
```
---
### Location Details
 - Capital del [Clan Oscuro](../Clan%20Oscuro.md)
 - Está dividida en tres barrios:
	 - [Barrio Alto](Barrio%20Alto/Barrio%20Alto.md)
	 - [Barrio de los Mercaderes](Barrio%20de%20los%20Mercaderes/Barrio%20de%20los%20Mercaderes.md)
	 - [Barrio Bajo](Barrio%20Bajo/Barrio%20Bajo.md)

---
```RpgManagerID
### DO NOT EDIT MANUALLY IF NOT INSTRUCTED TO DO SO ###
type: 128
campaignSettings: 0
id: "ab5fc12b-4fc5-4a1a-9b6e-7aacb409209c"
campaignId: "de00bec5-aafa-43d1-9e8b-d8663d8eac5e"
parentId: "de00bec5-aafa-43d1-9e8b-d8663d8eac5e"
positionInParent: 0
```
[[Chelen|]]
[[Barrio Bajo|]]
[[Barrio Alto|]]
[[Barrio de los Mercaderes|]]
