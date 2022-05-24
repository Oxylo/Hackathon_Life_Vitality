# Hackathon Life & Vitality vrijdag 1 juli om 9:00 Hotel Breukelen 

Deze repo bevat de data die je gaat gebruiken op de Hackathon. 
Aanvullen met je eigen data is meer dan toegestaan maar zeker niet verplicht.

Zet de bestanden (totaal ruim 500 MB wanneer je ook de ruwe datset van de BRFSS-websitet download) bij voorkeur **voorafgaand** aan de Hackathon op je computer.

# Download instructies

* op de groene knop "Code" bovenin het scherm, klik op het pijltje
* selecteerd: "Download ZIP"
* Pak de ZIP file uit op jouw eigen computer


# Toelichting bij de bestanden

## Folder BRFSS

BRFSS completes more than 400,000 adult interviews each year in the US, making it the largest continuously conducted health survey system in the world.

1. brfss_level_1.csv : size = (10000 rows, 16 cols) --> a nicely decoded sample from the raw BRFSS dataset --> great set to get started!
2. brfss_level_2.csv : size = (10000 rows, 48 cols) --> equal to #1 but with some more columns
3. brfss2019_sample_raw.csv : size = (1000 rows, 15 cols) --> this sample from the raw data gives you a good idea how the original coded BRFSS data look like.
4. brfss2019_sample_decoded.csv : size = (1000 rows, 15 cols) --> equal to #3 but after we performed some decoding to make it better readbable for you.
5. explore_brfss_getting_started.ipynb : Notebook to get started with analysing #1 and/or #2.
6. BRFSS2019_decodingtabs_simplified.xlsx : contains decoding tables for each interview question (you only news this when you feel brave enough to analyze LLCP2019ASC.ZIP, see below).
7. colnames.xlsx : contains decoding table for column names (same comment as #6 applies here).

The complete raw dataset LLCP2019ASC.ZIP can be downloaded here: 
* https://www.cdc.gov/brfss/annual_data/annual_2019.html (click the first link under header "Data Files": **2019 BRFSS Data (ASCII)** ZIP – 66.2 MB)

For more information on 2019 BRFSS Survey Data and Documentation, have you may have a look at:
* https://www.cdc.gov/brfss/annual_data/2019/pdf/codebook19_llcp-v2-508.HTML

## Folder CBS

Daar waar BRFSS Amerikaanse data bevat op persoonsnivo, bevat CBS Nederlandse data op diverse aggregatienivo's, o.a. naar regio of wijk.

1. Buurtinformatie.csv : aantal laag, middelbaar en hoog opgeleiden per gemeente, wijk en buurt in Nederland.
2. Buurtinformatie_Nieuw.csv : idem met update.
2. Gezondheidsmonitor16_83674NED.csv : bevat informatie over de gezondheid, sociale situatie en leefstijl van de Nederlandse bevolking van 18 jaar of ouder woonachtig in particuliere huishoudens. 
3. Gezondheidsmonitor20_85012NED.csv : idem maar dan voor 2020.
4. Gezondheidsonderzoek_83021NED.csv : bevat cijfers over de leefstijl en (preventief) gezondheidsonderzoek van de Nederlandse bevolking in particuliere huishoudens.
5. LeefstijlenPreventie_83385NED.csv : bevat cijfers over leefstijl en (preventief) gezondheidsonderzoek van de Nederlandse bevolking.
6. VoorzSociaalDomein_84662NED.csv : bevat cijfers over het aantal cliënten en huishoudens dat gebruik heeft gemaakt van voorzieningen in het sociaal domein. 
7. CBSdata.pptx : aanvullende informatie over CBS-data.
8. StatLine-Inhoudsopgave-Nederlandst.pdf : overzicht Statline onderzoeken.


Have fun!