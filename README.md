# Soạn hồ sơ niêm yết cấp GCN – UBND xã Lãnh Ngọc

Công cụ chạy trên trình duyệt (một file `index.html`, không cần cài đặt hay máy chủ) để soạn bộ hồ sơ niêm yết cấp Giấy chứng nhận và xuất ra file Word (.docx).

## Cách dùng chung (GitHub Pages)

1. Tạo repo mới trên GitHub (ví dụ `soan-ho-so-niem-yet-gcn`), tải toàn bộ file trong thư mục này lên nhánh `main`.
2. Vào **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
3. Sau 1–2 phút, mọi người mở link: `https://<tên-tài-khoản>.github.io/<tên-repo>/`

## Lưu ý

- Cần có mạng khi mở lần đầu: công cụ tải thư viện JSZip từ `cdn.jsdelivr.net` để nén và xuất file .docx.
- Hồ sơ lưu trong `localStorage` của từng trình duyệt, không gửi đi đâu. Mỗi người chỉ thấy hồ sơ trên máy của mình.
- Khối **Hồ sơ** (cột trái): **Lưu** / **Lưu mới** để giữ hồ sơ vào danh sách, **Mở để sửa** (hoặc bấm đúp) để lấy lại thông tin sau này, **Nhân bản**, **Xóa**, **+ Hồ sơ mới**.
- Nên bấm **Xuất file** định kỳ để sao lưu (.json); dùng **Nhập file** để khôi phục hoặc chuyển sang máy khác. Xóa dữ liệu trình duyệt sẽ mất danh sách hồ sơ nếu chưa sao lưu.
- Không commit file hồ sơ thật (họ tên, CCCD, địa chỉ...) lên repo công khai.
