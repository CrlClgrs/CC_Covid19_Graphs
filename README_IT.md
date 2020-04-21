# CC_Covid19_Graphs
(English version [here](README.md))

Per navigare attraverso i grafici seguire il seguente link:

[EN]
https://crlclgrs.github.io/CC_Covid19_Graphs/

[IT]
https://crlclgrs.github.io/CC_Covid19_Graphs/it/index.html


Se avete domande, contattatemi su Twitter:
[@ClgClgrs](https://twitter.com/intent/tweet?screen_name=CrlClgrs&ref_src=twsrc%5Etfw)

## Updated to 21-Apr-2020

Questo è un semplice progetto che prende i dati da:
[Dati COVID-19 Italia](https://github.com/pcm-dpc/COVID-19).

I grafici sono realizzati con la splendida libreria [plot.ly](https://plotly.com/).

Si possono trovare grafici relativi a:
- NAZIONE / ITALIA
- ZONA GEOGRAFICA / NORD / CENTRO / SUD
- REGIONE / Tutte le regioni italiane


## Spiegazione dei Grafici

### ABSOLUTE_STACKS
#### TOTALE CASI
Il numero di casi fino ad oggi (positivi + deceduti + guariti)
#### POSITIVI
Il numero di persone attualmente positive
#### OSPEDALIZZATI
Il numero di persone attualmente in ospedale
#### GUARITI
Il numero di persone guarite fino ad oggi
#### DECEDUTI
Il numero di persone decedute fino ad oggi
#### TERAPIA INTENSIVA
Il numero di persone attualmente in terapia intensiva
#### TOTALE CASI STIM CON [DELTA GIORNO(TOTALE CASI)<FIT GAUSS>]
Il valore di oggi di TOTALE CASI è ricalcolto usando il valore di ieri di TOTALE CASI + la stima della differenza trovata da DELTA GIORNO(TOTALE CASI)<FIT GAUSS>
#### POSITIVI<FIT GAUSS>
Un fitting gaussiano di POSITIVI
#### GUARITI STIM CON [DELTA GIORNO(GUARITI)<FIT GAUSS>]
Il valore di oggi di GUARITI è ricalcolto usando il valore di ieri di GUARITI + la stima della differenza trovata da DELTA GIORNO(GUARITI)<FIT GAUSS>
#### DECEDUTI STIM CON [DELTA GIORNO(DECEDUTI)<FIT GAUSS>]
Il valore di oggi di DECEDUTI è ricalcolto usando il valore di ieri di DECEDUTI + la stima della differenza trovata da DELTA GIORNO(DECEDUTI)<FIT GAUSS>
### RELATIVE_CHARTS_1
#### DECEDUTI / POSITIVI
Valore di DECEDUTI / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### GUARITI / POSITIVI
Valore di GUARITI / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### POSITIVI DI OGGI / POSITIVI
Valore di POSITIVI DI OGGI / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(POSITIVI) / POSITIVI
Valore di DELTA GIORNO(POSITIVI) / Valore di POSITIVI --- entrambi al valore del giorno corrente
### RELATIVE_CHARTS_2
#### POSITIVI / TAMPONI
Valore di POSITIVI / Valore di TAMPONI --- entrambi al valore del giorno corrente
#### POSITIVI / TAMPONI<FIT GAUSS>
Un fitting gaussiano di POSITIVI / TAMPONI
#### POSITIVI DI OGGI / DELTA GIORNO(TAMPONI)
Valore di POSITIVI DI OGGI / Valore di DELTA GIORNO(TAMPONI) --- entrambi al valore del giorno corrente
#### DELTA GIORNO(POSITIVI) / DELTA GIORNO(TAMPONI)
Valore di DELTA GIORNO(POSITIVI) / Valore di DELTA GIORNO(TAMPONI) --- entrambi al valore del giorno corrente
### NEW_VALUES_IN_DAY
#### POSITIVI DI OGGI
Il numero di persone trovate positive nel giorno
#### DELTA GIORNO(GUARITI)
Valore di GUARITI oggi - Valore di GUARITI ieri
#### DELTA GIORNO(DECEDUTI)
Valore di DECEDUTI oggi - Valore di DECEDUTI ieri
#### DELTA GIORNO(OSPEDALIZZATI)
Valore di OSPEDALIZZATI oggi - Valore di OSPEDALIZZATI ieri
#### DELTA GIORNO(TERAPIA INTENSIVA)
Valore di TERAPIA INTENSIVA oggi - Valore di TERAPIA INTENSIVA ieri
#### DELTA GIORNO(GUARITI)
Valore di GUARITI oggi - Valore di GUARITI ieri
#### DELTA GIORNO(GUARITI)<FIT GAUSS>
Un fitting gaussiano di DELTA GIORNO(GUARITI)
#### DELTA GIORNO(DECEDUTI)
Valore di DECEDUTI oggi - Valore di DECEDUTI ieri
#### DELTA GIORNO(DECEDUTI)<FIT GAUSS>
Un fitting gaussiano di DELTA GIORNO(DECEDUTI)
### NEW_VALUES_ON_TOT_POSITIVI
#### DELTA GIORNO(POSITIVI) / POSITIVI
Valore di DELTA GIORNO(POSITIVI) / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(OSPEDALIZZATI) / POSITIVI
Valore di DELTA GIORNO(OSPEDALIZZATI) / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(GUARITI) / POSITIVI
Valore di DELTA GIORNO(GUARITI) / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI
Valore di DELTA GIORNO(TERAPIA INTENSIVA) / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(DECEDUTI) / POSITIVI
Valore di DELTA GIORNO(DECEDUTI) / Valore di POSITIVI --- entrambi al valore del giorno corrente
#### DELTA GIORNO(POSITIVI) / POSITIVI - POLY FIT ORD 3
Un fitting polinomiale di DELTA GIORNO(POSITIVI) / POSITIVI stimato con ordine 3
#### DELTA GIORNO(OSPEDALIZZATI) / POSITIVI - POLY FIT ORD 3
Un fitting polinomiale di DELTA GIORNO(OSPEDALIZZATI) / POSITIVI stimato con ordine 3
#### DELTA GIORNO(GUARITI) / POSITIVI - POLY FIT ORD 3
Un fitting polinomiale di DELTA GIORNO(GUARITI) / POSITIVI stimato con ordine 3
#### DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI - POLY FIT ORD 3
Un fitting polinomiale di DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI stimato con ordine 3
#### DELTA GIORNO(DECEDUTI) / POSITIVI - POLY FIT ORD 3
Un fitting polinomiale di DELTA GIORNO(DECEDUTI) / POSITIVI stimato con ordine 3
#### DELTA GIORNO(POSITIVI) / POSITIVI - POLY FIT ORD 2
Un fitting polinomiale di DELTA GIORNO(POSITIVI) / POSITIVI stimato con ordine 2
#### DELTA GIORNO(OSPEDALIZZATI) / POSITIVI - POLY FIT ORD 2
Un fitting polinomiale di DELTA GIORNO(OSPEDALIZZATI) / POSITIVI stimato con ordine 2
#### DELTA GIORNO(GUARITI) / POSITIVI - POLY FIT ORD 2
Un fitting polinomiale di DELTA GIORNO(GUARITI) / POSITIVI stimato con ordine 2
#### DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI - POLY FIT ORD 2
Un fitting polinomiale di DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI stimato con ordine 2
#### DELTA GIORNO(DECEDUTI) / POSITIVI - POLY FIT ORD 2
Un fitting polinomiale di DELTA GIORNO(DECEDUTI) / POSITIVI stimato con ordine 2
#### DELTA GIORNO(POSITIVI) / POSITIVI - POLY FIT ORD 1
Un fitting polinomiale di DELTA GIORNO(POSITIVI) / POSITIVI stimato con ordine 1
#### DELTA GIORNO(OSPEDALIZZATI) / POSITIVI - POLY FIT ORD 1
Un fitting polinomiale di DELTA GIORNO(OSPEDALIZZATI) / POSITIVI stimato con ordine 1
#### DELTA GIORNO(GUARITI) / POSITIVI - POLY FIT ORD 1
Un fitting polinomiale di DELTA GIORNO(GUARITI) / POSITIVI stimato con ordine 1
#### DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI - POLY FIT ORD 1
Un fitting polinomiale di DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI stimato con ordine 1
#### DELTA GIORNO(DECEDUTI) / POSITIVI - POLY FIT ORD 1
Un fitting polinomiale di DELTA GIORNO(DECEDUTI) / POSITIVI stimato con ordine 1
### NEW_VALUES_STACKS
#### DELTA GIORNO(POSITIVI)
Valore di POSITIVI oggi - Valore di POSITIVI ieri
#### POSITIVI DI OGGI
Il numero di persone trovate positive nel giorno
#### -DELTA GIORNO(DECEDUTI)
Negativo di DELTA GIORNO(DECEDUTI)
#### -DELTA GIORNO(GUARITI)
Negativo di DELTA GIORNO(GUARITI)
### NEW_VALUES_DIFF_TO_YESTERDAY
#### DELTA GIORNO(DELTA GIORNO(POSITIVI))
Valore di DELTA GIORNO(POSITIVI) oggi - Valore di DELTA GIORNO(POSITIVI) ieri
#### DELTA GIORNO(DELTA GIORNO(GUARITI))
Valore di DELTA GIORNO(GUARITI) oggi - Valore di DELTA GIORNO(GUARITI) ieri
#### DELTA GIORNO(DELTA GIORNO(DECEDUTI))
Valore di DELTA GIORNO(DECEDUTI) oggi - Valore di DELTA GIORNO(DECEDUTI) ieri
#### DELTA GIORNO(DELTA GIORNO(TERAPIA INTENSIVA))
Valore di DELTA GIORNO(TERAPIA INTENSIVA) oggi - Valore di DELTA GIORNO(TERAPIA INTENSIVA) ieri
### FORECASTS_ON_SPEED
#### POSITIVI
Il numero di persone attualmente positive
#### POSITIVI STIM CON COEFF [DELTA GIORNO(POSITIVI) / POSITIVI - POLY FIT ORD 2]
Il valore di oggi di POSITIVI è ricalcolto usando il valore di ieri di POSITIVI * il coefficiente stimato con DELTA GIORNO(POSITIVI) / POSITIVI - POLY FIT ORD 2
#### OSPEDALIZZATI
Il numero di persone attualmente in ospedale
#### OSPEDALIZZATI STIM CON COEFF [DELTA GIORNO(OSPEDALIZZATI) / POSITIVI - POLY FIT ORD 2]
Il valore di oggi di OSPEDALIZZATI è ricalcolto usando il valore di ieri di OSPEDALIZZATI * il coefficiente stimato con DELTA GIORNO(OSPEDALIZZATI) / POSITIVI - POLY FIT ORD 2
#### GUARITI
Il numero di persone guarite fino ad oggi
#### GUARITI STIM CON COEFF [DELTA GIORNO(GUARITI) / POSITIVI - POLY FIT ORD 3]
Il valore di oggi di GUARITI è ricalcolto usando il valore di ieri di GUARITI * il coefficiente stimato con DELTA GIORNO(GUARITI) / POSITIVI - POLY FIT ORD 3
#### DECEDUTI
Il numero di persone decedute fino ad oggi
#### DECEDUTI STIM CON COEFF [DELTA GIORNO(DECEDUTI) / POSITIVI - POLY FIT ORD 2]
Il valore di oggi di DECEDUTI è ricalcolto usando il valore di ieri di DECEDUTI * il coefficiente stimato con DELTA GIORNO(DECEDUTI) / POSITIVI - POLY FIT ORD 2
#### TERAPIA INTENSIVA
Il numero di persone attualmente in terapia intensiva
#### TERAPIA INTENSIVA STIM CON COEFF [DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI - POLY FIT ORD 2]
Il valore di oggi di TERAPIA INTENSIVA è ricalcolto usando il valore di ieri di TERAPIA INTENSIVA * il coefficiente stimato con DELTA GIORNO(TERAPIA INTENSIVA) / POSITIVI - POLY FIT ORD 2
