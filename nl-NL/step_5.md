## ASCII-kunst

Laten we iets leukers printen dan alleen tekst: ASCII-kunst! ASCII-kunst (uitgesproken als '* ask-ie * ') is het maken van ** afbeeldingen van tekst **.

+ Voeg wat kunst toe aan je programma - een afbeelding van een hond!
    
    ![screenshot](images/me-dog.png)

De poten van de hond zijn gemaakt met behulp van het sluisteken ` | ` (Engels: pipe) die je kunt typen door op <kbd> Shift + \ te drukken </kbd> op de meeste UK/US toetsenborden.

+ Als je op ** Run **klikt zul je zien dat er een fout in je nieuwe code zit.
    
    ![screenshot](images/me-dog-bug.png)
    
    Dat komt omdat er in de tekst een apostrof ` ' ` zit, waardoor Python denkt dat dit het einde van de tekst is!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophe `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)