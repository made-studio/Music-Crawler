# The Music Barometer


## Description

Användaren möts av en sida som visar en topplista med Storbritanniens topp tre mest lyssnade låtar. 
Längre ned visas tre cirkeldiagram över de mest lyssnade genrerna i USA, Sverige och Storbritannien samt en analys varje lands resultat. 
Resultaten för sångerna och genrerna hämtas med hjälp av sökspindlar. Sökspindlarna går igenom alla album länkar på apple musics topp 100 listor och sparar albumens genrer i en SQL databas.

![image](https://github.com/made-studio/Music-Crawler/assets/117782646/a369af2a-7fbc-4592-b156-c517509f6e46)
![image](https://github.com/made-studio/Music-Crawler/assets/117782646/5fcc4a3b-e249-445c-aacc-bc43000a4031)
### Registrering av mail
Om användaren klickar på “Subscribe” har hen möjlighet att fylla i sin mailadress och få ett mail utskick med Storbritanniens topp tre låtar, se bilden nedan. 
E-mailadressen sparas även i en databas. Varje månad rensas databaserna på låtar, topplistorna söks igenom på nytt och alla mailadresser i databasen får ett mail med de nya topplåtarna. 
Dessa funktioner är dock inaktiverade för tillfället på grund av praktiska skäl.
![image](https://github.com/made-studio/Music-Crawler/assets/117782646/7ac6662d-9cbf-49d0-82fa-5a7643aaafac)
![image](https://github.com/made-studio/Music-Crawler/assets/117782646/a4ba50a1-e34e-4958-84c9-28950ec25f58)
### Cirkeldiagram med beskrivning
