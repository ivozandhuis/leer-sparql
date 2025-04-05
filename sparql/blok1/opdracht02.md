# Opdracht 2 
_In deze opdracht leer je hoe je FILTER en REGEX gebruikt_

Ook de Bibliotheque National de France heeft een SPARQL-endpoint voor het beschikbaar stellen van de catalogusinformatie. Zou daar ook een exemplaar van Mulisch' Stenen Bruidsbed zijn te vinden? 

Ze gebruiken in Frankrijk Dublin Core Terms en RDA in plaats van Schema.org. 

## 2.1 
- Bekijk <http://rdvocab.info/Elements/publishersName>. Waar is deze property voor bedoeld?
- Open in [YASGUI](http://yasgui.triply.cc/) een nieuw tabblad en gebruik dit endpoint: https://data.bnf.fr/sparql 
- Maak een query die antwoord geeft op de volgende vraag: Welke boeken zijn er uitgegeven door "De Bezige bij" (Neem deze spelling met hoofdletters precies over!). Geef in het resultaat de URI van het boek en de titel.  (Antwoord: [yasgui-link](https://api.triplydb.com/s/zZUnCvWmE))
- Volg de URI om te zien waar je uitkomt.

## 2.2 
- Bekijk [http://purl.org/dc/terms/title](http://purl.org/dc/terms/title). 
- Breid de query uit zodat alleen boeken worden weergegeven met het woord "bruidsbed" in de titel.

Antwoord: [yasgui-link](https://api.triplydb.com/s/q7JAIQh_n)

## 2.3. 
- Kun je ook een query maken die je een overzicht geeft van de data die over een van de twee resultaten beschikbaar is, net als bij opdracht 1.3? (Antwoord: [yasgui-link](https://api.triplydb.com/s/vLITihRww))

Einde blok 1.