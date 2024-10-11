# <p align="center"> Triển khai Wordpress trên hosting cPanel </p>

## 1. Download mã nguồn Wordpress

- Truy cập vào đường dẫn [này](https://vi.wordpress.org/download/) để tiến hành tải mã nguồn Wordpress.

![alt text](image-111.png)
<p align="center">Tải xuống phiên bản mới nhất 6.6.2</p>

<p align="center"><image src="image-112.png"/></p>
<p align="center">Bạn sẽ nhận được một file .zip</p>

## 2. Truy cập vào trang quản trị cPanel

<p align="center"><image src="image-113.png"/></p>
<p align="center">Vào phần dịch vụ Web hosting và click vào "Đăng nhập vào cPanel"</p>

## 3. Upload mã nguồn lên hosting

![alt text](image-114.png)
<p align="center">Kéo xuống và truy cập vào phần "File Manager"</p>

![alt text](image-115.png)
<p align="center">Vào thư mục "public_html" và xóa hết file, thư mục hiện có</p>

![alt text](image-116.png)
<p align="center">Chọn Upload để tiến hành upload mã nguồn wordpress lên</p>

![alt text](image-117.png)
<p align="center">Chọn Upload và lựa chọn file .zip đã tải ở bước trên</p>

![alt text](image-118.png)
<p align="center">Sau khi Upload và giải nén file .zip đó ta sẽ có một thư mục wordpress như trên</p>

> Ta cần phải di chuyển tất cả nội dung trong folder wordpress ra ngoài, đồng thời xóa file .zip và folder wordpress


![alt text](image-119.png)
<p align="center">Như vầy là ta đã đưa mã nguồn lên thành công </p>

## 4. Tạo database trên cPanel

![alt text](image-121.png)
<p align="center">Quay trở lại cPanel và click vào  MySQL Databases</p>

![alt text](image-122.png)
<p align="center">Nhập tên Database và tiến hành tạo</p>

![alt text](image-123.png)
<p align="center">Tại phần user, khởi tạo một user với password đủ mạnh</p>

![alt text](image-124.png)
<p align="center">Ta tiến hành thêm user đó vào trong database tạo ở phía trên</p>

![alt text](image-125.png)
<p align="center">Khởi tạo quyền cho user này</p>

## 5. Thiết lập Wordpress

> Truy cập vào tên miền đã đăng kí trước đó trên trình duyệt

![alt text](image-126.png)
<p align="center">Chúng ta sẽ thấy giao diện này, tiếp tục nhấn vào thực hiện ngay</p>

![alt text](image-127.png)
<p align="center">Nhập tên database và user đã tạo trước đó</p>

![alt text](image-128.png)
<p align="center">Xác thực database thành công</p>

![alt text](image-129.png)
<p align="center">Khởi tạo user đăng nhập trang web</p>

![alt text](image-130.png)
<p align="center">Tạo thành công</p>

 ![alt text](image-2.png)
 <p align="center">Đăng nhập với user vừa khởi tạo phía trên, ta sẽ vào được giao diện của Wordpress</p>