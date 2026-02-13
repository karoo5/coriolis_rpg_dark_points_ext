# Coriolis - Dark Points Tracker

Un'estensione per Owlbear Rodeo che ti permette di tenere traccia dei Dark Points nel gioco di ruolo Coriolis: The Third Horizon.

## ✨ Caratteristiche

- **Gettoni 3D Animati**: Ogni Dark Point è rappresentato da un gettone 3D con animazione di fluttuazione
- **Controlli Semplici**: Aggiungi e rimuovi Dark Points con un click
- **Azioni Rapide**: Bottoni per aggiungere rapidamente +3 o +5 DP
- **Persistenza**: I Dark Points vengono salvati nella stanza e condivisi con tutti i giocatori
- **Design Tematico**: Grafica ispirata all'estetica di Coriolis con colori rosso scuro e il simbolo della mezzaluna

## 🚀 Installazione

### Metodo 1: Installazione Locale (per sviluppo)

1. Scarica tutti i file dell'estensione:
   - `index.html`
   - `manifest.json`
   - `icon.svg`

2. Metti tutti i file in una cartella sul tuo computer

3. Avvia un server locale nella cartella. Puoi usare:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js (se hai http-server installato)
   npx http-server -p 8000
   ```

4. In Owlbear Rodeo, vai su **Extensions** → **Install** → **Install from URL**

5. Inserisci l'URL: `http://localhost:8000/manifest.json`

### Metodo 2: Hosting Online (consigliato)

1. Carica i file su un servizio di hosting gratuito come:
   - GitHub Pages
   - Netlify
   - Vercel
   - Cloudflare Pages

2. Una volta caricati, ottieni l'URL pubblico del tuo `manifest.json`

3. In Owlbear Rodeo, vai su **Extensions** → **Install** → **Install from URL**

4. Inserisci l'URL pubblico del manifest

## 📖 Come Usare

1. Una volta installata, clicca sull'icona dell'estensione nella barra laterale di Owlbear Rodeo

2. Si aprirà un pannello che mostra:
   - Il conteggio totale dei Dark Points
   - I gettoni 3D animati per ogni DP
   - I controlli per aggiungere/rimuovere DP

3. **Come GM**, puoi:
   - **+ Aggiungi DP**: Aggiunge un Dark Point
   - **- Rimuovi DP**: Rimuove un Dark Point
   - **+3 DP / +5 DP**: Aggiunge rapidamente 3 o 5 Dark Points
   - **Reset**: Azzera tutti i Dark Points (chiede conferma)

4. I Dark Points sono condivisi con tutti nella stanza in tempo reale!

## 🎮 Note sul Gioco

In Coriolis: The Third Horizon, i Dark Points rappresentano la crescente influenza delle Icone Oscure. Il GM può spenderli per:
- Rilanciare i dadi
- Attivare abilità speciali dei PNG
- Creare complicazioni narrative
- Altro secondo le regole del gioco

## 🛠️ Personalizzazione

Puoi facilmente modificare:
- **Colori**: Cambia i colori nel CSS (cerca `#e74c3c` per il rosso)
- **Simbolo**: Modifica il simbolo nei gettoni (cerca `☪` nell'HTML)
- **Animazioni**: Regola le animazioni nel `@keyframes float`

## 📝 Requisiti Tecnici

- Owlbear Rodeo (versione con supporto per estensioni)
- Un browser moderno (Chrome, Firefox, Safari, Edge)

## 🐛 Problemi Comuni

**L'estensione non si carica**
- Verifica che il server locale sia in esecuzione
- Controlla che l'URL del manifest sia corretto
- Assicurati che il browser possa accedere all'URL

**I Dark Points non si salvano**
- Verifica che l'SDK di Owlbear Rodeo sia caricato correttamente
- Controlla la console del browser per eventuali errori

## 📄 Licenza

Questo è un progetto open source. Sentiti libero di modificarlo e condividerlo!

## 🙏 Credits

Creato per migliorare l'esperienza di gioco di Coriolis: The Third Horizon su Owlbear Rodeo.

---

**Buone Avventure nel Terzo Orizzonte!** ☪️
