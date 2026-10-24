# TCGITA — One Piece Card Game in italiano

### Il simulatore fan made con le carte e gli effetti in italiano

Per quanto ne sappiamo, è il **primo simulatore di One Piece TCG pensato per giocare con gli effetti delle carte in italiano**.
Gratuito, per Windows.

> [!IMPORTANT]
> **Progetto fan made, non ufficiale.** TCGITA non è affiliato, approvato né sponsorizzato da Bandai o da altri titolari dei diritti di One Piece.
> È nato solo perché manca un simulatore ufficiale e serve ai giocatori italiani che vogliono imparare e giocare nella propria lingua.
> **Quando sarà disponibile un simulatore ufficiale, TCGITA verrà ritirato.**

## Scarica e gioca

**[⬇ Scarica l'ultima versione per Windows](../../releases/latest)**: scegli **`TCGITA-setup.exe`**.

1. **Installa** `TCGITA-setup.exe` e avvialo (crea il collegamento sul Desktop). Se Windows mostra *"Windows ha protetto il PC"*,
   premi **Ulteriori informazioni** e poi **Esegui comunque**: succede perché il programma non è firmato.
2. **Attendi il primo avvio (circa 4 minuti, una volta sola).** L'app scarica l'elenco delle carte dal sito ufficiale; non chiuderla.
   Poi puoi giocare subito: le immagini arrivano in background e in alto compare "Immagini N%" finché non sono tutte arrivate.
3. **Scegli un nome** ed entri nella lobby. Premi **Partita veloce** per giocare online oppure **Solo contro il bot** per provare da solo.

Requisiti: Windows 10 o 11 e una connessione a internet. In alternativa all'installer c'è **`TCGITA-portable.zip`**:
estrai **tutto** il contenuto in una cartella e avvia `tcgita.exe` (non avviarlo da dentro lo zip).

## Perché esiste

La maggior parte dei simulatori del gioco è interamente in inglese. Per chi comincia, imparare le regole e leggere gli effetti delle carte
in una lingua che non è la propria è un ostacolo in più. TCGITA offre l'interfaccia e **i testi delle carte in italiano**, per capire
meglio il sistema di gioco. La traduzione degli effetti è generata automaticamente dal testo ufficiale in inglese e può contenere qualche imperfezione:
con il menu **Testo carte** puoi sempre passare all'originale.

## Cosa puoi fare

- **Giocare online** con altri giocatori: **Partita veloce** ti abbina al primo avversario in attesa, oppure crei una stanza e dai il codice a un amico.
- **Giocare contro il bot**, subito e senza aspettare nessuno.
- **Creare i tuoi mazzi** nell'editor: cerca per codice o nome, importa ed esporta liste come `4xOP01-024`.
- **Seguire le regole complete**: sasso-carta-forbici per decidere chi comincia, mulligan, DON!!, battaglie con Blocker e Counter, Doppio Attacco, Trigger ed effetti delle carte.

## Giocare online: se non trova il server

Il server online, per ora, ha un indirizzo che può cambiare. L'app prova ad aggiornarlo da sola leggendo il file [`hub.json`](hub.json) di questa pagina.
Se non ci riesce, nella lobby apri il blocco **Server di gioco**, copia da [`hub.json`](hub.json) l'indirizzo che comincia con `https://` e incollalo nella casella.

Se compare **"Dati delle carte non aggiornati"**, premi **Aggiorna i dati delle carte** nella lobby e riprova.

## Aggiornare l'app

Scarica l'ultima versione da **[Releases](../../releases/latest)** e installala sopra la vecchia: i tuoi dati e le immagini già scaricate restano.
Con lo zip, estrai la nuova versione in una cartella nuova.

## Assistenza

Apri una segnalazione in **[Issues](../../issues)** e allega il file `setup.log` che trovi in `%APPDATA%\it.tcgita.app\data`,
scrivendo cosa stavi facendo.

## Note legali

TCGITA è un progetto gratuito, senza scopo di lucro e non ufficiale. One Piece, One Piece Card Game e i relativi nomi, personaggi, immagini e testi
sono di proprietà dei rispettivi titolari. **Immagini e testi delle carte non fanno parte di TCGITA**: l'app li scarica dal sito ufficiale
direttamente sul tuo PC al primo avvio, e le immagini mostrano la scritta "SAMPLE" in sovrimpressione, come sul sito. TCGITA viene fornito
così com'è, senza garanzie.
