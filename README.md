
# Hướng Dẫn Tạo Github và làm quen với viết hướng dẫn bằng Markdown

# A. Github

## 1. Đăng Ký Tài Khoản GitHub

### Bước 1: Truy Cập Trang Đăng Ký
- Mở trình duyệt và truy cập [GitHub](https://github.com/).
- Nhấp vào nút **Sign up** ở góc trên bên phải của trang.

### Bước 2: Điền Thông Tin Cá Nhân
- **Email Address**: Nhập địa chỉ email của bạn.
- **Password**: Tạo mật khẩu mạnh và an toàn.
- **Username**: Chọn tên người dùng duy nhất, GitHub sẽ kiểm tra tính khả dụng của tên.
- **Verify Account**: Xác minh bằng cách giải câu đố (CAPTCHA).
- Sau đó nhấp vào **Create account** để tiếp tục.

### Bước 3: Xác Minh Email
- GitHub sẽ gửi một email xác nhận đến địa chỉ bạn đã cung cấp.
- Mở email và nhấp vào liên kết để xác minh tài khoản.

## 2. Khởi Tạo Repository Trên GitHub

### Bước 1: Đăng Nhập Vào Tài Khoản GitHub
- Truy cập [https://github.com/](https://github.com/) và đăng nhập vào tài khoản của bạn.
<div style="text-align:center"><img src="image-47.png " width="300" height="350" /></div>
<div style="text-align:center"><img src="image-47.png "/></div>

### Bước 2: Tạo Một Repository Mới
- Ở góc trên bên phải, nhấp vào biểu tượng **+** và chọn **New repository**.

<div style="text-align:center"><img src="image-48.png " height="200" /></div>

### Bước 3: Cấu Hình Repository
- **Repository name**: Nhập tên cho repository (ví dụ: `my-first-repo`).

![alt text](image-49.png)

- **Description**: (Tuỳ chọn) Thêm mô tả ngắn về repository.
- **Privacy**:
  - Chọn **Public** để repository có thể được xem bởi bất kỳ ai.
  - Chọn **Private** nếu bạn muốn repository chỉ được xem bởi bạn hoặc những người bạn cho phép.

![alt text](image-57.png)

- **Initialize this repository with**:
  - Chọn **Add a README file** để tạo một tệp README.md cơ bản.
  - Nếu muốn, bạn có thể thêm `.gitignore` hoặc chọn một giấy phép cho repository (license).
- Nhấp vào **Create repository**.

![alt text](image-51.png)

- Vậy là bạn đã tạo thành công một repository của riêng mình

![alt text](image-58.png)

- Bạn sẽ thấy hướng dẫn sử dụng git để đấy dự án lên GitHub ở phía bên dưới

![alt text](image-59.png)

## 3. Sử Dụng Git Để Đẩy Dự Án Lên GitHub

- Nếu bạn chưa có sẵn git trên máy tính thì tiến hành cài đặt git theo hướng dẫn sau [Download Git](https://phoenixnap.com/kb/how-to-install-git-windows)

### Bước 1: Khởi Tạo Repository Cục Bộ
- Truy cập vào Folder nơi bạn muốn lưu trữ dụ án, Click chuột phải và chọn __Git Bash Here__:

![alt text](image-53.png)

- Sử dụng câu lệnh sau để khởi tạo repository cục bộ:
```bash
git init
```
![alt text](image-54.png)

- Sử dụng câu lệnh sau để tạo một file README.md với nội dung **"# my-first-repo"**:
```bash
echo "# my-first-repo" >> README.md
```

<div style="text-align:center"><img src="image-60.png "/></div>


### Bước 2: Kết Nối Repository Cục Bộ Với GitHub
- Sao chép URL của repository bạn vừa tạo trên GitHub. Sau đó, chạy lệnh sau để liên kết repository cục bộ với GitHub:
```bash
git remote add origin https://github.com/dinhcongpham/my-first-repo.git
```
![alt text](image-56.png)

### Bước 3: Thêm Tệp Và Đẩy Lên GitHub
- Thêm tệp vào repository cục bộ:
```bash
git add README.md
```
- Commit các thay đổi:
```bash
git commit -m "first commit"
```
- Tạo Branch chính cho dự án là main
```
git branch -M main
```
- Đẩy code lên GitHub:
```bash
git push -u origin main
```
<div style="text-align:center"><img src="image-61.png "/></div>

## 4. Kiểm Tra Trên GitHub
- Mở trình duyệt và truy cập vào repository của bạn trên GitHub. Các tệp vừa đẩy sẽ xuất hiện trong repository.

![alt text](image-62.png)

---

Vậy là bạn đã hoàn tất quá trình tạo tài khoản GitHub, khởi tạo repository và đẩy dự án đầu tiên của mình lên GitHub!

---

# B. Markdown

Markdown là một ngôn ngữ đánh dấu đơn giản, dễ đọc và dễ viết. Nó thường được sử dụng để tạo các tệp README, ghi chú, và các tài liệu khác.

## 1. Tiêu Đề (Headers)

Để tạo tiêu đề, sử dụng dấu `#`. Bạn có thể sử dụng từ 1 đến 6 dấu `#` để tạo các tiêu đề có cấp độ khác nhau.

Ví dụ:
```markdown
# Tiêu đề 1
## Tiêu đề 2
### Tiêu đề 3
#### Tiêu đề 4
##### Tiêu đề 5
###### Tiêu đề 6
```

## 2. In Đậm và In Nghiêng

- **In đậm**: Đặt từ hoặc cụm từ cần in đậm trong hai dấu `** hoặc __`.
- *In nghiêng*: Đặt từ hoặc cụm từ cần in nghiêng trong một dấu `* hoặc _`.
- ***In đậm và nghiêng***: Đặt trong ba dấu `*** hoặc ___`.

Ví dụ:
```markdown
**Chữ in đậm**      __Chữ in đậm__
*Chữ in nghiêng*     _Chữ in nghiêng_
***Chữ vừa in đậm vừa in nghiêng***
___Chữ vừa in đậm vừa in nghiêng___
```

## 3. Danh Sách (Lists)

- **Danh sách không thứ tự**: Sử dụng dấu `-`, `*` hoặc `+`.
- **Danh sách có thứ tự**: Sử dụng số và dấu chấm.

Ví dụ:
```markdown
- Mục 1
- Mục 2
  - Mục 2.1
  - Mục 2.2

1. Mục 1
2. Mục 2
   1. Mục 2.1
   2. Mục 2.2
```

## 4. Link và Hình Ảnh

- **Link**: Sử dụng cú pháp `[text](URL)`.
- **Hình ảnh**: Sử dụng cú pháp `![alt text](URL)`.

Ví dụ:
```markdown
[Link đến Google](https://www.google.com)

![Hình ảnh ví dụ](https://via.placeholder.com/150)
```

## 5. Đoạn Mã (Code)

- Để hiển thị mã trong dòng, sử dụng dấu `.
- Để hiển thị khối mã, sử dụng ba dấu ```.

Ví dụ:

Đây là một đoạn mã trong dòng: `code`.


Đây là một khối mã:
```
function example() {
    console.log("Hello, Markdown!");
}
```


## 6. Trích Dẫn (Blockquotes)

Sử dụng dấu `>` để tạo trích dẫn.

Ví dụ:
```markdown
> Đây là một trích dẫn.
```

## 7. Chia Dòng (Line Breaks)

Sử dụng ba dấu gạch ngang `---` để tạo một đường chia.

Ví dụ:
```markdown
---
```

## 8. Bảng (Tables)

Sử dụng dấu `|` để tạo bảng. Bạn có thể sử dụng dấu `-` để phân chia giữa tiêu đề và nội dung.

Ví dụ:
```markdown
| Cột 1 | Cột 2 | Cột 3 |
|-------|-------|-------|
| Dữ liệu 1 | Dữ liệu 2 | Dữ liệu 3 |
| Dữ liệu A | Dữ liệu B | Dữ liệu C |
```

## 9. Danh sách tác vụ (Task List)

Sử dụng dấu `- [ ]` cho các nhiệm vụ chưa hoàn thành và `- [x]` cho các nhiệm vụ đã hoàn thành.

Ví dụ:
```markdown
- [x] Hoàn thành bước 1
- [ ] Hoàn thành bước 2
- [ ] Hoàn thành bước 3
```

## 10. Kết Luận

Đây là những cú pháp cơ bản của Markdown, cùng với việc sử dụng Git - Github bạn có thể tạo ra những hướng dẫn Readme.md file chuyên nghiệp.

---
