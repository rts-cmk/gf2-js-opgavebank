**Øvelse 1: Brug af `for`-loop til at udskrive tal**

Opgave: Brug en `for`-loop til at udskrive tal fra 1 til 5 i konsollen.

```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

**Øvelse 2: Brug af `while`-loop til at tælle ned**

Opgave: Brug en `while`-loop til at tælle ned fra 10 til 1 og udskrive tallene i konsollen.

```javascript
let tal = 10;
while (tal >= 1) {
  console.log(tal);
  tal--;
}
```

**Øvelse 3: Brug af `forEach` til at udskrive elementer i en liste**

Opgave: Opret en liste af farver og brug `forEach` til at udskrive hver farve i konsollen.

```javascript
let farver = ["rød", "blå", "grøn", "gul"];

farver.forEach(function (farve) {
  console.log(farve);
});
```