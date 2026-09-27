# Backend API - Theater Management System

<details>
<summary><b>🇻🇳 Hiển thị Tiếng Việt (Vietnamese)</b></summary>

## Giới thiệu
Đây là Backend API cho Hệ thống Quản lý Rạp chiếu phim, cung cấp các API RESTful an toàn và quản lý nghiệp vụ hệ thống.
Được xây dựng với **Spring Boot 3.5.6**, kết hợp với **Spring Security (OAuth2, JWT)**, và **Spring Data JPA**.

## Công nghệ & Công cụ yêu cầu
| Công nghệ | Phiên bản/Chi tiết |
|---|---|
| **Java** | 21 |
| **Spring Boot** | 3.5.6 |
| **Cơ sở dữ liệu** | PostgreSQL 42.7.3 |
| **Bảo mật** | Spring Security, OAuth2, JWT (jjwt 0.11.5) |
| **ORM** | Spring Data JPA, Hibernate (hypersistence-utils 3.7.3) |

## Tải và Cài đặt
Trước tiên, hãy chắc chắn rằng bạn đã thiết lập một cơ sở dữ liệu PostgreSQL.
Di chuyển vào thư mục backend:
```bash
cd backend
```

## Cách chạy ứng dụng

### 1. Biến môi trường
Cấu hình các biến môi trường sau trong hệ thống của bạn hoặc trong IDE:
| Biến | Mô tả |
|---|---|
| `SPRING_DATASOURCE_URL` | URL JDBC CSDL (ví dụ: `jdbc:postgresql://localhost:5432/theater`) |
| `SPRING_DATASOURCE_USERNAME` | Tên người dùng CSDL |
| `SPRING_DATASOURCE_PASSWORD` | Mật khẩu CSDL |
| `JWT_SECRET` | Khóa bí mật dùng để mã hóa JSON Web Tokens |

### 2. Các lệnh khởi chạy
Sử dụng Maven wrapper có sẵn để build và chạy ứng dụng:
```bash
# Build dự án
./mvnw clean install

# Chạy ứng dụng
./mvnw spring-boot:run
```

</details>

<details open>
<summary><b>🇬🇧 Show English (Default)</b></summary>

## Introduction
This is the Backend API for the Theater Management System, providing secure RESTful APIs and handling the core business logic.
Built with **Spring Boot 3.5.6**, featuring **Spring Security (OAuth2, JWT)**, and **Spring Data JPA**.

## Tech Stack & Required Tools
| Tech Stack | Version/Details |
|---|---|
| **Java** | 21 |
| **Spring Boot** | 3.5.6 |
| **Database** | PostgreSQL 42.7.3 |
| **Security** | Spring Security, OAuth2, JWT (jjwt 0.11.5) |
| **ORM** | Spring Data JPA, Hibernate (hypersistence-utils 3.7.3) |

## Download and Install
First, ensure you have set up a PostgreSQL database instance.
Navigate to the backend directory:
```bash
cd backend
```

## How to Run

### 1. Environment Variables
Configure the following environment variables in your system or IDE:
| Variable | Description |
|---|---|
| `SPRING_DATASOURCE_URL` | Database JDBC URL (e.g. `jdbc:postgresql://localhost:5432/theater`) |
| `SPRING_DATASOURCE_USERNAME` | Database username |
| `SPRING_DATASOURCE_PASSWORD` | Database password |
| `JWT_SECRET` | Secret key for JSON Web Tokens |

### 2. Commands
Use the provided Maven wrapper to build and run the application:
```bash
# Build the project
./mvnw clean install

# Run the application
./mvnw spring-boot:run
```

</details>
