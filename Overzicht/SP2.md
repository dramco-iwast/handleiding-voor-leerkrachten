---
layout: default
title: SP2 Randvoorwaarden IoT systeem
parent: Overzicht project
has_toc: true
has_children: false
nav_order: 5
---
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

_Deze [ppt-presentatie](./../assets/files/IoT_Intro_bijscholing.pptx) gebruikten we om het internet der dingen en de werking van sensoren te introduceren tijdens de bijscholing._

_Je kan eventueel volgende ondersteunende presentatie [PDF](./../assets/files/IoT_IoTree.pdf) en [ppt](./../assets/files/IoT_IoTree.pptx) gebruiken om het internet en het Internet der Dingen bij je leerlingen te introduceren_

_Je kan eventueel volgende ondersteunende presentatie [ppt](./../assets/files/elektronische_systemen.pptx) gebruiken om elektronische systemen en sensoren bij je leerlingen te introduceren_

_Je kan eventueel volgende ondersteunende tekst [PDF](./../assets/files/verdieping_draadlozecommunicatie/JC_iotree.pdf) gebruiken om draadloze communicatie met je leerlingen te introduceren_

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

Eventueel kan je aan de leerlingen volgende vragen voorleggen om na te gaan of ze alles goed begrepen hebben, of je kan hen aan de hand van deze vragen en een selectie bronnen ([handleiding voor leerlingen](https://dramco-iwast.github.io/handleiding-voor-leerlingen/SP2/inhoud.html), [ppt IoT](./../assets/files/IoT_IoTree.pptx), [ppt sensoren](./../assets/files/elektronische_systemen.pptx)) antwoorden op onderstaande vragen laten formuleren.
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

