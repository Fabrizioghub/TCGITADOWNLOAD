# TCGITA — download

Simulatore gratuito del One Piece Card Game, da giocare sul tuo PC e online con gli altri giocatori.

> Non è affiliato né approvato da Bandai. Le immagini e i testi delle carte **non sono in questo programma**:
> al primo avvio l'app li scarica dal sito ufficiale direttamente sul tuo PC.

## Come si scarica e si installa

1. Vai alla pagina **[Releases](../../releases/latest)** e scarica **`TCGITA-setup.exe`**.
   Se preferisci non installare, scarica **`TCGITA-portable.zip`**: estrai tutto in una cartella e avvia `tcgita.exe`.
2. Avvia il programma. Windows può mostrare l'avviso "Windows ha protetto il PC" perché il programma non è firmato:
   premi **Ulteriori informazioni** e poi **Esegui comunque**.
3. **Al primo avvio** vedrai la schermata "Primo avvio" per circa 4 minuti: sta scaricando l'elenco delle carte dal sito
   ufficiale. Succede una volta sola. Poi le immagini arrivano in background mentre giochi (le carte senza immagine si
   vedono come testo).
4. Scegli un nome e sei nella lobby.

Serve Windows 10 o 11 e una connessione a internet. I dati stanno nella cartella `%APPDATA%\it.tcgita.app\data`.

## Giocare online

Nella lobby premi **Partita veloce**: l'app ti mette in coda e ti abbina al primo giocatore in attesa. Anche l'altro
giocatore deve premere **Partita veloce**.

### Se "Partita veloce" non trova il server

Il server online, per ora, ha un indirizzo che può cambiare. Il programma prova ad aggiornarlo da solo leggendo il file
[`hub.json`](hub.json) di questa pagina. Se non ci riesce, nella lobby compare un avviso con una casella: copia da
[`hub.json`](hub.json) l'indirizzo che comincia con `https://` e incollalo lì.

### "Dati delle carte non aggiornati"

Se il sito ufficiale ha aggiunto o modificato carte, premi **Aggiorna i dati delle carte** nella lobby e riprova.

## Se qualcosa non funziona

Apri una segnalazione in **Issues** e allega il file `setup.log` che trovi nella cartella dei dati
(`%APPDATA%\it.tcgita.app\data`).
