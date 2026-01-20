# Portfolio Website - Nguyen Thieu Huy

Đây là website portfolio cá nhân được thiết kế đơn giản, chuyên nghiệp và responsive.

## 🌟 Tính năng

- ✅ Thiết kế hiện đại, tối giản
- ✅ Responsive design (desktop, tablet, mobile)
- ✅ Dark mode tự động (theo system preferences)
- ✅ Animations mượt mà
- ✅ SEO-friendly với meta tags
- ✅ Performance tối ưu
- ✅ Accessibility (a11y) tốt

## 📁 Cấu trúc file

```
portfolio/
├── index.html          # Trang chủ
├── projects.html       # Danh sách dự án
├── publications.html   # Bài báo nghiên cứu
├── experience.html     # Kinh nghiệm làm việc
├── blog.html          # Blog cá nhân
├── cv.html            # CV/Resume
├── styles.css         # CSS styling
├── CV.pdf             # CV PDF file
└── avatar.svg         # Ảnh đại diện (placeholder)
```

## 🚀 Cách sử dụng

1. **Thêm ảnh đại diện:**
   - Đổi tên ảnh của bạn thành `avatar.jpg` và đặt trong thư mục portfolio
   - Hoặc cập nhật đường dẫn `src="avatar.jpg"` trong các file HTML

2. **Cập nhật thông tin:**
   - Mở các file HTML và thay thế thông tin cá nhân
   - Cập nhật links GitHub, LinkedIn, email
   - Thêm/sửa projects, publications theo nhu cầu

3. **Chạy website:**
   - Mở file `index.html` bằng trình duyệt
   - Hoặc dùng Live Server extension trong VS Code

## 🎨 Tùy chỉnh

### Thay đổi màu sắc
Mở `styles.css` và chỉnh sửa CSS variables:

```css
:root{
  --bg:#ffffff;        /* Màu nền */
  --text:#111827;      /* Màu chữ */
  --link:#0b57d0;      /* Màu link */
  --border:#e5e7eb;    /* Màu viền */
  --panel:#fafafa;     /* Màu panel */
}
```

### Thêm/Xóa sections
Chỉnh sửa trong phần navigation của các file HTML:

```html
<nav class="topnav__links">
  <a href="publications.html">Publications</a>
  <a href="projects.html">Projects</a>
  <a href="experience.html">Experience</a>
  <a href="blog.html">Blog</a>
  <a href="cv.html">CV</a>
</nav>
```

## 🌐 Deploy

Bạn có thể deploy website lên:
- **GitHub Pages**: Free hosting cho static sites
- **Netlify**: Deploy tự động từ GitHub
- **Vercel**: Hỗ trợ tốt cho static sites
- **Cloudflare Pages**: Fast và free

### Deploy với GitHub Pages:
1. Tạo repository mới trên GitHub
2. Upload các file lên repository
3. Vào Settings → Pages
4. Chọn branch `main` và folder `/` (root)
5. Website sẽ có địa chỉ: `https://username.github.io/repository-name`

## 📝 To-Do

- [ ] Thêm ảnh avatar.jpg
- [ ] Cập nhật links cho projects (GitHub repos, demos)
- [ ] Thêm links cho publications (papers, slides)
- [ ] Viết blog posts
- [ ] Thêm Google Analytics (nếu cần)
- [ ] Thêm contact form (nếu cần)

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS với variables, grid, flexbox
- **Vanilla JavaScript**: Minimal JS cho dynamic year
- **Google Fonts**: Inter font family

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 📄 License

Free to use for personal portfolio.

---

**Made with ❤️ by Nguyen Thieu Huy**
