# Portfolio cá nhân – FIT4014

**Sinh viên:** Nguyễn Trọng Phúc  
**Mã số sinh viên:** 1671020251  
**Trường:** Đại học Đại Nam  
**Ngành:** Công nghệ thông tin  
**Học phần:** FIT4014 – Thiết kế web và triển khai hệ thống phần mềm  
**GitHub:** [tphuc2311](https://github.com/tphuc2311)  
**Website:** [https://tphuc2311.github.io/portfolio-fit4014/](https://tphuc2311.github.io/portfolio-fit4014/)

## 1. Giới thiệu dự án

Đây là website portfolio cá nhân dạng tĩnh, được xây dựng để giới thiệu thông tin sinh viên, định hướng học tập, kỹ năng đang rèn luyện và một số nhóm bài tập thực hành. Dự án sử dụng HTML5, CSS3 và JavaScript thuần, không yêu cầu framework hoặc quy trình build.

## 2. Mục tiêu

- Thực hành xây dựng cấu trúc và giao diện website.
- Tổ chức mã nguồn thành các thư mục, tệp rõ ràng.
- Sử dụng Git và GitHub để lưu trữ, theo dõi các lần cập nhật.
- Viết tài liệu README, nhật ký sử dụng AI và ghi chú phiên bản.
- Triển khai website tĩnh bằng GitHub Pages.

## 3. Công nghệ sử dụng

| Công nghệ | Vai trò trong dự án |
|---|---|
| HTML5 | Xây dựng cấu trúc nội dung và các khu vực của trang |
| CSS3 | Thiết kế màu sắc, bố cục, hiệu ứng và giao diện responsive |
| JavaScript | Điều khiển menu trên màn hình nhỏ và cập nhật năm hiện tại |
| Git | Theo dõi lịch sử thay đổi mã nguồn |
| GitHub | Lưu trữ repository và quản lý phiên bản |
| GitHub Pages | Triển khai website để truy cập công khai |

## 4. Cấu trúc thư mục

```text
portfolio-fit4014/
├── index.html
├── README.md
├── AI_LOG.md
├── RELEASE_NOTES.md
├── .nojekyll
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── main.js
```

## 5. Các khu vực và chức năng chính

1. **Trang đầu:** giới thiệu ngắn gọn sinh viên và liên kết đến các khu vực nội dung.
2. **Giới thiệu:** trình bày thông tin học tập và mã số sinh viên.
3. **Kỹ năng:** giới thiệu các kiến thức đang học và thực hành về HTML/CSS, JavaScript, Git/GitHub.
4. **Dự án học tập:** giới thiệu website portfolio và các nhóm bài tập cơ sở dữ liệu, lập trình hướng đối tượng.
5. **Định hướng:** nêu mục tiêu củng cố kiến thức, thực hành dự án và cải thiện quy trình làm việc.
6. **Liên hệ:** cung cấp liên kết GitHub cá nhân và repository dự án.
7. **Tương tác:** menu điều hướng có thể mở/đóng trên màn hình nhỏ; năm ở chân trang được cập nhật tự động bằng JavaScript.

## 6. Chạy website trên máy cá nhân

- Tải repository về máy hoặc giải nén gói mã nguồn.
- Mở thư mục dự án trong Visual Studio Code.
- Mở `index.html` trực tiếp bằng trình duyệt. Có thể sử dụng tiện ích Live Server để thuận tiện khi chỉnh sửa.
- Không cần cài đặt npm package hoặc chạy lệnh build.

## 7. Repository và triển khai GitHub Pages

Repository: <https://github.com/tphuc2311/portfolio-fit4014>  
Website: <https://tphuc2311.github.io/portfolio-fit4014/>

Cấu hình triển khai được thực hiện tại **Settings → Pages**:

- Source: `Deploy from a branch`.
- Branch: `main`.
- Folder: `/(root)`.

Sau khi đẩy commit lên nhánh `main`, GitHub Actions sẽ thực hiện quy trình build và deployment của GitHub Pages. Có thể xem trạng thái trong thẻ **Actions** hoặc mục **Deployments** của repository.

## 8. Quy trình cập nhật mã nguồn

Mở Terminal tại thư mục repository đã clone và chạy:

```bash
git status
git add .
git commit -m "docs: hoàn thiện nội dung portfolio"
git push origin main
```

Nếu repository đã được cấu hình remote, không cần chạy lại `git remote add origin`. Có thể kiểm tra địa chỉ remote bằng:

```bash
git remote -v
```

## 9. Kiểm thử trước khi nộp

- [ ] Mở website bằng URL GitHub Pages.
- [ ] Kiểm tra các liên kết điều hướng đến đúng khu vực.
- [ ] Kiểm tra menu mở/đóng trên màn hình nhỏ.
- [ ] Kiểm tra bố cục trên máy tính và điện thoại, bảo đảm không tràn ngang.
- [ ] Kiểm tra liên kết GitHub và repository.
- [ ] Mở Developer Tools, kiểm tra Console và Network để phát hiện lỗi.
- [ ] Đối chiếu nội dung dự án với bài làm thực tế để bảo đảm có thể giải thích khi giảng viên hỏi.

## 10. Giới hạn của sản phẩm

- Đây là website tĩnh, chưa có backend, cơ sở dữ liệu trực tuyến hoặc chức năng đăng nhập.
- Phần dự án học tập mô tả các nhóm bài thực hành; khi thuyết trình cần sử dụng đúng bài làm cụ thể đã thực hiện.
- Website không công khai email cá nhân; kênh liên hệ hiện tại là GitHub.

## 11. Tác giả

- **Họ và tên:** Nguyễn Trọng Phúc
- **Mã số sinh viên:** 1671020251
- **Trường:** Đại học Đại Nam
- **Ngành:** Công nghệ thông tin
- **Học phần:** FIT4014
- **GitHub:** <https://github.com/tphuc2311>

---

*Tài liệu được cập nhật cùng mã nguồn dự án. Người thực hiện cần tự kiểm tra website đã triển khai và bảo đảm nội dung trình bày phản ánh đúng sản phẩm thực tế.*
