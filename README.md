# Ứng Dụng Phần Mềm Mã Nguồn Mở Odoo Cho Quy Trình Bán Mỹ Phẩm Của Doanh Nghiệp L'Oréal

Dự án này là bài báo cáo kết thúc học phần "Hệ thống Thông tin Quản lý" tại Trường Đại học Ngoại ngữ - Tin học Thành phố Hồ Chí Minh (HUFLIT). Nội dung tập trung vào việc ứng dụng giải pháp ERP mã nguồn mở Odoo để số hóa và tối ưu hóa các quy trình bán hàng, tồn kho và quản lý quan hệ khách hàng (CRM) cho tập đoàn mỹ phẩm L'Oréal.

## 👥 Nhóm Thực Hiện
**Nhóm 25**
* Phan Hoàng Ân (23DH110177)
* Nguyễn Thị Trà Mi (23DH112041)

**Giảng viên hướng dẫn:** Th.S Trần Anh Duy

## 🎯 Mục Tiêu Dự Án
* Phân tích hiện trạng quy trình bán mỹ phẩm của L'Oréal
* Đề xuất mô hình triển khai các module Odoo: Sales, Inventory và CRM
* Thiết lập và thử nghiệm giải pháp thông qua các kịch bản thực tế.

## 🛠️ Công Nghệ & Giải Pháp Sử Dụng
Dự án đề xuất sử dụng **Odoo** (phiên bản 17/18) vì tính linh hoạt, khả năng tùy biến cao và chi phí sở hữu tổng thể thấp hơn so với các giải pháp thương mại khác.

### Các Module Odoo Cốt Lõi:
*   **Sales Management (Quản lý bán hàng):** Hỗ trợ toàn bộ quy trình từ tạo báo giá đến xác nhận đơn hàng, đáp ứng bán hàng đa kênh (B2C, B2B).
*   **Inventory Management (Quản lý tồn kho):** Thiết lập nhiều kho vị trí lưu trữ, quản lý lô/seri và áp dụng quy tắc FIFO (First-In, First-Out) để quản lý chất lượng và hạn sử dụng.
*   **CRM (Quản lý quan hệ khách hàng):** Xây dựng hồ sơ khách hàng 360 độ, theo dõi lịch sử tương tác để cá nhân hóa chiến dịch tiếp thị và chăm sóc khách hàng.

## ⚙️ Kịch Bản Thử Nghiệm (Demo)
Dự án đã triển khai và cấu hình dữ liệu mẫu (danh mục sản phẩm, khách hàng, nhân viên, kho bãi) để chạy các kịch bản thực tế sau:

1.  **Kịch bản 1: Mua hàng online trên Odoo eCommerce (B2C)**
    *   Khách hàng lẻ đặt mua sản phẩm qua kênh TMĐT.
    *   Hệ thống tự động tạo Sales Order, kiểm tra tồn kho và kích hoạt lệnh xuất kho.
2.  **Kịch bản 2: Mua hàng trực tiếp Offline trên Odoo bằng PoS (Bán lẻ)**
    *   Sử dụng ứng dụng Point of Sale (PoS) để xử lý giao dịch tại cửa hàng, tìm kiếm khách hàng VIP để áp dụng ưu đãi.
    *   Hệ thống tự động trừ tồn kho và cập nhật lịch sử mua hàng vào CRM.
3.  **Kịch bản 3: Nhập kho sản phẩm (Purchase → Inventory)**
    *   Tạo Đơn Mua Hàng (Purchase Order), nhận hàng (Receipt) và tự động cập nhật số lượng tồn kho thực tế.
