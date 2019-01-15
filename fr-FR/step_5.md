## Art ASCII

Let’s print something much more fun than text: ASCII art! L'Art ASCII (prononcé '* ask-i * ') crée ** des images à partir de texte ** .

+ Ajoutons un peu d'art à ton programme - une photo d'un chien!
    
    ![screenshot](images/me-dog.png)

Les jambes du chien sont fabriqués à partir du caractère barre verticale `|` que tu peux saisir en appuyant sur <kbd>Shift + \</kbd> sur la plupart des claviers anglais ou américains.

+ Si tu cliques sur ** Exécuter ** , tu verras qu'il y a un bug dans ton nouveau code.
    
    ![screenshot](images/me-dog-bug.png)
    
    C'est parce que ton texte contient une apostrophe ` ' ` que Python pense que c'est la fin du texte!
    
    ![screenshot](images/me-dog-quote.png)

+ Pour corriger cela, il suffit de mettre une barre oblique inverse ` \ ` avant l'apostrophe dans le mot ` ici ` . Cela indique à Python que l'apostrophe fait partie du texte.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)