# Guida TORO Agroindustriale - GitBook

## Descrizione Progetto
Questa è una guida utente per il sito web TORO Agroindustriale, scritta in formato GitBook (Markdown). La guida spiega come utilizzare la dashboard WordPress per gestire prodotti, categorie e contenuti del sito.

## Stato del Progetto
**Controlla sempre il file `.claude/WORK_LOG.md`** all'inizio di ogni conversazione per:
- Vedere lo stato corrente del lavoro
- Leggere appunti e decisioni precedenti
- Capire quali sezioni sono completate e quali sono in lavorazione

Quando completi task importanti o prendi decisioni, **aggiorna il `.claude/WORK_LOG.md`**.

## Modalità di Interazione

### "Ragioniamo insieme"
Quando l'utente usa questa espressione:
- **NON modificare file o codice**
- **NON usare strumenti di editing** (Write, Edit, NotebookEdit)
- Rispondi alle domande, proponi soluzioni, discuti opzioni
- Aspetta esplicita autorizzazione prima di procedere con modifiche

### "Passo passo"
Quando l'utente chiede qualcosa "passo passo":
- Fornisci **UNA SOLA** indicazione/comando alla volta
- **ASPETTA il feedback** dell'utente prima di procedere
- Non anticipare i passi successivi
- Procedi solo dopo conferma dell'utente

## Struttura
- File markdown numerati sequenzialmente (es. `01-introduzione.md`, `02-prodotti.md`)
- Cartella `assets/` per le immagini, organizzata per sezione
- Il contenuto viene pubblicato su GitBook

## Convenzioni

### Stile e Formattazione
- Usa un tono chiaro e professionale
- Includi screenshot dove necessario con percorsi relativi (es. `assets/nome-sezione/immagine.jpg`)
- Usa emoji solo quando esplicitamente richiesto
- Usa il formato standard GitBook per heading, liste e codice

### Immagini
- Salva screenshot in `assets/nome-sezione/`
- Usa nomi descrittivi (es. `tipi-prodotto-01.jpg`)
- Riferimenti relativi nel markdown

### Git
- Il file `.claude/README.md` viene committato (informazioni di progetto per Claude)
- Il file `.claude/settings.local.json` è nel .gitignore (configurazioni locali)
- Fai commit significativi con messaggi descrittivi in italiano

#### Workflow Branch

**SOLO per Claude Code Web** (https://claude.ai/code/):
- **All'inizio di ogni sessione**: il sistema crea automaticamente un branch `claude/guide-confirmation-XXXXXXX`
- **Lavoro sul branch automatico**: tutte le modifiche vanno su questo branch
- **Limitazione tecnica**: Claude Code Web può pushare SOLO su branch `claude/...`, non su `main` (errore 403)
- **Commit e push**: lavoro normalmente sul branch `claude/...` e pusho lì
- **Merge su main**: l'utente fa merge manualmente (o via PR) da `claude/...` a `main`
- **Sincronizzazione GitBook**: GitBook si aggiorna solo DOPO il merge su `main`

**Per Claude CLI**:
- Nessuna limitazione sui branch
- Lavoro direttamente su `main` e pusho normalmente
- GitBook si sincronizza immediatamente

## Repository
- GitHub: andreacianni/toro-ag-guida
- GitBook: [\[URL se disponibile\]](https://andyaea.gitbook.io/toro-ag-guida-amministratore)

## Note
- Il sito usa WordPress con custom post types per i prodotti
- I prodotti hanno categorie, immagini hero, thumbnail, schede tecniche e video
