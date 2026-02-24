## Introduzione a Docker

### Un po' di contesto
> Inizialmente ogni applicazione veniva eseguite su un unico server fisico, praticamente un server per ogni applicazione.
>> Problema: Spreco di Risorse

> Successivamente ci siamo orientati verso la virtualizzazione che ha reso le cose sicuramente migliori, un'unico server fisico poteva girare più di una applicazione.
>> Problemi: Ogni macchina virtuale necessita del proprio sistema operativo, consomendo risorse in termini di CPU, RAM e Spazio Disco, oltre ad eventuali costi di licenze.


### I Container
    Ci offrono la possibilità di 'PACCHETTIZZARE' UN'APPLICAZIONE e renderla trasportabile e disponibile verso altri sistemi.

    I container sono un'ambiente isolato che funzioni nello stesso sistema operativo.

    Un container è una piccola entità al cui interno viene eseguite un'applicazione in maniera autonoma, contenendo tutti i componenti e le dipendenze essenziale, cioè rende i container trasportabili che è uno dei maggiori punti di forza di questa tecnologia.


### Docker
    Risolve un problema fondamentale: La necessità di avere degli ambiente di sviluppo identici per ogni singolo componente applicativo e per ogni sviluppatore nelle sue macchine diverse.

- **BUILD** -> *COSTRUISCI*
- **SHIP** -> *SPEDISCI*/*SPOSTA*
- **RUN** -> *ESEGUI*


#### Docker Engine 
    Il componenete principale di Docker, si occupa di eseguire il container.

- Esistono due versioni di Docker
    - Enterprise Edition
    - Community Edition


#### Docker è OpenSource
-   La maggiore parte è scritta con Go

#### L'Open Container Initiative (OCI)
- Un'organizzazione che se occupa di standardizzare l'infrastruttura DOCKER, al momento sono stati pubblicati due standard (vedremo più avante):
    -   image-spec
    -   Runtime-spec