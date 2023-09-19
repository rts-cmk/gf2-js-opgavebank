**Øvelse 1: Tjek alderen**

Opgave: Skriv en simpel betinget sætning, der tjekker om en person er gammel nok til at købe alkohol. Hvis personens alder er 18 år eller derover, skal du udskrive "Du kan købe alkohol", ellers udskrive "Du er for ung til at købe alkohol."

```javascript
var alder = 20;

if (alder >= 18) {
  console.log("Du kan købe alkohol.");
} else {
  console.log("Du er for ung til at købe alkohol.");
}
```

**Øvelse 2: Vurder et tal**

Opgave: Skriv en betinget sætning, der vurderer om et tal er positivt, negativt eller nul. Udskriv resultatet.

```javascript
var tal = -5;

if (tal > 0) {
  console.log("Tallet er positivt.");
} else if (tal < 0) {
  console.log("Tallet er negativt.");
} else {
  console.log("Tallet er nul.");
}
```

**Øvelse 3: Find det største tal**

Opgave: Skriv en betinget sætning, der finder det største af tre tal og udskriver det.

```javascript
var tal1 = 15;
var tal2 = 7;
var tal3 = 23;
var stoerste;

if (tal1 >= tal2 && tal1 >= tal3) {
  stoerste = tal1;
} else if (tal2 >= tal1 && tal2 >= tal3) {
  stoerste = tal2;
} else {
  stoerste = tal3;
}

console.log("Det største tal er: " + stoerste);
```

**Øvelse 4: Konvertering af dage til tekst**

Opgave: Skriv en switch/case-sætning, der tager et tal fra 1 til 7 som input (repræsenterende en dag i ugen) og returnerer den tilsvarende tekstlige repræsentation af dagen (f.eks. 1 til "mandag", 2 til "tirsdag", osv.). Hvis inputtet er uden for dette interval, skal det returnere "Ugyldig dag".

```javascript
var dagNummer = 3;
var dagTekst;

switch (dagNummer) {
  case 1:
    dagTekst = "mandag";
    break;
  case 2:
    dagTekst = "tirsdag";
    break;
  case 3:
    dagTekst = "onsdag";
    break;
  case 4:
    dagTekst = "torsdag";
    break;
  case 5:
    dagTekst = "fredag";
    break;
  case 6:
    dagTekst = "lørdag";
    break;
  case 7:
    dagTekst = "søndag";
    break;
  default:
    dagTekst = "Ugyldig dag";
}

console.log("Dag " + dagNummer + " svarer til " + dagTekst);
```