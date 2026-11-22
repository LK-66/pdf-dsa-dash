# PDF DSA Dash

App web per allievi con DSA: apri un PDF o una foto, evidenzia e annota, leggi il testo con l'OCR, ascoltalo e correggilo.

**Apri l'app:**
- Versione 1 (stabile): https://lk-66.github.io/pdf-dsa-dash/
- Versione 2: https://lk-66.github.io/pdf-dsa-dash/v2/
- Versione 3 · PDF DSA iPad: https://lk-66.github.io/pdf-dsa-dash/ipad/

## Funzioni
- Viewer PDF con zoom, evidenziatore (4 colori), sottolineatura, penna, evidenziatore a mano libera e note
- OCR gratuito nel browser (Tesseract): per pagina, per area o con la fotocamera; pulizia automatica dell'immagine e parole incerte segnate in arancione
- Editor DSA (Lexend / OpenDyslexic, spaziature, temi) con lettura ad alta voce dal cursore ed evidenziazione della parola
- Modalità Lettura a tutto schermo (ideale con il Controller lettura dell'iPad)
- Correzione dell'OCR con Copilot o Claude (copia/incolla)
- Esportazione: PDF annotato, PNG, Word, PDF del testo, file delle annotazioni

## Uso su iPad / iPhone
Apri il link in **Safari** → Condividi → **Aggiungi alla schermata Home**.
I testi e le foto restano sul dispositivo: nulla viene caricato su server.

## Novità della versione 2
- Scanner a tutto schermo: scatto, ritaglio con gli angoli, rotazione
- Dopo lo scatto le righe riconosciute sono evidenziate: tocca o trascina per scegliere quali inserire
- OCR in italiano, francese, tedesco, inglese o misto
- Voci del browser per IT · FR · DE · EN con riconoscimento automatico della lingua frase per frase
- Modalità Lettura con Play / Pausa / Stop, velocità, lingua e tocco sulla parola per partire da lì
- OCR più preciso: foto a piena risoluzione con la fotocamera del dispositivo, lettura in scala di grigi con secondo tentativo automatico in bianco/nero per fotocopie e ombre, titoli separati dai paragrafi
- Su iPad e iPhone: «Testo da Apple (Fotocamera)»: copi il testo con Testo attivo dell'app Fotocamera e lo incolli con un tasto
- «Scatta e riconosci con Apple»: avvia il Comando rapido «Testo DSA» (Scatta foto → Estrai testo dall'immagine → Copia negli appunti) e al ritorno incolla il testo
- Il testo dell'editor viene salvato automaticamente nel browser

## PDF DSA iPad (versione 3)
- Si lavora nell'editor a tutto schermo; il PDF si apre a tutto schermo con «PDF» e si torna con «‹ Editor»
- «Scansiona testo»: su iPad avvia il Comando rapido «Testo DSA» (riconoscimento di Apple); si torna con «‹ Safari» nella stessa scheda e si incolla con il banner «Incolla nell'editor»
- «Importa testo nell'editor» dal PDF aggiunge il testo senza cancellare quello già scritto
- Menu ▾: incolla testo copiato, OCR dell'app con scelta delle righe, istruzioni del comando
- Quaderni: testi salvati per materia (Materia › Titolo) solo con «Salva»; ricaricando la pagina l'editor riparte vuoto; ricerca, backup in un file
- Scrivi a mano: area a righe per scrivere con l'Apple Pencil (Scribble) e inserire al cursore
- Semplifica: prepara per Copilot o Claude la richiesta di semplificare il testo per un allievo DSA (Facile / Molto facile); la risposta viene aggiunta sotto con titoletti, grassetti ed elenchi
- Lettore PDF più robusto (motore caricato dal CDN, con riserva dove i worker sono bloccati)
