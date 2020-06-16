## ASCII art

Hãy in thứ gì đó thú vị hơn nhiều so với văn bản: nghệ thuật ASCII! Nghệ thuật ASCII (phát âm '* ask-e * ') tạo ** hình ảnh từ văn bản **.

+ Hãy thêm một số nghệ thuật vào chương trình của bạn - một hình ảnh của một con chó!
    
    ![ảnh chụp màn hình](images/me-dog.png)

Chân của con chó được tạo ra bằng ký tự ống ` | ` mà bạn có thể nhập bằng cách nhấn <kbd> Shift + \ </kbd> trên hầu hết các bàn phím tiếng Anh / Mỹ.

+ Nếu bạn nhấp vào ** Run **, bạn sẽ thấy rằng có một lỗi trong mã mới của bạn.
    
    ![ảnh chụp màn hình](images/me-dog-bug.png)
    
    Đó là vì văn bản của bạn chứa dấu nháy đơn ` ' ` , mà Python nghĩ là kết thúc của văn bản!
    
    ![ảnh chụp màn hình](images/me-dog-quote.png)

+ Để khắc phục điều này, chỉ cần đặt dấu gạch chéo ngược ` \ ` trước dấu nháy đơn trong từ ` here's `. Điều này nói với Python rằng dấu nháy đơn là một phần của văn bản.
    
    ![ảnh chụp màn hình](images/me-dog-bug-fix.png)

+ Nếu bạn thích, bạn có thể sử dụng ba dấu nháy đơn `'''` thay vì một dấu, cho phép bạn in nhiều dòng văn bản với lệnh `print`:
    
    ![ảnh chụp màn hình](images/me-dog-triple-quote.png)