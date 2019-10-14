## ASCII art

Let’s print something much more fun than text: ASCII art! ASCII art (pronounced '*ask-e*') is creating **pictures out of text**.

+ Let's add some art to your program — a picture of a dog!
    
    ![skjermbilde](images/me-dog.png)

The dog's legs are made using the pipe character `|` which you can type by pressing <kbd>Shift + \ </kbd> on most UK/US English keyboards.

+ If you click **Run**, you'll see that there's a bug in your new code.
    
    ![skjermbilde](images/me-dog-bug.png)
    
    That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!
    
    ![skjermbilde](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![skjermbilde](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![skjermbilde](images/me-dog-triple-quote.png)