## Τέχνη ASCII

Ας εκτυπώσουμε κάτι πολύ πιο διασκεδαστικό από το κείμενο: Τέχνη ASCII! Η τέχνη ASCII (προφέρεται '*άσκι*') δημιουργεί **εικόνες από κείμενο**.

+ Ας προσθέσουμε τέχνη στο πρόγραμμά σου - μια εικόνα ενός σκύλου!
    
    ![screenshot](images/me-dog.png)

The dog's legs are made using the pipe character `|` which you can type by pressing <kbd>Shift + \ </kbd> on most UK/US English keyboards.

+ Αν κάνετε κλικ στο **Run**, θα δείτε ότι υπάρχει ένα σφάλμα στο νέο σας κώδικα.
    
    ![screenshot](images/me-dog-bug.png)
    
    That's because your text contains an apostrophe `'`, which Python thinks is the end of the text!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)