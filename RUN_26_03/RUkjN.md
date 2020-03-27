**COVID19 Output analysis data updated to March 26, 2020**.

DRAFT

EDIT: - Removed the graphs for the individual provinces. - English
version, work in progress

Questo report è relativo all' elaborazione dei dati sulla diffusione del
COVID-19 in Italia e nelle singole regioni/province. I dati sono forniti
dalla protezione civile Italiana, consultabili al segunte link:

"https://github.com/pcm-dpc/COVID-19"

Tale report non è da intendersi come ufficiale o come definitivo nei
termini delle previsioni incluse. I modelli non sono di tipo predittivo,
bensì equazioni che descrivono i dati disponibili fino a questo momento.
Il loro scopo è quello di valutare l andamento attuale, in modo da poter
dedurre una eventuale accelerazione o decelerazione del contagio. In
generale per ogni campione di dati viene selezionata una prima finestra
temporale e la si utilizza per elaborare il modello (fitting) per poi
confrontarlo con i giorni successivi.

I valori reali che non sono stati utilizzati per la stima del modello
possono sia riferirsi a giorni passati, sia a giorni futuri, per una
mera valutazione qualitativa.

-Per quanto concerne i dati regionali e provinciali, il fit è di tipo
esponenziale/lineare. Una stima della funzione logistica/sigmoide viene
effettuata per alcune regioni e/o province. Tale andamento viene stimato
sulla base di una finestra temporale precedente con il fine di
verificare che il punto/i punti futuri si collochino al di sopra o al di
sotto della curva esponenziale, nell'assunzione che tale scostamento
indichi un accelerazione o decelerazione del contagio.

-Per quanto concerne i dati nazionali, viene anche effettuata una stima
qualitativa sulla base della funzione logistica/sigmoide,
nell'assunzione che il giorno previsto di azzeramento dei contagi, sia
conservativo verso il limite inferiore, ossia la minima data che occorre
aspettare.

-Le stime vengono effettuate minimizzando la distanza quadratica media
dalle curve ed i casi reali (Non Linear Least Square). Ogni modello non
tiene conto dei punti iniziali secondo l'ipotesi di una sottostima dei
contagi nei giorni che vanno da fine Febbraio/inizio Marzo.

Models and reports are under continuous review.

Source: https://github.com/marcelchiarello/C19dataAnalysis

Site: https://marcelchiarello.github.io/C19dataAnalysis/

Author: Marcello Chiarello

[marcello.chiarello@outlook.com](mailto:marcello.chiarello@outlook.com)

Contents
--------

-   [GRAFICI ITALIA](#2)
-   [GRAFICI PUGLIA](#3)
-   [GRAFICI LOMBARDIA](#4)
-   [GRAFICI VENETO](#5)
-   [GRAFICI PIEMONTE](#6)
-   [GRAFICI EMILIA ROMAGNA](#7)
-   [GRAFICI CAMPANIA](#8)
-   [GRAFICI SICILIA (Non presente)](#9)
-   [GRAFICI ABRUZZO](#10)
-   [GRAFICI BASILICATA](#11)
-   [GRAFICI CALABRIA](#12)
-   [GRAFICI CAMPANIA](#13)
-   [GRAFICI FRIULI VENEZIA GIULIA](#14)
-   [GRAFICI LAZIO](#15)
-   [GRAFICI LIGURIA](#16)
-   [GRAFICI MARCHE](#17)
-   [GRAFICI MOLISE](#18)
-   [GRAFICI P.A. Bolzano](#19)
-   [GRAFICI P.A. Trento](#20)
-   [GRAFICI SARDEGNA (Non presente)](#21)
-   [GRAFICI TOSCANA](#22)
-   [GRAFICI UMBRIA](#23)
-   [GRAFICI VALLE D' AOSTA](#24)
-   [DATI PUGLIA](#25)
-   [DATI LOMBARDIA](#26)
-   [DATI VENETO](#27)
-   [DATI PIEMONTE](#28)
-   [DATI EMILIA ROMAGNA](#29)
-   [DATI CAMPANIA](#30)
-   [DATI SICILIA](#31)
-   [DATI ABRUZZO](#32)
-   [DATI BASILICATA](#33)
-   [DATI CALABRIA](#34)
-   [DATI CAMPANIA](#35)
-   [DATI VENEZIA GIULIA](#36)
-   [DATI LAZIO](#37)
-   [DATI LIGURIA](#38)
-   [DATI MARCHE](#39)
-   [DATI MOLISE](#40)
-   [DATI P.A. Bolzano](#41)
-   [DATI P.A. Trento](#42)
-   [DATI SARDEGNA](#43)
-   [DATI TOSCANA](#44)
-   [DATI UMBRIA](#45)
-   [DATI VALLE D' AOSTA](#46)

GRAFICI ITALIA {#2}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Total cases summary

TABLE =

  1×4 table

    Contagiati    Deceduti    Tamponi    Dimessi
    __________    ________    _______    _______

      80539         8165      361060      10361 

 
Tabella riassuntiva casi giornalieri

TABLE =

  1×4 table

    Contagiati    Deceduti    Tamponi    Dimessi
    __________    ________    _______    _______

       6153         662        36615       999  

***********************
Stima e previsioni dati nazionali
 
Intervallo dati utilizzati per la stima del modello: 10-Mar :: 24-Mar
```

![](RUN_01.png) ![](RUN_02.png) ![](RUN_03.png) ![](RUN_04.png)

GRAFICI PUGLIA {#3}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_05.png) ![](RUN_06.png)

GRAFICI LOMBARDIA {#4}
-----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_07.png) ![](RUN_08.png)

GRAFICI VENETO {#5}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_09.png) ![](RUN_10.png)

GRAFICI PIEMONTE {#6}
----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_11.png) ![](RUN_12.png)

GRAFICI EMILIA ROMAGNA {#7}
----------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_13.png) ![](RUN_14.png)

GRAFICI CAMPANIA {#8}
----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_15.png) ![](RUN_16.png)

GRAFICI SICILIA (Non presente) {#9}
------------------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_17.png) ![](RUN_18.png)

GRAFICI ABRUZZO {#10}
---------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_19.png) ![](RUN_20.png)

GRAFICI BASILICATA {#11}
------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_21.png) ![](RUN_22.png)

GRAFICI CALABRIA {#12}
----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_23.png) ![](RUN_24.png)

GRAFICI CAMPANIA {#13}
----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_25.png) ![](RUN_26.png)

GRAFICI FRIULI VENEZIA GIULIA {#14}
-----------------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_27.png) ![](RUN_28.png)

GRAFICI LAZIO {#15}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_29.png) ![](RUN_30.png)

GRAFICI LIGURIA {#16}
---------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_31.png) ![](RUN_32.png)

GRAFICI MARCHE {#17}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_33.png) ![](RUN_34.png)

GRAFICI MOLISE {#18}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_35.png) ![](RUN_36.png)

GRAFICI P.A. Bolzano {#19}
--------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_37.png) ![](RUN_38.png)

GRAFICI P.A. Trento {#20}
-------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_39.png) ![](RUN_40.png)

GRAFICI SARDEGNA (Non presente) {#21}
-------------------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_41.png) ![](RUN_42.png)

GRAFICI TOSCANA {#22}
---------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_43.png) ![](RUN_44.png)

GRAFICI UMBRIA {#23}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_45.png) ![](RUN_46.png)

GRAFICI VALLE D' AOSTA {#24}
----------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

![](RUN_47.png) ![](RUN_48.png)

DATI PUGLIA {#25}
-----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Puglia
 

TABLE =

  6×2 table

           province            casiGiornalieri
    _______________________    _______________

    "Bari"                           51       
    "Barletta-Andria-Trani"          20       
    "Brindisi"                        6       
    "Foggia"                         28       
    "Lecce"                          13       
    "Taranto"                        18       

    "Casi giornalieri totali:"    "136"

    "Casi regione totali:"    "1150"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI LOMBARDIA {#26}
--------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Lombardia
 

TABLE =

  12×2 table

           province            casiGiornalieri
    _______________________    _______________

    "Bergamo"                        386      
    "Brescia"                        334      
    "Como"                            56      
    "Cremona"                        214      
    "Lecco"                           83      
    "Lodi"                            84      
    "Mantova"                         74      
    "Milano"                         848      
    "Monza e della Brianza"          163      
    "Pavia"                          107      
    "Sondrio"                         41      
    "Varese"                          34      

    "Casi giornalieri totali:"    "2424"

    "Casi regione totali:"    "34082"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI VENETO {#27}
-----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Veneto
 

TABLE =

  7×2 table

    province     casiGiornalieri
    _________    _______________

    "Belluno"           15      
    "Padova"           141      
    "Rovigo"            23      
    "Treviso"           77      
    "Venezia"           46      
    "Verona"            98      
    "Vicenza"           75      

    "Casi giornalieri totali:"    "475"

    "Casi regione totali:"    "6675"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI PIEMONTE {#28}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Piemonte
 

TABLE =

  8×2 table

           province           casiGiornalieri
    ______________________    _______________

    "Alessandria"                    34      
    "Asti"                           21      
    "Biella"                          9      
    "Cuneo"                          46      
    "Novara"                         60      
    "Torino"                        295      
    "Verbano-Cusio-Ossola"            8      
    "Vercelli"                       28      

    "Casi giornalieri totali:"    "501"

    "Casi regione totali:"    "6361"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI EMILIA ROMAGNA {#29}
-------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Emilia Romagna
 

TABLE =

  9×2 table

          province          casiGiornalieri
    ____________________    _______________

    "Bologna"                     146      
    "Ferrara"                       8      
    "ForlÃ¬-Cesena"                59      
    "Modena"                      143      
    "Parma"                        86      
    "Piacenza"                     91      
    "Ravenna"                      64      
    "Reggio nell'Emilia"          112      
    "Rimini"                       53      

    "Casi giornalieri totali:"    "762"

    "Casi regione totali:"    "10816"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI CAMPANIA {#30}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Campania
 

TABLE =

  5×2 table

     province      casiGiornalieri
    ___________    _______________

    "Avellino"            8       
    "Benevento"           0       
    "Caserta"            12       
    "Napoli"             39       
    "Salerno"            24       

    "Casi giornalieri totali:"    "83"

    "Casi regione totali:"    "1280"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI SICILIA {#31}
------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Sicilia
 

TABLE =

  9×2 table

       province        casiGiornalieri
    _______________    _______________

    "Agrigento"               5       
    "Caltanissetta"           5       
    "Catania"                38       
    "Enna"                   43       
    "Messina"                47       
    "Palermo"                12       
    "Ragusa"                  6       
    "Siracusa"               13       
    "Trapani"                 1       

    "Casi giornalieri totali:"    "170"

    "Casi regione totali:"    "1164"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI ABRUZZO {#32}
------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Abruzzo
 

TABLE =

  4×2 table

     province     casiGiornalieri
    __________    _______________

    "Chieti"            29       
    "L'Aquila"           4       
    "Pescara"           33       
    "Teramo"            67       

    "Casi giornalieri totali:"    "133"

    "Casi regione totali:"    "946"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI BASILICATA {#33}
---------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Basilicata
 

TABLE =

  2×2 table

    province     casiGiornalieri
    _________    _______________

    "Matera"           12       
    "Potenza"          16       

    "Casi giornalieri totali:"    "28"

    "Casi regione totali:"    "134"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI CALABRIA {#34}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Calabria
 

TABLE =

  5×2 table

          province          casiGiornalieri
    ____________________    _______________

    "Catanzaro"                    2       
    "Cosenza"                      8       
    "Crotone"                      9       
    "Reggio di Calabria"          18       
    "Vibo Valentia"                5       

    "Casi giornalieri totali:"    "42"

    "Casi regione totali:"    "391"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI CAMPANIA {#35}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Campania
 

TABLE =

  5×2 table

     province      casiGiornalieri
    ___________    _______________

    "Avellino"            8       
    "Benevento"           0       
    "Caserta"            12       
    "Napoli"             39       
    "Salerno"            24       

    "Casi giornalieri totali:"    "83"

    "Casi regione totali:"    "1280"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI VENEZIA GIULIA {#36}
-------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Friuli Venezia Giulia
 

TABLE =

  4×2 table

     province      casiGiornalieri
    ___________    _______________

    "Gorizia"            10       
    "Pordenone"          18       
    "Trieste"            30       
    "Udine"              29       

    "Casi giornalieri totali:"    "87"

    "Casi regione totali:"    "1215"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI LAZIO {#37}
----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Lazio
 

TABLE =

  5×2 table

     province      casiGiornalieri
    ___________    _______________

    "Frosinone"           50      
    "Latina"               8      
    "Rieti"                2      
    "Roma"               139      
    "Viterbo"              0      

    "Casi giornalieri totali:"    "199"

    "Casi regione totali:"    "2092"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI LIGURIA {#38}
------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Liguria
 

TABLE =

  4×2 table

     province      casiGiornalieri
    ___________    _______________

    "Genova"             -20      
    "Imperia"             34      
    "La Spezia"           12      
    "Savona"              -1      

    "Casi giornalieri totali:"    "25"

    "Casi regione totali:"    "1331"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI MARCHE {#39}
-----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Marche
 

TABLE =

  5×2 table

        province         casiGiornalieri
    _________________    _______________

    "Ancona"                   49       
    "Ascoli Piceno"            31       
    "Fermo"                    44       
    "Macerata"                 10       
    "Pesaro e Urbino"          42       

    "Casi giornalieri totali:"    "176"

    "Casi regione totali:"    "3063"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI MOLISE {#40}
-----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Molise
 

TABLE =

  2×2 table

      province      casiGiornalieri
    ____________    _______________

    "Campobasso"          25       
    "Isernia"              5       

    "Casi giornalieri totali:"    "30"

    "Casi regione totali:"    "94"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI P.A. Bolzano {#41}
-----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione P.A. Bolzano
 

TABLE =

  1×2 table

    province     casiGiornalieri
    _________    _______________

    "Bolzano"          48       

    "Casi giornalieri totali:"    "48"

    "Casi regione totali:"    "906"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI P.A. Trento {#42}
----------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione P.A. Trento
 

TABLE =

  1×2 table

    province    casiGiornalieri
    ________    _______________

    "Trento"          75       

    "Casi giornalieri totali:"    "75"

    "Casi regione totali:"    "1297"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI SARDEGNA {#43}
-------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Sardegna
 

TABLE =

  5×2 table

       province       casiGiornalieri
    ______________    _______________

    "Cagliari"               9       
    "Nuoro"                 26       
    "Oristano"               0       
    "Sassari"               13       
    "Sud Sardegna"           4       

    "Casi giornalieri totali:"    "52"

    "Casi regione totali:"    "494"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI TOSCANA {#44}
------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Toscana
 

TABLE =

  10×2 table

       province        casiGiornalieri
    _______________    _______________

    "Arezzo"                 20       
    "Firenze"                55       
    "Grosseto"               27       
    "Livorno"                25       
    "Lucca"                  45       
    "Massa Carrara"           4       
    "Pisa"                   33       
    "Pistoia"                10       
    "Prato"                  11       
    "Siena"                  23       

    "Casi giornalieri totali:"    "253"

    "Casi regione totali:"    "3225"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI UMBRIA {#45}
-----------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
Tabella casi giornalieri per la regione Umbria
 

TABLE =

  2×2 table

    province     casiGiornalieri
    _________    _______________

    "Perugia"          77       
    "Terni"            15       

    "Casi giornalieri totali:"    "92"

    "Casi regione totali:"    "778"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

DATI VALLE D' AOSTA {#46}
-------------------

``` {.codeoutput}
RUN DATA: 26-Mar-2020
    "Tabella casi giornalieri per la regione "    "Valle d'Aosta"

 

TABLE =

  1×2 table

    province    casiGiornalieri
    ________    _______________

    "Aosta"            7       

    "Casi giornalieri totali:"    "7"

    "Casi regione totali:"    "408"

fonte: elaborazione dei dati della protezione civile
***********************
Stima e previsione dati regionali
 
Intervallo dati utilizzati per la stima del modello: 12-Mar :: 24-Mar
 
```

\
[Published with MATLAB®
R2018a](https://www.mathworks.com/products/matlab/)\

