## ASCII művészet

Írjunk ki valami sokkal szórakoztatóbbat, mint a szöveg: ez az ASCII művészet! ASCII művészet (ejtsd '*eszki*') **képet alkot a szövegből**.

+ Adjunk hozzá egy kis rajzot a programodhoz - egy kutya képét!
    
    ![képernyőkép](images/me-dog.png)

A kutya lábát a `|` cső karakterrel készítjük, amelyet az <kbd>AltGr + w </kbd> gombok megnyomásával írhatunk be a magyar billentyűzeten.

+ Ha a **Run** parancsra kattintasz, látni fogod, hogy van egy hiba az új kódodban.
    
    ![képernyőkép](images/me-dog-bug.png)
    
    Ez azért van, mert a szöveged aposztrófot `'` tartalmaz, melyről a Python azt hiszi, hogy a szöveg vége!
    
    ![képernyőkép](images/me-dog-quote.png)

+ Ezt úgy tudod kijavítani, hogy beszúrsz egy fordított per jelet `` (backslash) a Pythont megtévesztő aposztóf elé. Ez megmondja a Pythonnak, hogy az aposztróf a szöveg része.
    
    ![képernyőkép](images/me-dog-bug-fix.png)

+ Ha jobban tetszik, használhatsz három aposztrófot `'''` egy helyett, amely lehetővé teszi több szövegsor megjelenítését egyetlen `print` utasítással:
    
    ![képernyőkép](images/me-dog-triple-quote.png)