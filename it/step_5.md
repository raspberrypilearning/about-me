## Arte ASCII

Stampiamo qualcosa di molto più divertente del testo: ASCII art! Arte ASCII (pronunciato ' *ask-e* ') è creare **Immagini fuori testo**.

+ Aggiungiamo alcune opere d'arte al tuo programma — la foto di un cane!
    
    ![screenshot](images/me-dog.png)

Le gambe del cane sono realizzate utilizzando il carattere pipe `|` che puoi digitare premendo <kbd>Shift + \</kbd> con la maggior parte delle tastiere UK /US.

+ Se clicchi su **Run**, vedrai che c'è un bug nel tuo nuovo codice.
    
    ![screenshot](images/me-dog-bug.png)
    
    Questo è perchè il tuo testo contiene un'apostrofe `'`, il quale Python crede che sia la fine del testo!
    
    ![screenshot](images/me-dog-quote.png)

+ Per aggiustarlo, metti `` prima dell'apostrofo nella parola `here's`. Questo dice a Python che l'apostrofo è parte del testo.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Se preferisci, puoi usare tre apostrofi `'''` invece di una, il quale ti permette di stampare piú linee di testo con un estratto `print`:
    
    ![screenshot](images/me-dog-triple-quote.png)