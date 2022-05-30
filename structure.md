## Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario Potete usare uno dei seguenti metodi per consegnare l'esercizio: fate un file di markdown come visto in classe e pushatelo fate un diagramma ed esportatelo in formato png fate una tabella con google sheet o excell ed esportatela come immagine o pdf.


## Model: Car

## Table: Cars

- id:                                   bigint PK(NOTNULL, AUTOINCREMENT, UNIQUE)                           
- marca:                                VARCHAR(200) NOTNULL
- modello:                              VARCHAR(200) NOTNULL
- image:                                VARCHAR(255) NULL
- cilindrata:                           CHAR(16) NULL
- n_km:                                 CHAR(8) NULL
- anno_immatricolazione:                YEAR NULL
- carburante:                           VARCHAR(50) NULL
- trasmissione:                         VARCHAR(20) NULL
- potenza:                              CHAR(16) NULL
- descrizione:                          TEXT NULL
- prezzo:                               DECIMAL(6,3) NULL
- proprietari_precedenti:               TINYINT NULL
- categoria:                            VARCHAR(20) NOTNULL
- garanzia:                             TINYINT NULL
- n_porte:                              CHAR(8) NULL
- consumi:                              VARCHAR(100) NULL
- allestimento:                         VARCHAR(20) NULL
- class_emissioni:                      CHAR(8) NULL
- paese_origine:                        VARCHAR(70) NOTNULL DEFAULT('italy')