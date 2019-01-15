## ASCIIアート

テキストよりももっと楽しいものを表示しましょう：ASCIIアート！ ASCIIアート（「*ask-e*」と発音）とは **文字を使って作られた絵**のことです。

+ あなたのプログラムに作品を加えてみましょう - 犬の絵！
    
    ![スクリーンショット](images/me-dog.png)

犬の足は、パイプ文字 `| 123_7_2_321 Shift + \ </kbd> を押して入力できます。ほとんどの英国/米国英語キーボードで入力できます。</p>

<ul>
<li><p><strong>Run</strong>をクリックすると、新しいコードにバグがあることがわかります。</p>

<p><img src="images/me-dog-bug.png" alt="スクリーンショット" /></p>

<p>これは、テキストにアポストロフィ <code>'`が含まれているためです。これはPythonがテキストの終わりと考えるものです！

![スクリーンショット](images/me-dog-quote.png)</li> 

+ これを修正するには、アポストロフィの前にバックスラッシュ `` を `単語`に入れてください。日本語の場合ですと文字ボケする可能性がありますで、＋を使って二つの文字をつなげてください。もうしくはアポストロフィを削除してそのまま続けてください。 
    
    ![スクリーンショット](images/me-dog-bug-fix.png)

+ If you prefer, you can use three apostrophes `'''` instead of one, which allows you to print multiple lines of text with one `print` statement:
    
    ![スクリーンショット](images/me-dog-triple-quote.png)</ul>