# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Hoàng Nhật Anh

**MSSV:** 1871020064

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu điểm (Grade database) - chứa thông tin điểm số của sinh viên cần bảo mật.
- Asset 2: Nhật ký hệ thống (System logs) - ghi lại các hoạt động để kiểm tra và truy vết sự cố.
- Asset 3: Hệ thống xác thực (Authentication system) - đảm bảo chỉ người được phép truy cập.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Availability (A) - Sinh viên không thể đăng nhập, hệ thống không khả dụng.
- Sự cố B -> Integrity (I) - Điểm số bị thay đổi, mất tính toàn vẹn dữ liệu.
- Sự cố C -> Confidentiality (C) - Danh sách điểm bị lộ, mất tính bảo mật.

---

## 3. Phân tích sự cố B
- Threat: Thay đổi trái phép điểm số (Unauthorized modification of grades)
- Vulnerability: Kiểm soát truy cập yếu hoặc lỗ hổng trong mã (Weak access controls or code vulnerabilities like SQL injection)
- Mitigation: Triển khai kiểm soát truy cập dựa trên vai trò (RBAC), mã hóa dữ liệu và ghi nhật ký chi tiết (Implement RBAC, data encryption, and detailed logging)

---

## 4. Reflection
Viết 5-7 dòng.

Qua bài lab này, tôi đã học được về bộ ba CIA và cách áp dụng nó vào các sự cố thực tế. Việc xác định assets cần bảo vệ là bước quan trọng đầu tiên trong bảo mật thông tin. Việc ghép các sự cố với CIA giúp ưu tiên các biện pháp giảm thiểu rủi ro. Phân tích sự cố B cho thấy tầm quan trọng của kiểm soát truy cập và ghi nhật ký. Tổng thể, bài lab giúp tôi hiểu sâu hơn về quản lý rủi ro trong hệ thống thông tin. Ngoài ra, tôi cũng làm quen với quy trình sử dụng GitHub để nộp bài.

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em: FIT4012{A-A-B-I-C-C}

