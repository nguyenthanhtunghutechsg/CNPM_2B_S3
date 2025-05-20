# Dự án MERN

## Giới thiệu
Đây là một dự án full-stack sử dụng **MERN stack** (MongoDB, Express.js, React, Node.js). Dự án cung cấp một nền tảng cơ bản để xây dựng ứng dụng web, bao gồm giao diện người dùng (React) và API backend (Express.js, Node.js) kết nối với cơ sở dữ liệu MongoDB.

Ứng dụng này phù hợp cho các dự án như quản lý người dùng, blog, hoặc các ứng dụng CRUD.

## Công nghệ sử dụng
- **MongoDB**: Cơ sở dữ liệu NoSQL.
- **Express.js**: Framework cho API backend.
- **React**: Thư viện xây dựng giao diện người dùng.
- **Node.js**: Môi trường runtime cho backend.

## Yêu cầu
- **Node.js**: Phiên bản 14.x hoặc cao hơn.
- **MongoDB**: Cài đặt cục bộ hoặc sử dụng MongoDB Atlas.
- **npm** hoặc **yarn**: Quản lý gói phụ thuộc.
- Trình duyệt web (Chrome, Firefox, v.v.).

## Cài đặt

### 1. Clone repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Cài đặt phụ thuộc
#### Backend
```bash
cd server
npm install
```

#### Frontend
```bash
cd client
npm install
```

### 3. Cấu hình biến môi trường
Tạo file `.env` trong thư mục `server` với nội dung:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```
Thay `your_mongodb_connection_string` bằng chuỗi kết nối MongoDB (từ MongoDB Atlas hoặc cục bộ).

### 4. Chạy dự án
#### Backend
```bash
cd server
npm start
```
Backend chạy trên `http://localhost:5000`.

#### Frontend
```bash
cd client
npm start
```
Frontend chạy trên `http://localhost:3000` và tự động mở trong trình duyệt.

## Cấu trúc thư mục
```plaintext
your-repo/
├── client/                 # Frontend (React)
│   ├── public/             # File tĩnh
│   ├── src/                # Mã nguồn React
│   └── package.json
├── server/                 # Backend (Node.js + Express)
│   ├── routes/             # Định tuyến API
│   ├── models/             # Mô hình MongoDB
│   ├── controllers/        # Logic xử lý
│   └── package.json
├── .gitignore
└── README.md
```

## Sử dụng
- Truy cập `http://localhost:3000` để sử dụng giao diện React.
- Gọi API tại `http://localhost:5000/api` (xem tài liệu API trong `server/routes`).

## Đóng góp
- Mở issue trên GitHub để báo lỗi hoặc đề xuất tính năng.
- Gửi pull request với các thay đổi của bạn.

## Giấy phép
Dự án sử dụng [MIT License](LICENSE).
