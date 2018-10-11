## رسم ASCII

لنطبع شيئًا أكثر متعة من النصوص: رسم ASCII! رسم ASCII (تنطق '*أسكي*') هو رسم يقوم بإنشاء** صور من نصوص**.

+ دعونا نضيف بعض الرسوم إلى البرنامج - مثل صورة كلب!
    
    ![لقطة الشاشة](images/me-dog.png)

يمكن صنع أقدام الكلب باستخدام الحرف`|`الذي يمكنك كتابته بالضغط على <kbd>Shift + \ </kbd>على معظم لوحات المفاتيح الإنجليزية UK/US.

+ إذا نقرت فوق **Run**، فسترى أن هناك خطأ في تعليمتك البرمجية الجديدة.
    
    ![لقطة الشاشة](images/me-dog-bug.png)
    
    هذا لأن النص يحتوي على علامة فاصلة عليا`'`، يعتقد Python أنها نهاية النص!
    
    ![لقطة الشاشة](images/me-dog-quote.png)

+ لإصلاح هذا الأمر، ضع فقط شرطة مائلة للخلف `` قبل علامة الفاصلة العليا في كلمة `here's`. فهذا يخبر Python أن علامة الفاصلة العليا هي جزء من النص.
    
    ![لقطة الشاشة](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![لقطة الشاشة](images/me-dog-triple-quote.png)