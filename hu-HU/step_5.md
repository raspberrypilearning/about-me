## ASCII művészet

Írjunk ki valami sokkal szórakoztatóbbat, mint a szöveg: ez az ASCII művészet! ASCII művészet (ejtsd '*eszki*') **képet alkot a szövegből**.

+ Adjunk hozzá egy kis rajzot a programodhoz - egy kutya képét!
    
    ![képernyőkép](images/me-dog.png)

A kutya lábát a `|` cső karakterrel készítjük, amelyet a <kbd>Shift + \ </kbd> gombok megnyomásával írhatunk be a legtöbb UK/US angol billentyűzeten vagy a <1>AltGr + w </1> gombok megnyomásával a magyar billentyűzeten.

+ Ha a **Run** parancsra kattintasz, látni fogod, hogy van egy hiba az új kódodban.
    
    ![képernyőkép](images/me-dog-bug.png)
    
    Ez azért van, mert a szöveg egy plusz `'` aposztrófot tartalmaz, melyről a Python azt hiszi, hogy a szöveg vége!
    
    ![képernyőkép](images/me-dog-quote.png)

+ Ezt úgy tudod kijavítani, hogy beszúrsz egy fordított per jelet `` (backslash) a Pythont megtévesztő aposztóf elé. Ez megmondja a Pythonnak, hogy az aposztróf a szöveg része.
    
    ![képernyőkép](images/me-dog-bug-fix.png)

+ Ha jobban tetszik, használhatsz három aposztrófot `'''` egy helyett, amely lehetővé teszi több szövegsor megjelenítését egyetlen `print` utasítással:
    
    ![képernyőkép](images/me-dog-triple-quote.png)