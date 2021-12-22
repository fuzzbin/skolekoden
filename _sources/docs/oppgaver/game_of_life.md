# Conway's Game of Life

John Horton Conway var en britisk/amerikansk matematiker. Han er mest kjent som oppfinner av spillet Game of Life.

![stigespill](./img/Conway_glidere.gif)

Spillet består av et stort rutenett. En rute kalles også en celle. Cellene kan ha to tilstander, enten opplyste (levende) eller tomme (døde). Hver celle har kontakt med de åtte cellene som omslutter den. For hvert tidsskritt skal følgende regler følges:

* Alle levende celler med færre enn to levende naboceller dør av enshomhet
* Alle levende celler med to eller tre naboer fortsetter å leve til neste generasjon
* Alle levende celler med flere enn tre naboer dør på grunn av overbefolkning
* Alle døde celler med nøyaktig tre naboer blir levende som ved reproduksjon

## Oppgave

Lag en simulering som viser hvordan starttilstanden utvikler seg over tid.

---

_Denne oppgaven er laget av [fuzzbin](https://github.com/fuzzbin) og [bitjungle](https://github.com/bitjungle). Oppgaven er lisensiert under en [Creative Commons Navngivelse-DelPåSammeVilkår 4.0 Internasjonal lisens.](http://creativecommons.org/licenses/by-sa/4.0/)_
