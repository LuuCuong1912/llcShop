# 🛒 PROJECT GUIDE

> **Project:** LCShop  
> **Author:** Lưu Cường  
> **Mentor:** Anh T (ChatGPT)  
> **Project Type:** Portfolio Project  
> **Start Date:** Tháng 7/2026

---

# ⚠️ AI Instructions

Nếu bạn là AI (ChatGPT, Claude, Gemini...)

Đây là dự án đang được phát triển theo Sprint.

Trước khi trả lời hãy đọc toàn bộ file này.

Không được đề xuất làm lại từ đầu.

Không được bỏ qua các quyết định thiết kế đã được chốt.

Luôn đóng vai trò Senior Developer + Mentor.

Ưu tiên giải thích tư duy thay vì đưa code hoàn chỉnh.

Nếu có thay đổi kiến trúc hãy giải thích lý do.

---

# 1. Project Vision

LCShop là dự án website bán đồ công nghệ được xây dựng nhằm mô phỏng quy trình phát triển phần mềm trong doanh nghiệp.

Đây không chỉ là một website bán hàng mà còn là dự án Portfolio để xin việc vị trí Frontend Developer / Fullstack Developer.

Cũng như là dự án đánh dấu quá trình học tập và trưởng thành của Cường từ một sinh viên mới tốt nghiệp trở thành một Fullstack Developer.

Toàn bộ hệ thống được tự phân tích, tự thiết kế và tự phát triển theo quy trình doanh nghiệp.

Mục tiêu của dự án không phải code nhanh mà là hiểu toàn bộ quy trình từ phân tích nghiệp vụ, thiết kế UI/UX, thiết kế Database, xây dựng Frontend, Backend và triển khai sản phẩm.

Mục tiêu cuối cùng là xây dựng một Portfolio chất lượng để ứng tuyển vào vị trí Frontend Developer hoặc Fullstack Developer.

---

# 2. Target Customer

Khách hàng mục tiêu:

- Sinh viên mới lên TP.HCM học tập.
- Người cần mua thiết bị công nghệ phục vụ học tập.
- Người muốn mua sản phẩm với giao diện đơn giản, dễ sử dụng.

---

# 3. Development Philosophy

Nguyên tắc phát triển dự án:

- Không code theo video.
- Không copy source.
- Hiểu trước khi code.
- Mỗi quyết định thiết kế đều phải có lý do.
- Phát triển theo Sprint giống doanh nghiệp.
- Mỗi Sprint chỉ tập trung vào một mục tiêu.

---

# 4. Current Progress

## Sprint 0

Completed

- Vision
- Feature List
- User Roles
- Business Flow

---

## Sprint 1

Completed

- Sitemap
- Home Wireframe
- Product Detail Wireframe
- Checkout Wireframe

---

## Sprint 2

Current

Database Design (ERD)

---

# 5. Business Analysis

Guest

Có thể:

- Xem trang chủ
- Xem sản phẩm
- Tìm kiếm sản phẩm
- Đăng ký
- Đăng nhập

Guest KHÔNG được:

- Đặt hàng
- Thanh toán
- Đánh giá
- Xem lịch sử đơn hàng

---

Customer

Có thể:

- Quản lý hồ sơ
- Thêm vào giỏ hàng
- Thanh toán
- Theo dõi đơn hàng
- Đánh giá sản phẩm

---

Admin

Có thể:

- Quản lý sản phẩm
- Quản lý danh mục
- Quản lý thương hiệu
- Quản lý đơn hàng
- Quản lý khách hàng
- Quản lý tồn kho
- Quản lý đánh giá

---

# 6. Business Flow

Guest

↓

Home

↓

Browse Products

↓

Login / Register

↓

Customer

↓

Product Detail

↓

Add To Cart

↓

Checkout

↓

Payment

↓

Order Success

↓

Shipping

↓

Receive Product

↓

Review Product

---

# 7. Completed Wireframes

- Home Page
- Product Detail
- Checkout

---

# 8. Database Progress

Completed Tables

- Users
- Categories
- Brands
- Products
- Product Images

In Progress

- Product Specifications

Next

- Cart
- Cart Items
- Orders
- Order Items
- Reviews
- Payments

---

# 9. Architecture Decisions

Decision 001

Category

1 -> N Product

Reason

Một Category có nhiều Product.

Một Product chỉ thuộc một Category.

Status

Accepted

---

Decision 002

Brand

1 -> N Product

Reason

Một Brand có nhiều Product.

Một Product chỉ thuộc một Brand.

Status

Accepted

---

Decision 003

Product

1 -> N Product Images

Reason

Một sản phẩm có nhiều hình ảnh.

Status

Accepted

---

Decision 004

Không sử dụng bảng ProductDetail.

Sử dụng ProductSpecifications.

Reason

Mỗi loại sản phẩm có thông số kỹ thuật khác nhau.

Status

Accepted

---

Decision 005

Product Specifications

Reason

Các loại sản phẩm có thông số kỹ thuật khác nhau, thiết kế này linh hoạt và tránh nhiều cột NULL.

Status

Accepted

---

# 10. Current Learning

Đã hiểu

- Business Flow
- Sitemap
- Wireframe
- One To Many
- Foreign Key
- Parent Child Table

Đang học

- Database Design
- Database Normalization

Chưa học

- React
- TypeScript
- API
- Authentication
- Backend

---

# 11. Coding Rules

- snake_case cho tên bảng và cột.
- Primary Key luôn là id.
- Foreign Key luôn có dạng *_id.
- created_at và updated_at cho các bảng chính.
- Không code khi chưa hiểu nghiệp vụ.

---

# 12. Current Task

Hoàn thiện Database Design.

Thiết kế đầy đủ ERD.

---

# 13. Next Task

- Hoàn thiện toàn bộ ERD.
- Chuẩn hóa Database.
- Khởi tạo React.
- Học React Fundamentals.
- Thiết kế Component.
- Kết nối API.

---

# 14. Mentor Notes

Mentor: Anh T

Định hướng dự án:

Đây là dự án được xây dựng theo hướng doanh nghiệp.

Mỗi bước phải:

- Phân tích.
- Thiết kế.
- Review.
- Sau đó mới code.

Ưu tiên hiểu tư duy thay vì học thuộc.

Không viết code khi chưa hiểu Database.

---

# 15. Session Log

## 2026-07-18

Hoàn thành:

- Vision
- Business Flow
- Sitemap
- Wireframes
- Bắt đầu thiết kế Database.

Hiểu:

- One To Many.
- Foreign Key.
- Category không chứa Product.
- Product chứa Category.
- Brand độc lập với Category.
- Product Images là bảng con của Product.

Next Session:

Tiếp tục hoàn thiện ERD.
