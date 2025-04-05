# Opdracht 3
_In deze opdracht leer je hoe OPTIONAL werkt._

Voor deze opdracht gaan we naar Zweden. Bij Kungliga Biblioteket in Stockholm bevat het SPARQL-endpoint de metadata over een boek met properties volgens een eigen datamodel. Laten we de boeken zoeken die door Mulisch zijn geschreven. 

## 3.1 
- Bekijk [https://id.kb.se/vocab/responsibilityStatement](https://id.kb.se/vocab/responsibilityStatement). Wat betekent deze property?
- We gaan zo een SPARQL query schrijven. Welke prefix zou je kiezen?
- Maak in YASGUI een query die een overzicht geeft van de URI's van de boeken in de collectie van de KB geschreven door "Harry Mulisch". Gebruik het endpoint https://libris.kb.se/sparql. (Antwoord: [yasgui-link](https://api.triplydb.com/s/E1OqficKQ))
- Hoeveel boeken heb je gevonden?

## 3.2
- Bekijk [https://id.kb.se/vocab/editionStatement](https://id.kb.se/vocab/editionStatement). Wat betekent deze property?
- Breid in YASGUI de query uit zodat ook de editionStatement wordt weergegeven. (Antwoord: [yasgui-link](https://api.triplydb.com/s/klnLke6Lt)
)
- Hoeveel boeken heb je gevonden?

## 3.3. 
- De query bij vraag 3.1 levert een ander aantal boeken op dan de query van opdracht 3.2. Waarom is dat? (Antwoord: Dat komt omdat niet alle boeken een editionStatement hebben.) 
- Pas de query aan zodat van alle boeken alleen de druk wordt weergegeven als deze ook aanwezig is in de data. (Antwoord: [yasgui-link](https://api.triplydb.com/s/DiCCubZuY))

Ga naar [Opdracht 04](opdracht04.md).

