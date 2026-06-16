🌱 Hệ Thống Quản Lý và Kinh Doanh Nông Sản Trực Tuyến

📖 Tổng quan

Hệ Thống Quản Lý và Kinh Doanh Nông Sản Trực Tuyến là một nền tảng thương mại điện tử hỗ trợ quản lý, kinh doanh và phân phối các sản phẩm nông sản trên môi trường số.

Hệ thống cho phép khách hàng tìm kiếm sản phẩm, đặt hàng, thanh toán và theo dõi đơn hàng trực tuyến. Đồng thời hỗ trợ quản trị viên, nhân viên xử lý đơn hàng và nhân viên giao hàng quản lý toàn bộ hoạt động kinh doanh từ sản phẩm, tồn kho, đơn hàng đến báo cáo doanh thu.

Ngoài ra hệ thống tích hợp Trợ lý AI hỗ trợ tư vấn sản phẩm, mùa vụ, chính sách mua hàng và giải đáp thắc mắc của khách hàng.

✨ Đặc trưng

👥 Quản lý người dùng và phân quyền

        •	Đăng ký, đăng nhập, quên mật khẩu.
        
        •	Xác thực JWT.
        
        •	Phân quyền theo vai trò:

                o	ADMIN
        
                o	STAFF
        
                o	DELIVERY
        
                o	CUSTOMER

🥬 Quản lý sản phẩm nông sản

        •	Quản lý danh mục sản phẩm.
        
        •	Quản lý sản phẩm.
        
        •	Quản lý hình ảnh sản phẩm.
        
        •	Quản lý tồn kho.
        
        •	Quản lý trạng thái hiển thị sản phẩm.

🛒 Giỏ hàng và yêu thích

        •	Thêm sản phẩm vào giỏ hàng.
        
        •	Cập nhật số lượng.
        
        •	Xóa sản phẩm khỏi giỏ hàng.
        
        •	Danh sách sản phẩm yêu thích.

📦 Quản lý đơn hàng

        •	Tạo đơn hàng.
        
        •	Theo dõi trạng thái đơn hàng.
        
        •	Lịch sử trạng thái đơn hàng.
        
        •	Hủy đơn hàng.
        
        •	Phân công giao hàng.

💳 Thanh toán

        •	Thanh toán khi nhận hàng (COD).
        
        •	Chuyển khoản ngân hàng.
        
        •	Tích hợp VNPay.
        
        •	Tích hợp MoMo (có thể mở rộng).

🚚 Quản lý giao hàng

        •	Phân công nhân viên giao hàng.
        
        •	Theo dõi trạng thái giao hàng.
        
        •	Quản lý lịch sử giao hàng.

⭐ Đánh giá sản phẩm

        •	Khách hàng đánh giá sản phẩm.
        
        •	Chấm điểm và bình luận.

🔔 Thông báo

        •	Thông báo đơn hàng.
        
        •	Thông báo khuyến mãi.
        
        •	Thông báo hệ thống.

🤖 Trợ lý AI

        •	Tư vấn sản phẩm.
        
        •	Gợi ý sản phẩm thay thế.
        
        •	Hỗ trợ tra cứu đơn hàng.
        
        •	Giải đáp chính sách giao hàng và thanh toán.

📊 Báo cáo thống kê

        •	Doanh thu.
        
        •	Đơn hàng.
        
        •	Khách hàng.
        
        •	Sản phẩm bán chạy.
        
        •	Tồn kho.

📋 Yêu cầu hệ thống

Trước khi chạy dự án hãy đảm bảo đã cài đặt:

Backend

        •	Java 17+
        
        •	Maven 3.9+

Frontend
        
        •	NodeJS 20+
        
        •	npm hoặc yarn

Database

        •	MySQL 8+

Công cụ hỗ trợ

        •	Docker (khuyến nghị)
        
        •	Git
        
        •	Postman
        
        •	IntelliJ IDEA
        
        •	VS Code

🛠️ Công nghệ sử dụng

Frontend

        •	NextJS
        
        •	JavaScript
        
        •	HTML5
        
        •	CSS3
        
        •	Axios
        
        •	Context API

Backend

        •	Spring Boot
        
        •	Spring Security
        
        •	Spring Data JPA
        
        •	Hibernate
        
        •	JWT Authentication
        
        •	Lombok
        
        •	Validation API

Database

        •	MySQL

AI Assistant

        •	OpenAI API hoặc mô hình AI tương đương

DevOps

        •	Docker
        
        •	Swagger/OpenAPI

🏗️ Kiến trúc hệ thống

Frontend (NextJS)

        │
        
        ▼
        
 REST API (JSON)
 
        │
        
        ▼
        
Backend (Spring Boot)

        │
        
 ┌──────        ┴──────┐
 
 ▼                    ▼
 
MySQL                       AI Service

🗄️ Cơ sở dữ liệu

Hệ thống hiện sử dụng 21 bảng:

        users
        
        roles
        
        permissions
        
        role_permissions
        
        categories
        
        products
        
        product_images
        
        cart_items
        
        wishlists
        
        shipping_addresses
        
        orders
        
        order_items
        
        order_status_history
        
        payments
        
        coupons
        
        reviews
        
        contacts
        
        notifications
        
        chat_messages
        
        password_reset_tokens
        
        migrations

⚙️ Hướng dẫn cài đặt

1. Clone dự án

        git clone https://github.com/your-organization/nong-san-online.git
        
        cd nong-san-online

2. Thiết lập Backend

        cd backend

        mvn clean install

        mvn spring-boot:run

Backend sẽ chạy tại:

        http://localhost:8080

3. Thiết lập Frontend

        cd frontend
        
        npm install
        
        npm run dev

Frontend sẽ chạy tại:

        http://localhost:3000

4. Thiết lập MySQL

Tạo database:

        CREATE DATABASE nongsan_db;

Cập nhật:

        spring.datasource.url=jdbc:mysql://localhost:3306/nongsan_db
        
        spring.datasource.username=root
        
        spring.datasource.password=your_password

🔐 Cấu hình Environment

Backend

        DB_URL=
        
        DB_USERNAME=
        
        DB_PASSWORD=
        
        JWT_SECRET=
        
        JWT_EXPIRE=
        
        MAIL_USERNAME=
        
        MAIL_PASSWORD=

OPENAI_API_KEY=

Frontend

        NEXT_PUBLIC_API_URL=http://localhost:8080/api/v1
        
        NEXT_PUBLIC_AI_URL=

📡 API Endpoints

Authentication

        POST /api/v1/auth/register
        
        POST /api/v1/auth/login
        
        POST /api/v1/auth/forgot-password
        
        POST /api/v1/auth/reset-password

Users

        GET    /api/v1/users
        
        GET    /api/v1/users/{id}
        
        PUT    /api/v1/users/{id}
        
        DELETE /api/v1/users/{id}

Categories

        GET    /api/v1/categories
        
        POST   /api/v1/categories
        
        PUT    /api/v1/categories/{id}
        
        DELETE /api/v1/categories/{id}

Products

        GET    /api/v1/products
        
        GET    /api/v1/products/{id}
        
        POST   /api/v1/products
        
        PUT    /api/v1/products/{id}

        DELETE /api/v1/products/{id}

Cart

        GET    /api/v1/cart
        
        POST   /api/v1/cart
        
        PUT    /api/v1/cart/{id}
        
        DELETE /api/v1/cart/{id}

Orders

        POST   /api/v1/orders
        
        GET    /api/v1/orders
        
        GET    /api/v1/orders/{id}
        
        PUT    /api/v1/orders/{id}
        
        DELETE /api/v1/orders/{id}

Payments

        POST /api/v1/payments
        
        GET  /api/v1/payments/{id}

Reviews

        POST   /api/v1/reviews
        
        GET    /api/v1/reviews/product/{id}
        
        DELETE /api/v1/reviews/{id}

AI Assistant

        POST /api/v1/chat
        
        GET  /api/v1/chat/history

👤 Các vai trò hệ thống

ADMIN

        •	Quản lý người dùng.
        
        •	Quản lý phân quyền.
        
        •	Quản lý sản phẩm.
        
        •	Quản lý đơn hàng.
        
        •	Quản lý mã giảm giá.
        
        •	Quản lý báo cáo.
        
        •	Quản lý AI.

STAFF

        •	Xác nhận đơn hàng.
        
        •	Chuẩn bị hàng.
        
        •	Cập nhật tồn kho.
        
        •	Hỗ trợ khách hàng.

DELIVERY

        •	Nhận đơn giao hàng.
        
        •	Cập nhật trạng thái giao.
        
        •	Xác nhận giao thành công.

CUSTOMER

        •	Đặt hàng.
        
        •	Thanh toán.
        
        •	Theo dõi đơn hàng.
        
        •	Đánh giá sản phẩm.
        
        •	Sử dụng AI Assistant.

🔄 Quy trình hoạt động

1. Khách hàng

Đăng ký

   ↓

Đăng nhập
   ↓

Tìm kiếm sản phẩm   
   ↓

Thêm vào giỏ hàng
   ↓

Đặt hàng
   ↓

Thanh toán
   ↓

Theo dõi đơn hàng

2. Nhân viên

Nhận đơn

   ↓

Xác nhận đơn
   ↓

Chuẩn bị hàng
   ↓

Bàn giao cho shipper

3. Shipper

Nhận đơn

   ↓

Giao hàng

   ↓

Cập nhật trạng thái
   ↓

Hoàn tất

🧪 Kiểm thử

Các chức năng chính cần kiểm thử:

•	Đăng ký tài khoản.

•	Đăng nhập.

•	Tìm kiếm sản phẩm.

•	Giỏ hàng.

•	Đặt hàng.

•	Thanh toán.

•	Quản lý sản phẩm.

•	Cập nhật trạng thái đơn hàng.

•	AI Assistant.

📈 Tiêu chí nghiệm thu

•	Người dùng đăng ký và đăng nhập thành công.

•	Quản lý sản phẩm hoạt động chính xác.

•	Giỏ hàng và đơn hàng hoạt động đúng.

•	Thanh toán hoạt động ổn định.

•	AI Assistant phản hồi chính xác.

•	Dữ liệu đảm bảo toàn vẹn.

•	Giao diện responsive trên Desktop, Tablet và Mobile.

🤝 Đóng góp

1.	Fork repository.

git checkout -b feature/your-feature

2.	Commit thay đổi.

git commit -m "feat: add new feature"

3.	Push source.

git push origin feature/your-feature

4.	Tạo Pull Request.

📜 License

Dự án được phát triển phục vụ mục đích học tập, nghiên cứu và triển khai thực tế.

License: MIT License

🙏 Lời cảm ơn

