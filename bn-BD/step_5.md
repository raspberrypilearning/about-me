## ASCII art

আসুন টেক্সট এর থেকেও আরও মজাদার কিছু প্রিন্ট করা যাক: ASCII আর্ট! ASCII art (উচ্চারণ '* অ্যাস-কি* ') টেক্সট থেকে </strong> ছবি তৈরি করছে </1> 

+ আসুন আপনার প্রোগ্রামে কিছু আর্ট যুক্ত করা যাক - একটি কুকুরের ছবি!
    
    ![screenshot](images/me-dog.png)

pipe character ` ব্যবহার করে কুকুরের পা তৈরি করা হয়েছে। ` যা আপনি <kbd> শিফট + \ টিপে টাইপ করতে পারেন </kbd> বেশিরভাগ ইউকে / মার্কিন ইংরেজী কীবোর্ডে।

+ আপনি যদি ক্লিক করেন ** রান ** , আপনি দেখতে পাবেন যে আপনার নতুন কোডে একটি বাগ আছে।
    
    ![screenshot](images/me-dog-bug.png)
    
    কারণ এটি আপনার টেক্সট এ একটি ঊর্ধকমা রয়েছে ` '` , Python যাকে টেক্সট এর শেষ বলে মনে করে। 
    
    ![screenshot](images/me-dog-quote.png)

+ এটি ঠিক করতে, কেবল একটি ব্যাকস্ল্যাশ রাখুন ` \ ` ` শব্দটিতে  ঊর্ধকমা এর আগে ` এখানে </0>। এটি পাইথনকে বোঝায় যে ঊর্ধকমা টেক্সট এর অংশ।
    
    ![screenshot](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![screenshot](images/me-dog-triple-quote.png)