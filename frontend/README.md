# Frontend Client - Theater Management System

<details>
<summary><b>🇻🇳 Hiển thị Tiếng Việt (Vietnamese)</b></summary>

## Giới thiệu
Đây là Ứng dụng Desktop Frontend cho Hệ thống Quản lý Rạp chiếu phim.
Giao diện người dùng được phát triển bằng **JavaFX 25** và thư viện **MaterialFX 11.13.6**, mang lại trải nghiệm hiện đại và mượt mà.

## Công nghệ & Công cụ yêu cầu
| Công nghệ | Phiên bản/Chi tiết |
|---|---|
| **Java** | 24 |
| **Framework** | JavaFX 25 |
| **Thư viện UI** | MaterialFX 11.13.6 |
| **Xác thực / Dữ liệu** | JWT (jjwt 0.11.5), Jackson, PostgreSQL |
| **Cấu hình** | dotenv-java 3.2.0 |

## Tải và Cài đặt
Di chuyển vào thư mục frontend:
```bash
cd frontend
```

## Cách chạy ứng dụng

### 1. Biến môi trường
Tạo file `.env` ở thư mục gốc của frontend hoặc cấu hình trên máy của bạn:
| Biến | Mô tả |
|---|---|
| `API_BASE_URL` | URL cơ sở của Backend API (ví dụ: `http://localhost:8080/api`) |
| `DB_URL` | URL CSDL PostgreSQL (nếu kết nối trực tiếp) |

### 2. Các lệnh khởi chạy
Sử dụng Maven để build và chạy ứng dụng:
```bash
# Build dự án
mvn clean install

# Chạy giao diện người dùng
mvn javafx:run
```

</details>

<details open>
<summary><b>🇬🇧 Show English (Default)</b></summary>

## Introduction
This is the Desktop Client Frontend for the Theater Management System.
The user interface is developed using **JavaFX 25** and the **MaterialFX 11.13.6** library, providing a modern and responsive experience.

## Tech Stack & Required Tools
| Tech Stack | Version/Details |
|---|---|
| **Java** | 24 |
| **Framework** | JavaFX 25 |
| **UI Library** | MaterialFX 11.13.6 |
| **Auth / Data** | JWT (jjwt 0.11.5), Jackson, PostgreSQL |
| **Config** | dotenv-java 3.2.0 |

## Download and Install
Navigate to the frontend directory:
```bash
cd frontend
```

## How to Run

### 1. Environment Variables
Create a `.env` file in the frontend root or set these environment variables:
| Variable | Description |
|---|---|
| `API_BASE_URL` | Backend API Base URL (e.g. `http://localhost:8080/api`) |
| `DB_URL` | PostgreSQL Database URL (if direct connect is needed) |

### 2. Commands
Use Maven to build and run the application:
```bash
# Build the project
mvn clean install

# Run the UI
mvn javafx:run
```

</details>
