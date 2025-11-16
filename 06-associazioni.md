# Collegamenti e Associazioni

Una delle parti più importanti della gestione del sito è creare i collegamenti giusti tra **Prodotti**, **Tipi di Prodotto** e **Applicazioni**. Questi collegamenti determinano come i contenuti appaiono e si relazionano sul sito.

## Come Funzionano i Collegamenti

### Schema delle Relazioni

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

### Risultato sul Sito

Quando crei questi collegamenti:
- La pagina del **Tipo di Prodotto** mostrerà tutti i prodotti associati
- La pagina dell'**Applicazione** mostrerà tutti i prodotti che la utilizzano
- La pagina del **Prodotto** mostrerà tipo e applicazioni correlate

---

## Collegare Prodotti e Tipi di Prodotto {#prodotti-tipi}

### Associazione Base (Obbligatoria)

Ogni prodotto DEVE essere associato a un tipo:

1. **Modifica il prodotto** (Prodotti → Modifica)
2. Trova la sezione **"Tipo di Prodotto"** nella colonna destra
3. **Seleziona UNA categoria** (non puoi selezionarne più di una)
4. Clicca **"Aggiorna"**

📷 *[Screenshot: Box tipo di prodotto nell'editor prodotto]*

⚠️ **Importante**: Se non selezioni un tipo di prodotto, il prodotto non apparirà correttamente sul sito.

### Verificare l'Associazione

**Dal prodotto:**
- Guarda la colonna destra nell'editor del prodotto
- Il tipo selezionato dovrebbe essere evidenziato

**Dal tipo di prodotto:**
- Vai a **Prodotti** → **Tipo di Prodotti**
- La colonna "Conteggio" mostra quanti prodotti sono associati

**Sul sito:**
- Vai alla pagina del tipo (es. `/prodotti/manichetta-e-ala-gocciolante/`)
- Dovresti vedere tutti i prodotti associati

---

## Collegare Prodotti e Applicazioni {#prodotti-applicazioni}

### Associazione Multiple

Un prodotto può essere usato per più applicazioni:

1. **Modifica il prodotto**
2. Trova la sezione **"Applicazioni"** nella colonna destra
3. **Seleziona una o più applicazioni** (checkbox multiple)
4. Clicca **"Aggiorna"**

📷 *[Screenshot: Box applicazioni con checkbox multipli]*

### Scegliere le Applicazioni Giuste

**Esempi pratici:**
- **Manichetta irrigazione** → Agrumeti, Vigneto, Ortaggi, Frutteti
- **Prodotto specializzato** → Solo Vigneto
- **Sistema irrigazione** → Ortaggi, Colture Protette, Agrumeti

💡 **Suggerimento**: Seleziona solo le applicazioni realmente pertinenti. Troppi collegamenti rendono confusa la navigazione.

### Verificare i Collegamenti

**Dal prodotto:**
- Nella sezione Applicazioni dovresti vedere le caselle selezionate

**Dall'applicazione:**
- Vai a **Applicazioni** nella lista
- Il conteggio mostra quanti prodotti sono associati

**Sul sito:**
- Pagina applicazione: `/applicazioni/agrumeti/` → mostra prodotti per agrumeti
- Pagina prodotto: mostra le applicazioni in cui è usato

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