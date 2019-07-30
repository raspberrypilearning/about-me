## Art ASCII

Affichons quelque chose de bien plus amusant que du texte : l’art ASCII ! L'art ASCII (prononcé '*a-ski*') crée **des images à partir de texte**.

+ Ajoutons un peu d'art à ton programme — une illustration d'un chien !
    
    ![capture d'écran](images/me-dog.png)

Les jambes du chien sont faites à partir du caractère barre verticale `|` que tu peux saisir en appuyant sur <kbd>Alt Gr + 6</kbd> sur ton clavier français.

+ Si tu cliques sur **Run**, tu verras qu'il y a une erreur dans ton nouveau code.
    
    ![capture d'écran](images/me-dog-bug.png)
    
    C'est parce que ton texte contient une apostrophe `'` et Python pense que c'est la fin du texte !
    
    ![capture d'écran](images/me-dog-quote.png)

+ Pour corriger cela, il suffit de mettre une barre oblique inverse `` avant l'apostrophe dans le mot `s'appelle`. Cela indique à Python que l'apostrophe fait partie du texte.
    
    ![capture d'écran](images/me-dog-bug-fix.png)

+ Si tu préfères, tu peux utiliser trois guillemets `"""` au lieu d'un apostrophe, ce qui te permet d'imprimer plusieurs lignes de texte avec une seule commande `print` :
    
    ![capture d'écran](images/me-dog-triple-quote.png)