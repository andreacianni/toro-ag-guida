# Gestire le Applicazioni

Le **Applicazioni** (chiamate anche Colture) rappresentano gli ambiti di utilizzo dei tuoi prodotti (es. "Agrumeti", "Vigneto", "Mais", "Colture Protette").

## Dove si Vedono le Applicazioni

**Sul sito pubblico:**
- Pagina archivio: `https://www.toro-ag.it/applicazioni/`
- Singola applicazione: `https://www.toro-ag.it/applicazioni/irrigazione-agrumeti/`

**Nell'amministrazione:**
- Menu → **Applicazioni**

---

## Visualizzare Applicazioni Esistenti

1. Nel menu laterale, clicca su **Applicazioni**
2. Vedrai la lista di tutte le applicazioni esistenti

📷 *[Screenshot: Lista applicazioni nell'admin]*

Ogni applicazione mostra:
- **Nome** (es. "Agrumeti")
- **Slug** (URL, es. "agrumeti")
- **Descrizione** breve
- **Numero prodotti** associati

💡 **Suggerimento**: Le applicazioni sono organizzate gerarchicamente - alcune possono avere sotto-categorie.

---

## Creare una Nuova Applicazione {#nuova-applicazione}

### Passo 1: Andare alla Creazione

1. Vai su **Applicazioni**
2. Clicca **"Aggiungi nuova Applicazione"** in alto

📷 *[Screenshot: Pulsante "Aggiungi nuova" evidenziato]*

### Passo 2: Informazioni Base

📷 *[Screenshot: Form creazione applicazione con campi evidenziati]*

**Campi principali:**

**Nome**
- Nome dell'applicazione (es. "Colture Protette")
- Apparirà come titolo nelle pagine

**Slug**
- Si genera automaticamente dal nome
- Puoi modificarlo se necessario
- Usa solo lettere minuscole, numeri e trattini

**Descrizione**
- Breve spiegazione dell'applicazione
- Apparirà nelle pagine di archivio

**Applicazione Padre (Opzionale)**
- Se questa è una sotto-categoria di un'applicazione esistente
- Lascia vuoto se è una categoria principale

### Passo 3: Immagini

**Thumbnail Coltura**
- Immagine piccola usata negli archivi e liste
- Dimensione consigliata: 400x300 pixel
- Campo **obbligatorio** ⚠️

📷 *[Screenshot: Campo thumbnail evidenziato come obbligatorio]*

**Immagine Coltura**
- Immagine grande per la pagina singola
- Dimensione consigliata: 1200x400 pixel
- Campo opzionale ma consigliato

📷 *[Screenshot: Campo immagine hero]*

### Passo 4: Descrizione Dettagliata

Nel campo **"Descrizione coltura"** puoi aggiungere:
- Informazioni dettagliate sull'applicazione
- Caratteristiche specifiche
- Consigli di utilizzo
- Formattazione con l'editor ricco (grassetto, elenchi, ecc.)

📷 *[Screenshot: Editor WYSIWYG per descrizione]*

### Passo 5: Brochure (Opzionale)

Se hai brochure specifiche per questa applicazione:
1. Campo **"Brochure coltura"**
2. Seleziona dalle brochure esistenti
3. Puoi associarne più di una

💡 **Suggerimento**: Le brochure devono essere create prima nella sezione **Brochure Colture**.

### Passo 6: Salvare

1. Verifica che tutti i campi obbligatori siano compilati
2. Clicca **"Aggiungi nuova Applicazione"**
3. Conferma che la creazione sia andata a buon fine

✅ **Risultato**: L'applicazione sarà visibile su `https://www.toro-ag.it/applicazioni/`

---

## Modificare un'Applicazione Esistente {#modificare-applicazione}

### Trovare l'Applicazione

1. Vai su **Applicazioni**
2. Cerca nella lista l'applicazione da modificare
3. Clicca **"Modifica"** sotto il nome

📷 *[Screenshot: Lista con link modifica evidenziato]*

### Modificare le Informazioni

Puoi modificare tutti i campi:
- **Testi e descrizioni**
- **Immagini** (thumbnail e immagine principale)
- **Brochure associate**
- **Categoria padre** (per riorganizzare la gerarchia)

### Cambiare la Gerarchia

Per spostare un'applicazione sotto un'altra:
1. Campo **"Applicazione Padre"**
2. Seleziona la categoria principale
3. Salva le modifiche

⚠️ **Attenzione**: Cambiare la gerarchia può modificare l'URL dell'applicazione.

### Salvare le Modifiche

1. Modifica i campi necessari
2. Clicca **"Aggiorna"** in basso
3. Verifica il risultato sul sito

---

## Associare Brochure e Documenti {#descrizioni-brochure}

### Brochure Esistenti

Per collegare brochure già presenti nel sistema:
1. Campo **"Brochure coltura"**
2. Seleziona dalla lista dropdown
3. Puoi selezionarne più di una tenendo premuto Ctrl

### Creare Nuove Brochure

Se la brochure che ti serve non esiste:
1. Clicca **"+ Aggiungi nuovo"** accanto al campo
2. Si aprirà la creazione brochure in una nuova finestra
3. Compila e salva la brochure
4. Torna alla tua applicazione e selezionala

📷 *[Screenshot: Pulsante "Aggiungi nuovo" nel campo brochure]*

### Gestire le Descrizioni

**Descrizione Breve**
- Usata negli archivi e anteprime
- Mantienila concisa (1-2 righe)

**Descrizione Dettagliata**
- Usata nella pagina singola dell'applicazione
- Puoi essere più descrittivo
- Usa l'editor per formattare il testo

---

## Organizzazione Gerarchica

### Creare Sotto-categorie

Per organizzare meglio le applicazioni:

**Esempio di gerarchia:**
```
Frutteti (principale)
├── Agrumeti
├── Noccioleto
└── Oliveto

Ortaggi (principale)
├── Cipolla
└── Fragola
```

**Come creare:**
1. Crea prima l'applicazione principale (es. "Frutteti")
2. Crea le sotto-applicazioni
3. Nel campo "Applicazione Padre" seleziona quella principale

### Riorganizzare Esistenti

Per spostare applicazioni esistenti:
1. Modifica l'applicazione da spostare
2. Cambia il campo "Applicazione Padre"
3. Salva le modifiche

📷 *[Screenshot: Selezione applicazione padre]*

---

## Collegamento con Prodotti

### Associazione Automatica

Quando associ un'applicazione a un prodotto:
- Il prodotto apparirà nella pagina dell'applicazione
- L'applicazione apparirà nella pagina del prodotto
- Si crea un collegamento bidirezionale

### Verificare i Collegamenti

Per vedere quali prodotti sono associati:
1. Vai alla lista delle applicazioni
2. Guarda la colonna **"Conteggio"** per vedere quanti prodotti
3. Clicca sul numero per vedere l'elenco dei prodotti

📷 *[Screenshot: Colonna conteggio nella lista applicazioni]*

---

## Problemi Comuni

**L'applicazione non appare sul sito**
- Verifica che sia stata salvata correttamente
- Controlla che la thumbnail sia stata caricata (campo obbligatorio)

**L'immagine thumbnail non si vede**
- Il campo thumbnail è obbligatorio
- Verifica che l'immagine sia stata caricata correttamente
- Prova con un'immagine di dimensioni diverse

**I prodotti non appaiono nell'applicazione**
- I prodotti devono essere associati dall'editor del singolo prodotto
- Vai su **Prodotti** → **Modifica prodotto** → seleziona le applicazioni

**La gerarchia non funziona**
- Verifica che l'applicazione padre esista
- Controlla che non ci siano cicli (A padre di B, B padre di A)

**Le brochure non si collegano**
- Le brochure devono esistere nella sezione **Brochure Colture**
- Verifica che siano pubblicate

---

**Prossimo**: [Allegati Multilingua →](05-allegati-multilingua.md)