# <p align="center">Hướng dẫn kiểm tra tài nguyên Email Hosting</p>

Email hosting là một giải pháp tuyệt vời cho cả cá nhân và doanh nghiệp, giúp cải thiện tính chuyên nghiệp và hiệu quả trong việc quản lý liên lạc qua email. Vinahost là nhà cung cấp dịch vụ này số 1 Việt Nam, đảm bảo hợp với nhu cầu của bạn và giúp bạn tối ưu hóa hiệu quả công việc, cũng như bảo mật thông tin an toàn tuyệt đối.


## 1. Kiểm tra các tài nguyên cơ bản


<div style="text-align:center"><img src="image-42.png" /></div>
<p align="center">Thông tin về dịch vụ Email Hosting được gửi qua mail (kèm hướng dẫn cấu hình nếu không phải dns mà vinahost quản lý)</p>

<div style="text-align:center"><img src="image-68.png" /></div>
<p align="center">Cấu hình được cấp phát cho dịch vụ</p>

<div style="text-align:center"><img src="image-69.png" /></div>
<p align="center">Cũng tại giao diện này, ta tiến hành truy cập vào cPanel để tiến hành các thao tác quản lý. Còn Webmail sẽ là giao diện thực hiện việc gửi và nhận mail.</p>

<div style="text-align:center"><img src="image-70.png" /></div>
<p align="center">Tại phía bên phải của trang Web sẽ có một block hiển thị các thông tin cấu hình cơ bản của Email Hosting.</p>

## 2. Kiểm tra khả năng gửi mail

![alt text](image-71.png)
<p align="center">Gửi mail tới congpd.tts@vinahost.vn </p>

![alt text](image-72.png)
<p align="center">congpd.tts@vinahost.vn nhận được mail thành công</p>

![alt text](image-73.png)
<p align="center">Gửi mail tới phamdinhcong0@gmail.com </p>

![alt text](image-74.png)
<p align="center">phamdinhcong0@gmail.com nhận mail thành công</p>

## 3. Kiểm tra khả năng nhận mail

![alt text](image-74.png)
<p align="center">phamdinhcong0@gmail.com gửi mail tới</p>

![alt text](image-75.png)
<p align="center">nhận được mail từ phamdinhcong0@gmail.com</p>

## 4. Kiểm tra bảo mật

![alt text](image-76.png)
<p align="center">thư được gửi đi tới email khác được bảo mật TLS, giúp tăng uy tín và bảo mật cho thư</p>

## 5. Kiểm tra khả năng spam của Email

![alt text](image-77.png)
<p align="center">Test thử với một vài trang Web tính điểm tỉ lệ email bị đưa vào mục spam. Điểm số tương đối cao >80, nó còn phụ thuộc vào nội dung email của bạn, nếu đủ sạch thì tỉ lệ bị đưa vào mục spam là khá thấp.</p>

## 6. Đăng nhập vào Outlook

<div style="text-align:center"><img src="image-79.png" /></div>
<p align="center">Truy cập control panel -> Mail (Microsoft Outlook) -> Manual setup</p>
<div style="text-align:center"><img src="image-80.png" /></div>
<p align="center">Lựa chọn POP or IMAP</p>
<div style="text-align:center"><img src="image-81.png" /></div>
<p align="center">Điền thông tin đăng nhập (Thông tin Incoming và Outgoing mail server được gửi và lưu ý ở trong mail đăng ký dịch vụ)</p>

![alt text](image-82.png)
<p align="center">Thêm tài khoản mới thành công</p>

![alt text](image-83.png)
<p align="center">Gặp phải lỗi khi tiến hành gửi mail tới mail khác</p>

> Lỗi này xảy rả khi bạn chưa cấu hình chính xác địa chỉ mail trên Outlook.

- Hướng dẫn sửa lỗi

![alt text](image-84.png)
<p align="center">Truy cập control panel -> Mail -> account -> lựa chọn accout bị lỗi -> nhấn vào More Settings ở góc dưới bên phải</p>

<div style="text-align:center"><img src="image-85.png" /></div>
<p align="center">Click vào tùy chọn "My..."</p>

> Như vậy là mail của bạn đã có thể gửi được mail thành công


## 7. Đăng nhập vào Thunder Bird

<div style="text-align:center"><img src="image-86.png" /></div>
<p align="center">Nhập email, password đồng thời click vào "Configure manually" để thiết lập thêm thông tin.</p>

<div style="text-align:center"><img src="image-88.png" /></div>
<p align="center">Thiết lập thông tin Incoming và Outcoming Server.</p>


![alt text](image-89.png)
<p align="center">Đăng nhập thành công.</p>


![alt text](image-90.png)
<p align="center">Lỗi sai cấu hình của Outgoing server SMTP.</p>

> Sai cấu hình Port cho SMTP, phía trên cấu hình port 995 là sai, cần phải đổi lại thành 465, port mặc định của SMTP

![alt text](image-91.png)
<p align="center">Vào Account Settings tiến hành chỉnh sửa</p>

> Bây giờ Thunder Bird đã có thể gửi nhận mail bình thường