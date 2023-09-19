**Øvelse 1: Beregn gennemsnittet**

Opgave: Skriv en funktion, der tager en liste af tal som input og returnerer gennemsnittet af tallene.

```javascript
function beregnGennemsnit(talListe) {
  let sum = 0;
  for (let i = 0; i < talListe.length; i++) {
    sum += talListe[i];
  }
  let gennemsnit = sum / talListe.length;
  return gennemsnit;
}

// Eksempel på brug:
let tal = [10, 20, 30, 40, 50];
let gennemsnitResultat = beregnGennemsnit(tal);
console.log("Gennemsnit:", gennemsnitResultat);
```

**Øvelse 2: Omregning af temperatur**

Opgave: Skriv en funktion, der konverterer temperaturer mellem Celsius og Fahrenheit. Brug formlen: Fahrenheit = (Celsius * 9/5) + 32.

```javascript
function celsiusTilFahrenheit(celsius) {
  let fahrenheit = (celsius * 9/5) + 32;
  return fahrenheit;
}

function fahrenheitTilCelsius(fahrenheit) {
  let celsius = (fahrenheit - 32) * 5/9;
  return celsius;
}

// Eksempel på brug:
let celsiusTemp = 25;
let fahrenheitResultat = celsiusTilFahrenheit(celsiusTemp);
console.log(celsiusTemp + " grader Celsius svarer til " + fahrenheitResultat + " grader Fahrenheit.");

let fahrenheitTemp = 68;
let celsiusResultat = fahrenheitTilCelsius(fahrenheitTemp);
console.log(fahrenheitTemp + " grader Fahrenheit svarer til " + celsiusResultat + " grader Celsius.");
```

**Øvelse 3: Find det største tal**

Opgave: Skriv en funktion, der tager en liste af tal som input og returnerer det største tal i listen.

```javascript
function findStoersteTal(talListe) {
  let stoerste = talListe[0];
  for (let i = 1; i < talListe.length; i++) {
    if (talListe[i] > stoerste) {
      stoerste = talListe[i];
    }
  }
  return stoerste;
}

// Eksempel på brug:
let tal = [12, 5, 8, 23, 17];
let stoersteTal = findStoersteTal(tal);
console.log("Det største tal i listen er: " + stoersteTal);
```