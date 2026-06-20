# Hồ Đắc Quang — CV (static site)

CV online dạng web tĩnh, song ngữ VN/EN.

- **`index.html`** — bản tiếng Việt (trang gốc)
- **`en.html`** — bản tiếng Anh
- Nút **VN | EN** góc trên phải để chuyển ngôn ngữ (ẩn khi in PDF)
- `anhcanhan.jpg` — ảnh chân dung (đường dẫn tương đối)
- `.nojekyll` — tắt Jekyll cho GitHub Pages

## Chạy thử local
Mở trực tiếp `index.html` bằng trình duyệt (double-click).

## Xuất PDF
Mở trang → `Ctrl + P` → *Save as PDF* → Margins: **None** → bật **Background graphics**.

## Cập nhật nội dung
Nguồn gốc nằm trong monorepo công việc: `O2O_V2/BA-draft/CV/HoDacQuang_2026_{vn,eng}.html`.
Sửa ở đó rồi copy đè `index.html` / `en.html` (giữ nguyên khối `.lang-switch`), commit lại là Pages tự cập nhật.
