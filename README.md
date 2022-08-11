# Team72 code-challenge

Vi vill att du skapar en API-service som kan skapa och uppdatera matcher för esportsevent.

---
# Bakgrund och uppgift

En match består av två olika lag som möter varandra vid en viss tidpunkt på en given Arena.
En match kan ha flertalet speltyper som beskriver vad man kan spela på.  För den här uppgiften räcker det med att implementera speltypen "1x2" - vem vinner matchen.
Som oddssättare vill jag kunna lista alla aktuella matcher. Jag vill kunna se vilka speltyper som finns tillgängliga för matchen. Och jag vill kunna uppdatera oddsen för speltyperna.
En speltyp beskriver ett spel som finns tillgängligt för matchen. Speltyperna har oddsvärden kopplade till sina olika utfall.


- Du behöver inte skapa en databas för ändamålet.
- Du behöver inte tillverka alla api:er utan välj det du vill.
- Du behöver inte ha något GUI.
- Om du gör någon kod, ladda upp det på något publik Git-space.
- Om du inte skulle hinna med att göra uppgiften så skulle vi vilja hör hur du har tänkte lösa det.


---

# Krav
Match
- En match SKA ha en matchbeskrivning.
- En match SKA ha en starttid.
- En match SKA ha en definierad arena.
- En eller flera speltyper ska kunna kopplas till en match.
- En speltyp SKA ha en beskrivning.
- En speltyp SKA ha odds kopplat till varje utfall.

Oddssättare
- Som oddssättare vill jag kunna lista vilka kommande matcher som finns.
- Som oddssättare vill jag kunna skapa nya matcher.
- Som oddssättare vill jag kunna uppdatera matchens beskrivning.
- Som oddssättare vill jag kunna uppdatera matchens starttid.
- Som oddssättare vill jag kunna uppdatera matchens arena.
- Som oddssättare vill jag kunna lista speltyper som finns på matchen.
- Som oddssättare vill jag kunna lägga till speltyper på matchen.
- Som oddssättare vill jag kunna uppdatera odds på matchens speltyper.


---

<footer>

Du måste skriva tjänsten på http-servern kestrel.

Vilket stöd skulle du ge användaren av API'erna?

Tänk på att detta endast ska vara en enkel demo som vi kan använda som underlag vid intervjutillfället.
Vi är ett plattformsteam så man behöver inte ta fram en helt egen bet engine. Även om det är lite coolt.

---
