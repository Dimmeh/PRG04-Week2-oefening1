# PRG04 week 2 Oefening 1

## Classes en instances

Een class in javascript ziet er als volgt uit:

```
class Car {
  constructor() {
    console.log("a car was created!");
    this.speed;
  }

  drive() {
    console.log('I am driving at speed ', this.speed);
  }
}
```

### Opdracht

- Test het project met de console
- Maak meerdere instances van de Car class
- Geef de class eigenschappen voor kleur en snelheid
- Geef elke instance zijn eigen kleur en snelheid

### Opdracht

- Voeg een stop functie toe die de speed van de auto op 0 zet
- Voeg een drive functie toe waarmee je een nieuwe snelheid kan meegeven als parameter
- Roep de functies aan

### Opdracht

- Geef de startwaarden van de instance door via de constructor, zodat je als volgt een instance kan aanmaken: 

`var c = new Car('red', 120);`
