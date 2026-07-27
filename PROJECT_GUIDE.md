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

# LCShop - Project Guide

Version: 1.0
Project Owner: Lưu Lý Cường

---

# Project Vision

LCShop là website thương mại điện tử bán các sản phẩm công nghệ dành cho sinh viên, đặc biệt hướng đến những bạn chuẩn bị lên TP.HCM học tập.

Mục tiêu của dự án không phải chỉ tạo ra một website bán hàng mà còn là Portfolio thể hiện tư duy Software Engineering, quy trình phát triển phần mềm và khả năng Fullstack Developer.

---

# Development Philosophy

Không học theo kiểu:

"Học xong mới làm."

Mà sẽ theo phương pháp:

Phân tích → Thiết kế → Code → Review → Refactor

Mọi tính năng đều phải được phân tích trước khi viết code.

---

# Frontend Design Decisions

## UI Style

Modern

Minimal

Professional

Clean

Apple Style

Responsive

---

## Color Palette

Primary
#2563EB

Primary Hover
#1D4ED8

Secondary
#1E40AF

Background
#F8FAFC

Surface
#FFFFFF

Border
#E5E7EB

Title
#111827

Body Text
#4B5563

Placeholder
#9CA3AF

Success
#22C55E

Warning
#F59E0B

Error
#EF4444

---

## Typography

Font Family

Inter

---

## Border Radius

12px

Áp dụng cho

Button

Input

Card

Modal

Badge

---

## Shadow

Sử dụng duy nhất

shadow-md

hoặc

0 2px 8px rgba(0,0,0,.08)

Không sử dụng shadow quá lớn.

---

## Spacing

Sử dụng hệ thống 8pt.

4

8

16

24

32

40

48

64

Không sử dụng khoảng cách ngẫu nhiên.

---

## UI Components

Button

Input

Card

Navbar

Footer

Product Card

Modal

Toast

Badge

Pagination

Search Box

Category Tabs

---

## Icon

Lucide React

---

## Animation

transition:200ms

Hover Scale

1.02

Không sử dụng animation rườm rà.

---

# Frontend Architecture

React

React Router

Axios

Context API (hoặc Redux sau này nếu cần)

Folder Structure

src

components/

pages/

layouts/

routes/

services/

hooks/

contexts/

assets/

utils/

constants/

styles/

---

# Wireframe

Đã hoàn thành

Home Page

Product Detail

Cart / Checkout

Các wireframe sẽ được sử dụng làm chuẩn khi code.

---

# Backend Design Decisions

Architecture

MVC + Service Layer

Không sử dụng Repository Pattern ở phiên bản đầu.

---

# Backend Flow

Frontend

↓

Router

↓

Middleware

↓

Controller

↓

Service

↓

Model

↓

Database

↓

Model

↓

Service

↓

Controller

↓

HTTP Response

↓

Frontend

---

# Responsibility

Router

- Chỉ định tuyến.

Middleware

- Authentication

- Authorization

- Validation

Controller

- Nhận Request

- Gọi Service

- Trả Response

Không chứa Business Logic.

Service

- Chứa toàn bộ Business Logic.

Model

- CRUD Database.

Không chứa Business Logic.

Database

- Chỉ lưu dữ liệu.

---

# Backend Folder Structure

src

config/

routes/

middlewares/

controllers/

services/

models/

---

Sau này sẽ mở rộng

validators/

utils/

constants/

uploads/

---

# Config

Config sẽ chứa

Database Connection

JWT Config

CORS Config

Cloudinary Config

Environment Config

---

# Environment Variables

.env sẽ chứa

PORT

NODE_ENV

Database

JWT

Cloudinary

Email

Client URL

Không lưu dữ liệu nghiệp vụ.

Không commit lên GitHub.

---

# API Style

RESTful API

Ví dụ

GET /products

GET /products/:id

POST /products

PUT /products/:id

DELETE /products/:id

POST /login

POST /register

POST /orders

GET /orders

---

# Database Principles

Thiết kế chuẩn hóa.

Sử dụng khóa chính id.

Tên bảng số nhiều.

Ví dụ

users

products

orders

order_items

cart_items

categories

brands

product_images

Không lưu dữ liệu trùng lặp.

---

# Business Rules

Order

1 Order

↓

N OrderItems

Product

1 Product

↓

N ProductImages

Category

1 Category

↓

N Products

Brand

1 Brand

↓

N Products

User

1 User

↓

N Orders

Cart

1 User

↓

1 Cart

Cart

1 Cart

↓

N CartItems

---

# Development Rules

Không Copy Code.

Không AI Generate toàn bộ Project.

Mọi đoạn code phải hiểu trước khi Merge.

Sau mỗi Sprint phải Review.

Sau mỗi Feature phải Commit Git.

Không Fix Bug bằng Copy Paste.

---

# Git Commit Convention

feat:

fix:

refactor:

docs:

style:

chore:

---

# Code Convention

camelCase

PascalCase

Tên biến rõ nghĩa.

Không viết tắt.

Không hard-code.

---

# Design Principles

Single Responsibility

DRY

KISS

RESTful

MVC

Clean Code

---

# Goal

Không chỉ tạo ra website.

Mà tạo ra một dự án đủ chất lượng để:

Portfolio

Phỏng vấn Fresher

Phỏng vấn Junior

Có khả năng mở rộng thành Production Project.

---

# Current Progress

Sprint 0 ✅

Business Analysis

Sprint 1 ✅

Business Flow

Sprint 2 ✅

Sitemap

Sprint 3 ✅

Wireframe

Sprint 4 ✅

ERD

Sprint 5 ⏳

REST API Design

Sprint 6

Project Setup

Sprint 7

Authentication

Sprint 8

Frontend Development

Sprint 9

Backend Development

Sprint 10

Integration

Sprint 11

Testing

Sprint 12

Deployment

---

# Mentor Notes

LCShop được xây dựng theo định hướng Software Engineering thay vì chỉ học cú pháp.

Ưu tiên tư duy thiết kế hệ thống, kiến trúc phần mềm và quy trình phát triển thực tế.

Mọi quyết định kiến trúc đều phải có lý do, không thêm thành phần chỉ vì dự án mẫu có.

Code phải dễ đọc, dễ mở rộng và dễ bảo trì.

# 📅 Nhật ký dự án LCShop
## Ngày: 19/07/2026

---

# 🎯 Mục tiêu buổi học

- Hoàn thiện thiết kế Database (ERD).
- Thống nhất kiến trúc Backend.
- Thống nhất môi trường phát triển.
- Chuẩn bị bước chuyển từ giai đoạn thiết kế sang lập trình.

---

# ✅ Công việc đã hoàn thành

## 1. Database (ERD)

Đã hoàn thiện phần lớn các bảng chính của hệ thống.

Bao gồm:

- users
- products
- product_images
- product_details
- categories
- carts
- cart_items
- orders
- order_items

### Quy tắc đã thống nhất

- Category 1 - N Products
- Product 1 - N ProductImages
- Product 1 - 1 ProductDetail
- User 1 - 1 Cart
- Cart 1 - N CartItems
- User 1 - N Orders
- Order 1 - N OrderItems

Không sử dụng quan hệ N-N trực tiếp.
Nếu có quan hệ nhiều - nhiều sẽ tách thành bảng trung gian.

---

## 2. Thiết kế Product

Đã thống nhất:

products chỉ lưu thông tin hiển thị.

Ví dụ:

- tên
- giá
- thumbnail
- category
- brand
- stock
- ...

Các thông số kỹ thuật:

- CPU
- RAM
- SSD
- Bảo hành
- Model
- Kích thước màn hình

được lưu trong bảng product_details.

Mục đích:

- Database chuẩn hóa.
- Có thể mở rộng nhiều loại sản phẩm khác nhau.

---

## 3. Cart và Order

Đã phân biệt rõ.

Cart:

- Giỏ hàng tạm.
- Có thể sửa.
- Có thể xóa.
- Chưa thanh toán.

Order:

- Đơn hàng đã được tạo.
- Lưu lịch sử mua hàng.
- Không phụ thuộc vào Cart sau khi Checkout.

Checkout sẽ copy dữ liệu từ Cart sang Order.

Sau khi tạo Order thành công:

- CartItem sẽ bị xóa.
- Cart vẫn tồn tại.

---

## 4. OrderItem

Đã thống nhất.

subtotal không lưu bằng tay.

Backend sẽ tính:

subtotal = quantity × unit_price

Service chịu trách nhiệm xử lý.

---

## 5. Frontend

Đã thống nhất:

Wireframe đã đủ để bắt đầu lập trình.

Bao gồm:

- Home
- Product List
- Product Detail
- Cart / Checkout

Các Wireframe sẽ còn được cải tiến trong quá trình phát triển.

Không cần thiết kế quá hoàn hảo ngay từ đầu.

---

## 6. Backend Architecture

Đã thống nhất sử dụng:

MVC + Service Layer

Luồng xử lý:

Client

↓

Router

↓

Middleware

↓

Controller

↓

Service

↓

Model

↓

Database

Controller:

- Nhận request.
- Trả response.

Service:

- Chứa toàn bộ Business Logic.

Model:

- Làm việc trực tiếp với Database.

Middleware:

- Authentication
- Authorization
- Validation
- Logging

---

## 7. Environment

Đã thống nhất sẽ sử dụng:

Frontend

- React
- Vite

Backend

- NodeJS
- ExpressJS

Database

- MySQL

Version Control

- Git
- GitHub

---

## 8. Docker

Đã tìm hiểu.

Ưu điểm:

- Môi trường đồng nhất.
- Chạy nhanh.
- Dễ triển khai.

Tuy nhiên quyết định hiện tại:

KHÔNG sử dụng Docker.

Lý do:

Muốn học MySQL từ nền tảng trước.

Sau khi thành thạo sẽ học Docker sau.

---

## 9. MySQL

Đã gặp lỗi:

Bad Download

Temp file removed

Nguyên nhân:

Không phải lỗi MySQL Server.

Là lỗi MySQL Installer không tải được package.

Kế hoạch:

Không dùng bản ZIP.

Sẽ cài lại MySQL Community Server đúng cách.

---

# 📚 Kiến thức học được hôm nay

- Chuẩn hóa Database.
- Quan hệ 1-1.
- Quan hệ 1-N.
- Vai trò của bảng trung gian.
- Khác nhau giữa Cart và Order.
- subtotal được tính bởi Backend.
- MVC Architecture.
- Service Layer Pattern.
- Middleware.
- Docker là gì.
- Vai trò của .env.
- Quy trình phát triển Backend.

---

# 📌 Quyết định cuối cùng

LCShop sẽ sử dụng:

Frontend

- React
- Vite

Backend

- NodeJS
- ExpressJS

Architecture

- MVC + Service Layer

Database

- MySQL

ORM

(Sẽ quyết định sau)

---

# 🎯 Công việc tiếp theo

Sprint tiếp theo:

1. Cài đặt MySQL Community Server thành công.
2. Tạo Database lcshop.
3. Import Database.
4. Kiểm tra toàn bộ bảng.
5. Khởi tạo Project Backend.
6. Khởi tạo Project Frontend.

---

# 📝 Mentor Note

Không đổi công nghệ chỉ vì gặp lỗi.

Ưu tiên hiểu bản chất trước.

Mục tiêu của dự án LCShop không phải chỉ tạo ra một website.

Mục tiêu là xây dựng một dự án Fullstack theo chuẩn doanh nghiệp để sử dụng làm Portfolio khi xin việc.

# 🎯 Triết lý phát triển LCShop

LCShop không được xây dựng theo hướng "code cho chạy".

Mỗi quyết định về:

- Database
- Kiến trúc
- API
- UI
- Frontend
- Backend

đều phải có lý do.

Mục tiêu cuối cùng:

- Hiểu bản chất.
- Viết code sạch.
- Dễ mở rộng.
- Có thể bảo trì.
- Có thể đưa vào Portfolio khi xin việc.

Trong quá trình phát triển:

- Không ngại refactor.
- Không sợ sửa Database.
- Không sợ thay đổi thiết kế nếu có giải pháp tốt hơn.

Ưu tiên chất lượng hơn tốc độ.

# Sprint 8 - Backend Foundation

Ngày cập nhật: 27/07/2026

---

# Mục tiêu

Bắt đầu xây dựng Backend cho dự án LCShop theo kiến trúc MVC.

Không viết chức năng ngay mà tập trung xây dựng nền móng của hệ thống.

---

# Công việc đã hoàn thành

## 1. Khởi tạo Backend

Đã tạo thư mục:

backend/

Đã khởi tạo NodeJS project:

```bash
npm init -y
```

Sinh ra file:

- package.json

---

## 2. Cài đặt thư viện

Production:

```bash
npm install express mysql2 dotenv cors bcrypt jsonwebtoken
```

Development:

```bash
npm install -D nodemon
```

Đã hiểu mục đích của từng package:

| Package | Chức năng |
|----------|-----------|
| express | Web Framework |
| mysql2 | Kết nối MySQL |
| dotenv | Đọc biến môi trường |
| cors | Cho phép Frontend gọi API |
| bcrypt | Băm mật khẩu |
| jsonwebtoken | JWT Authentication |
| nodemon | Tự khởi động lại server khi lưu file |

---

## 3. Xây dựng cấu trúc Backend

```text
backend
│
├── src
│   ├── config
│   ├── controllers
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── services
│   ├── utils
│   ├── app.js
│   └── server.js
│
├── .env
├── .gitignore
├── package.json
└── package-lock.json
```

---

## 4. Ý nghĩa từng thư mục

### config

Chứa toàn bộ cấu hình hệ thống.

Ví dụ:

- Database
- JWT
- Cloudinary

---

### controllers

Nhận Request.

Gọi Service.

Trả Response.

Không xử lý Business Logic.

---

### services

Là nơi xử lý toàn bộ Business Logic của hệ thống.

Ví dụ:

- Tính tổng tiền
- Kiểm tra tồn kho
- Kiểm tra quyền
- Kiểm tra Voucher

---

### models

Chỉ làm việc với Database.

Thực hiện:

- SELECT
- INSERT
- UPDATE
- DELETE

Không chứa Business Logic.

---

### routes

Khai báo API.

Ví dụ:

GET /products

POST /login

POST /orders

---

### middlewares

Chạy trước Controller.

Ví dụ:

- Authentication
- Authorization
- Validate Request
- Upload File
- Logger

---

### utils

Các hàm dùng chung.

Ví dụ:

- Format tiền
- Format ngày
- Generate Order Code

---

## 5. File .env

Là file chứa các thông tin cấu hình và dữ liệu nhạy cảm.

Ví dụ:

```env
PORT=5000

DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=******
DB_NAME=lcshop

JWT_SECRET=your-secret-key
```

Không được commit lên GitHub.

Đã thêm vào:

.gitignore

---

## 6. Hiểu sự khác nhau giữa app.js và server.js

### app.js

Có nhiệm vụ:

- Khởi tạo Express
- Khai báo Middleware
- Khai báo Routes

Không chạy Server.

Có thể hiểu:

"Xây dựng ứng dụng."

---

### server.js

Có nhiệm vụ:

- Đọc file .env
- Import app.js
- app.listen(PORT)

Có thể hiểu:

"Khởi động ứng dụng."

---

## 7. Luồng hoạt động Backend

server.js

↓

app.js

↓

Routes

↓

Middlewares

↓

Controllers

↓

Services

↓

Models

↓

Database

---

## 8. Tư duy kiến trúc

Controller

↓

Điều phối Request/Response

Service

↓

Xử lý nghiệp vụ

Model

↓

Làm việc với Database

Mỗi tầng chỉ đảm nhận đúng một trách nhiệm.

---

# Những điều đã thống nhất

- Áp dụng mô hình MVC.
- Business Logic chỉ nằm trong Service.
- Model không chứa Business Logic.
- Controller không thao tác trực tiếp với Database.
- Middleware dùng cho Authentication, Authorization và các xử lý dùng chung.
- Cấu hình nhạy cảm phải đặt trong .env.

---

# Chưa thực hiện

- Chạy Express Server.
- Kết nối MySQL.
- Viết db.js.
- Xây dựng API đầu tiên.
- Kết nối Frontend.

---

# Kế hoạch Sprint tiếp theo

## Sprint 9

Mục tiêu:

Làm cho Backend chạy thành công.

Thực hiện:

- Viết app.js.
- Viết server.js.
- Chạy npm run dev.
- Truy cập localhost:5000.
- Hiển thị thông báo:

Welcome to LCShop Backend 🚀

Sau khi Express hoạt động ổn định sẽ chuyển sang:

Kết nối MySQL theo chuẩn MVC.

📅 Project Guide Update - Sprint 10

Ngày: 27/07/2026

✅ Hoàn thành
1. MySQL
Cài đặt thành công MySQL Workbench.
Import thành công Database lcshop.
Kết nối thành công từ Backend.
Hoàn thành config/db.js bằng Connection Pool (mysql2/promise).

Xác nhận kết nối thành công với:

✅ Connected to MySQL


2. Backend Foundation

Hoàn thành cấu trúc dự án:

backend/
│
├── config/
│     db.js
│
├── controllers/
│
├── models/
│
├── routes/
│
├── services/
│
├── middlewares/
│
├── .env
│
├── app.js
│
└── server.js

6. Tư duy phát triển API

Mỗi API đều đi theo quy trình:

Route

↓

Controller

↓

Service

↓

Model

↓

Database

↓

Model

↓

Service

↓

Controller

↓

Response

Đã thống nhất bổ sung:

constants/
constants/

httpStatus.js

messages.js

roles.js

orderStatus.js

paymentMethod.js

Mục tiêu:

Không hard-code.
Tăng khả năng bảo trì.
Dễ mở rộng.

🚀 Sprint tiếp theo
Sprint 11

Module Product

Mục tiêu

Hoàn thành API đầu tiên:

GET /api/products

Theo đúng MVC.

Thứ tự thực hiện:

1. product.route.js

↓

2. product.controller.js

↓

3. product.service.js

↓

4. product.model.js

↓

5. SELECT * FROM products

↓

6. Trả JSON

↓

7. Test bằng Postman
