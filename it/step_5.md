## Arte ASCII

Stampiamo qualcosa di molto più divertente del testo: ASCII art! Arte ASCII (pronunciato ' *ask-e* ') è creare **Immagini fuori testo**.

+ Aggiungiamo alcune opere d'arte al tuo programma — la foto di un cane!
    
    ![screenshot](images/me-dog.png)

Le gambe del cane sono realizzate utilizzando il carattere pipe `|` che puoi digitare premendo <kbd>Shift + \</kbd> con la maggior parte delle tastiere UK /US.

+ Se clicchi su **Run**, vedrai che c'è un bug nel tuo nuovo codice.
    
    ![screenshot](images/me-dog-bug.png)
    
    That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophe `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)