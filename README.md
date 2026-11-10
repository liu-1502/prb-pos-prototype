# PRB POS — prototype

Prototype giao diện cho POS quán mamak Malaysia (RM, SST 6%, service charge 10% cho dine-in, làm tròn 5 sen). Mỗi màn là một file HTML độc lập, không build, không backend — mở thẳng bằng trình duyệt.

| File | Màn |
|---|---|
| `till.html` | Màn Till: gọi món, giỏ hàng, thanh toán, Orders, Stock, Overview của quản lý, kết ca |
| `hq-console.html` | Console phía HQ |
| `index.html` | Trang chỉ mục hai màn trên |

## Chạy thử

Mở `index.html` bằng trình duyệt, hoặc chạy một server tĩnh trong thư mục này:

```
python3 -m http.server 8777
```

rồi vào `http://127.0.0.1:8777/`.

## Đăng nhập (prototype)

PIN in sẵn ngay trên màn đăng nhập: `1234` — Aina · Cashier, `9999` — Farid · Manager. Đây là dữ liệu giả của prototype, không phải thông tin đăng nhập thật.

Quản lý vào thẳng màn **Overview**; thu ngân vào thẳng màn **Order**.

## Theme

Bốn bộ màu (đỏ mặc định, nâu, xanh lá, vàng) đổi được ở menu người dùng → Demo → Theme.

## Ảnh món

Tải từ Wikimedia Commons, giấy phép và tác giả ghi trong [`img/CREDITS.md`](img/CREDITS.md).
