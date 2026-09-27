# Theater Management System

<details>
<summary><b>🇻🇳 Hiển thị Tiếng Việt (Vietnamese)</b></summary>

## Giới thiệu
Hệ thống Quản lý Rạp chiếu phim là một giải pháp phần mềm toàn diện bao gồm Backend (API REST) và Frontend (Ứng dụng Desktop). 
- **Backend**: Xây dựng bằng Spring Boot, cung cấp các API RESTful mạnh mẽ và an toàn.
- **Frontend**: Ứng dụng Desktop hiện đại phát triển bằng JavaFX và MaterialFX.

## Công cụ yêu cầu
Để chạy dự án này, bạn cần cài đặt các công cụ sau:
- **Java Development Kit (JDK)**: Java 21 cho Backend và Java 24 cho Frontend.
- **Maven**: Công cụ quản lý dự án (Backend đã bao gồm Maven Wrapper `mvnw`).
- **PostgreSQL**: Cơ sở dữ liệu quan hệ (Phiên bản 42.7.3+).
- **Git**: Để sao chép mã nguồn.

## Tải và Cài đặt
1. Mở terminal hoặc command prompt.
2. Chạy lệnh sau để tải mã nguồn:
   ```bash
   git clone https://github.com/jimtrung/theater-management.git
   cd theater-management
   ```
3. Tạo một cơ sở dữ liệu mới trong PostgreSQL cho ứng dụng.

## Cách chạy ứng dụng

### 1. Chạy Backend
Mở một terminal mới và di chuyển vào thư mục backend:
```bash
cd backend
```
Thiết lập các biến môi trường cần thiết (ví dụ: trong cấu hình hệ thống hoặc IDE của bạn):
- `SPRING_DATASOURCE_URL`: URL kết nối JDBC tới PostgreSQL.
- `SPRING_DATASOURCE_USERNAME`: Tên người dùng cơ sở dữ liệu.
- `SPRING_DATASOURCE_PASSWORD`: Mật khẩu cơ sở dữ liệu.
- `JWT_SECRET`: Khóa bí mật dùng để mã hóa JSON Web Tokens.

Build và chạy Backend:
```bash
# Build dự án
./mvnw clean install

# Khởi chạy ứng dụng
./mvnw spring-boot:run
```

### 2. Chạy Frontend
Mở một terminal khác và di chuyển vào thư mục frontend:
```bash
cd frontend
```
Tạo file `.env` (hoặc thiết lập biến môi trường) để cấu hình:
- `API_BASE_URL`: URL của Backend API (ví dụ: `http://localhost:8080/api`).
- `DB_URL`: URL kết nối trực tiếp đến PostgreSQL (nếu cần).

Build và chạy Frontend:
```bash
# Build dự án
mvn clean install

# Khởi chạy giao diện người dùng
mvn javafx:run
```

</details>

<details open>
<summary><b>🇬🇧 Show English (Default)</b></summary>

## Introduction
The Theater Management System is a comprehensive software solution consisting of a robust Backend API and a modern Desktop Frontend.
- **Backend**: Built with Spring Boot, providing secure and powerful RESTful APIs.
- **Frontend**: A sleek Desktop application developed using JavaFX and MaterialFX.

## Required Tools
To run this project, you need the following tools installed on your system:
- **Java Development Kit (JDK)**: Java 21 for Backend and Java 24 for Frontend.
- **Maven**: Dependency and project management tool (Backend includes Maven Wrapper `mvnw`).
- **PostgreSQL**: Relational database (Version 42.7.3+).
- **Git**: For version control and cloning the repository.

## Download and Install
1. Open your terminal or command prompt.
2. Clone the repository using the following command:
   ```bash
   git clone https://github.com/jimtrung/theater-management.git
   cd theater-management
   ```
3. Create a new database in PostgreSQL for the application.

## How to Run

### 1. Running the Backend
Open a terminal and navigate to the backend directory:
```bash
cd backend
```
Set up the necessary environment variables (e.g., in your system settings or IDE):
- `SPRING_DATASOURCE_URL`: The JDBC connection URL for PostgreSQL.
- `SPRING_DATASOURCE_USERNAME`: Your database username.
- `SPRING_DATASOURCE_PASSWORD`: Your database password.
- `JWT_SECRET`: A secret key for JSON Web Token encryption.

Build and run the Backend application:
```bash
# Build the project
./mvnw clean install

# Run the Spring Boot application
./mvnw spring-boot:run
```

### 2. Running the Frontend
Open another terminal and navigate to the frontend directory:
```bash
cd frontend
```
Set up a `.env` file (or environment variables) for configuration:
- `API_BASE_URL`: The base URL for the Backend API (e.g., `http://localhost:8080/api`).
- `DB_URL`: Direct PostgreSQL database connection URL (if required).

Build and run the Frontend application:
```bash
# Build the project
mvn clean install

# Run the JavaFX UI
mvn javafx:run
```

</details>
