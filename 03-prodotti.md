# Gestire i Prodotti

I **Prodotti** sono i singoli elementi del tuo catalogo (es. "Aqua-Traxx® FlowControl™", "Tempus® Air Programmatori"). Ogni prodotto viene assegnato a un Tipo di Prodotto e può essere associato a una o più Applicazioni (colture).

## Dove si Vedono i Prodotti

**Sul sito pubblico:**
- Nelle pagine dei tipi: <a href="https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/" target="_blank">https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/</a>
- Pagina prodotto singolo: <a href="https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/aqua-traxx-flowcontrol/" target="_blank">https://www.toro-ag.it/prodotti/manichetta-e-ala-gocciolante/aqua-traxx-flowcontrol/</a>

**Nell'amministrazione:**

**Passo 1: Accedere ai prodotti**

Clicca su **"Prodotti"** nella barra laterale per visualizzare l'elenco di tutti i prodotti.

![Elenco prodotti](assets/prodotti/prodotti-00-admin-1.jpg)

**Passo 2: Modificare un prodotto**

Clicca su **"Modifica"** sotto il nome del prodotto che vuoi modificare.

![Modifica di un prodotto](assets/prodotti/prodotti-00-admin-2.jpg)

---

## Come i Campi Custom Appaiono sul Sito

Di seguito la corrispondenza tra gli elementi visualizzati nel frontend e i singoli campi da compilare nel backend.

### Titolo

**Nel frontend:**

![Titolo nel frontend](assets/prodotti/prodotti-01-titolo-front.jpg)

**Nel backend:**

![Campo Titolo](assets/prodotti/prodotti-01-titolo-back.jpg)

Modifica il campo **"Titolo"** nella parte superiore dell'editor (funzionamento standard WordPress).

---

### Descrizione

**Nel frontend:**

![Descrizione nel frontend](assets/prodotti/prodotti-02-descrizione-front.jpg)

**Nel backend:**

![Editor descrizione](assets/prodotti/prodotti-02-descrizione-back.jpg)

Usa l'editor principale con formattazione Rich Text per inserire la descrizione completa del prodotto con tutte le informazioni tecniche.

---

### Immagine in Evidenza

**Nel frontend:**

![Immagine principale del prodotto](assets/prodotti/prodotti-03-immagine-front.jpg)

**Nel backend:**

![Campo Immagine in Evidenza](assets/prodotti/prodotti-03-immagine-back.jpg)

Clicca **"Imposta immagine in primo piano"** nella colonna destra. Dimensione consigliata: 800x600px.

---

### Tipo di Prodotto

**Nel frontend:**

Il Tipo di Prodotto determina la categoria principale e la struttura URL del prodotto.

![Breadcrumb con tipo di prodotto](assets/prodotti/prodotti-04-tipo-front.jpg)

**Nel backend:**

![Selezione Tipo di Prodotto](assets/prodotti/prodotti-04-tipo-back.jpg)

Nella colonna destra, seleziona il **"Tipo di Prodotto"** appropriato (es. "Manichetta e Ala Gocciolante", "Gocciolatori", "Tempus® Air Programmatori").

⚠️ **Importante**: Il prodotto apparirà nella pagina archivio del tipo selezionato.

---

### Applicazioni

**Nel frontend:**

![Applicazioni con icone](assets/prodotti/prodotti-05-applicazioni-front.jpg)

**Nel backend:**

![Selezione Applicazioni](assets/prodotti/prodotti-05-applicazioni-back.jpg)

Nella colonna destra, seleziona una o più **"Applicazioni"** (es. Agrumeti, Noccioleto, Ortaggi, Cipolla, Fragola, Vigneto).

💡 Puoi selezionare più applicazioni per lo stesso prodotto.

---

### Galleria Prodotto

**Nel frontend:**

![Carousel/Galleria immagini](assets/prodotti/prodotti-06-galleria-front.jpg)

**Nel backend:**

![Campo Galleria Prodotto](assets/prodotti/prodotti-06-galleria-back.jpg)

Nella colonna destra, clicca **"Aggiungi file"** nel campo **"Galleria Prodotto"** per aggiungere immagini aggiuntive al carousel.

💡 L'immagine in evidenza viene inclusa automaticamente nel carousel.

---

### Schede Prodotto

**Nel frontend:**

![Schede scaricabili nel frontend](assets/prodotti/prodotti-07-schede-front.jpg)

**Nel backend:**

![Campo Schede Prodotto](assets/prodotti/prodotti-07-schede-back.jpg)

Seleziona le schede tecniche dal campo **"Scheda Prodotto"**. Clicca **"Aggiungi"** per cercare e selezionare le schede esistenti.

💡 Per gestire i file delle schede, vedi [Allegati Multilingua](05-allegati-multilingua.md).

---

### Documenti Prodotto

**Nel frontend:**

![Documenti nel frontend](assets/prodotti/prodotti-08-documenti-front.jpg)

**Nel backend:**

![Campo Documenti Prodotto](assets/prodotti/prodotti-08-documenti-back.jpg)

Seleziona brochure e documenti dal campo **"Documento Prodotto"**. Clicca **"Aggiungi"** per cercare e selezionare i documenti esistenti.

💡 Per gestire i file dei documenti, vedi [Allegati Multilingua](05-allegati-multilingua.md).

---

### Video Prodotto

**Nel frontend:**

![Video nel frontend](assets/prodotti/prodotti-09-video-front.jpg)

**Nel backend:**

![Campo Video Prodotto](assets/prodotti/prodotti-09-video-back.jpg)

Seleziona i video dimostrativi dal campo **"Video Prodotto"**. Clicca **"Aggiungi"** per cercare e selezionare i video esistenti.

💡 Per gestire i video, vedi [Allegati Multilingua](05-allegati-multilingua.md).

---

## Aggiungere un Nuovo Prodotto

1. Vai su **Prodotti** → **Aggiungi nuovo**
2. Compila tutti i campi descritti sopra
3. Assicurati di selezionare almeno:
   - Un **Tipo di Prodotto**
   - Almeno un'**Applicazione**
   - L'**Immagine in evidenza**
4. Clicca **"Pubblica"**

✅ Il prodotto sarà visibile nella pagina del tipo di prodotto corrispondente.

---

## Modificare un Prodotto Esistente

1. Vai su **Prodotti**
2. Trova il prodotto nella lista (puoi usare i filtri per tipo o applicazione)
3. Clicca **"Modifica"** sotto il titolo
4. Modifica i campi necessari
5. Clicca **"Aggiorna"**

---

## Problemi Comuni

**Il prodotto non appare nel tipo di prodotto**
- Verifica che il "Tipo di Prodotto" sia selezionato
- Controlla che il prodotto sia "Pubblicato"

**Le immagini non si caricano**
- Verifica dimensioni (non oltre 2MB)
- Prova formati diversi (JPG/PNG)

**I documenti/schede/video non si collegano**
- Devono esistere già nel sistema come Allegati Multilingua
- Verifica nella sezione appropriata prima di associarli

---

**Prossimo**: [Gestire le Applicazioni →](04-applicazioni.md)
