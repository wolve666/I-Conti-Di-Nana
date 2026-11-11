# I conti di Nana

![Versione](https://img.shields.io/badge/versione-2.1-E3B505) ![Tipo](https://img.shields.io/badge/tipo-PWA-2C2C2A) ![Piattaforma](https://img.shields.io/badge/Android-Chrome-3F8F6E) ![Dati](https://img.shields.io/badge/dati-solo%20sul%20telefono-7C7B76)

App per la gestione dei conti di casa, nata per sostituire un foglio Excel: spese ed entrate del mese, ripartizione del conto corrente, progetti con fondi propri e risparmi. Funziona come un'app installata sul telefono, anche senza connessione.

**Indirizzo:** https://wolve666.github.io/I-Conti-Di-Nana/

---

## Indice

- [Funzioni](#funzioni)
  - [Conticini](#conticini)
  - [Progetti](#progetti)
  - [Conti del mese](#conti-del-mese)
  - [Grafici](#grafici)
  - [Risparmi](#risparmi)
  - [Strumenti](#strumenti)
  - [Aspetto e navigazione](#aspetto-e-navigazione)
- [Installazione](#installazione)
- [Aggiornamento](#aggiornamento)
- [Dati e backup](#dati-e-backup)
- [Struttura dei file](#struttura-dei-file)
- [Tecnologie](#tecnologie)
- [Storico delle versioni](#storico-delle-versioni)

---

## Funzioni

### Conticini

La scheda principale dell'app, al centro della barra in basso. Spiega come è composta la disponibilità del conto corrente, come in un foglio di calcolo.

- **Disponibilità sul conto**: l'importo presente sul conto, aggiornato a mano.
- **Voci divise in due gruppi**: *Spese* (auto, casa, spesa…) e *Investimenti e progetti*, ognuno con il proprio subtotale.
- **Tasti − e +** su ogni voce per togliere o aggiungere un importo; toccando il nome si modifica la voce e si vedono le ultime variazioni.
- **Riepilogo**: totale spese, totale investimenti, totale assegnato, disponibilità e differenza (verde se resta qualcosa da assegnare, rossa se si supera la disponibilità).

| Esempio | Importo |
|---|---|
| Auto | 200 € |
| Casa | 700 € |
| Spesa | 300 € |
| **Totale assegnato** | **1200 €** |
| Disponibilità sul conto | 1500 € |
| **Differenza** | **+300 €** |

**Collegamento con i progetti.** Una voce può essere collegata a un progetto: il suo importo coincide sempre con il fondo del progetto. Aggiungere 200 € alla voce "Viaggio Londra" li versa nel progetto; togliere 150 € dalla scheda del progetto aggiorna la voce. I due lati restano sempre allineati.

### Progetti

Pianificazione di spese e obiettivi, con conteggi **separati** dai conti del mese: ogni progetto è una "bolla" a sé.

- **Quadratoni** con nome, fondo disponibile, avanzamento rispetto al budget e data obiettivo.
- **Fondo del progetto**: aggiungi fondi, registra spese, togli fondi.
- **Spese previste**: elenco di ciò che servirà con importo stimato e totale ancora da spendere; quando una voce viene pagata si spunta e la spesa esce dal fondo.
- **Storico** di tutti i movimenti del progetto.
- Budget, data obiettivo e nota facoltativi; alla creazione si può aggiungere subito il progetto ai Conticini.

### Conti del mese

- Riepilogo del mese: rimasto, entrate, uscite e soldi messi da parte, con barra proporzionale.
- Inserimento rapido di **uscite, entrate e risparmi** con importo, categoria, data e nota.
- **Filtri** per tipo (uscite, entrate, risparmi) e **per categoria**, con totale del mese e dell'anno della categoria scelta.
- **Spese e entrate fisse** (affitto, bollette, stipendio) da aggiungere al mese con un tocco.
- Navigazione tra i mesi con le frecce.

### Grafici

- Spese per categoria del mese (ciambella).
- Entrate e uscite degli ultimi 12 mesi.
- Guadagno o perdita mese per mese.
- Andamento dei risparmi accumulati.

### Risparmi

- **Salvadanai** con obiettivo facoltativo e barra di avanzamento.
- Versamenti e prelievi, totale messo da parte.

### Strumenti

- **Calcolatrice flottante**: pallino sopra il pulsante +, si apre come finestra compatta e trascinabile, con somme, sottrazioni, moltiplicazioni, divisioni e percentuali. "Usa come importo" inserisce il risultato nel modulo aperto.
- **Categorie personalizzabili** per spese ed entrate.
- **Esportazione CSV** apribile con Excel.

### Aspetto e navigazione

- **Due temi**: *Sobrio* (bianco, grigio e giallo, fiori appena accennati) e *Fiori* (rosa e rosso con ibischi hawaiani).
- **Swipe** a destra e a sinistra per passare tra le schede, con animazione di scorrimento.
- **Tasto indietro** del telefono: chiude i moduli, esce dalle schede dei progetti e ripercorre le schede visitate.
- **Riquadri spostabili**: tenendo premuto un riquadro per mezzo secondo si solleva e si trascina dove si preferisce (Conticini, Mese, Grafici, scheda progetto e ordine dei progetti). Ripristinabile da Impostazioni.
- **Animazioni**: pioggia di petali sui risparmi e sui fondi aggiunti, cuoricini sulle entrate, numeri che scorrono, icone delle schede che rispondono al tocco. Si disattivano da sole se il telefono ha "riduci animazioni".

---

## Installazione

1. Aprire l'indirizzo dell'app con **Chrome** sul telefono Android.
2. Toccare il pulsante **Installa** accanto al nome dell'app (in alternativa: menu ⋮ di Chrome → *Installa app*).
3. L'app compare tra le applicazioni con la sua icona e si apre a schermo intero.

> Su iPhone: Safari → Condividi → *Aggiungi alla schermata Home*.

## Aggiornamento

1. Scaricare i file aggiornati.
2. Nel repository GitHub, da Chrome: **Add file → Upload files** (se il pulsante non compare, attivare *Sito desktop* dal menu di Chrome).
3. Caricare i file sovrascrivendo i precedenti e confermare con **Commit changes**.
4. Dopo un paio di minuti, riaprire l'app: la versione accanto al nome deve corrispondere a quella nuova.

> L'app per Android di GitHub non permette di caricare file: usare il sito da browser.

## Dati e backup

- Tutti i dati restano **solo sul telefono** (memoria del browser): non vengono inviati a nessun server.
- Disinstallare l'app o cancellare i dati di Chrome può eliminarli: esportare un **backup** ogni tanto da *Impostazioni → Backup*.
- Il backup (file JSON) si può reimportare sullo stesso o su un altro dispositivo.
- Le versioni nuove convertono automaticamente i dati delle precedenti.

## Struttura dei file

| File | Contenuto |
|---|---|
| `index.html` | L'intera app: interfaccia, stili e logica |
| `manifest.webmanifest` | Nome, colori e icone per l'installazione |
| `sw.js` | Service worker: installazione e funzionamento offline |
| `icon-180.png`, `icon-192.png`, `icon-512.png` | Icone dell'app |
| `maskable-192.png`, `maskable-512.png` | Icone con margine per le forme rotonde di Android |

## Tecnologie

- HTML, CSS e JavaScript in un unico file, senza framework.
- Progressive Web App (manifest e service worker), pubblicata con **GitHub Pages**.
- [Chart.js](https://www.chartjs.org/) per i grafici, font Nunito e Pacifico da Google Fonts.
- Salvataggio con `localStorage` del browser.

## Storico delle versioni

| Versione | Novità |
|---|---|
| **2.1** | Correzione dei glitch grafici di barra e tocchi, animazioni delle icone delle schede, riquadri spostabili con pressione lunga |
| **2.0** | Scheda Conticini, progetti con fondi separati dai conti del mese e collegati ai Conticini, swipe tra le schede, tasto indietro, pulsante di installazione |
| **1.5** | Pagina Progetti con spese previste |
| **1.4** | Filtro per categoria e calcolatrice flottante |
| **1.3** | Temi Sobrio e Fiori |
| **1.2** | Nuova icona |
| **1.1** | Animazioni ed effetti |
| **1.0** | Prima versione: conti del mese, grafici, salvadanai, spese fisse, backup |
