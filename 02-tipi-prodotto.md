# Gestire i Tipi di Prodotto

I **Tipi di Prodotto** rappresentano una tassonomia custom che organizza i tuoi prodotti in termini specifici (es. "Manichetta e Ala Gocciolante", "Tempus® Air Programmatori", "Gocciolatori"). Nel frontend, questa tassonomia viene visualizzata come **"Prodotti"**.

## Dove si Vedono i Tipi di Prodotto

**Sul sito pubblico:**
- Pagina archivio: <a href="https://www.toro-ag.it/prodotti/" target="_blank">https://www.toro-ag.it/prodotti/</a>
- Singola categoria: <a href="https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/" target="_blank">https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/</a>

**Nell'amministrazione:**

_[Screenshot della voce "Tipo di Prodotti" nella barra laterale]_

---

## Come i Campi Custom Appaiono sul Sito

Ogni campo che compili nell'amministrazione ha una corrispondenza precisa nel frontend. Ecco la mappa completa:

### Nome e Descrizione → Titolo e Contenuto Pagina

![Nome prodotto backend vs frontend](assets/tipi-prodotto/tipi-prodotto-01.jpg)

Il **Nome** del tipo diventa il **titolo principale** della pagina, mentre la **Descrizione** diventa il testo introduttivo.

### Thumbnail → Griglia Tipi di Prodotto

![Thumbnail backend vs frontend](assets/tipi-prodotto/tipi-prodotto-03-thumb.jpg)

La **Thumbnail** (miniatura) appare nella griglia della pagina `/prodotti/` quando si visualizzano tutti i tipi di prodotto.

### Immagine Hero → Header Pagina Tipo

![Immagine Hero backend vs frontend](assets/tipi-prodotto/tipi-prodotto-02-hero.jpg)

L'**Immagine Hero** diventa l'immagine grande in cima alla pagina del singolo tipo di prodotto.

### Schede e Documenti → Sezioni Download

![Schede e Documenti backend vs frontend](assets/tipi-prodotto/tipi-prodotto-04-schede-documenti.jpg)

Le **Schede Prodotto** e i **Documenti** associati appaiono come link scaricabili organizzati in sezioni dedicate nella pagina del tipo.

### Video → Player Video nella Pagina

![Video backend vs frontend](assets/tipi-prodotto/tipi-prodotto-05-video.jpg)

I **Video** associati vengono mostrati con un player integrato (YouTube) nella pagina del tipo di prodotto.