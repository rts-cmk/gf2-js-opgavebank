1. **Undgå uendelige løkker:** Hvis du ikke har en betingelse, der kan blive falsk, vil din løkke køre uendeligt, hvilket kan føre til, at din applikation fryser eller browseren ikke reagerer. Dette kaldes en uendelig løkke, og det er en af de mest almindelige fejl i programmering.

2. **Kontrol over løkkens varighed:** Løkker bruges normalt til at gentage en bestemt handling et begrænset antal gange eller indtil en bestemt betingelse er opfyldt. Ved at have en betingelse, der kan blive falsk, har du kontrol over, hvor mange gange løkken gentages. Dette er afgørende for at undgå overdreven brug af systemressourcer og for at opretholde programydelse.

3. **Sikkerhed:** Uendelige løkker kan føre til programkrasch og ubehagelige brugeroplevelser. At have en betingelse, der på et tidspunkt bliver falsk, giver en sikkerhedsfunktion, der beskytter mod uventet og uønsket opførsel.

4. **Logik og klarhed:** En betingelse i en løkke gør koden mere forståelig for andre udviklere, der læser din kode. De kan hurtigt forstå, hvad løkken er beregnet til, og hvornår den skal stoppe.

Lad mig give dig et eksempel på, hvorfor en betingelse er nødvendig. Forestil dig, at du ønsker at udskrive tal fra 1 til 10 ved hjælp af en løkke. Uden en betingelse, der bliver falsk, ville det se sådan ud:

```javascript
while (true) {
  console.log("Dette vil køre uendeligt!");
}
```

Dette ville skabe en uendelig løkke, der aldrig stopper, og din kode ville aldrig gå videre til noget andet. Ved at bruge en betingelse kan du bestemme, hvornår løkken skal afsluttes:

```javascript
let i = 1;

while (i <= 10) {
  console.log(i);
  i++;
}
```

Her er betingelsen `i <= 10` afgørende for at stoppe løkken, når `i` når værdien 11.

Så husk altid at have en betingelse, der på et tidspunkt bliver falsk, når du arbejder med løkker. Det er en grundlæggende og vigtig regel for at undgå uendelige løkker og sikre, at din kode kører korrekt og effektivt.