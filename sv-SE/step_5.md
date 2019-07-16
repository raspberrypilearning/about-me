## ASCII -konst

Låt oss skriva ut något mycket roligare än text: ASCII -konst! ASCII -konst (uttalad "*ask-ii*") skapar **bilder ur text**.

+ Låt oss lägga till lite konst i ditt program - en bild av en hund!
    
    ![skärmdump](images/me-dog.png)

Hundens ben är gjorda med streckkaraktären `|` som du kan skriva genom att trycka på <kbd>Shift + \ </kbd> på de flesta brittiska/amerikanska tangentbord.

+ Om du klickar på **Kör**, ser du att det finns ett fel i din nya kod.
    
    ![skärmdump](images/me-dog-bug.png)
    
    Det beror på att texten innehåller en apostrof `'`, som Python tycker är slutet på texten!
    
    ![skärmdump](images/me-dog-quote.png)

+ Lös problemet genom att bara sätta ett omvänt snedstreck `` innan apostrofen i ordet `här är`. Detta berättar Python att apostrof är en del av texten.
    
    ![skärmdump](images/me-dog-bug-fix.png)

+ Om du föredrar kan du använda tre apostrofer ` '' '` istället för en, som låter dig skriva ut flera rader med text med ett ` utskrift ` uttryck:
    
    ![skärmdump](images/me-dog-triple-quote.png)