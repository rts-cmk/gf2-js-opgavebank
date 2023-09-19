**Hvad er en JavaScript-funktion?**

En JavaScript-funktion er en blok af genanvendelig kode, der udfører en bestemt opgave eller handling. Funktioner er grundlæggende byggesten i programmering, da de giver dig mulighed for at organisere og strukturere din kode på en logisk måde. Forestil dig dem som små værktøjer eller opskrifter, som du kan kalde på, når du har brug for dem.

**Formålet med JavaScript-funktioner:**

Formålet med at bruge funktioner er flerfoldigt:

1. **Genbrugelighed:** Funktioner giver dig mulighed for at skrive en bestemt opgave én gang og bruge den igen og igen uden at skulle gentage koden. Dette reducerer fejl og gør din kode mere vedligeholdelig.

2. **Abstraktion:** Funktioner tillader dig at abstrahere komplekse opgaver bag en enkelt funktionssignatur. Dette gør din kode mere læsbar, da du kan kalde funktionen med en enkelt linje i stedet for at skulle forstå hele dens implementering.

3. **Opdeling af opgaver:** Ved at opdele din kode i mindre funktioner kan du håndtere komplekse problemer ved at tackle dem i mindre, mere håndterbare bidder. Dette gør det lettere at udvikle og fejlrette din kode.

**Sådan opretter du en JavaScript-funktion:**

For at oprette en funktion i JavaScript, skal du bruge følgende syntaks:

```javascript
function navnPåFunktion(parameter1, parameter2) {
  // Kode, der udfører opgaven
  // Du kan bruge parameter1 og parameter2 i koden
  return resultat; // Valgfrit: returner resultatet af opgaven
}
```

Her er en forklaring på hvert element:

- **function:** Dette er nøgleordet, der fortæller JavaScript, at du opretter en funktion.
- **navnPåFunktion:** Dette er navnet på din funktion. Det er, hvad du bruger til at kalde funktionen senere.
- **parameter1, parameter2:** Dette er input til din funktion. Du kan have nul eller flere parametre, og de er adskilt af kommaer.
- **{ ... }:** Alt koden, der skal udføre opgaven, går indeni disse krølleparenteser.
- **return:** Dette er valgfrit, men hvis du bruger det, returnerer det resultatet af din funktion til den del af din kode, der kaldte funktionen.

**Eksempel på brug af en funktion:**

Lad os sige, at vi vil oprette en funktion, der lægger to tal sammen og returnerer resultatet:

```javascript
function add(x, y) {
  let resultat = x + y;
  return resultat;
}

let sum = add(5, 3); // Kalder funktionen med 5 og 3 som argumenter
console.log(sum); // Udskriver 8 til konsollen
```

Her opretter vi funktionen `add`, der tager to parametre, `x` og `y`, lægger dem sammen og returnerer resultatet. Vi kalder derefter funktionen med værdierne 5 og 3 og gemmer resultatet i variablen `sum`.

Dette er en grundlæggende introduktion til JavaScript-funktioner, men de kan blive meget mere komplekse, når du begynder at arbejde med dem i dybden. Funktioner er en afgørende del af JavaScript og enhver anden programmeringssprog, da de hjælper dig med at organisere og strukturere din kode på en måde, der gør det lettere at udvikle, fejlrette og vedligeholde dine projekter.