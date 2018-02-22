## Arte ASCII

Let’s print something much more fun than text: ASCII art! ASCII art (pronounced '*ask-e*') is creating **pictures out of text**.

+ Añadamos un poco de arte a tu programa, ¡la imagen de un perro!
    
    ![screenshot](images/me-dog.png)

Las patas del perro se hacen usando el carácter `|` que se puede escribir tecleando <kbd>Shift + \</kbd> en la mayoría de teclados, o que se encuentra en el superior izquierdo del teclado.

+ Si haz clic en **Run**, verás que hay un error en tu nuevo código.
    
    ![screenshot](images/me-dog-bug.png)
    
    ¡Eso es porque el texto contiene una comilla `'`, que Python cree es el fin del texto!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Si lo prefieres, puedes usar tres comillas `'''` en lugar de uno, permitiéndote imprimir múltiples líneas de texto con un sentencia `print`:
    
    ![screenshot](images/me-dog-triple-quote.png)