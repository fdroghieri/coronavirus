# coronavirus

repository dedicato all'emergenza COVID-19 in Umbria
(in costruzione)


| Nome campo                  | Descrizione                       | Equivalente nazionale                  | Formato                       | Esempio             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                        | Data dell’informazione            | data                                   | YYYY-MM-DD HH:MM:SS (ISO 8601) Ora italiana | 2020-03-05 12:15:45 |
| **stato**                       | Stato di riferimento              | stato                                  | XYZ (ISO 3166-1 alpha-3)      | ITA                 |
| **codice_geo**              | Codice area geografica (codice ISTAT per i comuni) o della struttura (ad es. ospedali) |         | Numero                        | 55004                  |
| **denominazione_geo**       | Denominazione dell'area o struttutra       |                                                   | Testo                         | Amelia             |
| **lat**                         | Latitudine (centroide)            | lat                               | WGS84                         | 42.6589177          |
| **long**                        | Longitudine (centroide)           | log                              | WGS84                         | 13.70439971         |
| **residenti**                 | Totale residenti Istat 2019              |                       | Numero                        | 11819                   |
| **casi_positivi**                 | Totale dei casi positivi ad oggi diagnosticati; somma: totale_attualmente_positivi + dimessi_guariti + deceduti              | totale_casi         | Numero                        | 3                   |
| **isolamento_volontario**      | Attuale numero di persone (non testate positive) che sono in isolamento fiduciario in casa o altra struttura non ospedaliera |                        | Numero                        | 3                   |
| **in_isolamento_domiciliare**      | Attuale numero di casi positivi che sono in isolamento contumaciale in casa o altra struttura non ospedaliera | isolamento_domiciliare                       | Numero                        | 3                   |
| **usciti_da_isolamento**      | Totale numero di casi positivi usciti dall'isolamento |                        | Numero                        | 3                   |
| **ricoverati_totale**        | Attuale numero dei casi positivi che sono ricoverati in ospedale; somma: di_cui_ricoverati_con_sintomi + di_cui_ricoverati_in_terapia_intensiva              | totale_ospedalizzati            | Numero                        | 3                   |
| **di_cui_ricoverati_con_sintomi**      | Attuale numero di casi positivi che sono ricoverati in reparti diversi dalla terapia intensiva | ricoverati_con_sintomi    | Numero                        | 3                   |
| **di_cui_ricoverati_in_terapia_intensiva**           | Attuale numero di casi positivi ricoverati in terapia intensiva   | terapia_intensiva                         | Numero                        | 3                   |
| **attualmente_positivi** | Attuale numero di casi positivi; somma: ricoverati_totale + in_isolamento_domiciliare)      | totale_attualmente_positivi  | Numero                        | 3                   |
| **nuovi_positivi**  | Nuovi attualmente positivi; cioè: attualmente_positivi - attualmente_positivi _del giorno prima_       | nuovi_attualmente_positivi  | Numero                        | 3                   |
| **tasso_positivi_x1000**  | Tasso totale casi positivi ogni 1000 abitanti residenti; cioè: casi_positivi / residenti * 1000       |   | Numero                        | 0,85                   |
| **guariti**             | Totale dei casi positivi che risolvono i sintomi dell’infezione da Covid-19 e che risultano negativi in due test consecutivi effettuati a distanza di 24 ore uno dall’altro           | dimessi_guariti                            | Numero                        | 3                   |
| **deceduti**                    | Totale dei casi positivi che sono deceduti, anche con diagnosi post-mortem; La conferma che la causa del decesso è attribuibile esclusivamente al SARS-CoV-2 verrà dichiarata dall’Istituto Superiore di Sanità | deceduti                                  | Numero                        | 3                   |
| **tamponi_eseguiti**                     | Totale dei tamponi (test) effettuati, un soggetto può essere sottoposto a più tamponi quindi non è indicativo delle persone controllate                    | tamponi                        | Numero                        | 3                   |
