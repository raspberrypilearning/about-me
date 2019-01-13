## Artă ASCII

Haideți să tipărim ceva mai distractiv decât text: artă ASCII! ASCII art (pronounced '*ask-e*') is creating **pictures out of text**.

+ Să adăugăm elemente artistice la programul tău - o imagine a unui câine!
    
    ![screenshot](images/me-dog.png)

The dog's legs are made using the pipe character `|` which you can type by pressing <kbd>Shift + \ </kbd> on most UK/US English keyboards.

+ Dacă dați click pe **Run**, veți vedea că există o eroare în codul vostru.
    
    ![screenshot](images/me-dog-bug.png)
    
    That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)