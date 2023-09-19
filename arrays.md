**Øvelse 1: Opret en liste af navne**

Opgave: Opret en liste (array) af dine venners navne og gem den i en variabel. Udskriv derefter listen i konsollen.

```javascript
let venner = ["Anna", "Lars", "Maria", "Sofie"];
console.log(venner);
```

**Øvelse 2: Tilføj og fjern elementer fra en liste**

Opgave: Opret en liste af farver og gem den i en variabel. Tilføj en ny farve til listen og fjern en eksisterende farve. Udskriv den opdaterede liste i konsollen.

```javascript
let farver = ["rød", "blå", "grøn", "gul"];
farver.push("orange"); // Tilføj en farve
farver.splice(1, 1);   // Fjern den anden farve ("blå")
console.log(farver);
```

**Øvelse 3: Find elementer i en liste**

Opgave: Opret en liste af tal og gem den i en variabel. Find indekset af et bestemt tal i listen og udskriv det i konsollen.

```javascript
let talListe = [10, 20, 30, 40, 50];
let talletAtFinde = 30;
let indeks = talListe.indexOf(talletAtFinde);
console.log("Tallet " + talletAtFinde + " er på indeks " + indeks);
```

**Øvelse 4: Brug af `forEach` til at udskrive elementer**

Opgave: Opret en liste af dine yndlingsfrugter og brug `forEach` til at udskrive hver frugt i konsollen.

```javascript
let yndlingsfrugter = ["æble", "banan", "jordbær", "appelsin"];

yndlingsfrugter.forEach(function (frugt) {
  console.log(frugt);
});
```

**Øvelse 5: Fjern det sidste element med `pop`**

Opgave: Opret en liste af dage i ugen og brug `pop` til at fjerne den sidste dag. Udskriv den opdaterede liste i konsollen.

```javascript
let ugedage = ["mandag", "tirsdag", "onsdag", "torsdag", "fredag", "lørdag", "søndag"];

let sidsteDag = ugedage.pop();
console.log("Fjernede sidste dag:", sidsteDag);
console.log("Opdateret liste:", ugedage);
```

**Øvelse 6: Tjek om et element eksisterer med `includes`**

Opgave: Opret en liste af tal og brug `includes` til at tjekke, om et bestemt tal eksisterer i listen. Udskriv resultatet i konsollen.

```javascript
let talListe = [5, 10, 15, 20, 25, 30];
let talAtTjekke = 20;

if (talListe.includes(talAtTjekke)) {
  console.log(talAtTjekke + " findes i listen.");
} else {
  console.log(talAtTjekke + " findes ikke i listen.");
}
```
