# lovecard-templates

Kho HTML tĩnh của các mẫu thiệp LoveCard (clone từ lovecard.click), phục vụ qua GitHub Pages.

- `<slug>/index.html` – mẫu trên lovecard.click (ví dụ `thiepso01/`)
- `_external/<host>/<slug>/index.html` – mẫu trên domain phụ
- `assets/`, `builder/` – ảnh, font, JS dùng chung (đường dẫn tương đối, không sửa cấu trúc)
- `.nojekyll` – để GitHub Pages phục vụ cả thư mục bắt đầu bằng `_`

Bật GitHub Pages: Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`.
URL: `https://<user>.github.io/lovecard-templates/<slug>/`
