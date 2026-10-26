# 🫧 Bubble Echoes

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Mobile First](https://img.shields.io/badge/Mobile-First-00f0ff?style=for-the-badge)

**Bubble Echoes** è un moderno arcade *Bubble Shooter* sviluppato con un'architettura **single-file** (zero dipendenze esterne), progettato specificamente per dispositivi mobili con controlli *Pure Touch* e grafica vettoriale ultra-nitida.

🎮 **[Gioca alla Live Demo su GitHub Pages](https://davide23567.github.io/bubble-echoes/)**

---

## ✨ Caratteristiche Principali

* **🎯 Controlli Pure Touch & Mira Sniper:** Tocca e trascina in qualsiasi punto dello schermo per mirare; rilascia per sparare. Il raggio laser animato calcola fino a **5 rimbalzi sulle pareti** e mostra una *Bolla Fantasma* nel punto esatto di incastro.
* **💎 Grafica Cel-Shaded HD (Zero Blur):** Motore di rendering scalato sul `devicePixelRatio` nativo dello smartphone per contorni affilati al pixel, onde d'urto vettoriali, *screen shake* ed esplosioni particellari.
* **🔄 Sistema di Scambio (Swap):** Tocca lo slot `⇄ SWAP` in basso a sinistra per scambiare la bolla nel cannone con quella successiva in coda.
* **💣 Bolle Speciali:**
  * **Bomba:** Esplode all'impatto distruggendo tutte le bolle circostanti con un'onda d'urto.
  * **Jolly (Arcobaleno):** Si abbina automaticamente ai gruppi di qualsiasi colore adiacente.
* **🔥 Combo, Valanghe e Difficoltà Progressiva:** Moltiplicatori per scoppi consecutivi, super bonus per le bolle fatte cadere nel vuoto e discesa dinamica del soffitto con sblocco progressivo fino a 6 colori.
* **🎵 Audio Procedurale (Web Audio API):** Colonna sonora synth in loop ed effetti sonori (sparo, rimbalzi, combo, esplosioni) generati in tempo reale via codice, senza alcun file audio esterno.
* **🌍 Multilingua & Salvataggio Record:** Interfaccia in stile *Glassmorphism* con switch istantaneo **Italiano / Inglese** e salvataggio automatico del miglior punteggio (`localStorage`).

---

## 🕹️ Come Giocare

1. **Mira:** Tieni premuto e scorri il dito sullo schermo per orientare il puntatore laser e la *Bolla Fantasma*.
2. **Spara:** Solleva il dito per lanciare la bolla.
3. **Scambia:** Tocca l'indicatore `⇄ SWAP` in basso a sinistra per cambiare la bolla attiva prima di tirare.
4. **Sopravvivi:** Abbina 3 o più bolle dello stesso colore prima che il contatore `TETTO / DROP` (in basso a destra) arrivi a zero facendo scendere la griglia oltre la linea rossa di pericolo.

---

## 🚀 Installazione ed Esecuzione

Il gioco è interamente contenuto in un singolo file ed è eseguibile istantaneamente:

1. Clona questa repository:
   ```bash
   git clone [https://github.com/davide23567/bubble-echoes.git](https://github.com/davide23567/bubble-echoes.git)
   ```
2. Apri il file `index.html` in qualsiasi browser moderno (o avvialo direttamente tramite il server locale di **Acode** su smartphone).

---

## 🛠️ Tecnologie Utilizzate

* **HTML5 Canvas** (Rendering 2D con DPI Scaling nativo)
* **CSS3 Vanilla** (Layout Flexbox, animazioni fluide e UI *Glassmorphism*)
* **JavaScript ES6+ Vanilla** (Fisica a sub-step, Flood-Fill BFS per Match-3 e rilevamento bolle sospese, Web Audio API)
* 
