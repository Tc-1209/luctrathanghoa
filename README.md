# Link ngắn — tài khoản mới

Trang nhỏ, mở ra là **tự chuyển ngay** sang Web App của **tài khoản Google mới**. Không dùng để ghim, chỉ để link ngắn hơn.
Được xuất bản từ repo công khai `Tc-1209/luctrathanghoa` (GitHub Pages). Sửa ở đây thì chép sang repo đó.

| Link | Mở |
|---|---|
| https://tc-1209.github.io/luctrathanghoa/ | Trang chọn hệ thống |
| https://tc-1209.github.io/luctrathanghoa/ketca | Kết ca |
| https://tc-1209.github.io/luctrathanghoa/ship | Tính ship |
| https://tc-1209.github.io/luctrathanghoa/nhansu | Nhân sự |

- Đổi link `/exec` (khi tạo **bản triển khai mới**): sửa dòng `var APP_URL = …` ở **cả** `index.html` và `404.html`.
  Cập nhật code bình thường (bút chì → Phiên bản mới) thì link `/exec` **không đổi**, không cần sửa gì.
- `404.html` giống hệt `index.html`: GitHub Pages trả trang này cho `…/ketca`, `…/ship`, `…/nhansu` (không có file thật).
- Trang chỉ chứa link `/exec` (vốn đã gửi cho nhân viên); app vẫn bắt đăng nhập Google + PIN nên để công khai không lộ dữ liệu.
