# Trang Web Giới Thiệu Cá Nhân - Portfolio Nguyễn Tấn Tài

## 📁 Cấu Trúc Dự Án

```
Web/
├── index.html              # Trang chủ
├── resume.html             # Trang resume/CV
├── projects.html           # Danh sách dự án
├── assets/
│   ├── css/
│   │   └── style.css       # Stylesheet chính
│   ├── js/
│   │   └── script.js       # JavaScript chính
│   └── images/             # Thư mục hình ảnh (chưa dùng)
└── README.md               # File này
```

## 🌐 Các Trang Web

### 1. **index.html** - Trang Chủ
- Hero section với giới thiệu cá nhân
- Section về kỹ năng (6 kỹ năng chính)
- Phần thông tin cá nhân
- Form liên hệ

### 2. **resume.html** - Trang Resume
- Thông tin học vấn chi tiết
- Các kỹ năng kỹ thuật
- Kinh nghiệm làm việc
- Danh sách các dự án tiêu biểu
- Chứng chỉ và giải thưởng
- Nút in/tải resume

### 3. **projects.html** - Trang Dự Án
- Lưới hiển thị 6 dự án
- Bộ lọc theo ngôn ngữ (All, C++, Python, Web)
- Thông tin chi tiết của từng dự án
- Thống kê dự án (số lượng, ngôn ngữ, dòng mã, hoàn thành)

## 🎨 Thiết Kế

### Màu Sắc (Color Scheme)
- **Primary**: #2563eb (Blue)
- **Secondary**: #64748b (Slate)
- **Background**: #f8fafc
- **Text**: #1e293b

### Font
- Primary: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Modern, dễ đọc, phù hợp cho Portfolio

### Responsive Design
- Mobile-first approach
- Breakpoints: 768px (tablet), 480px (mobile)
- Grid layout responsive
- Flexible navigation

## 💻 Tính Năng

### HTML
- ✅ Semantic HTML5
- ✅ Meta tags cho SEO
- ✅ Viewport configuration
- ✅ Accessibility attributes

### CSS
- ✅ CSS Grid & Flexbox
- ✅ Responsive design
- ✅ Smooth transitions & animations
- ✅ Hover effects
- ✅ Print styles

### JavaScript
- ✅ Navigation active state
- ✅ Contact form validation
- ✅ Projects filtering
- ✅ Smooth scroll
- ✅ Scroll animation
- ✅ Intersection Observer
- ✅ Counter animation

## 🚀 Cách Sử Dụng

### 1. Mở Trang Web
- Double-click vào `index.html` hoặc
- Sử dụng Live Server trong VS Code

### 2. Điều Hướng
- Sử dụng navbar để chuyển giữa các trang
- Các liên kết được đánh dấu active khi đang xem

### 3. Tương Tác
- **Resume**: Click "In/Tải Resume" để in hoặc lưu PDF
- **Projects**: Sử dụng các nút lọc để xem dự án theo category
- **Contact**: Điền form để gửi tin nhắn (hiện chỉ hiển thị alert)

## 📱 Responsive Breakpoints

| Device | Width | Notes |
|--------|-------|-------|
| Desktop | > 768px | Full layout |
| Tablet | 768px - 480px | Grid adapts |
| Mobile | < 480px | Single column |

## 🔧 Tự Customize

### Thay Đổi Thông Tin Cá Nhân
1. Mở `index.html`, `resume.html`, `projects.html`
2. Tìm và thay thế:
   - "Nguyễn Tấn Tài" → Tên của bạn
   - "25127493" → MSSV của bạn
   - Email, điện thoại, địa chỉ

### Thay Đổi Màu Sắc
- Mở `assets/css/style.css`
- Chỉnh sửa CSS variables ở phần `:root`
```css
--primary-color: #2563eb;
--primary-hover: #1d4ed8;
/* ... các màu khác */
```

### Thêm Dự Án Mới
- Copy một `project-card` trong `projects.html`
- Thay đổi thông tin và data-category
- Cập nhật icon emoji

### Thêm Hình Ảnh
- Upload hình vào `assets/images/`
- Thay thế `.image-placeholder` bằng `<img>` tag

## 📚 Cấu Trúc File CSS

```css
/* 1. Global Styles */
/* 2. Navigation */
/* 3. Hero Section */
/* 4. Buttons */
/* 5. Skills Section */
/* 6. About Section */
/* 7. Contact Section */
/* 8. Resume Section */
/* 9. Projects Section */
/* 10. Footer */
/* 11. Responsive Design */
/* 12. Print Styles */
```

## 🎯 Tính Năng JavaScript

### Navigation
- Tự động đặt active link dựa trên current page
- Smooth scroll khi click anchor links

### Contact Form
- Validation cơ bản
- Email format check
- Alert khi submit thành công

### Projects Filter
- Filter by category (All, C++, Python, Web)
- Smooth animation
- Update active button state

### Animations
- Intersection Observer cho scroll animations
- Fade in effect khi scroll
- Counter animation cho stats

## 🌟 Điểm Nổi Bật

1. **Hiện Đại**: Design clean, professional
2. **Responsive**: Hoạt động tốt trên mọi thiết bị
3. **Interactive**: Các tương tác mượt mà
4. **SEO Friendly**: Semantic HTML, meta tags
5. **Printable**: Resume có thể in/lưu PDF
6. **Fast**: Lightweight, tối ưu hóa

## 📝 Lưu Ý

- Contact form hiện chỉ hoạt động locally (cần backend để lưu data)
- Các link demo/mã nguồn trong projects trỏ đến "#" (cần cập nhật)
- Chưa có hình ảnh thực (dùng placeholder emoji)
- Social links cần cập nhật URL

## 🔗 Liên Kết Liên Quan

- [HTML5 Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)

## 👨‍💻 Tác Giả

**Nguyễn Tấn Tài**
- MSSV: 25127493
- Email: taintran.it@gmail.com
- Lớp: 25C09

---

**Tạo ngày**: 2026
**Phiên bản**: 1.0
**License**: Free to use and modify

---

Chúc bạn thành công với trang web giới thiệu cá nhân! 🎉
