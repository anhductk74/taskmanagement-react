# 04. Non-Functional Requirements (Yêu cầu phi chức năng)

## 1. Hiệu năng (Performance)
- [ ] Hệ thống phải đảm bảo thời gian phản hồi dưới 2 giây cho 95% các yêu cầu.
- [ ] Trang dashboard phải tải hoàn tất trong vòng 3 giây với dữ liệu trung bình.
- [ ] Hệ thống có khả năng mở rộng để phục vụ 500 người dùng đồng thời.

## 2. Khả năng sử dụng (Usability)
- [ ] Giao diện phải dễ sử dụng, thân thiện với người dùng không chuyên về kỹ thuật.
- [ ] Có tài liệu hướng dẫn sử dụng cho từng vai trò: Admin, PM, Member.
- [ ] Hệ thống hỗ trợ responsive (trên desktop, tablet, mobile).

## 3. Bảo mật (Security)
- [ ] Tất cả tài khoản phải xác thực qua email (SMTP).
- [ ] Hệ thống phải sử dụng HTTPS cho mọi giao tiếp.
- [ ] Mỗi tài khoản phải có quyền hạn phù hợp với vai trò được phân.
- [ ] Mật khẩu được mã hoá và lưu trữ an toàn theo chuẩn bcrypt.
- [ ] Cơ chế phân quyền chi tiết (Role-based access control – RBAC).
- [ ] Tự động logout sau 15 phút không hoạt động.

## 4. Khả năng bảo trì và nâng cấp (Maintainability & Scalability)
- [ ] Mã nguồn được tổ chức rõ ràng theo mô-đun.
- [ ] Có log hệ thống chi tiết phục vụ theo dõi lỗi và audit.
- [ ] Hệ thống hỗ trợ backup và restore dữ liệu định kỳ.
- [ ] Cho phép mở rộng module như chấm công, chấm điểm, báo cáo nâng cao mà không ảnh hưởng hệ thống chính.

## 5. Khả năng tương thích (Compatibility)
- [ ] Hệ thống hoạt động tốt trên các trình duyệt hiện đại: Chrome, Firefox, Edge.
- [ ] Ứng dụng không yêu cầu plugin cài thêm.

## 6. Tính ổn định (Reliability)
- [ ] Tỷ lệ uptime hệ thống phải đạt ≥ 99%.
- [ ] Hệ thống phải phục hồi dữ liệu sau khi gặp sự cố (theo lịch backup).

## 7. Đa ngôn ngữ (Internationalization)
- [ ] Hệ thống hỗ trợ ít nhất 2 ngôn ngữ: Tiếng Việt và Tiếng Anh.
- [ ] Có thể thêm ngôn ngữ mới bằng cấu hình.

## 8. Khả năng ghi nhận & giám sát (Audit & Monitoring)
- [ ] Lưu lại nhật ký hoạt động người dùng (login, sửa dữ liệu...).
- [ ] Gửi thông báo lỗi đến Admin qua email khi có sự cố hệ thống.

