## ASCII kunst

Lad os udskrive noget meget mere sjovt end tekst: ASCII kunst! ASCII kunst (udtalt '* ask-e * ') skaber ** billeder uden for tekst **.

+ Lad os tilføje noget kunst til dit program - et billede af en hund!
    
    ![screenshot](images/me-dog.png)

Hundens ben laves ved hjælp af rørkarakteren ` | ` som du kan skrive ved at trykke på <kbd> Shift + \ </kbd> på de fleste britiske / amerikanske engelske tastaturer.

+ Hvis du klikker på ** Kør **, vil du se, at der er en fejl i din nye kode.
    
    ![screenshot](images/me-dog-bug.png)
    
    Det skyldes, at din tekst indeholder et apostrof ` ' ` , som Python mener er slutningen af ​​teksten!
    
    ![screenshot](images/me-dog-quote.png)

+ For at rette op på dette skal du blot sætte en tilbageslag ` \ ` før apostrof i ordet ` here´s `. Dette fortæller Python, at apostrof er en del af teksten.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Hvis du foretrækker det, kan du bruge tre apostrof ` ''' ` i stedet for en, som giver dig mulighed for at udskrive flere tekstlinjer med en ` print ` udmelding:
    
    ![screenshots](images/me-dog-triple-quote.png)