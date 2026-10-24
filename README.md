# 🚀 Neon Impact: Protocol Zero

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Canvas API](https://img.shields.io/badge/Canvas_API-00599C?style=for-the-badge&logo=html5&logoColor=white)

**Neon Impact: Protocol Zero** è un frenetico sparatutto arcade 2D (Shoot 'em up) sviluppato interamente in **Vanilla JavaScript** e **HTML5 Canvas**, senza l'utilizzo di motori grafici o librerie esterne. 

Progettato con un approccio **Mobile-First**, il gioco offre un'esperienza fluida su smartphone grazie a controlli touch ottimizzati e un motore di rendering leggero.

## ✨ Caratteristiche Principali
*   **Zero Dipendenze**: 100% Vanilla JS, un singolo file HTML per la logica principale.
*   **Controlli Touch Avanzati (LERP)**: Sistema di movimento fluido con offset visivo che impedisce al dito di coprire la navicella durante le fasi più concitate.
*   **Delta Time Rendering**: La velocità di gioco e i cooldown rimangono costanti a prescindere dal frame rate (FPS) del dispositivo.
*   **Ottimizzazione Mobile**: Utilizzo di *Alpha Compositing* al posto dei pesanti filtri ombra nativi per garantire i 60fps anche su dispositivi di fascia media.
*   **Game Feel**: Screen shake, hit-stop, effetti particellari e un sistema di audio procedurale (Web Audio API) senza bisogno di file mp3 esterni.
*   **5 Livelli di Difficoltà Crescente**: Inclusi 5 pattern unici per i boss, con il boss finale dotato di una doppia fase epica.
*   **Responsive UI**: Menu adattivi, supporto per mancini/destrorsi e lock automatico dello schermo in landscape.

## 🎮 Controlli
*   **Movimento (Touch)**: Scorri sulla metà sinistra dello schermo (o destra, se impostato per mancini) per muovere la navicella.
*   **Fuoco (Touch)**: Tieni premuto sulla metà opposta dello schermo per sparare.
*   **Mouse (Desktop)**: Il gioco supporta l'emulazione del touch tramite click e trascinamento del mouse (ideale tramite i DevTools del browser).

## 🛠️ Installazione e Avvio
Essendo un progetto web nativo, non c'è bisogno di build tools, npm o server complessi.

1. Clona il repository:
   ```bash
   git clone [https://github.com/davide23567/neon-impact.git](https://github.com/davide23567/neon-impact.git)
