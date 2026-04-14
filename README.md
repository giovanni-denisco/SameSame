# Same Same - Party Game 🎮

**Same Same** è una web app interattiva progettata per movimentare serate tra amici. Il gioco mette alla prova la sintonia tra i partecipanti attraverso sfide di velocità, domande a risposta chiusa e votazioni di gruppo.

L'applicazione è una **PWA (Progressive Web App)** leggera, ottimizzata per l'uso su dispositivi mobile, che non richiede installazione e funziona direttamente dal browser.

---

## 🚀 Caratteristiche principali

- **Gestione Squadre:** Interfaccia intuitiva per aggiungere un numero illimitato di squadre.
- **Tre Modalità di Gioco:**
  - 🔵 **Sincronia (Standard):** Due o più opzioni tra cui scegliere contemporaneamente per testare l'affinità.
  - 🟡 **Flash:** Sfide rapide di associazione verbale o visiva.
  - 🟢 **Chi del gruppo?:** Domande basate sulla percezione sociale e sulla conoscenza tra gli amici.
- **Sistema di Punteggio in Tempo Reale:** Classifica dinamica aggiornata dopo ogni turno.
- **Design Adattivo:** Interfaccia dark-mode moderna con feedback visivi colorati basati sulla categoria della carta pescata.

---

## 🛠️ Implementazione Tecnica

Il progetto è stato sviluppato seguendo la filosofia "Vanilla Stack", senza l'ausilio di framework pesanti, per garantire massime prestazioni e tempi di caricamento istantanei.

### Tecnologie utilizzate:
- **HTML5:** Strutturazione semantica dei contenuti e dell'area di gioco.
- **CSS3 (Custom Properties):** - Utilizzo di variabili CSS per una gestione coerente dei colori.
  - Layout basato su **Flexbox** per la massima responsività.
  - Animazioni e transizioni fluide per il cambio delle carte.
- **JavaScript (ES6):**
  - Gestione dinamica del mazzo tramite array di oggetti.
  - Logica dei turni e calcolo dei punteggi.
  - Manipolazione del DOM in tempo reale per aggiornare l'interfaccia senza ricaricare la pagina.

### Architettura del codice:
Il cuore della logica risiede nella funzione `pescaCarta()`, che estrae casualmente una carta dal mazzo, ne identifica il tipo e applica dinamicamente le classi CSS necessarie per cambiare il tema visivo (bordi e badge) e la formattazione del testo.

---

## 📱 Come Giocare

1. **Aggiunta Squadre:** Inserisci i nomi dei team nella schermata iniziale.
2. **Setup:** Una volta inserite almeno due squadre, clicca su **GIOCA**.
3. **Turni:** L'app indicherà automaticamente a quale squadra tocca.
4. **Pesca:** Clicca su **PESCA CARTA** per visualizzare la sfida.
5. **Votazione:**
   - Se i giocatori hanno dato la stessa risposta/superato la prova, clicca su **UGUALI** (+1 punto e si continua a pescare).
   - Se le risposte sono diverse, clicca su **DIVERSI** (fine turno e passaggio alla squadra successiva).

---

## 🔧 Personalizzazione

È
