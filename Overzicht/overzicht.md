---
layout: default
title: Overzicht project
nav_order: 2
---

# Voorstelling KU Leuven Technologiecampus Gent en de opleiding industrieel ingenieur Elektronica-ICT

Ter inleiding van dit project willen we graag vragen volgende filmpjes in de klas te laten zien, zodat de leerlingen weten waar dit project ontstaan is en wat de link is met onze opleiding industrieel ingenieur, afstudeerrichting elektronica-ICT.

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

_We geven op bovenstaande webpagina enkele handvaten, maar we raden je aan zelf na te denken hoe je binnen jouw leerlingengroep de brainstorm best vormgeeft. Mogelijke probleemstellingen/onderzoeksvragen worden gesuggereerd op de leerlingenwebsite._

Op volgende websites vind je mogelijk inspiratie:
* [thomas](https://www.kuleuven.be/thomas/page/werkvormen-brainstormen/)
* [tumult](https://www.tumult.nl/werkvormen-2-creatieve-ideeen-verzamelen-brainstormen/)

Hieronder komt een (groeiend) lijstje van probleemstellingen die klassen in het verleden onderzocht hebben:
* Hoe groot is het verschil in geluidniveau vooraan en achteraan het klaslokaal? Welke factoren hebben een invloed op het geluidsniveau(verschil)?
* Hoe is het gesteld met de luchtvervuiling op weg van en naar school en in de schoolomgeving?

# SP 2 Randvoorwaarden IoT systeem

## Korte beschrijving
Wat is het Internet der Dingen? 
Meetgegevens: 
* wat (welke sensoren)? 
* hoe (werkingsprincipe sensoren)?
* waar (afstand tot gateway)? 
* wanneer (polling vs threshold)?

## Ondersteunend materiaal

Uitleg voor de leerlingen vind je [hier](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP2/inhoud.html)

_Je kan eventueel volgende ondersteunende presentatie [PDF](./../assets/files/IoT_IoTree.pdf) en [ppt](./../assets/files/IoT_IoTree.pptx) gebruiken om het internet en het Internet der Dingen bij je leerlingen te introduceren_

_Je kan eventueel volgende ondersteunende presentatie [ppt](./../assets/files/elektronische_systemen.pptx) gebruiken om elektronische systemen en sensoren bij je leerlingen te introduceren_

_Je kan zelf kiezen hoe diep je leerlingen op bepaalde zaken laat ingaan, naargelang je eigen achtergrond en voorkennis en interesse van de leerlingen: werking van het internet, types sensoren en werkingsprincipe van de beschikbare IoT sensoren, dataverwerking op de sensorborden (bv. geluidsensor), ..._

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

### Samenvattende oefening

Eventueel kan je aan de leerlingen volgende vragen voorleggen om na te gaan of ze alles goed begrepen hebben, of je kan hen aan de hand van deze vragen en een selectie bronnen ((handleiding voor leerlingen0[https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP2/inhoud.html], (ppt IoT)[./../assets/files/IoT_IoTree.pptx], (ppt sensoren)[./../assets/files/elektronische_systemen.pptx]) antwoorden op onderstaande vragen laten formuleren.
* Hoe werkt het internet?
    * _Het internet is een wereldwijd netwerk van computernetwerken. Het laadt ons toe emails te sturen, websites te raadplegen, te communiceren via chat, ..._
    * _Toegang tot het internet kan zowel via kabel als draadloos. Draadloze internettoegang is bijvoorbeeld toegang via Wifi, wanneer je smartphone of laptop verbinding maakt met een wifi-router of via ja smartphone via het cellulaire netwerk voor mobiele telefonie, vb. 3G of 4G (en in de toekomst ook 5G)._
    * _Wanneer je "draadloos internet" gebruikt, is enkel de verbinding tussen je toestel en de wifi-router of gsm-mast draadloos. Vanaf daar verloopt het dataverkeer via kabels, bv. coax-kabel, koperen kabel of glasvezel). Zelfs intercontinentale verbindingen (bv.tussen Europa en Amerika) loopt over heel aantal dikke bundels kabels die op de bodem van de oceaan liggen._
* Wat is het internet der dingen?
    * _Het internet der dingen verbindt niet enkel computers en smartphones met het internet, maar ook meer alledaagse dingen, zoals je thermostaat, deurbel, lamp, ..._
    * _Dit schept nieuwe mogelijkheden:_
        * _Monitoren (en eventueel ingrijpen) vanop afstand, bv. je verwarming die aanspringt wanneer je op het werk naar huis vertrekt_
        * _Hoger gebruiksgemak: bv. je plant die een seintje geeft wanneer die dringend water moet krijgen_
* Wat zijn uitdagingen in IoT?
    * _Communicatie: zowel de hoeveelheid verstuurde data, als de snelheid waarmee en de afstand waarover die verstuurt moeten worden, vormen belangrijke uitdagingen. In functie van de toepassing moet bekeken worden welke datahoeveelheden, -snelheden en afstanden haalbaar en wenselijk zijn. Het is bv. niet gewenst de hele dag door de video van een camera aan je voordeur, geplaatst om inbrekers te betrappen, naar je smartphone te streamen. In dat geval kies je misschien beter voor een ander type alarm en sla je de video lokaal op, of stuur je enkel de video door wanneer je detecteert dat er effectief een inbraak plaatsvindt._
    * _Energie: IoT devices zijn vaak draadloos met het internet verbonden en werken daardoor ook vaak op batterijen. Het is ongewenst batterijen vaak te gaan vervangen, dus die devices moeten lang autonoom kunnen werken, maar we willen vaak ook niet dat de batterij te groot wordt. Daarom is het belangrijk dat IoT devices zuinig met energie omspringen, bv. door hoeveelheid geregistreerde en doorgestuurde data te beperken, door de devices te laten 'slapen' als een geen 'interessante events' plaatsvinden, ..._
* Wat is een sensor?
    * _Een sensor is een apparaat dat een stimulus opvangt en omzet naar een elektrisch signaal._
    * _De transferfunctie geeft het verband tussen de stimulus aan de ingang en het gemeten uitgangssignaal. Bij een gekende transferfunctie kan voor een bepaalde uitgangsspanning de ingangswaarde van de stimulus bepaald worden._
* (Uitbreiding) Op welke verschillende manieren kunnen we sensoren classificeren?
    * _O.b.v. WAT ze meten: fysisch, chemisch, biologisch, ..._
    * _O.b.v. HOE ze meten: resistief, capacitief, ..._
    * _O.b.v. energie: actief vs passief_
    * _O.b.v. uitgangssignaal: analoog vs digitaal_
* (Uitbreiding) Wat is een mogelijk werkingsprincipe van een microfoon?
    * _Resistief: bv. carbon microfoon: de microfoon bestaat uit twee metalen platen, met daartussen koolstofpoeder. Geluid dat invalt op het diafragma (eerste metalen plaatje) doet de afstand tussen beide platen variëren, mee met de trillingen in de geluidsgolf.  Hierdoor wordt het koolstofpoeder meer (bij samendrukken van beide plaatjes) of minder (bij uit elkaar halen van beide plaatjes) samengedrukt, waardoor de weerstand respectievelijk afneemt of toeneemt. Die weerstandsverandering resulteert in een variabele uitgangsspanning, die de variaties van het invallende geluidssignaal volgt._
    * _Capacitief: een condensator is een elektrische component waarin aan de ene zijde elektrische lading opgeslagen kan worden, met gelijktijdige opslag van de tegengestelde lading aan de andere zijde. De capaciteit is het vermogen van een condensator om elektrische lading op te slaan. Vaak worden parallele plaat condensatoren gebruikt. In dat geval wordt de capaciteit o.a. bepaald door de oppervlakte van de platen en de afstand tussen beide platen. Een condensatormicrofoon is gebaseerd op verschillen in capaciteit bij invallend geluid. De microfoon bestaat uit een dun membraan met daarop een goud of aluminium laagje, dichtbij een vast metalen plaatje. Samen vormen het membraan en het metalen plaatje een condensator. Wanneer er geluid invalt op het membraan, varieert de afstand tussen het membraan en het plaatje, waardoor ook de capaciteit varieert. De capaciteitsverandering resulteert in variaties in de uitgangsspanning, die het invallende geluid volgen._
* (Uitbreiding) Wat is een mogelijk werkingsprincipe van een temperatuursensor?
    * _Resistief: materialen met een hoge temperatuurcoëfficiënt (d.w.z. waarvan de geleidbaarheid sterk varieert i.f.v. de temperatuur) zijn goede materialen voor een temperatuursensor. Gezien de weerstand afhangt van de geleidbaarheid, lengte en oppervlakte van de weerstand, zal bij dergelijke materialen, de weerstandswaarde sterk variëren met variaties in temperatuur. De weerstandswaarde kan teruggerekend worden naar de temperatuur als de transferfunctie van de sensor gekend is._ 
* (Uitbreiding) Wat is een mogelijk werkingsprincipe van de luchtvochtigheidssensor?
    * _Resistief: bepaalde materialen hebben een variabele geleidbaarheid wanneer ze vocht absorberen. Deze materialen zijn de basis van hygristors, die vochtigheid kunnen opmeten._


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

Als je leerlingen met Python aan de slag gaan, vind je heel veel info op [stack overflow](https://stackoverflow.com/) of via [google](https://www.google.com/) met de zoekopdracht "Python ..."
Via libraries kan je extra functies inladen. Gebruik hiervoor het commando "import <lib> as <nameToUse>".
Handige libraries zijn:
* SciPy.Stats (onderdeel van SciPy) - statistische functies, bv statistische testen
* Pandas (onderdeel van SciPy) - data-analyse en -manipulatie
* Numpy (onderdeel van SciPy) - wetenschappelijk rekenen, wiskundige functies
* Matplotlib (onderdeel van SciPy): pyplot, dates - visualisaties
* Seaborn (gebaseerd op Matplotlib): data visualisaties

Als je leerlingen met MS Excel aan de slag gaan, veronderstellen dat ze hiervoor voldoende voorkennis hebben of dat je als leerkracht de nodige ondersteuning voorziet. Op [youtube](https://www.youtube.com/watch?v=6gvMOkCW0ug) leggen we alvast uit hoe je de data uit het platform in MS Excel inlaadt.

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

De implementatie van het iSTEM-principe _coöperatief leren_ is in handen van de begeleidende leerkracht. Uiteraard raden we aan leerlingen in groepjes te laten werken en waar mogelijk van elkaar te laten leren, bv. door ze door samen te werken een rijkere dataset te laten verzamelen of een rijkere probleemstelling te laten verkennen.

