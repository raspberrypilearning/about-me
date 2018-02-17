## Arte ASCII

Imprimamos algo más divertido que simple texto, ¡arte ASCII! El arte ASCII (pronunciado '*ask-i*') crea **imágenes a partir de texto**.

+ Añadamos un poco de arte a tu programa, ¡la imagen de un perro!
    
    ![screenshot](images/me-dog.png)

Las patas del perro se hacen usando el carácter `|` que se puede escribir tecleando <kbd>Shift + \</kbd> en la mayoría de teclados, o que se encuentra en el superior izquierdo del teclado.

+ Si haz clic en **Run**, verás que hay un error en tu nuevo código.
    
    ![screenshot](images/me-dog-bug.png)
    
    ¡Eso es porque el texto contiene una comilla `'`, que Python cree es el fin del texto!
    
    ![screenshot](images/me-dog-quote.png)

+ Para solucionarlo, simplemente coloca una barra inversa `` antes de la comilla que forme la cola del perro `'`.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Si lo prefieres, puedes usar tres comillas `'''` en lugar de uno, permitiéndote imprimir múltiples líneas de texto con un sentencia `print`:
    
    ![screenshot](images/me-dog-triple-quote.png)