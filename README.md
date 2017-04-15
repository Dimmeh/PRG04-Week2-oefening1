# PRG04 week 2 Oefening 1

## Classes en instances

Een class in javascript ziet er als volgt uit:

```
class Car {
  constructor() {
    console.log("a car was created!");
    this.color = 'red';
    this.speed = 100;
  }

  drive() {
    console.log('I am driving at speed ', this.speed);
  }
}
```

### Opdracht

- Lees het javascript bestand goed door en zorg dat je begrijpt wat er gebeurt
- Maak meerdere instances van de Car class
- Geef elke instance zijn eigen kleur en snelheid
- Roep de drive en stop functies van de instances aan

### Opdracht

- Voeg zelf een eigenschap en een functie toe aan de car class en roep deze aan
- Geef de startwaarden van de instance door via de constructor, zodat je als volgt een instance kan aanmaken: 

`var c = new Car('red', 120);`

Test de code met de console
