# 🚀 Neon Impact: Protocol Zero

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Canvas API](https://img.shields.io/badge/Canvas_API-00599C?style=for-the-badge&logo=html5&logoColor=white)
![Live Demo](https://img.shields.io/badge/Gioca_Online-00ffff?style=for-the-badge&logo=google-chrome&logoColor=black)

**Neon Impact: Protocol Zero** è uno sparatutto arcade 2D a scorrimento (Shoot 'em up) sviluppato in puro **Vanilla JavaScript** e **HTML5 Canvas**, senza l'impiego di librerie o motori di terze parti.

Progettato con un approccio **Mobile-First**, garantisce un avvio immediato in orientamento orizzontale su qualsiasi browser mobile, abbinato a un sistema di movimento fluido tramite interpolazione lineare.

---

### 🕹️ [CLICCA QUI PER GIOCARE SUBITO ONLINE](https://davide23567.github.io/neon-impact/)

---

## ✨ Caratteristiche Principali
*   **Avvio Immediato in Landscape**: Gestione automatica dell'orientamento dello schermo all'apertura della pagina.
*   **Controlli Touch con Interpolazione (LERP)**: Sistema di controllo a scorrimento con offset visivo che previene l'occlusione visiva della navicella da parte del dito.
*   **Delta Time Engine**: Velocità di gioco, cadenza di tiro e pattern dei nemici uniformati indipendentemente dal refresh rate (60Hz, 90Hz, 120Hz).
*   **Audio Sintetizzato (Web Audio API)**: Effetti sonori per spari, esplosioni, danni e sirene boss generati proceduralmente via codice, senza file audio esterni.
*   **Prestazioni Ottimizzate**: Rendering a basso consumo energetico tramite tecniche di fusione trasparente (Alpha Compositing).
*   **5 Livelli e Boss Fight**: Progressioni con nemici diversificati (Kamikaze, Incrociatori pesanti con impulsi EMP) e scontro finale su due fasi.
*   **Supporto Multipiattaforma**: Interfaccia ottimizzata per touch screen e controlli secondari attivi per mouse e tastiera (`WASD`/Frecce, `Spazio` per sparare, `P`/`Esc` per la pausa).

## 🎮 Schema dei Controlli
*   **Movimento**: Scorri con il dito sulla metà sinistra dello schermo (o destra se impostata la modalità mancini nelle opzioni).
*   **Sparo**: Mantieni premuto sulla metà opposta dello schermo per attivare il fuoco continuo.
*   **Pausa**: Tasto dedicato posizionato nell'angolo in alto a destra.

## 🛠️ Esecuzione in Locale
1. Clona il repository:
   ```bash
   git clone [https://github.com/davide23567/Neon-Impact.git](https://github.com/davide23567/Neon-Impact.git)
