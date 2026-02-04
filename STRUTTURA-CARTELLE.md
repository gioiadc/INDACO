# Struttura delle Cartelle del Progetto

indaco-workshop/
│
├── index.html                          # Pagina principale (OBBLIGATORIO)
├── README.md                           # Istruzioni (opzionale)
│
└── images/                             # Cartella per le immagini (DA CREARE)
    ├── logo-trieste.png               # Logo Università di Trieste
    ├── logo-milano.png                # Logo Università di Milano  
    ├── logo-torino.png                # Logo Università di Torino
    └── banner-indaco.png              # Banner del progetto INDACO


## Formati Consigliati per le Immagini

### Loghi delle Università
- **Formato:** PNG o SVG (preferibile SVG per la scalabilità)
- **Dimensioni suggerite:** 400x240 pixel (proporzione 5:3)
- **Sfondo:** Trasparente (PNG) o bianco
- **Peso file:** < 200 KB ciascuno

### Banner del Progetto
- **Formato:** PNG o JPG
- **Dimensioni suggerite:** 2000x400 pixel (proporzione 5:1)
- **Risoluzione:** 72-150 dpi (per web)
- **Peso file:** < 500 KB

## Esempio di Comandi Git (opzionale)

Se preferisci usare Git da linea di comando invece dell'interfaccia web:

```bash
# 1. Clona il repository (dopo averlo creato su GitHub)
git clone https://github.com/tuousername/indaco-workshop.git

# 2. Entra nella cartella
cd indaco-workshop

# 3. Copia i file (index.html e README.md) nella cartella

# 4. Crea la cartella images e aggiungi le immagini
mkdir images
# (copia i file immagine nella cartella images)

# 5. Aggiungi tutti i file
git add .

# 6. Fai il commit
git commit -m "Prima versione del sito INDACO Workshop"

# 7. Carica su GitHub
git push origin main
```

## Link Utili

- **GitHub Pages Documentation:** https://docs.github.com/pages
- **Guida Markdown:** https://guides.github.com/features/mastering-markdown/
- **Ottimizzazione Immagini Online:** https://tinypng.com/ o https://squoosh.app/

## Note Importanti

1. **Nomi dei File:** Usa nomi senza spazi, preferibilmente tutto minuscolo
   - ✅ Corretto: `logo-trieste.png`
   - ❌ Evitare: `Logo Trieste.PNG`

2. **Estensioni:** Usa sempre estensioni minuscole (.png, .jpg, non .PNG, .JPG)

3. **Percorsi Relativi:** Nel codice HTML usa sempre percorsi relativi
   - ✅ Corretto: `images/logo-trieste.png`
   - ❌ Evitare: `/images/logo-trieste.png` o `C:/Users/.../logo-trieste.png`

4. **Caratteri Speciali:** Evita caratteri accentati o speciali nei nomi dei file
   - ✅ Corretto: `banner-indaco.png`
   - ❌ Evitare: `banner-indacò.png`
