# De Regio Vecht Terug - Data

Dit repository bevat een selectie van de onderliggende gegevens van het onderzoek naar de Gemeenteraadsverkiezingen van 2018
zoals gepresenteerd op de bijeenkomst [De Regio Vecht Terug](https://regiovechtterug.nl/).

## Waarschuwing / noot vooraf

Dit zijn ruwe gegevens die speciaal voor deze middag zijn klaargezet. 
We vinden het belangrijk (en leuk!) dat veel mensen met de bestanden kunnen werken.
Echter, we willen niet dat er conclusies worden getrokken uit een onjuist gebruik van de bestanden of omdat er door slordigheden van onze kant fouten in de gegevens zitten.
We zouden het daarom op prijs stellen als mensen die de gegevens willen gebruiken voor een publicatie even voorafgaand ons zeggen wat er precies gedaan is, dan kunnen wij even checken of dat correct lijkt. 
Dit kan door een (publiek) [issue aan te maken](https://github.com/nruigrok/regiovechtterug/issues/new?labels=Analyse) of door [ons even te mailen](mailto:nelruigrok@nieuwsmonitor.org). 

Via de issues kan je ook [inhoudelijke vragen over de gegevens stellen](https://github.com/nruigrok/regiovechtterug/issues/new?labels=Vraag). 

## Beschrijving van de gegevensbestanden:

+ [panelsurvey_stemgedrag.csv](panelsurvey_stemgedrag.csv) Voornaamste bestand met panelsurvey gegevens. Per respondent staan hier achtergrondgegevens (inc. weging) en stemgedrag 2014, 2017, 2018. Voor 2018 zijn stemintentie (voor de campagne), stemgedrag, en stemkeuze in het referendum opgenomen. Voor 2014 en 2018 is er een tweede versie van de kolom waarbij alle lokale partijen zijn samengevoegd.
+ [panelsurvey_mediumgebruik.csv](panelsurvey_mediumgebruik.csv) Mediumgebruik per respondent. Per respondent is er een rij per medium dat deze respondent heeft aangegeven te gebruiken, met daarin de frequentie en welk platform (krant, site, fb) gebruikt hij/zij gebruikt
+ [panelsurvey_issues.csv](panelsurvey_issues.csv) Issue-agenda en issue-ownership per respondent. Elke rij bevat een issue dat door een respondent belangrijk werd gevonden, en de partij die deze respondent associeert met het issue. Als een issue herhaald wordt dan associeerde een respondent meerdere issues met de partij. 
+ [news_topics.csv](news_topics.csv) Onderwerpen zoals ze in het nieuws zijn gekomen op basis van automatische inhoudsanalyse (dmv een Structural Topic Model geconditioneerd op regio en door ons geselecteerd en samengevoegd tot een beperkt aantal issues). Om auteursrechtelijke redenen is dit samengevoegd per medium. 
+ [news_parties.csv](news_parties.csv) Aandacht voor de partijen per medium, gebaseerd op automatische inhoudsanalyse door middel van zoektermen per partij. 

