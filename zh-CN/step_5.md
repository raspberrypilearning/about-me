## ASCII字符画

让我们输出一些比文本更有趣的东西：ASCII字符画。 ASCII字符画（发音为*ask-e*）是一种通过**文本创作的文字图像**。

+ 现在让我们在已编写的程序里加张文字图像——一只狗！
    
    ![截图](images/me-dog.png)

这只狗的腿用字符`|`代替，要输入该字符，按<kbd>Shift + \ </kbd>键即可。

+ 如果单击**Run**，屏幕上会显示代码里存在一个错误。
    
    ![截图](images/me-dog-bug.png)
    
    因为你的文本里包含一个单引号`'`，使Python认为文本到此就结束了！
    
    ![截图](images/me-dog-quote.png)

+ 要解决这个问题，只需要在`here's`一词中的单引号前加上``即可。 反斜线告诉Python单引号是文本内容的一部分。
    
    ![截图](images/me-dog-bug-fix.png)

+ 如果你愿意，你也可以使用一对连续三个单引号`'''`，这可以在一个`print`语句中输出多行文字。
    
    ![截图](images/me-dog-triple-quote.png)