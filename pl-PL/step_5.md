## ASCII art

Wyświetlmy coś znacznie fajniejszego niż tekst: ASCII art! ASCII art (wymawiane jak "*aski*") to tworzenie **obrazów za pomocą tekstu**.

+ Dodajmy do programu trochę sztuki - obrazek psa!
    
    ![screenshot](images/me-dog.png)

Nogi psa są wykonane przy użyciu tzw. znaku potoku `|`, który możesz wpisać naciskając <kbd>Shift + \</kbd> na większości polskich klawiatur.

+ Kiedy klikniesz przycisk **Run** zobaczysz, że w twoim nowym kodzie jest błąd.
    
    ![screenshot](images/me-dog-bug.png)
    
    To dlatego, że twój tekst zawiera apostrof `'`, więc Python myśli, że to koniec tekstu!
    
    ![screenshot](images/me-dog-quote.png)

+ Aby to naprawić, umieść lewy ukośnik `` przed apostrofem, czyli ogonem psa. Dzięki temu Python wie, że ten apostrof to część tekstu.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)