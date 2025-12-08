# Classificazione URL: Rilevazione di Phishing con Modello CART

Questo progetto analizza un dataset di URL per distinguere siti legittimi da phishing utilizzando un modello di classificazione CART (Classification and Regression Tree).

---

### 📁 Contenuto del Repository

📘 **1. Presentazione PDF**

La presentazione riporta:
- I dati utilizzati e il problema affrontato
- Le feature utilizzate (e quali scartate)
- La preparazione dei dati
- Le analisi svolte su di essi
- Il funzionamento del modello
- I risultati ottenuti
- La validazione dei risultati ottenuti

🧪 **2. Notebook Python**

Il notebook contiene:
- Pulizia e preprocessamento del dataset
- Estrazione e trasformazione delle feature
- Analisi esplorativa (EDA)
- Calcolo della correlazione tra feature e classe
- Addestramento del modello CART
- Visualizzazione dei primi livelli dell’albero
- Valutazione delle performance

📊 **3. Cartella “plots”**

Qui si trovano tutti i grafici generati dal notebook in formato immagine con relativo numero per il riferimento al notebook Python.

---

### 🧠 Obiettivo del Progetto

Il progetto mira a:
- Identificare pattern ricorrenti negli URL malevoli
- Evidenziare feature che distinguono maggiormente phishing e legittimi
- Addestrare un modello interpretabile e visivamente analizzabile
- Valutare l’efficacia del modello tramite metriche apposite

---

### 🌳 Modello Utilizzato

CART — Classification and Regression Tree, scelto perché:
- Semplice da interpretare
- Ottimo per capire quali feature sono più discriminanti
- Rappresentabile graficamente

Il modello è stato addestrato sulle feature estratte dal dataset, tra cui:
- Numero di slash nell'URL
- Utilizzo di HTTPS
- Presenza di caratteri speciali nell'URL
- Presenza di titolo nella pagina
- Numero di sottodomini
- ecc

---

### 📈 Principali Risultati

- Le feature maggiormente correlate con URL legittimi presentano comportamenti coerenti con siti stabili e strutturati
- Le feature correlate con URL di phishing mostrano pattern più irregolari, tipici di URL generati artificialmente
- Il modello CART ha permesso di individuare decisioni chiare e interpretabili
- Buone performance globali (i valori sono riportati nella presentazione e nel notebook)

---

### 🛠️ Tecnologie Utilizzate

- Python
- Librerie pandas, numpy, matplotlib, seaborn, scikit-learn, collections, 
- Jupyter Notebook

---

### 👥 Autori

Progetto realizzato da:
- Davide Cristallo
- Lorenzo Rota
- Thomas Petrò

---

***Fonte dataset: https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset***
