# 📊 Esercitazione Finale - Data Analyst (Excel & Power Pivot)

## 📌 Obiettivo del progetto

La Regione Marche ha richiesto lo sviluppo di un sistema per la **gestione e analisi delle strutture ricettive del territorio**. Questo progetto è stato realizzato utilizzando **Excel avanzato**, **Power Query** e **Power Pivot** per ottimizzare, analizzare e visualizzare i dati provenienti da due dataset principali.

---

## 📂 Dati forniti

- **elencostrutture.xlsx**  
  Contiene informazioni dettagliate su ogni struttura ricettiva (nome, categoria, indirizzo, città, ecc.)

- **prezzimedi.csv**  
  Riporta i **prezzi medi** delle strutture per città.

---

## ✅ Esercizi svolti

### 🔹 Esercizio 1: Maschera di ricerca dinamica

Nel file `ELENCOSTRUTTURE.xlsx`, è stata creata una maschera di **ricerca interattiva**:

- Aggiunto un **menù a tendina** nella cella `C3` per selezionare il **Nome della Struttura**.
- Completamento automatico delle informazioni relative alla struttura selezionata (celle azzurre).
- Calcolo dinamico:
  - Numero **totale** di strutture presenti nella regione.
  - Numero di strutture **nella stessa città** della struttura selezionata (celle grigie).

---

### 🔹 Esercizio 2: Tabella Pivot

Nel foglio `PIVOT` è stata creata una **tabella pivot** che mostra:

- Il **numero di strutture** per **categoria**.
- Possibilità di **filtrare per città**.

Questo consente una visione immediata della distribuzione delle strutture ricettive per tipologia e località.

---

### 🔹 Esercizio 3: Modello dati in Excel

Nel file `MODELLO DATI.xlsx`:

1. **Power Query**:
   - Caricamento della tabella "Strutture Ricettive" da `ELENCOSTRUTTURE.xlsx`.
   - Pulizia dei dati: rimozione righe vuote, uniformazione maiuscole/minuscole, eliminazione spazi superflui, ecc.
   - Caricamento della tabella "Prezzi" da `prezzimedi.csv` con relative trasformazioni.

2. **Power Pivot**:
   - Inserimento delle due tabelle nel modello dati.
   - Creazione di una **relazione** tra le tabelle basata sulla **città**.
   - Pronta per ulteriori analisi e visualizzazioni dinamiche.

---

## 💼 Tecnologie e strumenti utilizzati

- Microsoft Excel (con funzionalità avanzate)
- Power Query
- Power Pivot
- Tabelle Pivot
- Data cleaning & transformation

---

## 🙋‍♀️ Autrice

**Alexandra Belacurencu**  
_Data Analyst in formazione, con passione per i dati, la chiarezza e la trasformazione delle informazioni in conoscenza._

📫 Contatti: [LinkedIn](https://www.linkedin.com/in/alexandra-belacurencu | [Email](mailto:alexandra.belacurencu@gmail.com)

---

## 📜 Motto personale

> “Chi osa può cambiare il suo destino. Ogni passo è un'opportunità, ogni sogno è una possibilità.”

---

## 📁 Struttura del repository
Esercitazione/ │ ├── ELENCOSTRUTTURE.xlsx # Maschera di ricerca e dati strutture ├── PREZZIMEDI.csv # Prezzi medi per città └── MODELLO DATI.xlsx # Modello dati con Power Query e Power Pivot

---

## ✅ Conclusioni

Questo progetto mostra come l'analisi dei dati, anche in Excel, possa supportare una gestione informata delle strutture ricettive di un territorio, attraverso l'integrazione tra **interattività**, **modellazione dati** e **automazione dei processi**.

---
