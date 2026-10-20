# 🌍 VibeCoded GeoGame v2.0 — World Explorer Edition

Ein modernes, interaktives Geografie-Webgame im **Glassmorphism Dark-Mode Design**. Entwickelt als schnelle Single-File Web-Applikation ohne Build-Step – einfach im Browser öffnen und loslegen.

---

## ✨ Neue Features in v2.0

### 🎮 5 Abwechslungsreiche Spielmodi
1. **🏳️ Flaggen-Meister:** Erkenne Länder anhand ihrer Nationalflagge über 10 spannende Runden.
2. **🏛️ Hauptstadt-Sprint:** Ordne jedem Land die richtige Hauptstadt zu.
3. **📍 Karten-Pinpoint (Neu):** Setze deinen eigenen Pin auf einer unbeschrifteten, interaktiven Dunkel-Weltkarte (Leaflet.js). Die Distanz zum echten Land wird per Haversine-Formel in Kilometern berechnet!
4. **📈 Einwohner-Duell (Higher or Lower):** Entscheide im Survival-Modus, welches von zwei Ländern mehr Einwohner hat.
5. **⚡ 60s Speed-Blitz:** Spiele gegen die Uhr! Richtige Antworten bringen dir wertvolle Bonus-Sekunden.

### 🚀 Progression, Gamification & Tools
* **XP-, Level- & Rang-System:** Steige vom *Tourist* bis zum *Weltmeister* auf.
* **Tägliche Missionen (Daily Quests):** Drei tägliche Herausforderungen für Extra-XP.
* **Joker-System:** Nutze den **50:50-Joker** oder lass dir einen **Geografie-Hinweis** (Subregion & Einwohnerzahl) anzeigen.
* **Kontinent-Filter:** Trainiere gezielt *Weltweit*, *Europa*, *Asien*, *Amerika*, *Afrika* oder *Ozeanien*.
* **Interaktiver Welt-Atlas:** Integriertes Nachschlagewerk mit Echtzeit-Suche und direkter Google-Maps-Verknüpfung.
* **Web-Audio Sound-Synthesizer:** Dynamische Soundeffekte ganz ohne externe MP3-Dateien.
* **Offline-Fallback:** Lädt live alle Staaten über die *REST Countries API* und nutzt bei fehlender Internetverbindung automatisch einen integrierten Offline-Datensatz.

---

## 🛠️ Tech-Stack

* **Frontend:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (CDN) + Custom Glassmorphism UI
* **Karten-Engine:** [Leaflet.js](https://leafletjs.com/) + CartoDB Dark Matter Tiles
* **Icons & Effekte:** [Lucide Icons](https://lucide.dev/) & `canvas-confetti`
* **Datenbank / Persistenz:** `localStorage` für Highscores, XP, Streaks und Erfolge

---

## 🚀 Schnellstart (Installation)

Da das gesamte Projekt in einer einzigen `index.html` gebündelt ist, wird kein lokaler Node-Server oder Bundler benötigt:

```bash
# 1. Repository klonen
git clone [https://github.com/dein-username/VibeCoded-GeoGame.git](https://github.com/dein-username/VibeCoded-GeoGame.git)

# 2. In das Verzeichnis wechseln
cd VibeCoded-GeoGame

# 3. Direkt im Browser öffnen
start index.html
