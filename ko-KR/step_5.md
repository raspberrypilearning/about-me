## ASCII 아트

텍스트보다 훨씬 흥미로운 것을 출력해 봅시다: ASCII art! ASCII(*ask-e* 라고 발음) 아트는 **pictures out of text**를 만드는 것입니다.

+ 프로그램에 아트를 추가해 봅시다 - 개 그림을 말이죠!
    
    ![screenshot](images/me-dog.png)

강아지의 다리는 수직선 기호 `|`로 만들어지는데 <kbd>Shift + \</kbd> 대부분의 영국/미국식 영어 키보드에서 입력할 수 있습니다.

+ **Run**을 클릭하면, 당신이 작성한 코드에 버그를 볼 수 있습니다.
    
    ![screenshot](images/me-dog-bug.png)
    
    이것은 작은따옴표`'`가 포함되어 있기 때문인데, 파이썬은 이것을 문장의 끝이라고 인식합니다!
    
    ![screenshot](images/me-dog-quote.png)

+ 이것을 고치려면 역 슬래시 `\`를 `here's`의 작은따옴표 앞에 넣어 주면 됩니다. 이렇게 하면 파이썬은 작은따옴표가 텍스트의 일부라고 인식합니다.
    
    ![screenshot](images/me-dog-bug-fix.png)

+ 만약 작은 따옴표를 하나 대신 3 개 `'''` 를 사용한다면 하나의 출력문 `print`으로 다 수의 문자열을 출력하는 것이 가능 합니다.
    
    ![screenshot](images/me-dog-triple-quote.png)