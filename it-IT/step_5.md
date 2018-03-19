## Disegni ASCII

Let’s print something much more fun than text: ASCII art! ASCII art (pronounced '*ask-e*') is creating **pictures out of text**.

+ Aggiungiamo un bel disegno al tuo programma: aggiungiamo l'immagine di un cane!
    
    ![screenshot](images/me-dog.png)

Per realizzare le zampe del cane, utilizza la barra verticale `|`, che puoi digitare premendo <kbd>Shift + \ </kbd> (questo tasto si trova in alto a sinistra sulla tua tastiera).

+ Se fai click su **Run**, vedrai che c'è un problema con il tuo nuovo codice.
    
    ![screenshot](images/me-dog-bug.png)
    
    Questo perché il tuo codice contiene un apostrofo `'`, e Python pensa che si tratti della fine del testo!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Se preferisci, puoi usare tre apostrofi `'''` invece di uno. Questo ti permetterà di stampare più righe di testo utilizzando il comando `print` una volta sola:
    
    ![screenshot](images/me-dog-triple-quote.png)