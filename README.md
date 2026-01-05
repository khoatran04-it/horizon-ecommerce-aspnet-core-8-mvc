# 🛡️ HORIZON - Nền tảng Thương mại Điện tử Tactical Cao cấp

[![Live Demo](https://img.shields.io/badge/demo-os--horizon.site-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://os-horizon.site/)
[![Platform](https://img.shields.io/badge/.NET-8.0-512bd4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/)
[![Database](https://img.shields.io/badge/SQL_Server-2022-cc2927?style=for-the-badge&logo=microsoft-sql-server)](https://www.microsoft.com/en-us/sql-server/)

## 📝 Giới thiệu
**Horizon** là một hệ thống thương mại điện tử (B2C) hoàn chỉnh, tập trung vào thị trường ngách là thiết bị Gaming và phụ kiện phong cách Tactical. Dự án được xây dựng với mục tiêu không chỉ tạo ra một giao diện mua sắm độc đáo mà còn tích hợp các chiến lược vận hành thực tế: từ bảo mật thanh toán, tối ưu hóa SEO đến quản trị kho vận dựa trên dữ liệu.

> **Slogan:** *"Walk Past The Horizon."*

---

## 🚀 Tính năng Chiến lược (Core Features)

### 1. Vận hành & Thanh toán (E-commerce Core)
*   **Thanh toán VnPay Protocol:** Tích hợp cổng thanh toán quốc gia, tự động hóa quy trình xác thực, trừ kho thời gian thực và lưu nhật ký giao dịch (`Transactions`).
*   **Quản trị kho vận (Inventory Logs):** Hệ thống `Product Receipts` ghi nhận giá vốn và lịch sử nhập hàng, cho phép tính toán lợi nhuận ròng chính xác.
*   **Hệ thống Giỏ hàng (Cargo Manifest):** Sử dụng **Session JSON Serialization** để tối ưu hiệu suất và lưu trữ đối tượng phức tạp.

### 2. Digital Marketing & SEO Tối ưu
*   **URL Friendly (Slug):** Tự động hóa quy trình sinh Slug chứa từ khóa từ tên sản phẩm, tối ưu cho bộ máy tìm kiếm Google.
*   **Social Marketing:** Triển khai **Open Graph (OG Tags)** cho phép hiển thị ảnh, giá và mô tả chuyên nghiệp khi chia sẻ lên Facebook/Zalo.
*   **Email Marketing:** Tích hợp **Mailchimp** để thu thập dữ liệu khách hàng (Lead Generation) và triển khai các chiến dịch "Intel Briefing".

### 3. Trải nghiệm người dùng & CRM
*   **QRF Support (Livechat):** Nhúng hệ thống **Tawk.to** hỗ trợ khách hàng 24/7 theo thời gian thực.
*   **Phân tích hành vi:** Sử dụng **Google Analytics 4 (GA4)** để giám sát luồng truy cập và tối ưu hóa phễu bán hàng.
*   **Giao diện Modern Light:** Thiết kế tối giản, tập trung vào sản phẩm, đảm bảo tốc độ phản hồi nhanh (< 2s).

---

## 🛠️ Tech Stack (Hệ thống Khí tài)

| Thành phần | Công nghệ triển khai |
| :--- | :--- |
| **Backend** | C# / ASP.NET Core 8.0 (MVC) |
| **ORM** | Entity Framework Core 8 (Code-First) |
| **Identity** | ASP.NET Core Identity (Role-based Authorization) |
| **Frontend** | Bootstrap 5, CSS3 Variables, JavaScript, Chart.js |
| **Dịch vụ 3rd Party** | VnPay Gateway, Mailchimp, Tawk.to, GA4 |
| **Hạ tầng Cloud** | SmarterASP Hosting, TenTen DNS, SSL (Let's Encrypt) |

---

## 🏗️ Kiến trúc Hệ thống
Dự án áp dụng cấu trúc **Areas** để tách biệt luồng nghiệp vụ quản trị và khách hàng:
- **`Area/Admin`**: Trung tâm điều hành (Dashboard, Thống kê doanh thu, Quản lý kho, Cập nhật trạng thái đơn hàng).
- **`Area/Customer`**: Cửa hàng trực tuyến (Tìm kiếm, Bộ lọc Sidebar, Luồng Checkout bảo mật).
- **`Infrastructure`**: Chứa các bộ Helper nâng cao (`SlugHelper`, `VnPayLibrary`, `SessionExtensions`).

---

## 👨‍💻 Kỹ năng đúc kết (Key Learnings)
- Làm chủ quy trình phát triển sản phẩm từ ý tưởng đến triển khai Cloud (**End-to-End Development**).
- Tư duy thiết kế Cơ sở dữ liệu quan hệ chặt chẽ cho các hệ thống giao dịch tài chính.
- Kỹ năng tích hợp và xử lý API/SDK từ các bên thứ ba chuyên nghiệp.
- Tối ưu hóa hiệu năng ứng dụng và bảo mật Web theo tiêu chuẩn OWASP.

---

## 📞 Thông tin Liên hệ
- **Họ và tên:** [Trần Đăng Khoa]
- **Email:** [khoatran04.it@gmail.com]
- **Tên miền dự án:** [https://os-horizon.site/](https://os-horizon.site/)
- **LinkedIn:** []

---
*© 2025 Horizon Project - Built with passion and code.*