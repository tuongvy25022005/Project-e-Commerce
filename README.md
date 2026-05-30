# Project-e-Commerce
# Dự Án Xây Dựng Cửa Hàng Kinh Doanh Phụ Kiện Nữ Shell Love
### Tổng quan và Mục tiêu dự án
- Mô hình kinh doanh: B2C (Business to Consumer) chuyên bán lẻ phụ kiện thời trang nữ (khăn, kính, băng đô, kẹp tóc, nón).
- Đối tượng khách hàng: Nữ giới từ 18–30 tuổi, thu nhập 7-9 triệu/tháng, có thói quen mua sắm trực tuyến.
- Mục tiêu: Xây dựng và mô phỏng vận hành website TMĐT (shelllove.vn) với đầy đủ các quy trình từ trưng bày, chốt đơn, thanh toán, đến quản lý kho và CSKH.
### Cơ sở hạ tầng và Nền tảng
- Hệ thống mạng nội bộ (LAN): 8 máy tính kết nối qua switch chia sẻ dữ liệu an toàn.
- Hệ thống Internet (WAN): Gói GigaNet Viettel (150Mbps) kết hợp Router TP-Link Archer C7 băng tần kép.
- Lưu trữ dữ liệu: Điện toán đám mây Google Workspace Business Standard (5TB) để sao lưu, phân quyền tài liệu nội bộ.
- Nền tảng Website: Giao diện trực quan, chia danh mục rõ ràng (Catalog), tích hợp giỏ hàng, trang thanh toán và tra cứu đơn hàng.
### Cơ cấu nhân sự (Quy mô 8 người)
- Bộ phận lãnh đạo (2 người): Giám đốc điều hành và Quản lý vận hành.
- Bộ phận chuyên môn (4 người): Kế toán, Nhân viên kho, Nhân viên nhập liệu sản phẩm, Nhân viên chăm sóc khách hàng.
- Bộ phận kỹ thuật (2 người): Nhân viên kỹ thuật hệ thống (quản trị mạng) và Nhân viên quản trị website.
### Chiến lược E-Marketing
- Google Ads (SEM): Chạy quảng cáo tìm kiếm (Google Search) với các từ khóa mục tiêu (khăn choàng cổ nữ, kẹp tóc vintage...) và quảng cáo video trên YouTube. Ngân sách: 430.000 VNĐ/ngày.
- Mạng xã hội (TikTok): Xây dựng kênh TikTok "Shell Love" đăng video vào khung giờ vàng (18h30 - 19h00).
- TikTok Ads: Chạy quảng cáo chuyển đổi trên nền tảng video ngắn với ngân sách 700.000 VNĐ/ngày nhắm tới tệp khách hàng nữ 18-30 tuổi.
### Hệ thống Bảo mật Thông tin
- Bảo mật vật lý: Camera giám sát 24/7 (lưu trữ 14 ngày), khóa cơ phòng máy chủ, trang bị bộ lưu điện UPS (1000VA).
- Bảo mật truy cập: Quy định mật khẩu mạnh (đổi mỗi 30 ngày), xác thực hai lớp (2FA) cho quản trị viên, phân quyền truy cập nghiêm ngặt theo vai trò (Admin, Kế toán, Kho...).
- Bảo mật mạng: Tường lửa (Firewall) trên Router TP-Link, phần mềm chống xâm nhập Wordfence Security (chống Brute force), và Cloudflare (chống tấn công DDoS, xác minh CAPTCHA).
### Thanh toán và Logistics
- Phương thức thanh toán: Chuyển khoản ngân hàng (Vietcombank), Ví điện tử (quét mã QR MoMo, VNPay), và Thanh toán khi nhận hàng (COD).
- Chính sách giao hàng: Giao toàn quốc qua GHN, J&T Express, Viettel Post. Miễn phí vận chuyển cho đơn từ 300.000 VNĐ.
- Chính sách đổi trả: Hỗ trợ đổi trả trong vòng 3 ngày nếu có lỗi từ nhà sản xuất hoặc quá trình vận chuyển. Cho phép đồng kiểm khi nhận hàng.
### Quản trị Quan hệ Khách hàng (CRM)
- CRM vận hành: Trang bị hệ thống Câu hỏi thường gặp (FAQ), bộ lọc tìm kiếm/so sánh sản phẩm, và bong bóng chat Messenger trực tuyến.
- CRM phân tích: Theo dõi hành vi người dùng trên web, tự động hiển thị mục "Sản phẩm tương tự" để tăng tỷ lệ chốt đơn (Upsell/Cross-sell).
- CRM cộng tác: Triển khai "Chính sách khách hàng thân thiết" (10.000đ = 1 điểm tích lũy = 500đ) để đổi quà/voucher. Tặng voucher 10% trong tháng sinh nhật.
### Quản lý Chuỗi cung ứng (SCM)
- Công cụ sử dụng: Phần mềm quản lý bán hàng KiotViet.
- Upstream (Thượng nguồn): Quản lý thông tin và công nợ với các nhà cung cấp (Lecos, Mantis, Mặt Trời Hồng...).
- Internal (Nội bộ): Quản lý tồn kho theo mã hàng, tự động trừ kho khi có đơn, tiến hành kiểm kê định kỳ.
- Downstream (Hạ nguồn): Tạo mã vận đơn, theo dõi trạng thái giao hàng của đối tác vận chuyển và xử lý khiếu nại.
### Tác giả 
**Hồ Vũ Tường Vy**
