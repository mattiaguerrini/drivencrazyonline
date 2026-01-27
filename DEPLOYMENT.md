# 🚀 GUIDA AL DEPLOYMENT SU GITHUB PAGES

Segui questi passaggi per pubblicare il gioco su GitHub Pages e condividerlo con gli amici!

## 📋 Prerequisiti

- Account GitHub (gratuito) - [Registrati qui](https://github.com/signup)
- Il file ZIP scaricato

## 🔧 Passo 1: Crea un Nuovo Repository

1. Vai su [GitHub](https://github.com)
2. Clicca sul pulsante **"+"** in alto a destra
3. Seleziona **"New repository"**
4. Compila i campi:
   - **Repository name**: `drive13k-multiplayer` (o un nome a tua scelta)
   - **Description**: "Dr1v3n Wild - Multiplayer racing game"
   - **Public**: Seleziona questa opzione (GitHub Pages richiede repo pubblici per utenti free)
   - ✅ **Add a README file**: Lascia deselezionato (lo abbiamo già)
5. Clicca **"Create repository"**

## 📤 Passo 2: Carica i File

### Opzione A: Upload via Web (più semplice)

1. Nella pagina del tuo nuovo repository, clicca **"uploading an existing file"**
2. Estrai il contenuto dello ZIP sul tuo computer
3. Trascina TUTTI i file e cartelle nella pagina di GitHub
4. Scrivi un messaggio di commit (es: "Initial commit")
5. Clicca **"Commit changes"**

### Opzione B: Upload via Git (più professionale)

```bash
# Estrai lo ZIP e vai nella cartella
cd drive13k-multiplayer

# Inizializza Git
git init

# Aggiungi tutti i file
git add .

# Crea il primo commit
git commit -m "Initial commit"

# Collega al repository remoto (sostituisci USERNAME e REPO)
git remote add origin https://github.com/USERNAME/REPO.git

# Pusha i file
git branch -M main
git push -u origin main
```

## 🌐 Passo 3: Attiva GitHub Pages

1. Nel tuo repository, clicca su **"Settings"** (in alto)
2. Nel menu a sinistra, clicca su **"Pages"**
3. In **"Source"**, seleziona **"main"** branch
4. Clicca **"Save"**
5. Aspetta 1-2 minuti per la pubblicazione

## ✅ Passo 4: Accedi al Gioco!

Il tuo gioco sarà disponibile su:

```
https://USERNAME.github.io/REPO-NAME/
```

Ad esempio:
- Se il tuo username è `mario` 
- E il repository si chiama `drive13k-multiplayer`
- L'URL sarà: `https://mario.github.io/drive13k-multiplayer/`

## 🎮 Passo 5: Condividi e Gioca!

1. Copia l'URL del tuo gioco
2. Condividilo con i tuoi amici
3. Tutti aprite l'URL nei vostri browser
4. Uno di voi crea una stanza (premi M → Crea Stanza)
5. Gli altri entrano con il codice
6. Premete tutti "PRONTO"
7. Iniziate a giocare! 🏁

## 🔄 Aggiornare il Gioco

Se vuoi aggiornare il gioco in futuro:

### Via Web:
1. Vai nel repository
2. Clicca sul file da modificare
3. Clicca sull'icona della matita (Edit)
4. Fai le modifiche
5. Commit changes

### Via Git:
```bash
# Modifica i file localmente
# Poi:
git add .
git commit -m "Aggiornamento"
git push
```

## 🎨 Personalizzazioni Opzionali

### Cambiare il titolo della pagina
Modifica `index.html`, riga 3:
```html
<title>Il Tuo Titolo Personalizzato</title>
```

### Aggiungere una descrizione
Modifica `README.md` con le tue informazioni.

### Usare un dominio personalizzato
1. Acquista un dominio (es: myawesomegame.com)
2. In Settings → Pages, aggiungi il tuo dominio in "Custom domain"
3. Configura il DNS del tuo dominio per puntare a GitHub Pages

## 🐛 Risoluzione Problemi

### "404 - Page not found"
- Aspetta 2-3 minuti dopo aver attivato Pages
- Verifica che il branch sia "main" nelle impostazioni
- Controlla che `index.html` sia nella root del repository

### "Il gioco non si carica"
- Apri la console del browser (F12)
- Controlla gli errori
- Verifica che tutti i file siano stati caricati

### "Impossibile connettersi in multiplayer"
- Verifica che entrambi i giocatori abbiano il gioco aperto
- Controlla che il codice stanza sia corretto
- Prova a ricreare la stanza

### Il repository è privato
- GitHub Pages gratuito funziona solo con repository pubblici
- Vai in Settings → General → "Change repository visibility" → Make public

## 📊 Statistiche di Utilizzo

Dopo qualche giorno, puoi vedere quante persone visitano il tuo gioco:
1. Settings → Pages
2. Vedrai i dati di traffico se attivi GitHub Insights

## 🔒 Privacy e Sicurezza

- ✅ Il gioco è completamente client-side
- ✅ Nessun dato viene salvato sui server
- ✅ Le connessioni multiplayer sono peer-to-peer
- ✅ GitHub Pages usa HTTPS automaticamente

## 💡 Consigli Pro

1. **Condividi sui social**: Posta l'URL su Twitter, Facebook, Reddit
2. **Crea un QR Code**: Usa un generatore online per creare un QR code dell'URL
3. **Aggiungi analytics**: Integra Google Analytics se vuoi statistiche dettagliate
4. **Fai un fork**: Se trovi bug o vuoi miglioramenti, fai un fork del progetto originale

## 📝 Checklist Finale

- [ ] Repository creato
- [ ] File caricati
- [ ] GitHub Pages attivato
- [ ] URL funzionante
- [ ] Gioco testato in multiplayer
- [ ] URL condiviso con gli amici
- [ ] Divertimento garantito! 🎉

## 🆘 Serve Aiuto?

- Controlla la [documentazione di GitHub Pages](https://docs.github.com/pages)
- Apri una Issue nel repository originale
- Cerca su Google: "github pages troubleshooting"

## 🎉 Fatto!

Congratulazioni! Il tuo gioco è ora online e accessibile da tutto il mondo!

Condividi l'URL con i tuoi amici e inizia a giocare! 🚗💨

---

**Buon divertimento!** 🎮
