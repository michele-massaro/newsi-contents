# 🧠 Newsi – La Rivoluzione AI per le Notizie Personalizzate

## 🗒️ Intro

Questo progetto è stato sviluppato nell’ambito del **Codemotion Hackathon - "Il futuro dell’editoria digitale"**, con l’obiettivo di reinventare il modo in cui utenti, contenuti e brand interagiscono grazie all’intelligenza artificiale.

## 👥 Team

Il team dietro **Newsi** è composto da professionisti e appassionati di AI, UX e tecnologie web, uniti dalla volontà di innovare il panorama dell’editoria digitale.  
**Membri del team**:

- Elisa Franz – UX/UI Designer
- Francesca Franz – UX/UI Designer
- Francesco Meneguzzo – Software Engineer
- Michele Massaro – Software Engineer

## 🚀 Overview

**Newsi** è una piattaforma AI che trasforma il modo in cui leggiamo le notizie. Invece di offrire contenuti "taglia unica", Newsi riscrive ogni articolo editoriale, adattandolo al profilo, al linguaggio e persino allo stato d’animo di ciascun utente. Un nuovo standard di personalizzazione per lettori, editori e brand.

## 🎯 Value Proposition

- **Per gli utenti**: ricevi solo notizie che parlano il tuo linguaggio, nel tono che preferisci, rese più accessibili e coinvolgenti.
- **Per editori e brand**: aumenta l’engagement, migliora i KPI chiave e crea nuove opportunità di monetizzazione grazie a contenuti personalizzati.

## 🧩 Come Funziona

1. **Profilazione Utente**

   - Preferenze esplicite (es. interessi)
   - Comportamenti impliciti (lettura e interazione)
   - Assegnazione a un cluster dinamico vettoriale

2. **Tagging & Generazione Articoli**

   - L’articolo originale viene semantizzato
   - Un LLM genera 30–50 varianti (Gen-Z, business, storytelling…)

3. **Caching Distribuito**

   - Edge functions restituiscono le varianti generate → latenza <150ms

4. **UI Interattiva**
   - Interfaccia a card con mesh-gradient
   - Micro-feedback: 👍 / cambia tono → reinforcement learning

## 📈 KPI Monitorati

| KPI                  | Perché è Importante            |
| -------------------- | ------------------------------ |
| Dwell Time           | Misura l’interesse del lettore |
| CTR Home → Article   | Verifica la pertinenza         |
| % Articoli condivisi | Indica valore e viralità       |
| TTFB                 | Valuta performance tecnica     |

## 🧪 Stack Tecnologico

- LLM + RL loop per generazione e ottimizzazione contenuti
- Edge Computing per caching e latenza
- Vector profiling e semantic tagging
- UI React-based integrata con CMS

## 🖌 Identità Visiva

- **Font**: Montserrat (corpo), Source Serif Pro (H2)
- **Palette**:

  - `#121212` – testo
  - `#2D9CDB` – CTA
  - `#6FCF97` – badge
  - `#F2F2F2` – sfondo
  - `#1B3A4B` – bottoni/hover

- **Logo**: bot + balloon da chat → tecnologia amichevole

## 🔍 Posizionamento & Competitor

| Feature                      | Newsi | Google News | Flipboard | SmartNews | Bloomreach | Recombee |
| ---------------------------- | :---: | :---------: | :-------: | :-------: | :--------: | :------: |
| Personalizzazione Reale-Time |  ✅   |     ❌      |    ❌     |    ❌     |     ✅     |    ✅    |
| Profilazione con onboarding  |  ✅   |     ❌      |    ❌     |    ❌     |  ✅ (B2B)  | ✅ (B2B) |
| Tono e linguaggio adattivo   |  ✅   |     ❌      |    ❌     |    ❌     |     ❌     |    ❌    |
| Contenuti modificati da AI   |  ✅   |     ❌      |    ❌     |    ❌     |     ✅     |    ✅    |
| Grafica adattiva             |  ✅   |     ❌      |    ✅     |    ❌     |     ✅     |    ✅    |
| Interfaccia moderna          |  ✅   |     ❌      |    ✅     |    ❌     |     ❌     |    ❌    |
| Raccolta feedback per RL     |  ✅   |     ❌      |    ❌     |    ❌     |     ✅     |    ✅    |
| Dashboard per Editori        |  ✅   |     ❌      |    ❌     |    ❌     |     ✅     |    ✅    |
| Marketplace Editoriale       |  ✅   |     ❌      |    ❌     |    ❌     |     ❌     |    ❌    |

## 📱 Prototipo UI

🔗 [Figma – Prototipo Newsi](https://www.figma.com/design/bUzqrC3Zo8OTRdeNYk7Jtu/Newsi?node-id=0-1&t=MTj18LtgopCmg38J-1)

## 🌱 Visione Futura

- App mobile iOS/Android
- Text-to-speech e accessibilità aumentata
- Adattamento a contenuti educativi, paper scientifici, narrativa
- Cluster dinamici sempre più raffinati
