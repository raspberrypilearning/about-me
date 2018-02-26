## Arte ASCII

Vamos a imprimir algo mucho más divertido que el texto: ¡arte ASCII! Arte ASCII (pronunciado '*ask-i* ') es la creación de **imágenes a partir de texto**.

+ Añadamos un poco de arte a tu programa, ¡la imagen de un perro!
    
    ![screenshot](images/me-dog.png)

Las patas del perro se hacen usando el carácter `|` que se puede escribir tecleando <kbd>mayúsculas+\</kbd> en la mayoría de teclados, o que se encuentra en el superior izquierdo del teclado.

+ Si haz clic en **Run**, verás que hay un error en tu nuevo código.
    
    ![screenshot](images/me-dog-bug.png)
    
    ¡Eso es porque el texto contiene una comilla `'`, que Python cree es el fin del texto!
    
    ![screenshot](images/me-dog-quote.png)

+ Para solucionar esto, simplemente coloque una barra invertida `` antes de la comilla que forma la cola del perro `'`. Esto le dice a Python que la comilla es parte del texto.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Si lo prefieres, puedes usar tres comillas `'''` en lugar de uno, permitiéndote imprimir múltiples líneas de texto con un sentencia `print`:
    
    ![screenshot](images/me-dog-triple-quote.png)