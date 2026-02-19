# S1P2 – Flexbox Components Exercise

## 📌 Descrizione

Questo progetto consiste nella realizzazione di tre componenti utilizzando esclusivamente **CSS Flexbox**, come richiesto dall’esercizio S1P2:

- Product Card  
- Navigation Bar  
- Responsive Article (senza media queries)  

L’obiettivo dell’esercizio è dimostrare la comprensione del modello di distribuzione dello spazio di Flexbox (main axis e cross axis), evitando layout forzati con margin o dimensioni fisse inutili.

---

## 🎯 Obiettivi dell’esercizio

- Utilizzare `display: flex` per costruire layout strutturati
- Gestire correttamente:
  - `flex-direction`
  - `justify-content`
  - `align-items`
  - `flex-wrap`
  - `flex` shorthand
- Realizzare una versione mobile dell’articolo **senza utilizzare media queries**
- Utilizzare gli asset forniti nel pacchetto ufficiale

---

## 🧱 Componenti realizzati

### 1️⃣ Product Card

Struttura verticale con:
- Immagine in alto
- Blocco informativo sotto
- Titolo e prezzo distribuiti su una riga con `justify-content: space-between`
- Bottone centrato
- Bordi arrotondati

Layout gestito con:
- `flex-direction: column`
- Allineamento sull’asse trasversale
- Distribuzione dello spazio sull’asse principale

---

### 2️⃣ Navigation Bar

Barra di navigazione orizzontale con:
- Pulsanti stile "pill"
- Pulsante centrale più grande con icona
- Distribuzione uniforme degli elementi

Layout gestito con:
- `display: flex`
- `justify-content` per la distribuzione orizzontale
- `align-items` per l’allineamento verticale

---

### 3️⃣ Responsive Article (senza media queries)

Versione desktop:
- Immagine a sinistra
- Testo a destra

Versione mobile:
- Testo sopra
- Immagine sotto

Il comportamento responsive è ottenuto utilizzando:
- `flex-wrap`
- `flex` con `flex-basis`
- `wrap-reverse` per invertire l’ordine quando il layout va a capo

Non sono state utilizzate media queries.

---

## 🔘 Toggle Mobile (Extra Feature)

È stato aggiunto un pulsante che permette di forzare manualmente la visualizzazione mobile dell’articolo anche su desktop.

Il funzionamento è basato su:
- `classList.toggle()` in JavaScript
- Applicazione di una classe `.is-mobile`
- Gestione del layout interamente via CSS

Il JavaScript non modifica il layout direttamente: si limita ad aggiungere o rimuovere una classe.

---

## 📂 Struttura del progetto
.
├── index.html
├── style.css
└── assets/

