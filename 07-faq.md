# Domande Frequenti

Raccolta delle domande più comuni e soluzioni ai problemi che potresti incontrare nella gestione del sito.

---

## Domande Generali

### Non riesco ad accedere all'amministrazione
**Problema**: Non riesco ad entrare in wp-admin

**Soluzioni**:
1. **Verifica le credenziali**: Username e password corretti?
2. **Controlla l'URL**: Stai andando su `https://www.toro-ag.it/wp-admin/`?
3. **Cancella cache browser**: Prova con Ctrl+F5
4. **Prova browser diverso**: Potrebbe essere un problema di cookie
5. **Contatta l'assistenza tecnica** se il problema persiste

### Ho fatto una modifica ma non si vede sul sito
**Problema**: Le modifiche non appaiono sul frontend

**Soluzioni**:
1. **Hai pubblicato?** Verifica che il contenuto sia "Pubblicato" e non "Bozza"
2. **Cache del sito**: Aspetta 5-10 minuti per l'aggiornamento automatico
3. **Refresh forzato**: Vai alla pagina e premi Ctrl+F5
4. **Verifica associazioni**: Controlla che tipi/applicazioni siano selezionati correttamente

### Posso annullare una modifica?
**Risposta**: Sì, in diversi modi

**Opzioni**:
- **Revisioni**: WordPress salva versioni precedenti automaticamente
- **Ripristina da cestino**: Se hai eliminato qualcosa per errore
- **Salva come bozza**: Prima di pubblicare modifiche importanti
- **Backup**: Contatta l'assistenza per ripristini importanti

---

## Problemi con i Tipi di Prodotto

### Non riesco a creare un nuovo tipo di prodotto
**Possibili cause**:
- **Permessi insufficienti**: Verifica di avere il ruolo amministratore
- **Nome già esistente**: Controlla che non esista già un tipo con lo stesso nome
- **Campi obbligatori**: Assicurati di compilare tutti i campi richiesti

**Soluzioni**:
1. Prova con un nome diverso
2. Verifica di aver compilato tutti i campi
3. Ricarica la pagina e riprova

### Il tipo di prodotto non appare nell'elenco dei prodotti
**Problema**: Non vedo il tipo quando creo/modifico un prodotto

**Cause**:
- Il tipo è stato salvato come bozza
- Problemi di sincronizzazione temporanei

**Soluzioni**:
1. Vai a **Tipo di Prodotti** → verifica che sia pubblicato
2. Ricarica la pagina di modifica del prodotto
3. Prova a ricreare il tipo se necessario

### L'immagine del tipo non si carica
**Problema**: Errore durante l'upload delle immagini

**Soluzioni**:
1. **Dimensione file**: Riduci sotto i 2MB
2. **Formato**: Usa JPG o PNG
3. **Nome file**: Evita caratteri speciali, spazi o accenti
4. **Connessione**: Verifica la connessione internet
5. **Prova immagini diverse**: Potrebbe essere un file corrotto

---

## Problemi con i Prodotti

### Il prodotto non appare nella categoria giusta
**Problema**: Il prodotto non si vede nella pagina del tipo di prodotto

**Controlli da fare**:
1. **Tipo di prodotto selezionato**: È stato scelto il tipo corretto?
2. **Prodotto pubblicato**: Lo stato è "Pubblicato"?
3. **URL corretto**: Stai guardando la pagina giusta?

**Passi per risolvere**:
1. Modifica il prodotto
2. Verifica la sezione "Tipo di Prodotto" sulla destra
3. Seleziona il tipo corretto
4. Clicca "Aggiorna"
5. Vai alla pagina del tipo per verificare

### Non riesco a caricare la galleria immagini
**Problema**: Errori durante l'upload delle immagini

**Limitazioni da ricordare**:
- **Massimo 10 immagini** nella galleria
- **Dimensione singola**: Massimo 2MB per immagine
- **Formati supportati**: JPG, PNG, GIF

**Soluzioni**:
1. **Ridimensiona le immagini** prima del caricamento
2. **Carica una per volta** se hai problemi
3. **Rinomina i file** con nomi semplici
4. **Svuota cache browser** e riprova

### I documenti non si collegano al prodotto
**Problema**: Non riesco a associare schede o documenti

**Cause comuni**:
- I documenti non esistono ancora nel sistema
- I documenti sono in bozza
- Problemi di permessi

**Soluzioni**:
1. **Verifica che i documenti esistano**:
   - Vai a **Schede Prodotto** o **Documenti Prodotti**
   - Controlla che siano pubblicati
2. **Crea i documenti mancanti** prima di associarli
3. **Ricarica la pagina** di modifica del prodotto

---

## Problemi con le Applicazioni

### L'applicazione creata non appare sul sito
**Problema**: L'applicazione non si vede in `/applicazioni/`

**Controlli essenziali**:
1. **Thumbnail obbligatoria**: Hai caricato l'immagine thumbnail?
2. **Stato**: L'applicazione è stata salvata correttamente?
3. **Prodotti associati**: Ci sono prodotti che usano questa applicazione?

**Soluzioni**:
1. **Carica la thumbnail** (campo obbligatorio)
2. **Associa almeno un prodotto** all'applicazione
3. **Verifica la gerarchia** se è una sotto-categoria

### Non riesco a creare sotto-categorie di applicazioni
**Problema**: La gerarchia non funziona

**Soluzioni**:
1. **Crea prima la categoria padre**
2. **Nella categoria figlia**, seleziona la padre nel campo appropriato
3. **Verifica che non ci siano cicli** (A padre di B, B padre di A)
4. **Salva entrambe** le categorie

### I prodotti non appaiono nell'applicazione
**Problema**: La pagina dell'applicazione è vuota

**Causa più comune**: I prodotti non hanno l'applicazione selezionata

**Soluzione**:
1. Vai ai **Prodotti** che dovrebbero apparire
2. **Modifica ogni prodotto**
3. Nella sezione **Applicazioni** sulla destra, **seleziona l'applicazione**
4. **Salva il prodotto**
5. **Ripeti per tutti i prodotti** pertinenti

---

## Problemi Comuni {#problemi-comuni}

### "Errore durante il salvataggio"
**Possibili cause**:
- Connessione internet instabile
- File troppo grandi
- Sessione scaduta

**Soluzioni**:
1. **Copia il testo** prima di riprovarе
2. **Ricarica la pagina** e riprova
3. **Riduci dimensioni** delle immagini
4. **Ri-effettua il login** se necessario

### "Impossibile caricare il file"
**Controlli**:
- **Dimensione**: Sotto i 2MB?
- **Formato**: PDF per documenti, JPG/PNG per immagini?
- **Nome file**: Senza spazi, accenti o caratteri strani?

**Soluzioni**:
1. **Rinomina il file** (es: `scheda_prodotto.pdf`)
2. **Comprimi l'immagine** se troppo grande
3. **Prova formato diverso** (JPG invece di PNG)

### "La pagina non si carica"
**Browser e cache**:
1. **Prova browser diverso** (Chrome, Firefox, Safari)
2. **Cancella cache e cookie**
3. **Disattiva estensioni** del browser temporaneamente
4. **Prova connessione diversa** (mobile hotspot)

### Modifiche non visibili immediatamente
**Normale!** Il sito ha cache per migliorare le prestazioni

**Tempistiche**:
- **Cache browser**: 5 minuti
- **Cache server**: 10-15 minuti
- **CDN**: Fino a 30 minuti

**Forzare l'aggiornamento**:
1. **Ctrl+F5** sulla pagina interessata
2. **Aspetta 15-20 minuti** per aggiornamenti automatici
3. **Prova da dispositivo diverso** per verificare

---

## Risoluzione Problemi Avanzati

### Prodotto con URL sbagliato
**Problema**: Il prodotto ha un URL che non corrisponde al tipo

**Causa**: Il tipo di prodotto è stato cambiato dopo la creazione

**Soluzione**:
1. **L'URL si aggiorna automaticamente** al cambio di tipo
2. **Aspetta qualche minuto** per la propagazione
3. **Se persiste**, vai su **Impostazioni** → **Permalink** → **Salva modifiche**

### Gerarchia delle applicazioni confusa
**Problema**: Struttura delle categorie disordinata

**Riorganizzazione**:
1. **Pianifica la struttura** su carta prima
2. **Crea le categorie principali** prima delle sottocategorie
3. **Modifica una per volta** le sottocategorie
4. **Verifica sul sito** dopo ogni modifica

### Perdita di associazioni
**Problema**: I collegamenti tra elementi sono spariti

**Prevenzione**:
- **Non eliminare mai** tipi o applicazioni che hanno prodotti associati
- **Prima sposta i prodotti** in altre categorie
- **Poi elimina** la categoria vuota

**Recupero**:
1. **Controlla il cestino** per elementi eliminati per errore
2. **Ripristina** se possibile
3. **Ricrea le associazioni** manualmente se necessario

---

## Manutenzione Periodica

### Controlli Mensili

**Cosa verificare**:
1. **Tutti i prodotti hanno tipo e applicazioni**
2. **Le immagini si caricano correttamente**
3. **I documenti PDF si aprono**
4. **I conteggi nelle liste sono ragionevoli**

**Come controllare**:
1. Vai a **Prodotti** → filtra per "Senza tipo"
2. Vai alle pagine principali del sito e testa la navigazione
3. Clicca su alcuni documenti per verificare che funzionino

### Pulizia Periodica

**Ogni 3-6 mesi**:
1. **Elimina bozze vecchie** non più necessarie
2. **Rimuovi immagini non utilizzate** dalla Media Library
3. **Controlla documenti obsoleti**
4. **Verifica link interni**

---

## Quando Chiedere Aiuto

### Problemi che richiedono assistenza tecnica

**Contatta l'assistenza per**:
- **Errori del server** (codici 500, 502)
- **Problemi di accesso persistenti**
- **Perdita di dati importante**
- **Malfunzionamenti del tema**
- **Aggiornamenti WordPress**

### Informazioni da preparare

**Quando contatti l'assistenza, fornisci**:
1. **Descrizione del problema** dettagliata
2. **Passi per riprodurre** l'errore
3. **Screenshot** degli errori
4. **Browser e dispositivo** utilizzati
5. **URL specifici** dove si verifica il problema

### Come testare prima di chiedere aiuto

**Verifica basic**:
1. **Ricarica la pagina** (Ctrl+F5)
2. **Prova con browser diverso**
3. **Verifica da dispositivo diverso**
4. **Controlla connessione internet**
5. **Aspetta 20-30 minuti** per cache

Se dopo questi controlli il problema persiste, è il momento di chiedere assistenza tecnica.

---

**🆘 Assistenza**: Se non trovi la soluzione qui, contatta il supporto tecnico con tutti i dettagli del problema.