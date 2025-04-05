# Opdracht 1
_In deze opdracht leer je het basisprincipe van een SPARQL query_

In deze les maken we gebruik van een SPARQL endpoint bij de Koninklijke Bibliotheek. Zij beheren ze de Nederlandse Bibliografie Totaal (NBT), een overzicht van alle boeken die in Nederland zijn uitgegeven. In de dataset zijn publicaties met behulp van properties uit Schema.org gemodelleerd. 

## 1.1. 
- Bekijk [http://schema.org/isbn](http://schema.org/isbn). Waar is deze property voor bedoeld?
- Open in [YASGUI](http://yasgui.triply.cc/) een nieuw tabblad en maak een query die antwoord geeft op de volgende vraag: "wat is de URI van het boek met het ISBN-nummer 9789023476825?" Gebruik dit endpoint: http://data.bibliotheken.nl/sparql
- (Antwoord: [yasgui-link](https://api.triplydb.com/s/Lv-2t6BWQ))
- Volg de URI om te zien waar je uitkomt.

## 1.2. 
- Bekijk [http://schema.org/name](http://schema.org/name). Waar is deze property voor bedoeld?
- Breid de query uit de vorige opdracht uit zodat je antwoord krijgt op de vraag: "Wat is de titel van het boek met het ISBN-nummer 9789023476825?"
- (Antwoord: [yasgui-link](https://api.triplydb.com/s/3euSLu_se))

## 1.3.
- Open in [YASGUI](http://yasgui.triply.cc/) een nieuw tabblad en maak een query die antwoord geeft op de volgende vraag: "welke properties zijn er allemaal vastgelegd over het boek met ISBN 9789023476825?"
- (Antwoord: [yasgui-link](https://api.triplydb.com/s/aUNgV3I3B))

Ga naar [Opdracht 02](opdracht02.md).