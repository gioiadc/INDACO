# INDACO Final Workshop - Pagina Web

Questa è la pagina web per il Final Workshop del progetto PRIN INDACO che si terrà il 19 febbraio 2025 presso l'Università di Trieste.

## 📋 Contenuto del Pacchetto

- `index.html` - La pagina web principale dell'evento

## 🚀 Come Pubblicare su GitHub Pages

### Passo 1: Crea un Repository su GitHub

1. Vai su [GitHub](https://github.com) e accedi al tuo account
2. Clicca su "New repository" (+ in alto a destra)
3. Dai un nome al repository (es. `indaco-workshop`)
4. Seleziona "Public"
5. Clicca su "Create repository"

### Passo 2: Carica i File

1. Nella pagina del repository, clicca su "uploading an existing file"
2. Trascina il file `index.html` nell'area di upload
3. **Crea una cartella `images/` e carica i loghi delle università e il banner del progetto**
4. Clicca su "Commit changes"

### Passo 3: Attiva GitHub Pages

1. Nel tuo repository, vai su **Settings** (⚙️)
2. Nel menu laterale, clicca su **Pages**
3. In "Source", seleziona **main** branch
4. Clicca su **Save**
5. Dopo qualche minuto, vedrai l'URL del tuo sito (es. `https://tuousername.github.io/indaco-workshop/`)

## 🖼️ Aggiungere i Loghi e il Banner

### Posizionamento dei File

Crea una cartella chiamata `images` nel tuo repository e carica:
- I **3 loghi delle università** (formato consigliato: PNG o SVG)
- Il **banner del progetto INDACO**

### Modifica del Codice HTML

Nel file `index.html`, sostituisci i placeholder con i veri percorsi delle immagini:

#### Per i Loghi delle Università:

Cerca questa sezione (circa riga 335):
```html
<div class="logo-placeholder">
    <!-- Sostituire con: <img src="logo-universita-1.png" alt="Logo Università 1"> -->
    Logo Università 1
</div>
```

Sostituisci con:
```html
<div class="logo-placeholder">
    <img src="images/logo-trieste.png" alt="Logo Università di Trieste">
</div>
```

Ripeti per gli altri due loghi (Milano e Torino).

#### Per il Banner:

Cerca questa sezione (circa riga 505):
```html
<div class="banner-placeholder">
    <!-- Sostituire con: <img src="banner-indaco.png" alt="Banner INDACO Project"> -->
    Banner del Progetto INDACO
</div>
```

Sostituisci con:
```html
<div class="banner-placeholder">
    <img src="images/banner-indaco.png" alt="Banner INDACO Project">
</div>
```

## 🎨 Personalizzazioni Suggerite

### 1. Colori
Se vuoi cambiare i colori principali, modifica queste variabili CSS (all'inizio del file):
- Sfondo header: `#1e3c72` e `#2a5298` (linee 26-27, 53-54)
- Colore principale: `#667eea` (varie occorrenze)

### 2. Email di Contatto
Alla riga 518, modifica l'email di contatto:
```html
<a href="mailto:info@indaco-project.it" class="cta-button">Contattaci</a>
```

### 3. Aggiungere Informazioni Mancanti
Nel programma, alcuni interventi non hanno il titolo. Puoi aggiungerlo cercando il nome del relatore e aggiungendo sotto:
```html
<div class="title">Titolo della presentazione</div>
```

## 📱 Caratteristiche della Pagina

✅ **Design Responsive** - Si adatta perfettamente a smartphone, tablet e desktop  
✅ **Animazioni Fluide** - Effetti hover sugli elementi interattivi  
✅ **Tipografia Moderna** - Font leggibili e professionali  
✅ **Organizzazione Chiara** - Programma diviso in sessioni mattutina e pomeridiana  
✅ **Evidenziazione delle Pause** - Pausa pranzo e pause brevi ben visibili  
✅ **Accessibilità** - Contrasti di colore ottimizzati per la leggibilità  

## 🔧 Risoluzione Problemi

### Le immagini non si vedono
- Verifica che i percorsi dei file siano corretti
- Assicurati che le immagini siano nella cartella `images/`
- Controlla che i nomi dei file corrispondano esattamente (maiuscole/minuscole)

### La pagina non si aggiorna
- Svuota la cache del browser (Ctrl+F5 o Cmd+Shift+R)
- Aspetta qualche minuto dopo aver fatto commit su GitHub
- Verifica che GitHub Pages sia attivo nelle impostazioni

### Il layout appare rotto su mobile
- Assicurati di non aver modificato le media queries
- Testa la pagina usando gli strumenti sviluppatore del browser (F12)

## 📧 Contatti

Per domande o assistenza tecnica sulla pagina web, contatta il team INDACO.

## 📄 Licenza

Questa pagina è stata creata per il progetto PRIN INDACO.
© 2025 - Università di Trieste, Milano, Torino

---

**Suggerimento:** Dopo aver pubblicato la pagina, condividi il link con tutti i partecipanti e sui canali social delle università coinvolte! 🎉
