# Gioco dell'Oca in Pygame

## Descrizione

Questo è una implementazione del classico gioco da tavolo "Gioco dell'Oca" utilizzando la libreria Pygame in Python. Il gioco supporta da 2 a 6 giocatori e include regole speciali per diverse caselle, aggiungendo un elemento di strategia e fortuna.

## Funzionalità

*   **Interfaccia Grafica:**  Utilizza Pygame per un'esperienza visiva interattiva.
*   **Supporto Multi-Giocatore:** Permette a 2-6 giocatori di partecipare.
*   **Regole Speciali:** Implementa regole specifiche per determinate caselle (es. casella 6, 19, 26, 42, 52, 58), influenzando il movimento dei giocatori.
*   **Schermate Interattive:** Include schermata di benvenuto, inserimento giocatori e regole del gioco.
*   **Immagini Personalizzate:** Utilizzo di immagini personalizzate per sfondi e pedine dei giocatori.
*   **Gestione dei Turni:** Gestisce i turni dei giocatori, inclusi i casi in cui un giocatore deve saltare un turno.

## Installazione

1.  **Prerequisiti:** Assicurati di avere Python installato (preferibilmente la versione 3.x).

2.  **Installa Pygame:**

    ```bash
    pip install pygame
    ```

3.  **Clona il Repository (opzionale):** Se hai il codice sorgente in un repository Git, clonalo:

    ```bash
    git clone [URL del tuo repository]
    cd [nome della cartella del tuo progetto]
    ```

4.  **Scarica i File:** Assicurati di avere tutti i file necessari nella stessa directory:

    *   `GiocoOca.py` (o il nome del tuo file principale)
    *   La cartella `font_sfondo/` contenente i font (`Font1.ttf`, `Font4.ttf`, `Font5.ttf` e le immagini di sfondo: `Sfondo1.png`, `Sfondo2.png`, `Sfondo3.png`).
    *   La cartella `players/` contenente le immagini delle pedine (`Sparky.jpeg`, `Ciruzza.jpeg`, `ElPrimitivo.jpeg`, `Eugenio.jpeg`, `Natasha.jpeg`, `Jennifer.jpeg`).

## Come Eseguire il Gioco

1.  **Apri un Terminale o Prompt dei comandi.**
2.  **Naviga alla directory** dove hai salvato il file `GiocoOca.py` e le cartelle `font_sfondo/` e `players/`.
3.  **Esegui il gioco:**

    ```bash
    python GiocoOca.py
    ```

## Istruzioni di Gioco

1.  **Schermata di Benvenuto:** Premi INVIO per iniziare.
2.  **Inserimento Giocatori:** Inserisci il numero di giocatori (2-6) e premi INVIO.
3.  **Schermata delle Regole:** Premi '0' per confermare la lettura delle regole.
4.  **Gioco:**
    *   Premi SPAZIO per lanciare i dadi.
    *   Segui le istruzioni a schermo per il tuo turno.
    *   Il gioco gestirà automaticamente gli effetti delle caselle speciali.
    *   Il primo giocatore a raggiungere (o superare e retrocedere) la casella 63 vince.
5.  **Schermata di Vittoria:**
    *   Premi ESC per uscire dal gioco.
    *   Premi CTRL per ricominciare una nuova partita.

## Controlli

*   **INVIO:** Conferma nelle schermate di benvenuto e inserimento giocatori.
*   **0:** Conferma nella schermata delle regole.
*   **SPAZIO:** Lancia i dadi durante il gioco.
*   **ESC:** Esci dal gioco.
*   **CTRL:** Ricomincia una nuova partita dalla schermata di vittoria.

## Struttura dei File