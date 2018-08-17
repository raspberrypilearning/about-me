## АSCII уметност

Хајде на испишемо нешто много занимљивије од текста: ASCII уметност! ASCII уметност (чита се '*аски*') представља креирање **слика само од текста**.

+ Хајде да додамо мало уметности у програм - слику пса!
    
    ![screenshot](images/me-dog.png)

Ноге пса можеш направити користећи усправну црту`|` коју такође можеш добити притискањем <kbd>Shift + \</kbd> на већини енглеских тастатура.

+ Ако притиснеш **Run**, видећеш да постоји грешка у твом коду.
    
    ![screenshot](images/me-dog-bug.png)
    
    То је зато што текст садржи наводник `'`, због којег Python мисли да је дошао до краја текста!
    
    ![screenshot](images/me-dog-quote.png)

+ Како би ово исправио стави косу црту `` пре апострофа у речи `Pogle'`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophe `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)