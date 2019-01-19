## Artă ASCII

Haideți să tipărim ceva mai distractiv decât text: artă ASCII! Arta ASCII (pronunțat '*ask-i*') creează **imagini din text**.

+ Să adăugăm elemente artistice la programul tău - o imagine a unui câine!
    
    ![captură de ecran](images/me-dog.png)

Picioarele câinelui sunt realizate folosind caracterul bară verticală `|` pe care îl puteți tasta apăsând <kbd>Shift + \ </kbd> de pe majoritatea tastaturilor.

+ Dacă dați click pe **Run**, veți vedea că există o eroare în codul vostru.
    
    ![captură de ecran](images/me-dog-bug.png)
    
    Asta pentru că textul vostru conține caracterul `'`, pe care Python îl interpretează ca fiind sfârșitul textului!
    
    ![captură de ecran](images/me-dog-quote.png)

+ Pentru a repara asta, puneți caracterul backslash `` în fața apostrofului, adică coada câinelui. Acest lucru îi spune lui Python că apostroful face parte din text.
    
    ![captură de ecran](images/me-dog-bug-fix.png)

+ Dacă vreți, puteți folosi trei apostrofuri `‘’’` în loc de unul, ceea ce vă permite să tipăriți mai multe linii de text cu o singură comandă `print`:
    
    ![captură de ecran](images/me-dog-triple-quote.png)