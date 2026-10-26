# 🚀 Neon Impact

![HTML5](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Mobile First](https://img.shields.io/badge/Mobile-First-007AFF?style=for-the-badge)
![60 FPS](https://img.shields.io/badge/Performance-60_FPS-FF2D55?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Zero-Dependencies-34C759?style=for-the-badge)

**Neon Impact** è uno sparatutto arcade 2D spaziale frenetico con approccio *mobile-first*, sviluppato interamente in puro Vanilla JavaScript e HTML5 Canvas. Progettato per offrire un'esperienza fluida a 60fps su smartphone e desktop, racchiude grafica vettoriale neon, fisica particellare, controlli touch LERP e sintetizzatore audio in un singolo file HTML senza dipendenze esterne.

🎮 **[Gioca alla Live Demo qui](https://davide-raimondi.github.io/neon-impact/)**

---

## ✨ Caratteristiche Principali

* **🕹️ Controlli Touch LERP & Delta Time:** Movimento dell'astronave ultra-fluido con interpolazione lineare (LERP) calibrata per il controllo con un solo dito e loop di gioco basato su Delta Time per garantire la stessa velocità su qualsiasi frequenza di aggiornamento dello schermo.
* **👾 5 Livelli & Boss Fight Multi-Fase:** Progressione adrenalinica attraverso 5 settori spaziali con ondate di nemici unici e battaglie contro Boss dotati di pattern d'attacco dedicati.
* **⚡ Sistema di Power-Up & Armi:** Potenziamenti raccoglibili in tempo reale (fuoco multiplo, scudi energetici, overdrive) ed effetti di screen-shake e particelle neon ad ogni esplosione.
* **🔊 Audio Procedurale Sintetizzato:** Effetti sonori sci-fi ed esplosioni generati in tempo reale tramite **Web Audio API**, senza bisogno di caricare file audio esterni.
* **💾 Salvataggio Record Locale:** Massimi punteggi e progressi salvati automaticamente nel browser tramite `localStorage`.

---

## 🛠️ Architettura "Single-File"

L'intero gioco risiede in un unico file `index.html`:
* **Zero Dipendenze:** Nessun framework, libreria esterna o asset grafico/audio da scaricare.
* **Caricamento Istantaneo:** Pronto all'uso sia online che completamente offline.
* **Pronto per Web & Mobile Wrapper:** Ideale per GitHub Pages, PWA o l'integrazione diretta in una WebView Android/iOS.

---

## 🚀 Come Iniziare

1. Clona il repository o scarica il file `index.html`:
   ```bash
   git clone [https://github.com/davide-raimondi/neon-impact.git](https://github.com/davide-raimondi/neon-impact.git)
   
