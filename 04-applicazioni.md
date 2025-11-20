# Gestire le Applicazioni

Le **Applicazioni** (chiamate anche Colture) rappresentano gli ambiti di utilizzo dei tuoi prodotti (es. "Agrumeti", "Vigneto", "Mais", "Colture Protette").
Questa tassonomia permette di organizzare i prodotti per tipo di coltivazione e creare una connessione bidirezionale: i prodotti mostrano le applicazioni per cui sono adatti, e le applicazioni mostrano i prodotti disponibili.

---

## Dove si Vedono le Applicazioni

**Sul sito pubblico:**
- Pagina archivio: <a href="https://www.toro-ag.it/applicazioni/" target="_blank">https://www.toro-ag.it/applicazioni/</a>
- Singola applicazione: <a href="https://www.toro-ag.it/applicazioni/irrigazione-fragola/" target="_blank">https://www.toro-ag.it/applicazioni/irrigazione-fragola/</a>

## Accedere alla Modifica delle Applicazioni

### Dal Sito Pubblico

Nella pagina dell'applicazione, se loggato come Admin, clicca su **"Modifica Applicazione"** per accedere alla maschera di modifica.

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00b-admin.jpg" alt="modifica applicazione"></div>

⚠️ **Attenzione**: Non abilitare il Visual Builder di Divi durante la modifica, altrimenti potresti compromettere la formattazione della pagina.

### Nell'Amministrazione

Clicca su **"Applicazioni"** nella barra laterale per visualizzare l'elenco di tutte le applicazioni.

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00-admin.jpg" alt="Elenco applicazioni"></div>

#### Cercare un'Applicazione

Usa il campo di ricerca in alto a destra per trovare rapidamente un'applicazione specifica.

#### Modificare un'Applicazione

Clicca su **"Modifica"** sotto il nome dell'applicazione che vuoi modificare.

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00-admin.jpg" alt="Modifica di un'applicazione"></div>

---

## Come i Campi Custom Appaiono sul Sito

Di seguito la corrispondenza tra gli elementi visualizzati nel frontend e i singoli campi da compilare nel backend.

### Nome

**Nel frontend - Pagina archivio:**

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00-pagina.jpg" alt="Griglia applicazioni con nomi"></div>

**Nel frontend - Pagina singola:**

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00-singola.jpg" alt="Titolo dell'applicazione"></div>

**Nel backend:**

<div data-with-frame="true"><img src="assets/applicazioni/Applicazioni-00-admin.jpg" alt="Campo Nome"></div>

Modifica il campo **"Nome"** nella parte superiore del form (es. "Fragola", "Agrumeti", "Vigneto").

💡 Lo **Slug** viene generato automaticamente dal nome, ma puoi personalizzarlo se necessario.

---

### Descrizione

La descrizione viene utilizzata nelle pagine di archivio e nelle anteprime.

**Nel frontend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-01-descrizione-front.jpg" alt="Descrizione nel frontend"></div>

**Nel backend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-01-descrizione-back.jpg" alt="Editor descrizione"></div>

Usa l'editor **"Descrizione"** con formattazione Rich Text per inserire una descrizione breve ma esaustiva dell'applicazione.

---

### Thumbnail Coltura

L'immagine thumbnail è utilizzata nella griglia delle applicazioni (pagina archivio) e nelle liste.

**Nel frontend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-02-thumbnail-front.jpg" alt="Thumbnail nella griglia applicazioni"></div>

**Nel backend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-02-thumbnail-back.jpg" alt="Campo Thumbnail Coltura"></div>

Nel campo **"Thumbnail coltura"** clicca **"Aggiungi file"** per selezionare o caricare l'immagine.

⚠️ **Importante**: Questo campo è **obbligatorio** (contrassegnato con asterisco rosso). L'applicazione non verrà visualizzata senza una thumbnail.

💡 Dimensione consigliata: 600 per 450 pixel.

---

### Immagine Coltura (Hero)

L'immagine hero è la grande immagine visualizzata nella parte superiore della pagina singola dell'applicazione.

**Nel frontend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-03-hero-front.jpg" alt="Immagine Hero"></div>

**Nel backend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-03-hero-back.jpg" alt="Campo Immagine Coltura"></div>

Nel campo **"Immagine coltura"** clicca per selezionare l'immagine hero.

💡 Dimensione consigliata: 2560 per 300 pixel.

📌 **Nota**: Questo campo è opzionale ma fortemente consigliato per una migliore presentazione visiva.

---

### Brochure Coltura

Associa brochure e documenti specifici per questa applicazione.

**Nel frontend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-05-brochure-front.jpg" alt="Brochure nella sidebar"></div>

Le brochure appaiono nella sidebar della pagina singola dell'applicazione, pronte per il download.

**Nel backend:**

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-05-brochure-back.jpg" alt="Campo Brochure Coltura"></div>

Nel campo **"Brochure coltura"** cerca e seleziona le brochure esistenti. Puoi associarne più di una.

💡 Le brochure devono essere create prima nella sezione **"Tutte le Brochure"** → **"Brochure Colture"**.

💡 Clicca **"Aggiungi"** per aggiungere nuove brochure alla selezione.

---

### Prodotti Associati

<div data-with-frame="true"><img src="assets/applicazioni/applicazioni-07-prodotti-front.jpg" alt="Prodotti organizzati per tipo"></div>

I prodotti a cui è associtata l'applicazione vengono visulalizzati nella pagina organizzati per "Tipo di Prodotto" (Manichetta e Ala Gocciolante, Gocciolatori, Filtri, etc.).

**Associazione bidirezionale:**
- Quando associ un'applicazione a un prodotto, il prodotto appare automaticamente nella pagina dell'applicazione
- L'applicazione appare nella pagina del prodotto con la relativa icona

💡 Per associare prodotti a un'applicazione, vai su **Prodotti** → **Modifica prodotto** → seleziona le applicazioni nel campo **"Applicazioni"**.

💡 Per vedere quanti prodotti sono associati, guarda la colonna **"Conteggio"** nella lista delle applicazioni.

---

## Note Importanti

**Campo obbligatorio:**
- La **Thumbnail Coltura** è l'unico campo obbligatorio contrassegnato con asterisco rosso
- Senza thumbnail, l'applicazione non verrà visualizzata correttamente nella griglia

**Collegamento con prodotti:**
- I prodotti devono essere associati dall'editor del singolo prodotto
- Il collegamento è bidirezionale: modifica in un punto, appare in entrambi
- I prodotti sono automaticamente raggruppati per tipo nella pagina dell'applicazione

---

**Prossimo**: [Allegati Multilingua →](05-allegati-multilingua.md)
