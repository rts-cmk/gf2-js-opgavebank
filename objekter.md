**Øvelse 1: Opret et simpelt objekt med egenskaber**

Opgave: Opret et simpelt JavaScript-objekt kaldet `person`, der repræsenterer en person med navn, alder og by. Udskriv objektet i konsollen.

```javascript
let person = {
  navn: "Maria",
  alder: 25,
  by: "København"
};

console.log(person);
```

**Øvelse 2: Tilføj og opdater egenskaber i et objekt**

Opgave: Opret et objekt, der repræsenterer en bil med egenskaberne `mærke`, `model` og `år`. Tilføj og opdater egenskaberne i objektet, og udskriv det i konsollen.

```javascript
let bil = {
  mærke: "Toyota",
  model: "Camry",
  år: 2020
};

bil.model = "Corolla"; // Opdater model
bil.farve = "blå";     // Tilføj en ny egenskab

console.log(bil);
```

**Øvelse 3: Brug af objekter som opslag (lookup)**

Opgave: Opret et objekt, der indeholder priserne på forskellige varer i en butik. Lav en funktion, der tager en vare som input og returnerer prisen på den vare fra objektet. Udskriv prisen på en vare ved at kalde funktionen.

```javascript
let butiksPriser = {
  æble: 5,
  banan: 3,
  appelsin: 4,
  pære: 6
};

function findPris(vare) {
  return butiksPriser[vare];
}

let vareNavn = "banan";
let pris = findPris(vareNavn);
console.log("Prisen på " + vareNavn + " er " + pris + " kroner.");
```