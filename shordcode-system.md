# LISTA COMPLETA SHORTCODE TORO-AG

## 1. `[brochure_coltura_dettaglio]`
**Carica**: Brochure associate a una coltura (solo archivi tassonomia coltura)  
**Parametri**:
- `layout` - "card" o "list" (default: card)
- `titolo` - titolo personalizzato

---

## 2. `[agente_card]`
**Carica**: Card con dati dell'agente loggato (nome, indirizzo, territori, logout)  
**Parametri**: Nessuno

---

## 3. `[doc_plus]`
**Carica**: Documenti doc_plus collegati alla pagina con cover e allegati  
**Parametri**:
- `ids` - ID specifici (separati da virgola)
- `slugs` - slug specifici (separati da virgola)
- `layout` - tipo layout (default, grid, carousel, list)
- `title` - titolo sezione
- `griglia` - configurazione griglia

---

## 4. `[documenti_pagina]`
**Carica**: Lista documenti associati a una pagina (layout compatto)  
**Parametri**:
- `title` - titolo sezione

---

## 5. `[documenti_agente]`
**Carica**: Documenti per agenti loggati e attivi (categorie organizzate)  
**Parametri**:
- `layout` - "lista" o "gallery" (default: lista)

---

## 6. `[coltura_docs]`
**Carica**: Brochure PDF allegati a un termine coltura  
**Parametri**:
- `term_id` - ID termine coltura (opzionale, usa termine corrente se omesso)

---

## 7. `[elenco_prodotti_con_dettagli]`
**Carica**: Elenco prodotti raggruppati per tipo con documenti e schede (+ altra documentazione da pagine e colture)  
**Parametri**:
- `layout` - "grid" (default)

---

## 8. `[product_docs]`
**Carica**: Brochure, documentazione e colture associate a un prodotto  
**Parametri**: Nessuno (usa prodotto corrente)

---

## 9. SHORTCODE GRID (7 shortcode)

### `[toro_tipi_prod]`
**Carica**: Griglia tutti i tipi di prodotto  
**Parametri**: Nessuno

### `[toro_colture]`
**Carica**: Griglia tutte le colture  
**Parametri**: Nessuno

### `[toro_prodotti_tipo]`
**Carica**: Prodotti del tipo corrente (archivio tipo_di_prodotto)  
**Parametri**: Nessuno

### `[toro_culture_prodotto]`
**Carica**: Colture del prodotto corrente (single prodotto)  
**Parametri**: Nessuno

### `[toro_tipi_per_coltura]`
**Carica**: Tipi di prodotto raggruppati per coltura corrente  
**Parametri**: Nessuno

### `[toro_prodotti_page]`
**Carica**: Griglia prodotti selezionati in pagina  
**Parametri**:
- `title` - titolo sezione
- `columns` - numero colonne 1-6 (default: 3)
- `debug` - "true" per debug (default: false)

### `[toro_colture_page]`
**Carica**: Griglia colture selezionate in pagina  
**Parametri**:
- `title` - titolo sezione
- `columns` - numero colonne 1-6 (default: 3)
- `debug` - "true" per debug (default: false)

---

## 10. `[hero_tipo_prodotto_e_coltura]`
**Carica**: Immagine hero per archivi tipo_di_prodotto o coltura  
**Parametri**: Nessuno (automatico)

---

## 11. `[video_prodotto_v2]`
**Carica**: Video associati al prodotto corrente, filtrati per lingua  
**Parametri**: Nessuno

---

## 12. `[ricerca_agenti]`
**Carica**: Form ricerca rivenditori per regione/provincia con AJAX  
**Parametri**:
- `ordinamento` - "A-Z" o "N-S" (Nord-Sud) (default: A-Z)

---

## 13. `[scheda_prodotto]`
**Carica**: Lista schede prodotto collegate al prodotto corrente  
**Parametri**: Nessuno

---

## 14. `[scheda_prodotto_dettaglio]`
**Carica**: Card con schede e documenti del prodotto corrente (organizzati per lingua)  
**Parametri**: Nessuno

---

## 15. `[scheda_prodotto_tipo_dettaglio]`
**Carica**: Card con schede e documenti del tipo di prodotto corrente (archivio)  
**Parametri**: Nessuno

---

## 16. `[video_tipo_prodotto_v2]`
**Carica**: Video associati al tipo di prodotto corrente, filtrati per lingua  
**Parametri**: Nessuno (usa termine corrente tipo_di_prodotto)

---

## 17. `[carosello_video_pagina]`
**Carica**: Carosello Swiper con video della pagina (>3 video) o griglia statica (≤3)  
**Parametri**:
- `titolo` - titolo da mostrare sopra i video

---

## 18. `[video_pagina]`
**Carica**: Griglia statica video associati alla pagina corrente  
**Parametri**:
- `titolo` - titolo da mostrare sopra i video

---

## 19. `[video_prodotto]`
**Carica**: Griglia video associati a prodotto o tipo_di_prodotto, filtrati per lingua  
**Parametri**: Nessuno (automatico in base al contesto)

---

**TOTALE**: 19 shortcode funzionali

> **Note**: Tutti gli shortcode sono compatibili WPML con fallback automatico alla lingua di default quando necessario.