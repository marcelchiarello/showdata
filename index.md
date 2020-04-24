<!-- start -->
### For correct and optimal navigation, the use of a web browser from a PC or tablet is recommended.

## LAST DATA 24/04/2020 - 18:45

                    Casi     Attualmente_positivi    Morti    Guariti    Terapia_intensiva    Ospedalizzati    Ricoverati_con_sintomi    Tamponi
                   ______    ____________________    _____    _______    _________________    _____________    ______________________    _______
                   
    Totali         192994           106527           25969     60498           2173               24241                22068             1642356
    Giornalieri     +3021             -321            +420     +2922            -94                -897                 -803              +62447
                    Cases     Currently_positives    Deaths   Recovered    Intensive_care    Hospitalized    Hospitalized_with_symptoms   Tests                
    
Cases = Currently_positives + Recovered + Deaths

UPDATE 24/04:
- Nuovo dominio: <a href="www.covidrepo.com/">COVIDREPO.COM</a>
- E' stata corretta la visualizzazione dei valori negativi nei bar plot che trovate anche in anteprima sotto per terapie intensive ed ospedalizzati con sintomi.

UPDATE 21/04: 
- Le stime dei trend nazionali e regionali sono state aggiornate, ora sono calcolate sulla base dei dati che vanno dal 17/3 al 21/4.
- I report dei trend (data fitting) sono 2, uno sui casi giornalieri/totali nazionali e regionali, l'altro sui casi giornalieri/totali regionali con annesse province.
        
---

### Detailed Reports:

- [1 -Dati nazionali (National Data)](/RUN_24_04/RUN0/RUN.html)

- [2 -Fattori di crescita e letalità nazionali/regionali (National and regional growth factor and lethality)](/RUN_24_04/RUN6/RUN.html)

- [3 -Dati regionali e provinciali (Regional and Provincial Data)](/RUN_24_04/RUN2/RUN.html)

- [4 -Andamenti settimanali regioni NORD/SUD (WEEKLY TRENDS)](/RUN_24_04/RUN5/RUN.html)

- [5 -Confronti interregionali (Interregional comparisons)](/RUN_24_04/RUN4/RUN.html)

#### DATA FITTING - NATIONAL/REGIONAL TRENDS

- [6 -TOTAL CASES - Italy and Regions](/RUN_24_04/RUN1/RUN.html)

- [7 -TOTAL CASES - Regions and Provinces](/RUN_24_04/RUN13/RUN.html)

NOTE: New sigmoid-like equation used for data fitting:

<img src="http://latex.codecogs.com/svg.latex?Sig = \frac{a}{e^{b(x+c)} + a1e^{b1(x+c1)} - d}" border="0"/>

---

### The general situation (preview - see detailed reports for all charts):

Daily and Total Positives Trend:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_01.png">
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_02.png">
Daily intensive care by region:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_13.png">
Daily hospitalized with symphtoms by region:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_14.png">
Daily currently positives:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_15.png">
Daily Growth Factor:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN6/RUN_FACTORS_01.png">
Daily cases by region:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_11.png">
Daily tests by region:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_12.png">
Total cases by region:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_01.png">
Total hospitalized with symptoms:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN4/RUN_INTEREGION_05.png">
Total Cases vs Hospitalized, Recovered, Deaths:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN0/RUN_DATA_ITALIA_01.png">

<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN0/RUN_DATA_ITALIA_04.png">
Weekly Trends:
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN5/RUN_NEWTRENDS_01.png">
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN5/RUN_NEWTRENDS_02.png">
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN5/RUN_NEWTRENDS_03.png">

#### In Lombardia

<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_05.png">
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_06.png">

#### In Puglia

<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_03.png">
<img src="https://marcelchiarello.github.io/showdata/RUN_24_04/RUN1/RUN_DATA_FIT_TOTAL_CASES_ITALY_REGIONS_04.png">

See the report links above for all regions and provinces data charts.

## ARTICOLI E ANALISI (ARTICLES & ANALYSIS)

- [del 29 Marzo - Il picco in Lombardia. Ecco perchè serve analizzare e confrontare i dati regione per regione.](/ARTICLES/DES_29_03.md)
- [del 28 Marzo - Mancano gli standard nella comunicazione dei dati in Italia](/ARTICLES/DES_28_03.md)
- [del 27 Marzo - La giornata di oggi è di difficile valutazione ma ci sono dei lati positivi](/ARTICLES/DES_27_03.md)

---

### Data Source

- [PROTEZIONE CIVILE ITALIANA, GITHUB DATASET](https://github.com/pcm-dpc/COVID-19)

---

### ARCHIVE
[PREVIOUS DATA,PLOTS AND FITTING RESULTS](/archive.md)

---
