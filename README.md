# Bất Động Sản Sổ Đỏ — Trang tuyển dụng Môi giới

Trang landing page tuyển dụng môi giới bất động sản, thiết kế theo phong cách "hồ sơ giấy tờ / con dấu đỏ" — tông màu đất nung, rêu, nhũ đồng.

## 🚀 Deploy nhanh (GitHub → Vercel)

1. Đẩy repo này lên GitHub (đã có sẵn `index.html`).
2. Vào [vercel.com](https://vercel.com) → **Add New → Project** → chọn repo này.
3. Vercel tự nhận diện là static site, không cần Build Command / Output Directory → bấm **Deploy**.
4. Nhận link dạng `ten-repo.vercel.app`, chạy được ngay.

## 🌐 Gắn domain riêng

Vào **Project → Settings → Domains** trên Vercel, thêm domain/subdomain của bạn (ví dụ `moigioisodo.vinhgiupban.com`), sau đó tạo bản ghi **CNAME** trỏ theo hướng dẫn Vercel cung cấp tại nơi quản lý DNS.

## 📁 Cấu trúc

```
index.html      # Toàn bộ trang (HTML + CSS inline), không cần build
vercel.json     # Cấu hình deploy tĩnh cho Vercel
README.md       # File này
```

## 🛠 Việc cần làm tiếp (TODO)

- [ ] Thay 3 khung placeholder ảnh (đội ngũ / đào tạo / hoạt động) bằng ảnh thật.
- [ ] Kết nối form đăng ký với nơi lưu dữ liệu thật (email / Google Sheet / CRM) — hiện form chỉ demo `alert()`, chưa gửi dữ liệu đi đâu.
- [ ] (Giai đoạn sau) Chuyển toàn bộ nội dung này sang WordPress khi build chính thức trên host Armada.

## 📞 Liên hệ

- Hotline: 0938 121 937 (Mr. Thế Vinh)
- Zalo: https://zalo.me/0792227522
- Email: tranthevinhbdspro@gmail.com
