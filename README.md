# Workshop DAT101 2. nov 2020

Hver oppgave har en tilhørende html-fil. Last ned filen som hører til hver enkelt oppgave og skriv inn koden i denne.

I disse oppgavene bruker vi kun `console.log()` for å skrive ut resultater til konsollen.

### Oppgave 1
Opprett tre variabler:
* En som er av typen `Number`.
* En som er av typen `String`.
* En som er av typen `Boolean`.

Etterpå skal du bruke `typeof`-operatoren til å skrive ut hvilken type hver variabel er i konsollen. Når du kjører 
programmet skal konsollen viser følgende output:

`>> number`

`>> string`

`>> boolean`

(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)

### Oppgave 2
I denne oppgaven skal vi se nærmere på en del `string`-metoder.

I filen som hører til oppgaven er det allerede definert en konstant med navnet `myText` som inneholder en del tekst.

**a)** 
Bruk `includes`-metoden på teksten og undersøk om den inneholder noen av de følgende ordene:
* room
* door
* aunt
* uncle

Skriv ut resultatet i konsollen for hver av disse.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes

**b)** Undersøk hvor mange tegn teksten inneholder, og skriv svaret ut i konsollen. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length

**c)** Undersøk for hvilken index ordet _Kansas_ forekommer i teksten og skriv svaret ut i konsollen.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf

**d)** Lag en ny string hvor du erstatter alle forekomstene av _a_ med _BANANA_ og skriv den nye teksten ut i konsollen.
Merk deg! Her skal du ikke erstatte alle bokstavene _a_, men kun der hvor _a_ forekommer som en ubestemt artikkel. For eksempel
skal teksten _**I have a computer**_ bli om til teksten _**I have BANANA computer**_.

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replaceAll 
