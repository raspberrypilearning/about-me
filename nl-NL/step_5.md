## ASCII-kunst

Laten we iets leukers printen dan alleen tekst: ASCII-kunst! ASCII-kunst (uitgesproken als '* ask-ie * ') is het maken van ** afbeeldingen van tekst **.

+ Voeg wat kunst toe aan je programma - een afbeelding van een hond!
    
    ![screenshot](images/me-dog.png)

De poten van de hond zijn gemaakt met behulp van het sluisteken ` | ` (Engels: pipe) die je kunt typen door op <kbd> Shift + \</kbd> te drukken.

+ Als je op ** Run **klikt zul je zien dat er een fout in je nieuwe code zit.
    
    ![screenshot](images/me-dog-bug.png)
    
    Dat komt omdat er in de tekst een apostrof ` ' ` zit, waardoor Python denkt dat dit het einde van de tekst is!
    
    ![screenshot](images/me-dog-quote.png)

+ Om dit te herstellen zet je een schuine streep ` \ ` voor de apostrof die voor de letter ` t ` staat. Dit vertelt Python dat de apostrof deel uitmaakt van de tekst.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Als je wilt, kunt je drie apostrofs gebruiken ` ''' ` in plaats van één, waardoor je meerdere regels tekst kunt tonen met één ` print ` instructie:
    
    ![screenshot](images/me-dog-triple-quote.png)