# Trợ lý ảo thông minh siri
> Thông tin sản phẩm.
<p style="color: red;">Siri Version: 1.5</p>
<p style="color: blue;">By deverloper: Nguyen Hoang Khoi</p>


Chương trình trợ lý ảo được thiết kế để liên tục lắng nghe người dùng bằng từ khóa "hey siri". Khi từ khóa này được phát hiện, chương trình sử dụng tính năng nhận dạng giọng nói để xác định những gì người dùng đang nói.
Để xác định mục đích của người dùng, chương trình sử dụng lớp intentclassifier (có trong thư mục /intentclassfiter/intenclassfiter.py) và thuật toán Support Vector Machine (SVM) đã được đào tạo trên tập dữ liệu chứa các lời nhắc mẫu của người dùng cùng với mục đích của họ. Nhờ đó, chương trình có thể phân loại mục đích của người dùng một cách chính xác.
Dựa trên mục đích được phân loại, trợ lý ảo thực hiện các chức năng tương ứng, các chức năng này được lưu trữ trong thư mục /ai_functions. Qua đó, người dùng có thể tương tác với trợ lý ảo một cách dễ dàng và thuận tiện.


![](🤖)

## Installation

Windows:

```pip
pip install requments.txt
```
```open folder exe
Mở folder exe và nhấn vào file Siri.exe để cài đặt chương trình
```
## Usage example

Để sử dụng chương trình bạn chỉ cần click vào biểu tượng trợ  lý sau khi cài đặt hoàn tất ở bước trên và sau khi giao diện trợ lý hiện lên bạn chỉ cần ra lệnh bằng giọng nói:
ví dụ "bạn cho mình xem lịch học mới nhất" sau khi bạn nói xong trợ lý sẽ tự động tìm kiếm lịch học mới nhất cho bạn.

## Support assistant content

```Nội dung hỗ trợ
Tìm kiếm lịch học
Tra cứu điểm
Điểm số
Học bổng
Phòng ban
Học phí
```

## Release History

* version 1.5
    * Phiên bản ổn định và mới nhất

## Meta

Name – [@Nguyen Hoang Khoi]

[https://github.com/nguyenhoangkhoicm/]




