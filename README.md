# 🏟️ Sistema di Gestione Centro Sportivo — Progetto di Basi di Dati

Progetto universitario sviluppato per l'esame di **Basi di Dati** (Corso di Laurea in Informatica — Università degli Studi di Napoli "Parthenope").  
Il sistema modella, progetta e implementa una base di dati relazionale completa per la gestione operativa, amministrativa e logistica di un centro sportivo polifunzionale.

---

## 🎯 Obiettivi del Progetto

L'obiettivo principale è garantire l'integrità dei dati, eliminare le ridondanze e automatizzare i controlli operativi tipici di una struttura sportiva, tra cui:
* **Gestione Anagrafica:** Registrazione di soci/tesserati, istruttori qualificati e personale amministrativo.
* **Prenotazione Campi e Strutture:** Gestione degli slot orari per diverse discipline (calcio, tennis, padel, nuoto, palestra) con prevenzione automatica delle sovrapposizioni.
* **Corsi e Abbonamenti:** Gestione dei piani di abbonamento (mensili, annuali, ingressi), iscrizioni ai corsi collettivi e monitoraggio delle capienze massime.
* **Certificazioni e Scadenze:** Controllo della validità dei certificati medici agonistici/non agonistici e dello stato dei pagamenti.

---

## 🏗️ Fasi di Progettazione

Il database è stato realizzato seguendo l'intero ciclo di vita dell'ingegneria dei dati:

1. **Analisi dei Requisiti:** Raccolta e formalizzazione delle regole aziendali (Business Rules) e del glossario dei termini.
2. **Progettazione Concettuale (Schema E-R):** Identificazione di entità, attributi, relazioni, cardinalità e gerarchie di generalizzazione.
3. **Ristrutturazione e Progettazione Logica:** Traduzione dello schema E-R nel modello relazionale, normalizzazione (fino alla **3NF / BCNF**) e analisi delle ridondanze.
4. **Progettazione Fisica e Implementazione SQL:** Creazione dello schema tramite DDL, definizione di chiavi primarie, chiavi esterne, vincoli `CHECK` e indici per l'ottimizzazione delle prestazioni.

---

## 🛠️ Tecnologie e Competenze Utilizzate

* **DBMS:** Oracle Database
* **Linguaggi:** SQL (DDL, DML, DQL) e PL/SQL 
* **Modeling & Tools:** Draw.io / ERDPlus / SQL Developer Data Modeler
* **Concetti Chiave:** Normalizzazione, Integrità Referenziale, Trigger, Viste (`VIEW`), Query annidate e funzioni di aggregazione (`GROUP BY`, `HAVING`).

