## Arte ASCII

Vamos a imprimir algo mucho más divertido que el texto: ¡arte ASCII! Arte ASCII (pronunciado '*ask-i* ') es la creación de **imágenes a partir de texto**.

+ Añadamos un poco de arte a tu programa, ¡la imagen de un perro!
    
    ![screenshot](images/me-dog.png)

Las patas del perro se hacen usando el carácter `|` que se puede escribir tecleando <kbd>mayúsculas+\</kbd> en la mayoría de teclados, o que se encuentra en la esquina superior izquierda del teclado.

+ Si haces clic en **Run**, verás que hay un error en tu nuevo código.
    
    ![screenshot](images/me-dog-bug.png)
    
    ¡Eso es porque el texto contiene una comilla `'`, que Python cree que es el final del texto!
    
    ![screenshot](images/me-dog-quote.png)

+ Para solucionar esto, simplemente coloca una barra invertida `\` antes de la comilla que forma la cola del perro `'`. Esto le dice a Python que la comilla es parte del texto.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)