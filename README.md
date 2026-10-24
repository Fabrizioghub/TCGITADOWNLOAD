# TCGITA — il simulatore italiano del One Piece Card Game

**TCGITA** è un simulatore gratuito del **One Piece Card Game** pensato per il pubblico italiano.
La maggior parte dei simulatori non ha le carte tradotte: qui l'interfaccia è in italiano e **i testi delle carte si leggono in italiano**.
La traduzione è generata automaticamente dal testo ufficiale in inglese, quindi può avere qualche imperfezione;
con un menu puoi sempre passare al testo originale in inglese.

## Cosa puoi fare

- **Giocare contro il bot**, subito, senza aspettare nessuno.
- **Giocare online** con altri giocatori: **Partita veloce** ti abbina al primo avversario in attesa, oppure crei una stanza e dai il codice a un amico.
- **Creare i tuoi mazzi** nell'editor (cerca per codice o nome, importa ed esporta liste come `4xOP01-024`) e scegliere con quale giocare.
- Giocare le regole complete: sasso-carta-forbici per chi comincia, mulligan, DON!!, battaglie con Blocker e Counter, Doppio Attacco, Trigger e gli effetti delle carte.

Non è affiliato né approvato da Bandai. Le immagini e i testi delle carte **non sono dentro il programma**:
al primo avvio l'app li scarica dal sito ufficiale direttamente sul tuo PC. Le immagini sono quelle ufficiali,
quindi hanno la scritta "SAMPLE" in sovrimpressione.

## Come scaricarlo e farlo partire (Windows 10 e 11)

1. Apri la pagina **[Releases](../../releases/latest)** e scarica **`TCGITA-setup.exe`** (l'installer: crea il collegamento sul Desktop).
   Se preferisci non installare, scarica **`TCGITA-portable.zip`**, estrai **tutto** il contenuto in una cartella e avvia `tcgita.exe`
   (non avviarlo da dentro lo zip).
2. Avvia il programma. Windows può mostrare "Windows ha protetto il PC" perché il programma non è firmato:
   premi **Ulteriori informazioni** e poi **Esegui comunque**.
3. **Al primo avvio** vedrai la schermata **Primo avvio** per circa 4 minuti: l'app sta scaricando l'elenco delle carte dal sito ufficiale.
   Succede una sola volta. Poi puoi giocare subito; le immagini arrivano in background (le carte senza immagine si vedono come testo)
   e in alto compare "Immagini N%" finché non sono tutte arrivate.
4. Scegli un nome e sei nella **lobby**. Serve una connessione a internet; i dati si trovano in `%APPDATA%\it.tcgita.app\data`.

## Giocare online

Nella lobby premi **Partita veloce**: l'app ti mette in coda e ti abbina al primo giocatore in attesa (anche lui deve premere **Partita veloce**).

**Se non trova il server.** Per ora il server online ha un indirizzo che può cambiare. L'app prova ad aggiornarlo da sola leggendo il file
[`hub.json`](hub.json) di questa pagina. Se non ci riesce, apri nella lobby il blocco **Server di gioco**, copia da [`hub.json`](hub.json)
l'indirizzo che comincia con `https://` e incollalo nella casella.

**"Dati delle carte non aggiornati".** Se il sito ufficiale ha aggiunto o modificato carte, premi **Aggiorna i dati delle carte** nella lobby e riprova.

## Aggiornare l'app

Scarica di nuovo l'ultima versione da **[Releases](../../releases/latest)** e installala sopra la vecchia: i tuoi dati e le immagini già scaricate restano.
Con lo zip, estrai la nuova versione in una cartella nuova.

## Se qualcosa non funziona

Apri una segnalazione in **[Issues](../../issues)** e allega il file `setup.log` che trovi nella cartella dei dati (`%APPDATA%\it.tcgita.app\data`),
scrivendo anche cosa stavi facendo.
