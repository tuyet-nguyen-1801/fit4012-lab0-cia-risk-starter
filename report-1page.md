# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

## 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

## 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

## 3. Kết quả chính

**Assets:**
- Bảng điểm sinh viên
- Tài khoản đăng nhập (giảng viên/sinh viên)
- Cơ sở dữ liệu điểm
- Log thay đổi điểm

**CIA mapping:**
- Sự cố A -> Availability (hệ thống không đăng nhập được)
- Sự cố B -> Integrity (điểm bị sửa trái phép)
- Sự cố C -> Confidentiality (danh sách điểm bị lộ)

**Phân tích sự cố B:**
- Threat: Người dùng trái phép sửa điểm không đúng thẩm quyền
- Vulnerability: Phân quyền chưa chặt, không có log, thiếu MFA
- Mitigation: Bật MFA, phân quyền rõ vai trò, ghi log mọi thao tác sửa điểm

## 4. Kết luận ngắn
Qua bài lab này, em hiểu được tầm quan trọng của mô hình CIA trong việc phân tích sự cố bảo mật. Phần khó nhất là phân biệt rõ threat và vulnerability vì dễ nhầm lẫn giữa hai khái niệm này. Khi phân tích một sự cố an toàn thông tin, cần xác định rõ tài sản bị ảnh hưởng trước, sau đó mới truy ngược lại nguyên nhân và biện pháp xử lý.
