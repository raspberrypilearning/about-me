## ASCII művészet

Írjunk ki valami sokkal szórakoztatóbb szöveget, mint a szöveg: ASCII art! ASCII art ("*eszkii-art*") **képet alkot a szövegből**.

+ Adjunk hozzá egy kis művészetet a programhoz - egy kutya képét!
    
    ![képernyőkép](images/me-dog.png)

A kutya lába a `| cső karakterrel készül` amely beírhatja megnyomásával <kbd>Shift + \ </kbd> A legtöbb brit / amerikai angol billentyűzetet.

+ Ha a ****futtatásra kattint, látni fogja, hogy van egy hiba az új kódban.
    
    ![képernyőkép](images/me-dog-bug.png)
    
    Ez azért van, mert a szöveged `'` aposztrófot tartalmaz, melyről a Python azt hiszi, hogy a szöveg vége!
    
    ![képernyőkép](images/me-dog-quote.png)

+ Ezt kijavítani, csak egy `3_1_321 visszafordulót állítson be, mielőtt az apostropé a <code>itt`. Ez megmondja a Pythonnak, hogy az aposztróf a szöveg része.
    
    ![képernyőkép](images/me-dog-bug-fix.png)

+ Ha úgy tetszik, használhatsz három `' ' '` aposztrófot, az egy helyett, amely lehetővé teszi több szövegsor nyomtatását egy `print` utasítással:
    
    ![képernyőkép](images/me-dog-triple-quote.png)