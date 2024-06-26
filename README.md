# Ứng dụng đánh giá ẩn danh các thành viên trong nhóm (Group-Self-Assessment)
Mô tả ứng dụng

## Tên ứng dụng : Group Self Assessment
Group Self Assessment là một ứng dụng giúp người dùng tạo và đánh giá hiệu xuất làm việc của các thành viên trong nhóm . Ứng dụng giải quyết vấn đề tiếp thu ý kiến của mọi người và đánh giá bản thân mà không lo bị ảnh hưởng cảm xúc

## Đối tượng người dùng :

- Học sinh và sinh viên : Sử dụng để góp ý và đưa ra ý kiến cho nhau
- Giáo Viên : Đưa ra góp ý kiến cho học sinh , quản lý và đưa ra lời khuyên phù hợp với hiệu xuất làm việc của học sinh

## Các chức năng chính :

- Đăng nhập và đăng ký : Cho phép người dùng tạo tài khoản và đăng nhập để sử dụng các tính năng của ứng dụng.

- Tạo nhóm và quản lý nhóm : Cho phép người dùng tạo 1 nhóm có tính bảo mật riêng có thể thêm hoặc xoá thành viên , có thể xoá nhóm và xem thông tin đánh giá không ẩn danh

- Đánh giá thành viên : Cho phép người dùng đánh giá ẩn danh lẫn nhau trong nhóm 

- Cập nhật thông tin hồ sơ : Cho phép người dùng tự update thông tin cá nhân cũng như avatar , để tạo sự khác biệt

- Tổng hợp : Tổng hợp thông tin đánh giá , để đánh giá trực quan lượng đánh giá mà người dùng nhận được

## Cài đặt :

- i. Pull Project từ GitHub: Đầu tiên, hãy sử dụng Git để pull project từ GitHub về máy tính của bạn. Bạn có thể sử dụng lệnh sau trong terminal hoặc command prompt:
  - git clone https://github.com/VIEE02/14_Group-Self-Assessment.git
- ii. Mở xampp, Chọn start Apache và MySql -> Chọn Admin của MySql, chọn 'mới' -> Tạo hệ csdl tên 'database6'.
- iii. Chạy các câu lệnh trên terminal theo thứ tự: pip install mysql -> pip install pillow  để cài các thư viện cần dùng python manage.py makemigrations ->python manage.py migrate-> 
-> python manage.py runserver
- Sau khi hoàn tất các bước, web sẽ được chạy trên địa chỉ http://127.0.0.1:8000/.

## Thông tin thành viên :

- Đặng Chí Viễn - 20105361
- Hoàng Công Vũ - 21094651
- Nguyễn Vũ Thiện - 21112151

## Người tham gia :

- [@VIEE02](https://www.github.com/VIEE02)
- [@HoangCongVu](https://github.com/HoangCongVu)
- [@ngvuthien](https://github.com/ngvuthien)

## Trách nhiệm :

- Thành viên 1: Đặng Chí Viễn
  - Trách nhiệm 1: Phát triển backend và cơ sở dữ liệu
  - Trách nhiệm 2: Xây dựng và tích hợp frontend
  - Trách nhiệm 3: Quản lý source code trên git
  - Trách nhiệm 4: Quản lý và triển khai dự án trên máy chủ

- Thành viên 2: Nguyễn Vũ Thiện
  - Trách nhiệm 1: Thiết kế giao diện người dùng (UI/UX)
  - Trách nhiệm 2: Kiểm thử và đảm bảo chất lượng sản phẩm (QA)
  - Trách nhiệm 3: Quản lý bảo mật và xác thực người dùng
  - Trách nhiệm 4: Giám sát và xử lý các lỗi phát sinh trong quá trình sử dụng

- Thành viên 3: Hoàng Công Vũ
  - Trách nhiệm 1: Thiết kế giao diện người dùng (UI/UX)
  - Trách nhiệm 2: Tạo các mẫu giao diện cho các trang web chính
  - Trách nhiệm 3: Kiểm thử và đảm bảo chất lượng sản phẩm (QA)
  - Trách nhiệm 4: Giám sát và xử lý các lỗi phát sinh trong quá trình sử dung
