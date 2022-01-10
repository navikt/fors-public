## Velkommen til kodeoppgave 4 – et lite kortspill!

## Introduksjon
I denne oppgave skal vi utvikle et enkelt kortspill for to spillere. Vi skal ikke utvikle et brukergrensesnitt så vi vil la koden lage to virtuelle spillere med hver sin strategi for å vinne.

## Game play
I vårt spill bruker vi kort fra en vanlig kortstokk og sorterer kortene i fire bunker etter sort/type (suits). En av bunkene blir valgt som premiebunke og legges på bordet med ett kort opp. Premiebunken skal være stokket. 
Så får hver av spillerne utdelt hver sin bunke fra de resterende tre. Den siste bunken legges til side og er ikke med i spillet.
Spillet spilles så i en serie av runder med hemmelige veddemål. Hver spiller velger i hemmelighet ut et kort fra egen kortstokk som symboliserer hvor mye han har lyst til å vedde for å vinne premiekortet. Det betyr at den som legger på det høyeste kortet vinner premiekortet. Når bunken med premiekort er tom så teller hver av spillerne opp sine premier og den med høyest sum vinner.

## Regler og funksjonelle krav
* Vi forenkler spillet litt og velger ut et subsett av kort med verdi fra og med 2 til og med 9.
* En av spillerne skal spille med en strategi som gjør at han hver runde velger den samme verdien som premiekortet.
* En av spillerne skal hver runde velge et tilfeldig kort fra sin bunke.
* For hver runde skal det skrives ut hvilken runde som spilles, hvilken verdi premiekortet har samt hvilken verdi hver spiller har veddet.
* Når alle rundene er spilt skal poengsummen for hver av spillerne skrives ut samt en tekst som forteller hvilken spiller som har vunnet.
* Hvis spillerne har samme poengsum skrives det ut "Uavgjort".

## Ikke-funksjonelle krav
* Løsningen kan utvikles med hvilket som helst programmeringsspråk, men det må følge med en steg for steg oppskrift som forteller hva som må til for å få programmet til å kjøre.

## Levering
* Oppgaven bør leveres i form av en URL til et versjonskontrollert repository, f.eks. https://github.com eller https://gitlab.com. Begge tjenester tilbyr gratis repositories.
* Hvis leveringsmåten over ikke fungerer, så informere oss gjerne på e-post hvordan du ønsker å levere oppgaven.

## Lykke til :)
