# Classificazione URL: Rilevazione di Phishing con Modello CART

Questo progetto analizza un dataset di URL per distinguere siti legittimi da phishing, utilizzando un modello di classificazione CART (Classification and Regression Tree).
Sono stati inclusi:
Una presentazione del progetto
Il notebook con tutto il codice (pulizia, feature engineering, analisi, modellazione, valutazione)
Una cartella con le visualizzazioni generate (alberi decisionali, grafici di correlazione, analisi TLD, ecc.)

---

### 📁 Contenuto del Repository

📘 **1. Presentazione**
La presentazione riassume:
- Il problema affrontato
- Le feature estratte dagli URL
- Le analisi svolte
- Il funzionamento del modello
- Le conclusioni

🧪 **2. Notebook completo (.ipynb)**
Il notebook contiene:
- Pulizia e preprocessamento del dataset
- Estrazione e trasformazione delle feature
- Analisi esplorativa (EDA)
- Calcolo della correlazione tra feature e classe
- Addestramento del modello CART
- Visualizzazione dei primi livelli dell’albero
- Valutazione delle performance

📊 **3. Cartella “plots/”**
Qui si trovano tutti i grafici generati dal notebook, tra cui:
- Distribuzione dei TLD
- Percentuale di phishing per TLD
- Heatmap delle correlazioni
- Visualizzazione dell’albero decisionale
- Boxplot e distribuzioni per le feature

---

### 🧠 Obiettivo del Progetto
Il progetto mira a:
- Identificare pattern ricorrenti negli URL malevoli
- Evidenziare feature che distinguono maggiormente phishing e legittimi
- Addestrare un modello interpretabile e visivamente analizzabile
- Valutare l’efficacia del modello tramite metriche standard

---

### 🌳 Modello Utilizzato

CART — Classification and Regression Tree:
- Semplice da interpretare
- Ottimo per capire quali feature sono più discriminanti
- Rappresentabile graficamente (primi livelli nel notebook)

Il modello è stato addestrato sulle feature estratte dal dataset, tra cui:
- Lunghezza degli URL
- Numero di caratteri speciali
- TLD
- Numero di sottodomini
- Indicatori strutturali dell’URL
- Presenza o assenza di keyword sospette

---

### 📈 Principali Risultati

- Le feature maggiormente correlate con URL legittimi presentano comportamenti coerenti con siti stabili e strutturati.
- Le feature correlate con URL di phishing mostrano pattern più irregolari, tipici di URL generati artificialmente.
- Il modello CART ha permesso di individuare decisioni chiare e interpretabili.
- Buone performance globali (precision, recall, accuracy — valori riportati nel notebook).

---

### 🛠️ Tecnologie Utilizzate

- Python
- Librerie come pandas, numpy, matplotlib, seaborn, scikit-learn
- Jupyter Notebook

---

### 👥 Autori

Progetto realizzato da:
- Davide Cristallo
- Lorenzo Rota
- Thomas Petrò

---

***Fonte dataset: https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset***
