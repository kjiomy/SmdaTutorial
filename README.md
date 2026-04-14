# Social Media Data Analysis

Progetto finale per il corso di **Data Analysis** presso l'**Università di Catania**.  
L'obiettivo del progetto è l'estrazione, l'elaborazione e la visualizzazione di dati provenienti da piattaforme social tramite l'utilizzo di REST API e librerie Python.

---

## Panoramica del Progetto
Il software permette di interfacciarsi con le API dei social media per raccogliere dataset significativi, pulire i dati e generare grafici e insight sull'attività degli utenti. Il progetto include un'analisi tecnica completa e un tutorial passo-passo per replicare i risultati.

### Caratteristiche principali:
* **Data Extraction:** Utilizzo di REST API con autenticazione sicura.
* **Data Cleaning:** Gestione dei dati mancanti e normalizzazione tramite Pandas.
* **Visualizzazione:** Creazione di grafici statistici (Matplotlib/Seaborn).
* **Documentazione:** Tutorial interattivo in formato Jupyter Notebook.

---

## Tecnologie Utilizzate
* **Linguaggio:** Python 3.x
* **Librerie principali:** Pandas, Matplotlib, Requests, python-dotenv
* **Strumenti:** Jupyter Notebook, Git, REST APIs

---

## Installazione e Setup

### 1. Clonazione del repository
```bash
git clone [https://github.com/tuo-username/social-media-data-analysis.git](https://github.com/tuo-username/social-media-data-analysis.git)
cd social-media-data-analysis
```

### 2. Configurazione dell'ambiente
Si consiglia l'uso di un ambiente virtuale:
```bash
python -m venv venv
source venv/bin/activate  # Su Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Gestione delle Credenziali
Per motivi di sicurezza, le chiavi API non sono incluse.  
1. Copia il file `.env.example` e nominalo `.env`.
2. Inserisci il tuo `CLIENT_ID` e il tuo `TOKEN` all'interno del file `.env`.
```text
SOCIAL_API_KEY=inserisci_qui
