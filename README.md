# CV Website

Đây là website CV cá nhân được tạo từ template [MyCV](https://github.com/KhuongVo2105/MyCV).

## Cấu trúc project

```
myCV/
├── index.html          # File HTML chính
├── package.json        # Cấu hình project
├── css/               # Thư mục CSS
│   └── styles.css     # File CSS chính
├── js/                # Thư mục JavaScript
│   └── scripts.js     # File JS chính
├── assets/            # Thư mục tài nguyên
│   └── img/           # Hình ảnh
└── info.json          # File JSON chứa thông tin CV
```

## Cài đặt và chạy

1. Cài đặt dependencies:
```bash
npm install
```

2. Chạy development server:
```bash
npm start
# hoặc
npm run dev
```

3. Mở trình duyệt tại: http://localhost:3000

## Tùy chỉnh CV

### 1. Thông tin cá nhân
Chỉnh sửa file `index.html` để cập nhật:
- Tên
- Địa chỉ
- Số điện thoại  
- Email
- Các liên kết mạng xã hội

### 2. Hình ảnh profile
Thay thế file `assets/img/profile.jpg` bằng ảnh của bạn.

### 3. Nội dung CV
Cập nhật các section trong `index.html`:
- About (Giới thiệu)
- Education (Học vấn)
- Skills (Kỹ năng)
- Projects (Dự án)
- More (Thêm thông tin)

### 4. Sử dụng info.json
File `info.json` có thể được sử dụng để lưu trữ dữ liệu CV một cách có cấu trúc.

## Tính năng

- Responsive design (tương thích mobile)
- Smooth scrolling navigation
- Bootstrap 5 framework
- Font Awesome icons
- Modern và professional design

## Triển khai

Có thể deploy lên:
- GitHub Pages
- Netlify
- Vercel
- Hoặc bất kỳ hosting service nào

## Tác giả gốc

Template gốc được tạo bởi [KhuongVo2105](https://github.com/KhuongVo2105/MyCV)
