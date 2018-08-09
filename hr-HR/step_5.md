## ASCII umjetnost

Ispišimo nešto zabavnije od teksta: ASCII umjetnost! ASCII umjetnost (izgovara se'*ask-i*') stvara **slike od teksta**.

+ Dodajmo malo umjetnosti tvom programu — sliku psa!
    
    ![screenshot](images/me-dog.png)

Noge psa možeš napraviti koristeći znak `|`. Ispiši ga koristeći tipke <kbd>Shift + \ </kbd>.

+ Ako klikneš na **Run** vidjet ćeš da postoji greška u tvom novom kôdu.
    
    ![screenshot](images/me-dog-bug.png)
    
    To je zato što tvoj tekst sadrži znak navodnika `'` za koji Python misli da označava kraj teksta!
    
    ![screenshot](images/me-dog-quote.png)

+ Da bi ovo popravio, jednostavno dodaj znak `` prije znaka navodnika u riječi `Pogle`. Tako će Python znati da je znak navodnika dio teksta.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ Ako želiš, možeš koristiti i tri znaka navodnika `'''` umjesto jednog pa ćeš moći ispisati više linija teksta sa samo jednom `print` naredbom:
    
    ![screenshot](images/me-dog-triple-quote.png)