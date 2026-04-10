# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu điểm (Grade database)
- Nhật ký hệ thống (System logs)
- Hệ thống xác thực (Authentication system)

**CIA mapping:**
- Sự cố A -> Availability (A)
- Sự cố B -> Integrity (I)
- Sự cố C -> Confidentiality (C)

**Phân tích sự cố B:**
- Threat: Thay đổi trái phép điểm số
- Vulnerability: Kiểm soát truy cập yếu
- Mitigation: Triển khai RBAC và ghi nhật ký 

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)

Bài lab giúp tôi hiểu rõ bộ ba CIA và cách áp dụng vào phân tích sự cố. Phần khó nhất là xác định threat và vulnerability chính xác cho sự cố B. Khi phân tích sự cố an toàn, cần chú ý đến bối cảnh hệ thống và các mối đe dọa tiềm ẩn. Việc ghi nhật ký và kiểm soát truy cập là quan trọng để giảm thiểu rủi ro. Tôi cũng học được quy trình làm việc với GitHub.
