## ASCII-taide

Tulostetaan jotain paljon hauskempaa kuin pelkkä teksti: ASCII -taidetta! ASCII-taide (lausutaan "*ask-ii*") luo **kuvaa tekstistä**.

+ Lisätään hieman taidetta ohjelmaan - koiran kuva!
    
    ![ruutukaappaus](images/me-dog.png)

Koiran jalat on tehty putkimerkillä ` | ` jonka voit kirjoittaa painamalla <kbd>Vaihto + \</kbd> useimmissa UK/US -englanninkielisissä näppäimistöissä.

+ Jos napsautat **Suorita**, näet, että uudessa koodissasi on vika.
    
    ![ruutukaappaus](images/me-dog-bug.png)
    
    Tämä johtuu siitä, että tekstisi sisältää heittomerkin `'`, jota Python pitää tekstin loppuna!
    
    ![ruutukaappaus](images/me-dog-quote.png)

+ Voit korjata tämän helposti laittamalla kenoviivan `` ennen heittomerkkiä sanassa `here's`. Tämä kertoo Pythonille, että heittomerkki on osa tekstiä.
    
    ![ruutukaappaus](images/me-dog-bug-fix.png)

+ Jos haluat, voit käyttää kolmea heittomerkkiä `'''` yhden sijaan, jolloin voit tulostaa useita tekstirivejä yhdellä `print` lausekkeella:
    
    ![ruutukaappaus](images/me-dog-triple-quote.png)