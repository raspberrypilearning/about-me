## ASCII art

Let’s print something much more fun than text: ASCII art! ASCII art (pronounced '*ask-e*') is creating **pictures out of text**.

+ Let's add some art to your program — a picture of a dog!
    
    ![captura de pantalla](images/me-dog.png)

Les potes del gos s'han fet utilitzant el caràcter de tub `|` el qual pots reproduir prement les tecles <kbd>alt + 1</kbd>.

+ Si cliques **Run**, veuràs que hi ha un error en el teu nou codi.
    
    ![captura de pantalla](images/me-dog-bug.png)
    
    Això és perquè el teu text conté un apòstrof `'`, i Python pensa que és el final del text!
    
    ![captura de pantalla](images/me-dog-quote.png)

+ Per solucionar això, només has d'afegir una barra obliqua inversa `` abans de l'apòstrof que forma la cua del gos `'`. Això li diu a Python que l'apòstrof forma part del text.
    
    ![captura de pantalla](images/me-dog-bug-fix.png)

+ Si ho prefereixes, pots utilitzar tres apòstrofs `'''` en lloc d'un, el qual et permetrà imprimir múltiples línies de text amb l'ordre `print`:
    
    ![captura de pantalla](images/me-dog-triple-quote.png)