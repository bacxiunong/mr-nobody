# Mr. Nobody

> Mr. Nobody. Come from nowhere. Here to experience life.

Trang chủ của **bacxiunong.com** — giới thiệu một màn hình, kèm menu tới các phần khác:

| Đường dẫn | Nội dung | Repo |
|---|---|---|
| `/` | Giới thiệu | `mr-nobody` (repo này) |
| `/game-dap-chuot/` | Game Đập Chuột + trang quản trị `/game-dap-chuot/admin/` | `dap-chuot` |
| `/tim-hieu-van-vo/` | Dashboard các trường phái triết học | `van-vo` |

## Cách hoạt động

Repo này giữ tên miền `bacxiunong.com` trên Vercel. File `vercel.json` **chuyển tiếp ngầm (rewrite)** hai đường dẫn con sang hai project Vercel còn lại, người xem chỉ thấy một tên miền.
`/design/*` cũng được chuyển sang project game vì game dùng chung bộ design tokens ở đó.

## File

- `index.html` — lời giới thiệu + menu
- `style.css` — tông tím xám hoàng hôn, thành phố gập ngược, chữ hiện dần
- `assets/skyline.svg` — đường chân trời thành phố vẽ bằng SVG (tự tạo)
- `vercel.json` — chuyển hướng và chuyển tiếp các đường dẫn con

## Dùng ảnh nền thật

Đặt ảnh (bạn có quyền sử dụng) vào `assets/hero.jpg`, bỏ chú thích dòng `--hero-image` trong `style.css` và thêm `class="has-photo"` vào thẻ `<body>`.
