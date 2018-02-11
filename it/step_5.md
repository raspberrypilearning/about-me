## I simboli ASCII

Stampiamo qualcosa di molto più divertente di un semplice testo: i simboli ASCII! I simboli ASCII (pronuncia: '*ask-i*') permettono di creare delle **immagini a partire da un testo**.

+ Aggiungiamo un po' di arte al tuo programma: un'immagine di un cane!
    
    ![screenshot](images/me-dog.png)

The dog's legs are made using the pipe character `|` which you can type by pressing <kbd>Shift + \ </kbd> on most UK/US English keyboards.

+ If you click **Run**, you'll see that there's a bug in your new code.
    
    ![screenshot](images/me-dog-bug.png)
    
    That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophe `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)