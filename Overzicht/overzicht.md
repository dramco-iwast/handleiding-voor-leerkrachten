---
layout: default
title: Overzicht project
nav_order: 2
---

# Voorstelling KU Leuven Technologiecampus Gent en de opleiding industrieel ingenieur Elektronica-ICT

[Voorstelling KU Leuven Technologiecampus Gent](https://www.youtube.com/watch?v=zAj-Sjh6M2U&ab_channel=KULeuvenTechnologiecampusGent)
[Voorstelling opleiding industrieel ingenieur Elektronica-ICT](https://youtu.be/UQbW6TNYlA0)

# Uitdaging

### Korte beschrijving
We dagen je uit om een maatschappelijk of ecologisch relevant probleem in je schoolomgeving in kaart te brengen en eventueel op te lossen a.d.h.v. IoT technologie

### Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/Uitdaging/uitdaging.html)

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan zelf na te denken hoe je jouw leerlingengroep best laat nadenken over welke stappen binnen dit project zullen moeten worden doorlopen._

# SP 1 Brainstorm

### Korte beschrijving
Brainstorm: welke 'problemen' zou je mogelijk in kaart kunnen brengen? 
Randvoorwaarden: de IoT sensoren kunnen volgende zaken meten:
* geluid
* temperatuur
* luchtdruk
* luchtvochtigheid
* luchtkwaliteit
* drukknoppen: bv. gebruikers hun voorkeur laten ingeven, laten stemmen, ...

### Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP1/brainstorm.html)

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan zelf na te denken hoe je binnen jouw leerlingengroep de brainstorm best vormgeeft._

Op volgende websites vind je mogelijk inspiratie:
* [thomas](https://www.kuleuven.be/thomas/page/werkvormen-brainstormen/)
* [tumult](https://www.tumult.nl/werkvormen-2-creatieve-ideeen-verzamelen-brainstormen/)

# SP 2 Randvoorwaarden IoT systeem

## Korte beschrijving
"Wat is het Internet der Dingen? 
Meetgegevens: 
* wat (welke sensoren)? 
* hoe (werkingsprincipe sensoren)?
* waar (afstand tot gateway)? 
* wanneer (polling vs threshold)?"

## Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP2/inhoud.html)

_Je kan eventueel volgende ondersteunende presentatie [PDF](./../assets/files/IoT_IoTree.pdf) en [ppt](./../assets/files/IoT_IoTree.pptx) gebruiken om het internet en het Internet der Dingen bij je leerlingen te introduceren_

_Je kan eventueel volgende ondersteunende presentatie [ppt](./../assets/files/elektronische_systemen.pptx) gebruiken om elektronische systemen en sensoren bij je leerlingen te introduceren_

### Oefening: randvoorwaarden oplijsten

De leerlingen wordt gevraagd de beschikbare informatie door te nemen en de randvoorwaarden waarbinnen zij kunnen werken op te lijsten. Hierdoor zullen enkele tijdens de brainstorm geformuleerde ideeën vervallen. 

Het lijstje van randvoorwaarden waarmee leerlingen zeker rekening moeten houden:
* Energieverbruik: je kan ten snelste om de vijf minuten data doorsturen
* Afstand: afhankelijk van de omgeving en gebruikte gateway moet je op een bepaalde afstand van de gateway blijven. Dit kan variëren van enkele tientallen meters in een druk bemeubelde binnenruimte met veel metalen structuren, tot enkele kilometers wanneer de gateway op een dak in een rustige - vb landbouw - omgeving geplaatst is
* Beschikbare sensoren:
    * Temperatuur
    * Luchtdruk
    * Luchtvochtigheid
    * Luchtkwaliteit - geen CO_2 alleen!
    * Geluid: geen geluid onder 65 dB op te meten
    * Input van drukknopsensor: ongeveer 15 keer na elkaar stemmen, vervolgens enkele minuten wachten; of telkens enkele minuten tussen laten
    * Lichtsensor
    * Batterijspanning: zakt niet lineair met vermogen van de batterij.
* Geen actuatoren aanwezig -> beperk je tot onderzoeks- of monitoringtoepassingen


# SP 3 Selectie probleemstelling

## Korte beschrijving
Welke probleemstellingen uit de brainstorm zijn haalbaar om te onderzoeken met de IoT technologie die wij ter beschikking stellen?
* Wat moet je meten om een oplossing voor je probleemstelling te kunnen voorstellen?
* Wat zijn je onderzoeksvragen?

## Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP3/selectieProbleem.html)

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan zelf na te denken hoe je deze reflectie- en selectieoefeningen kan begeleiden. Neem contact op met iwast@kuleuven.be indien je de probleemstellingen en onderzoeksvragen die de leerlingen willen uitwerken graag even aan ons voorlegt._

# SP 4 Onderzoeksopzet

## Korte beschrijving

Op welke manier moet je de IoT sensoren configureren om je probleemstelling te onderzoeken/op te lossen?
* Welke sensor(en)?
* Hoeveel sensoren?
* Waar plaats je de sensor(en)?
* Wanneer moeten de sensoren gevens opmeten? Threshold of polling? Polling interval?
* Indien buiten: hoe kan je de sensoren beschermen tegen weersinvloeden?
Controleer of de data binnenkomt op het platform zoals je het verwacht: kloppen de intervallen? zijn de opgemeten waarden plausibel? ...?

## Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP4/onderzoeksopzet.html)

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan zelf na te denken hoe je de uitwerking van het onderzoeksopzet best ondersteunt voor jouw leerlingengroep._

# SP 5 Analyse meetresultaten

## Korte beschrijving

Wat zeggen de meetgegevens over je probleemstelling?
Je vindt de data op het platform. Je kan de data downloaden en in Excel of Python analyseren, afhankelijk van hoeveel je wil programmeren.
* Welke omgeving voor analyses? Excel? Python? ...?
* Welke analyses? 
    * visuele inspectie van de verzamelde data 
        * grafiek meetwaarden ifv de tijd (zie platform)
        * verdeling van de meetwaarden (normale vs binomiale vs uniforme vs ... verdeling)
        * boxplot geaggregeerde data ter vergelijking van 
            * verschillende sensoren (bv. geluid in het klaslokaal vs op de speelplaats)
            * verschillende tijdstippen (bv. geluid op weekdagen vs in het weekend)
    * beschrijvende statistiek
        * gemiddelde, mediaan, standaarddeviatie, interkwartielafstand voor meetwaarden
    * toetsende statistiek
        * hypothesetesten om meetwaarden doorheen de tijd, of opgemeten door verschillende sensoren, te vergelijken
    * regressie-analyses
        * verband tussen meetwaarden van twee sensoren (bv. zijn temperatuur en luchtvochtigheid in een klaslokaal aan elkaar gerelateerd?)
* Welke grafieken?

## Ondersteunend materiaal
Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP5/analyse.html)

_We geven op bovenstaande webpagina enkele handvaten hoe je de data-analyse kan starten, maar we raden je aan zelf na te denken welke analyses je precies van je leerlingen verwacht en in welke omgeving ze die moeten uitvoeren._

Indien gewenst kan je contact opnemen met iwast@kuleuven.be voor ondersteuning bij selectie en/of uitvoering van de analyses.


# SP 6 Synthese en reflectie

## Korte beschrijving
Welke besluiten kan je formuleren? 
* Wat is het antwoord  op je onderzoeksvragen? 
* Kan je nu een oplossing voor je probleem formuleren, of heb je hier nog meer materiaal/gegevens voor nodig?
* Heeft IoT je geholpen je probleem beter in kaart te brengen? 
* Wat waren de sterktes, beperkingen van de IoT technologie?

## Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP6/synthese.html)

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan je leerlingen te ondersteunen bij het formuleren van besluiten en reflecteren over dit project. Een template van een verslag kan bijvoorbeeld een goede basis zijn om leerlingen hun besluiten te laten samenvatten en kritisch te laten stilstaan bij de waarde van hun bevindingen en het verloop van het proces. Stuur dergelijke verslagen of andere eindproducten van leerlingen gerust door naar iwast@kuleuven.be, want wij zijn ook zeer geïnteresseerd in de leerlingenresultaten en steeds op zoek naar feedback op ons IoT systeem en op de ondersteunende materialen._

# Link subproblemen, onderwijsdoelen, STEM-disciplines en iSTEM-principes

SP | OWdoelen 2e gr | eindtermen 3e gr | STEM-disciplines | iSTEM-principes |
| ------------- |:-------------:|:-------------:|:-------------:| 
Uitdaging | | | | probleemgecentreerd |
1 | | | | geïntegreerd |
2 | (6.35), 6.40 | (6.24), 6.40 | S, T, E | geïntegreerd |
3 | 6.52, 13.11 | 6.39, 13.11 | E | |
4 | 4.2, (6.47), 13.12, 13.13 | 4.4, (6.34), 13.12, 13.13 | S, E, T | onderzoekend/ontwerpend leren |
5 | 4.5, 6.9, 6.18, 6.19, 6.49, 6.50, 6.52 | 4.5, 6.2, 6.13, 6.16, 6.37, 6.38 | M, T | onderzoekend leren, geïntegreerd |
6 | 6.52, 13.14 | 13.13, 13.14 | (S), (M), E | onderzoekend leren, geïntegreerd |
geheel | 6.55, 6.57| 6.40, 6.41, 6.42, 6.43 | |

De implementatie van het iSTEM-principe _coöperatief leren_ is in handen van de begeleidende leerkracht. Uiteraard raden we aan leerlingen in groepjes te laten werken en waar mogelijk van elkaar te laten leren, bv. door ze verschillende probleemcontexten of deelproblemen te laten onderzoeken.

