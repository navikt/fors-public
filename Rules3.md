## Velkommen til kodeoppgave 3 – en slags Yatzy!

## Om oppgaven
* Du kan benytte hvilket programmeringsspråk eller programvare du vil.
* Når du møter til intervju så vil vi at du kan demonstrere kjørbar kode.
* Oppgaven skal være dokumentert på en måte som gjør at vi forstår hva som skal til for å kjøre den.
* Om det er noe du gjerne skulle gjort, men ikke fikk tid til, vær så snill og fortell om det i README. Da kan gi deg noen plusspoeng for det likevel!
* Du bør uansett lage en README som forteller hvordan koden skal kjørs på en enklest mulig måte.


## Regler (1)
* Du skal lage et spill som simulerer en enkel variant av Yatzy
* Datamaskinen spiller selv, uten input fra noe menneske
* Spillet bruker 5 terninger
* Spillet skal ha en eller flere strategier for å få så mange poeng som mulig
* Det spilles om poeng i 6 kategorier, som angir hver sin verdi på terningen: Enere, toere, treere, firere, femmere og seksere
    * Det kastes en runde pr kategori, men strategien velger selv hvilken rekkefølge kategoriene tas i
    * Hver runde består av inntil tre kast
    * Etter et kast kan man spare på en eller flere terninger, og dermed kun kaste 5 - antall sparte terninger
    * Etter   et kast man man velge å ta inn terninger man har spart på i tidligere kast
* Terninger kastes ved å kalle et endepunkt
    * Endepunktet finner du her: http://nav-yatzy.herokuapp.com/throw
    * Endepunktet tar en parameter n som representerer antall terninger
    * Endepunktet vil returnere n verdier
    * Eksempel: http://nav-yatzy.herokuapp.com/throw?n=5

## Regler (2)
* Etter en runde skal en av kategoriene fylles ut med en poengsum
* Poengsummen for en kategori er verdien av terningen * antall terninger med denne verdien
    * Dersom du ikke fyller ut en poengsum, strykes en ledig kategori ved å sette den til 0
* Skriv ut poengsum og antall poeng pr kategori (sortert fra 1-6) ved spillets slutt
* Eksempel:
 ``` {
   "scorecard": {
     "1": 2,
     "2": 4,
     "3": 9,
     "4": 16,
     "5": 20,
     "6": 18
   },
   "total": 69
 }```

## Levering
* Oppgaven bør leveres i form av en URL til et versjonskontrollert repository, f.eks. https://github.com eller https://gitlab.com. Begge tjenester tilbyr gratis repositories.
* Hvis leveringsmåten over ikke fungerer så informere oss gjerne på e-post hvordan du ønsker å levere oppgaven.

## Lykke til :)
