## ASCII 藝術

來印出一些比文字更有趣的東西：ASCII 藝術！ ASCII 藝術 (發音為'*ask-e*') 指的是**用文字排出圖案**。

+ 讓我們為你的程式增添一些藝術氣息 — 排出一隻狗的圖案！
    
    ![截圖](images/me-dog.png)

狗的腿是使用字元`|`製作的，您可以在大多數英國/美國英語鍵盤上按<kbd>Shift + \</kbd>打出它。

+ 如果您點擊 **Run**，您會看到新程式中存在一個錯誤。
    
    ![截圖](images/me-dog-bug.png)
    
    那是因為你的文字裡包含一個撇號`'`，Python 將它誤認為是該文字的結尾了！
    
    ![截圖](images/me-dog-quote.png)

+ 要解決這個問題，只需在 `here's` 的撇號之前加上一個反斜杠 `` 。 這會告訴 Python︰撇號是文字的一部分。
    
    ![截圖](images/me-dog-bug-fix.png)

+ 您想要的話，也可以使用三個撇號`'''`而非一個，它將允許您使用一個`print`語句輸出多行文字：
    
    ![截圖](images/me-dog-triple-quote.png)