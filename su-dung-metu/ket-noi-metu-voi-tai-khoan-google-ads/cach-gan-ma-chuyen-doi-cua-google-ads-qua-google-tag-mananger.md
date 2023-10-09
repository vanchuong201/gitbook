# Cách gắn mã chuyển đổi của Google Ads qua Google Tag Mananger

## Cách 1: Gắn mã thẻ trang web toàn cầu (gtag) của Google Ads qua Google Tag Mananer.

### Bước 1: Sau khi kết nối METU với tài khoản Google Ads thành công theo cách tự gắn thẻ gtag --> Đăng nhập tài khoản Google Tag Mananger.

### Bước 2: Chọn Thẻ --> Mới. <a href="#buoc-2-chon-the-greater-than-moi" id="buoc-2-chon-the-greater-than-moi"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LxZ79\_ZQk-6mvHzyciy%2F-Ly1t0WRI2sV8JMBr-qq%2F-Ly1wAhZ3nm72ofAuvQs%2FUntitled.jpg?alt=media\&token=abba44d2-0700-4859-9bcf-b0c4015dbdac)

### Bước 3: Điền tiêu đề thẻ --> Chọn icon hình cây bút.

![](<../../.gitbook/assets/Untitled (19).jpg>)

### Bước 4: Chọn HTML tùy chỉnh.

![](<../../.gitbook/assets/Untitled (10).jpg>)

### Bước 5: Nhập mã theo dõi thẻ trang web toàn cầu (gtag) --> Lưu.

![](<../../.gitbook/assets/Untitled (31).jpg>)

### Bước 6: Gửi. <a href="#buoc-6-gui" id="buoc-6-gui"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LxZ79\_ZQk-6mvHzyciy%2F-Ly1t0WRI2sV8JMBr-qq%2F-Ly1zdTEy7p6UPQk-vpQ%2FUntitled.jpg?alt=media\&token=8cbe2342-e680-4caa-96c5-49e7d52d8e32)

### Bước 7: Xuất bản --> Tiếp tục. <a href="#buoc-7-xuat-ban-greater-than-tiep-tuc" id="buoc-7-xuat-ban-greater-than-tiep-tuc"></a>

![](https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LxZ79\_ZQk-6mvHzyciy%2F-Ly1t0WRI2sV8JMBr-qq%2F-Ly2-XlrVBcxGY\_k29Du%2FUntitled.jpg?alt=media\&token=09b78949-fe41-4fdf-bbf5-73c23fdf65ae)

## Cách 2: Gắn mã chuyển đổi cho từng nút của METU qua Google Tag Mananger.

### Bước 1: Sau khi kết nối METU với tài khoản Google Ads thành công theo cách tự gắn mã --> Trong tài khoản Google Ads, hãy nhấp vào trình đơn Công cụ và Cài đặt.

![](<../../.gitbook/assets/1 (4).jpg>)

### Bước 2: Chọn Đo lường: Chuyển đổi, thao tác này sẽ mở ra bảng Hành động chuyển đổi.

![](<../../.gitbook/assets/2 (1).jpg>)

### Bước 3: Chọn tên của hành động chuyển đổi mà bạn muốn gắn qua Google Tag Manager từ cột Hành động chuyển đổi.

![](<../../.gitbook/assets/3 (3).jpg>)

### Bước 4: Click vào mở rộng tab cho phần Thiết lập thẻ, rồi chọn Tự cài đặt thẻ.

![](<../../.gitbook/assets/4 (3).jpg>)

![](../../.gitbook/assets/5.jpg)

### Bước 5: Chọn tab Sử dụng thẻ Trình quản lý thẻ của Google.

![](<../../.gitbook/assets/6 (2).jpg>)

### Bước 6: Sao chép ID chuyển đổi và nhãn chuyển đổi gắn vào Goolge Tag Mananger.

![](../../.gitbook/assets/7.jpg)

### Bước 7: Truy cập vào tài khoản Google Tagmanager và tạo trình kích hoạt mới.

Lấy biến của hành động chuyển đổi trên trang web để đo hành động mà bạn muốn đo bằng cách sau: Ví dụ: Đo chuyển đổi Live Chat trên Metu với Google Tagmanager. Vào trang web click vào nút Live Chat trên trang web.

![](../../.gitbook/assets/8.jpg)

Sau đó sử dụng trình xem trước trong Google Tagmanager để lấy giá trị của nút (những giá trị này phải là những giá trị không đổi trong tất cả các lần click vào nút).

![](../../.gitbook/assets/9.jpg)

Vào tài khoản Google Tagmanager, thêm 2 biến vừa tìm được vào trình kích hoạt để đo chuyển đổi Live Chat như hình bên dưới.

![](../../.gitbook/assets/10.jpg)

### Bước 8: Tạo thẻ cho hành động chuyển đổi trong Google Tagmanager.

Bạn kích vào thẻ và nhấn thêm mới sau đó nhấn vào theo dõi chuyển đổi trên Google Ads.

![](../../.gitbook/assets/11.jpg)

Thêm ID chuyển đổi và nhãn chuyển đổi từ hành động mà bạn muốn đo chuyển đổi trong Google Ads. Sau đó chọn trình kích hoạt mà bạn vừa tạo cho hành động chuyển đổi này.

![](../../.gitbook/assets/12.jpg)

Sau khi hoàn thành xong nhớ ấn lưu và xuất bản thẻ và trình kích hoạt vừa tạo ra.
