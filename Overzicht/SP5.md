---
layout: default
title: SP5: Analyse meetresultaten
parent: Overzicht project
has_toc: true
has_children: false
nav_order: 6
---

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

Als je leerlingen met Python aan de slag gaan, vind je heel veel info op [stack overflow](https://stackoverflow.com/) of via [google](https://www.google.com/) met de zoekopdracht "Python ...".
Via libraries kan je extra functies inladen. Gebruik hiervoor het commando "import \<lib\> as \<nameToUse\>" (Vul tussen \< \> de librarie naam en de naam waaronder je de librarie wilt gebruiken in).
Handige libraries zijn:
* SciPy.Stats (onderdeel van SciPy) - statistische functies, bv statistische testen
* Pandas (onderdeel van SciPy) - data-analyse en -manipulatie
* Numpy (onderdeel van SciPy) - wetenschappelijk rekenen, wiskundige functies
* Matplotlib (onderdeel van SciPy): pyplot, dates - visualisaties
* Seaborn (gebaseerd op Matplotlib): data visualisaties
[Hier](./../assets/files/demo_python/python_demo.ipynb) vind je een Jupyter notebook dat als basis en mits aanpassingen kan gebruikt worden, met een eigen dataset of met [deze demo-dataset](./../assets/files/demo_python/iwast-the-chamber-of-secrets.csv).
Een Jupyter notebook kan je opstarten in je browser, bv Google chrome, door naar volgende [website van Jupyter](https://jupyter.org/try) te surfen en op 'Try JupyterLab' te klikken. Vervolgens upload je het (jupyter notebook)[./../assets/files/demo_python/python_demo.ipynb] en de [deze demo-dataset](./../assets/files/demo_python/iwast-the-chamber-of-secrets.csv) via 'Upload files' links. Eenmaal het notebook is geladen kan je het cell per cell uitvoeren door op het play-pijltje ('Run the selected cells and advance') te klikken.

Als je leerlingen met MS Excel aan de slag gaan, veronderstellen dat ze hiervoor voldoende voorkennis hebben of dat je als leerkracht de nodige ondersteuning voorziet. Op [youtube](https://www.youtube.com/watch?v=6gvMOkCW0ug) leggen we alvast uit hoe je de data uit het platform in MS Excel inlaadt.

Indien gewenst kan je contact opnemen met iwast@kuleuven.be voor ondersteuning bij selectie en/of uitvoering van de analyses.
