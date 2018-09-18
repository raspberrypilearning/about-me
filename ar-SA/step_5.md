## رسم ASCII

لنطبع شيئًا أكثر متعة من النصوص: رسم ASCII! رسم ASCII (تنطق '*أسكي*') هو رسم يقوم بإنشاء** صور من نصوص**.

+ دعونا نضيف بعض الرسوم إلى البرنامج - مثل صورة كلب!
    
    ![screenshot](images/me-dog.png)

يمكن صنع أقدام الكلب باستخدام الحرف` | `الذي يمكنك كتابته بالضغط على <kbd>Shift + \ </kbd>على معظم لوحات المفاتيح الإنجليزية UK/US.

+ إذا نقرت على ‘run’، فسترى أن هناك خطأ في التعليمات البرمجية الجديدة.
    
    ![screenshot](images/me-dog-bug.png)
    
    هذا لأن النص يحتوي على علامة اقتباس، يعتقد Python أنها تعني نهاية النص!
    
    ![screenshot](images/me-dog-quote.png)

+ To fix this, just put a backslash `` before the apostrophe in the word `here's`. This tells Python that the apostrophe is part of the text.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ يمكنك استخدام 3 علامات اقتباس ''' بدلًا من استخدام علامة اقتباس واحدة، إذا كنت تفضل ذلك، لطباعة أسطر متعددة من النص بعبارة print واحدة:
    
    ![screenshot](images/me-dog-triple-quote.png)