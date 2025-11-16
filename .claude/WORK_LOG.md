# Work Log - Guida Toro Ag

## Stato Progetto
**Ultimo aggiornamento**: 2025-11-16

### Sezioni Completate
- ✅ Introduzione (01-introduzione.md)
- ✅ Tipi di Prodotto (02-tipi-prodotto.md) - con mappatura campi custom backend→frontend
- ✅ Prodotti (03-prodotti.md) - con esempi nomi reali
- ✅ Applicazioni (04-applicazioni.md) - con gerarchia e nomi reali
- ✅ Collegamenti e Associazioni (05-associazioni.md) - con esempi pratici reali
- ✅ Gestione Documenti Multilingua (07-documenti-multilingua.md) - nuovo capitolo
- ✅ Screenshot menu laterale dashboard
- ✅ Screenshot tipi prodotto (5 immagini con corrispondenza backend→frontend):
  - tipi-prodotto-01.jpg: Nome e Descrizione
  - tipi-prodotto-02-hero.jpg: Immagine Hero
  - tipi-prodotto-03-thumb.jpg: Thumbnail
  - tipi-prodotto-04-schede-documenti.jpg: Schede e Documenti
  - tipi-prodotto-05-video.jpg: Video multilingua
- ✅ SUMMARY.md aggiornato con nuova sezione "Contenuti Multilingua"
- ✅ README.md aggiornato con riferimento gestione multilingua

### Funzionalità Documentate

#### Campi Custom e Visualizzazione Frontend
- Mappatura completa backend→frontend per Tipi di Prodotto
- Screenshot affiancati che mostrano dove ogni campo appare sul sito
- Documentazione dimensioni consigliate per immagini

#### Sistema Multilingua
- Tassonomia "Lingua" e logica di visualizzazione
- Versione italiana: mostra solo contenuti con lingua="italiano"
- Versione inglese: mostra contenuti in altre lingue raggruppati per lingua
- CPT documentati:
  - Schede Prodotto (`scheda_prodotto`)
  - Documenti Prodotto (`documenti_prodotto`)
  - Video
  - Brochure Colture (`brochure_coltura`)

#### Esempi con Nomi Reali
Sostituiti tutti gli esempi inventati con nomi reali:

**Tipi di Prodotto:**
- Manichetta e Ala Gocciolante
- Tempus® Air Programmatori
- Gocciolatori

**Prodotti:**
- Aqua Traxx PBX
- Aqua Traxx FC
- Aqua Traxx Elite
- Tempus® Air Programmatori

**Applicazioni/Colture:**
- Agrumeti
- Noccioleto
- Oliveto
- Vigneto
- Mais
- Colture Protette
- Frutteti
- Ortaggi
- Cipolla
- Fragola

**Gerarchia Applicazioni:**
```
Frutteti (principale)
├── Agrumeti
├── Noccioleto
└── Oliveto

Ortaggi (principale)
├── Cipolla
└── Fragola
```

### Commit Storia
1. **8b53fea** - Documenta campi custom e sistema multilingua
   - Aggiunta sezione visualizzazione frontend in 02-tipi-prodotto.md
   - Creato 07-documenti-multilingua.md
   - Aggiornati SUMMARY.md e README.md

2. **cc30f80** - Sostituisce esempi inventati con nomi reali
   - Sostituiti esempi Tipi di Prodotto e Prodotti
   - Aggiornati nomi schede documenti

3. **e5bafe7** - Aggiorna esempi con nomi reali di Applicazioni
   - Aggiornate tutte le Applicazioni con nomi reali
   - Corretta gerarchia con Frutteti/Ortaggi
   - Aggiornati esempi pratici in tutti i file

### Merge su Main
- ✅ Branch `claude/document-custom-fields-015ougqRNMxPvYi4pnieNGSx` merged su main
- ✅ Pubblicato su GitBook

## Appunti e Decisioni

### Struttura Contenuti
- File markdown numerati sequenzialmente
- Screenshot organizzati in `assets/nome-sezione/`
- Link GitBook: https://andyaea.gitbook.io/toro-ag-guida-amministratore

### Note Tecniche
- Il sito WordPress usa custom post types per i prodotti
- Pods configurato per gestire campi custom
- Tema figlio DIVI personalizzato gestisce visualizzazione multilingua
- Sistema multilingua NON usa WPML per documenti/video, ma tassonomia custom "Lingua"

### Istruzioni Aggiornate per Claude
1. **Merge su main**: Usare sempre `git merge origin/[branch-name]` per branch remoti
2. **Esempi**: Non inventare nomi, usare solo quelli dagli screenshot o chiedere all'utente
3. **Nomi reali documentati**: Riferirsi sempre alla lista in questo work log

### Prossimi Passi Potenziali
- [ ] Aggiungere screenshot per sezioni Prodotti e Applicazioni
- [ ] Documentare eventuali altri campi custom scoperti
- [ ] Aggiornare FAQ con problemi comuni sul multilingua
- [ ] Screenshot processo creazione documento multilingua

---
*Ultimo aggiornamento: 2025-11-16 - Completata documentazione campi custom e sistema multilingua*
