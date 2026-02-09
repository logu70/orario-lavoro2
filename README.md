# ⏱ Orario di Lavoro / Work Time Calculator

---

## 🇮🇹 Italiano

### Descrizione

**Orario di Lavoro** è un'applicazione web leggera e autonoma che aiuta i dipendenti a calcolare in tempo reale l'orario di uscita dal lavoro in base a due obiettivi:

1. **Buono pasto** — raggiungimento delle 6 ore effettive di lavoro, requisito minimo per ottenere il buono pasto.
2. **Giornata completa** — raggiungimento delle 7 ore e 12 minuti effettivi, corrispondenti all'orario contrattuale giornaliero.

L'applicazione tiene conto automaticamente della pausa pranzo e di eventuali uscite brevi durante la giornata.

### Funzionalità

- **Orologio in tempo reale** con aggiornamento al secondo
- **Calcolo automatico** dell'orario di uscita per buono pasto e giornata completa
- **Ore lavorate effettive** calcolate in tempo reale, al netto delle pause
- **Barre di progresso** animate per ciascun obiettivo
- **Indicatori colorati** del tempo rimanente: verde (normale), arancione (< 45 min), rosso (< 15 min)
- **Badge di stato** che segnalano "In corso" o "Completato ✓"
- **Uscite brevi illimitate** con aggiunta e rimozione dinamica
- **Riepilogo pause** con durata totale sempre visibile
- **Salvataggio automatico** dei dati nel browser (localStorage): riaprendo la pagina si ritrovano i valori inseriti
- **Layout responsive** ottimizzato per desktop e dispositivi mobili

### Come si usa

1. Aprire il file `orario-lavoro.html` nel browser.
2. Inserire l'**orario di arrivo** al lavoro.
3. Regolare gli orari di **inizio e fine pausa pranzo**.
4. Se necessario, aggiungere una o più **uscite brevi** cliccando il pulsante dedicato.
5. I risultati si aggiornano automaticamente in tempo reale.

### Requisiti

- Un browser web moderno (Chrome, Firefox, Safari, Edge)
- Nessuna installazione, server o dipendenza esterna richiesta

### Struttura

Il progetto è composto da un singolo file HTML autonomo che include CSS e JavaScript integrati.

```
orario-lavoro.html   ← file unico, aprire direttamente nel browser
```

---

## 🇬🇧 English

### Description

**Orario di Lavoro** (Work Time Calculator) is a lightweight, standalone web application that helps employees calculate their exit time from work based on two goals:

1. **Meal voucher** — reaching 6 effective working hours, the minimum requirement to earn the daily meal voucher.
2. **Full day** — reaching 7 hours and 12 minutes of effective work, corresponding to the standard daily contractual hours.

The application automatically accounts for the lunch break and any short breaks taken during the day.

### Features

- **Live clock** updating every second
- **Automatic calculation** of exit times for meal voucher and full day targets
- **Effective worked hours** calculated in real time, net of all breaks
- **Animated progress bars** for each target
- **Color-coded remaining time**: green (normal), orange (< 45 min), red (< 15 min)
- **Status badges** showing "In progress" or "Completed ✓"
- **Unlimited short breaks** with dynamic add/remove
- **Break summary** with total break duration always visible
- **Auto-save** to browser localStorage: data is preserved when reopening the page
- **Responsive layout** optimized for both desktop and mobile devices

### How to Use

1. Open `orario-lavoro.html` in your browser.
2. Enter your **arrival time** at work.
3. Adjust the **lunch break** start and end times.
4. If needed, add one or more **short breaks** using the dedicated button.
5. Results update automatically in real time.

### Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation, server, or external dependencies required

### Structure

The project consists of a single self-contained HTML file with embedded CSS and JavaScript.

```
orario-lavoro.html   ← single file, open directly in your browser
```

---

### License

This project is provided for personal use.
