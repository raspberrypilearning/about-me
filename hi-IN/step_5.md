## ASCII कला

चलो पाठ की तुलना में कुछ अधिक मजेदार प्रिंट करें: ASCII कला! ASCII कला (उच्चारण '*Ask-e*') पाठ से **चित्र बना रहा है** ।

+ चलो अपने कार्यक्रम में कुछ कला जोड़ते हैं - एक कुत्ते की तस्वीर!
    
    ![स्क्रीनशॉट](images/me-dog.png)

कुत्ते के पैर पाइप चरित्र `|` जिसे आप <kbd>Shift + \</kbd> दबाकर टाइप कर सकते हैं अधिकांश यूके / यूएस अंग्रेजी कीबोर्ड पर।

+ यदि आप **रन** क्लिक करते हैं, आप देखेंगे कि आपके नए कोड में एक बग है।
    
    ![स्क्रीनशॉट](images/me-dog-bug.png)
    
    ऐसा इसलिए है क्योंकि आपके पाठ में एपोस्ट्रोफी है `'`, जो पायथन को लगता है कि पाठ का अंत है!
    
    ![स्क्रीनशॉट](images/me-dog-quote.png)

+ इसे ठीक करने के लिए, बस एक बैकस्लैश डालें `\` शब्द में अपोस्ट्रोफ से पहले `here's` । यह पायथन को बताता है कि एपोस्ट्रोफी पाठ का हिस्सा है।
    
    ![स्क्रीनशॉट](images/me-dog-bug-fix.png)

+ यदि आप चाहें, तो आप तीन एपोस्ट्रोफ `'''` का उपयोग कर सकते हैं एक के बजाय, जो आपको एक `print` के साथ पाठ की कई पंक्तियों को प्रिंट करने की अनुमति देता है:
    
    ![स्क्रीनशॉट](images/me-dog-triple-quote.png)