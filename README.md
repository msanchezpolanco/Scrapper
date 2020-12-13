# Scrapper

Een versimpelde versie van [William Schmidt's](https://github.com/wilschmidtt/Google-Image-Scraper) tool.

Een Google Images web scrapping tool.

Google Chrome en Anaconda zijn vereist.

1. Download het project
2. Controlleer Chrome's versie (Settings > Help > About Google Chrome), download de overeenkomende versie van [Chromedriver](https://chromedriver.chromium.org/downloads).
3. Pak Chromedriver uit en verplaatst het uitvoerbaar bestand naar de root van het project.
5. Creeër een Anaconda environment en download de nodige dependencies met: 
  * `conda env update -f environment.yaml -n NAME_ENV`
6. Instructies voor het uitvoeren van script:
  * Via Prompt voer `python Scrapper.py -h` uit

In het geval dat men een Unix besturingssyteem gebruikt, verwijdert de bestandsextensie op lijn `105` in `Scrapper.py` van `Chromedriver.exe` naar `Chromedriver`.
