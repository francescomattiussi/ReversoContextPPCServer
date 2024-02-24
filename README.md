# ReversoContextPPC Server

> Il traduttore Reverso Context per l'architettura PPC e Intel

## Descrizione

Per maggiori informazioni su questo progetto visitare [questa pagina](https://github.com/francescomattiussi/ReversoContextPPCClient/tree/v1.0.0). Lo script si occupa di inviare richieste alle API di Reverso e inviare i dati ottenuti a un host presente sulla rete locale LAN, i dati inoltrati tra gli host locali avvengono tramite richieste HTTP.

Questa sezione del progetto, come quella lato client, non è attualmente in fase di sviluppo.

## Implementazione

Questo script richiede la versione 3.9 di Python e poggia sul framework Flask per la gestione delle richieste HTTPS, mentre viene usata la libreria [reverso_context_api](https://github.com/flagist0/reverso_context_api) per la gestione delle richieste alle API pubbliche di Reverso.

