# Collegamenti e Associazioni

I collegamenti tra **Prodotti**, **Tipi di Prodotto** e **Applicazioni** determinano come i contenuti appaiono e si relazionano sul sito.

## Come Funzionano i Collegamenti

### Schema delle Relazioni

Il sistema di associazioni può essere visto da **tre prospettive diverse**. Tutte sono valide e rappresentano lo stesso sistema di collegamenti, ma viste da angolazioni differenti.

#### 🏷️ Prospettiva: dal Tipo di Prodotto

```
TIPO DI PRODOTTO (es. "Manichetta e Ala Gocciolante")
    ├── PRODOTTO A (es. "Aqua Traxx PBX")
    │   ├── Applicazione: Agrumeti
    │   ├── Applicazione: Vigneto
    │   └── Documenti: Scheda tecnica
    │
    └── PRODOTTO B (es. "Aqua Traxx FC")
        ├── Applicazione: Ortaggi
        └── Applicazione: Colture Protette
```

💡 **Cosa significa**: Un tipo di prodotto contiene più prodotti specifici, ognuno dei quali può essere usato in diverse applicazioni.

---

#### 🌱 Prospettiva: dall'Applicazione

```
APPLICAZIONE (es. "Vigneto")
    ├── PRODOTTO A (es. "Aqua Traxx PBX")
    │   ├── Tipo: Manichetta e Ala Gocciolante
    │   └── Documenti: Scheda tecnica
    │
    ├── PRODOTTO C (es. "Irritec Spray System")
    │   ├── Tipo: Microirrigazione
    │   └── Documenti: Brochure vigneto
    │
    └── PRODOTTO D (es. "Filter Pro V200")
        ├── Tipo: Filtrazione
        └── Documenti: Manuale tecnico
```

💡 **Cosa significa**: Un'applicazione mostra tutti i prodotti utilizzabili in quel settore, indipendentemente dal tipo a cui appartengono.

---

#### 📦 Prospettiva: dal Prodotto Singolo

```
PRODOTTO (es. "Aqua Traxx PBX")
    │
    ├── Tipo di Prodotto
    │   └── Manichetta e Ala Gocciolante (1 solo tipo)
    │
    ├── Applicazioni
    │   ├── Agrumeti
    │   ├── Vigneto
    │   └── Ortaggi (multiple applicazioni possibili)
    │
    └── Documenti e Contenuti
        ├── Scheda Prodotto: "Aqua Traxx PBX Technical"
        ├── Documento: "Guida installazione"
        └── Video: "Demo irrigazione"
```

💡 **Cosa significa**: Un prodotto appartiene a UN tipo, può essere usato in MULTIPLE applicazioni, e può avere MULTIPLI documenti associati.

### Risultato sul Sito

Quando crei questi collegamenti, le tre prospettive si riflettono nelle pagine del sito:

**Pagina Tipo di Prodotto** (es. `/prodotti/manichetta-e-ala-gocciolante/`)
- Mostra tutti i prodotti di quel tipo
- Lista le applicazioni coperte dai prodotti del tipo
- Documenti comuni al tipo

**Pagina Applicazione** (es. `/applicazioni/vigneto/`)
- Mostra tutti i prodotti utilizzabili per quel settore
- Raggruppa prodotti di tipi diversi
- Brochure e documenti specifici per l'applicazione

**Pagina Prodotto** (es. `/prodotti/aqua-traxx-pbx/`)
- Mostra il tipo di appartenenza
- Lista tutte le applicazioni possibili
- Tutti i documenti, schede e video associati

💡 **In pratica**: Ogni pagina mostra le stesse relazioni, ma da una prospettiva diversa, permettendo all'utente finale di navigare in modo intuitivo da qualsiasi punto di partenza.

### Regole Chiave delle Relazioni

| Elemento | Tipo di Prodotto | Applicazioni | Documenti |
|----------|------------------|--------------|-----------|
| **Prodotto** | 1️⃣ UNO solo (obbligatorio) | ♾️ MULTIPLE (opzionale) | ♾️ MULTIPLI (opzionale) |
| **Tipo di Prodotto** | — | — | ♾️ MULTIPLI (opzionale) |
| **Applicazione** | — | — | ♾️ MULTIPLI (opzionale) |

**Cosa ricordare:**
- ✅ Ogni prodotto deve avere ESATTAMENTE un tipo di prodotto
- ✅ Un prodotto può avere zero, una o molte applicazioni
- ✅ Documenti e video possono essere associati a prodotti, tipi o applicazioni
- ❌ Un prodotto NON può avere più tipi contemporaneamente
- ❌ Non esiste un limite al numero di applicazioni o documenti

---

## Collegare Prodotti e Tipi di Prodotto {#prodotti-tipi}

I **Tipi di Prodotto** sono una tassonomia WordPress. Ogni prodotto deve essere associato a un tipo.

Nell'editor del prodotto, trovi il box **"Tipo di Prodotto"** nella colonna destra. Seleziona UNA categoria (obbligatoria).

📷 *[Screenshot: Box tipo di prodotto nell'editor prodotto]*

⚠️ **Importante**: Senza un tipo di prodotto associato, il prodotto non apparirà correttamente sul sito.

---

## Collegare Prodotti e Applicazioni {#prodotti-applicazioni}

Le **Applicazioni** sono una tassonomia WordPress. Un prodotto può essere associato a più applicazioni.

Nell'editor del prodotto, trovi il box **"Applicazioni"** nella colonna destra. Seleziona una o più applicazioni (opzionale, ma consigliato).

📷 *[Screenshot: Box applicazioni nell'editor prodotto]*

---

## Collegare Documenti e Contenuti {#documenti-contenuti}

### Tipi di Documenti

Il sistema gestisce diversi tipi di documenti:

**Schede Prodotto**
- Schede tecniche dettagliate
- Associate a prodotti specifici o tipi di prodotto

**Documenti Prodotto**
- Brochure, manuali, certificazioni
- Possono essere associati a più elementi

**Brochure Coltura**
- Documenti specifici per applicazioni
- Associate alle applicazioni

### Associare Schede Prodotto

**A un singolo prodotto:**
1. Modifica il prodotto
2. Sezione **"Scheda Prodotto"**
3. Seleziona schede esistenti o crea nuove

**A un tipo di prodotto:**
1. Modifica il tipo di prodotto
2. Sezione **"Scheda Prodotto tipo"**
3. Seleziona schede esistenti

📷 *[Screenshot: Campo scheda prodotto nell'editor]*

### Associare Documenti

**Documenti a Prodotti:**
1. Modifica il prodotto
2. Sezione **"Documento Prodotto"**
3. Seleziona documenti esistenti

**Documenti a Tipi:**
1. Modifica il tipo di prodotto
2. Sezione **"Documento Prodotto Tipo"**
3. Seleziona documenti esistenti

### Associare Video

**Video a Prodotti:**
1. Modifica il prodotto
2. Sezione **"Video Prodotto"**
3. Seleziona video esistenti

**Video a Tipi:**
1. Modifica il tipo di prodotto
2. Sezione **"Video"**
3. Seleziona video esistenti

---

## Workflow Completo per Nuovo Prodotto

### Checklist Passo-Passo

Quando aggiungi un prodotto completamente nuovo:

1. **✅ Verifica il Tipo di Prodotto**
   - Esiste già il tipo giusto?
   - Se no, crealo prima

2. **✅ Verifica le Applicazioni**
   - Esistono le applicazioni pertinenti?
   - Se no, creale prima

3. **✅ Crea il Prodotto**
   - Titolo e descrizione
   - Immagine in primo piano
   - Galleria (se necessaria)

4. **✅ Associazioni Obbligatorie**
   - Seleziona il Tipo di Prodotto (1 solo)
   - Seleziona le Applicazioni (1 o più)

5. **✅ Documenti (se disponibili)**
   - Schede tecniche
   - Brochure
   - Video dimostrativi

6. **✅ Test Finale**
   - Pubblica il prodotto
   - Controlla che appaia nelle pagine corrette
   - Verifica tutti i collegamenti

### Esempio Pratico

**Nuovo prodotto: "Aqua Traxx Elite"**

1. **Tipo**: Già esiste "Manichetta e Ala Gocciolante" ✅
2. **Applicazioni**: Servono "Ortaggi" e "Vigneto"
   - "Ortaggi" esiste ✅
   - "Vigneto" esiste ✅
3. **Prodotto**: Creo "Aqua Traxx Elite"
   - Associo a "Manichetta e Ala Gocciolante"
   - Associo a "Ortaggi" e "Vigneto"
4. **Documenti**: Associo scheda tecnica esistente
5. **Test**: Controllo che appaia in:
   - `/prodotti/manichetta-e-ala-gocciolante/`
   - `/applicazioni/ortaggi/`
   - `/applicazioni/vigneto/`

---

## Gestire Collegamenti Esistenti

### Modificare Associazioni

**Rimuovere associazioni:**
- Deseleziona l'elemento nell'editor
- Salva le modifiche
- Il collegamento sparisce automaticamente

**Aggiungere associazioni:**
- Seleziona elementi aggiuntivi
- Salva le modifiche
- I nuovi collegamenti appaiono

### Riorganizzare la Struttura

**Spostare prodotti tra tipi:**
1. Modifica il prodotto
2. Cambia il tipo di prodotto
3. L'URL del prodotto cambierà automaticamente

**Riorganizzare applicazioni:**
1. Modifica l'applicazione
2. Cambia l'applicazione padre
3. La gerarchia si aggiorna

⚠️ **Attenzione**: Cambiare la struttura può modificare gli URL. Verifica che non ci siano link esterni che si rompono.

---

## Problemi Comuni e Soluzioni

### "Il prodotto non appare nella categoria"

**Cause possibili:**
- Tipo di prodotto non selezionato → Selezionalo
- Prodotto in bozza → Pubblicalo
- Cache del sito → Aspetta qualche minuto

### "L'applicazione è vuota"

**Cause possibili:**
- Nessun prodotto associato all'applicazione
- Prodotti non pubblicati
- Associazioni sbagliate

**Soluzione:**
1. Vai ai prodotti che dovrebbero apparire
2. Verifica che abbiano l'applicazione selezionata
3. Verifica che siano pubblicati

### "I documenti non si vedono"

**Cause possibili:**
- Documenti non associati correttamente
- Documenti non pubblicati
- File PDF mancanti

**Soluzione:**
1. Verifica l'associazione nell'editor
2. Controlla che i documenti esistano
3. Verifica che i file siano caricati

### "Troppi prodotti in una categoria"

**Soluzione:**
- Crea sottocategorie più specifiche
- Rivedi la logica di classificazione
- Usa le applicazioni per filtrare meglio

---

## Best Practices

### Organizzazione Logica

**Per i Tipi di Prodotto:**
- Mantieni categorie chiare e non sovrapposte
- Non creare troppe categorie simili
- Usa nomi comprensibili agli utenti finali

**Per le Applicazioni:**
- Organizza per settore d'uso reale
- Usa la gerarchia per sotto-settori
- Evita duplicazioni concettuali

**Per i Prodotti:**
- Associa solo alle categorie pertinenti
- Non esagerare con le applicazioni multiple
- Mantieni coerenza nella nomenclatura

### Controlli Periodici

**Ogni mese:**
- Verifica che tutti i prodotti abbiano associazioni corrette
- Controlla che i conteggi nelle liste siano ragionevoli
- Testa la navigazione dal punto di vista dell'utente finale

**Prima di pubblicare nuovi prodotti:**
- Verifica la struttura esistente
- Controlla se servono nuove categorie
- Testa tutti i collegamenti

---

**Prossimo**: [Domande Frequenti →](07-faq.md)