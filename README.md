# Mẫu trang ứng dụng dùng thử – Xưởng Skill AI

Giao diện một công cụ AI cho video: dán link/kéo thả video, bộ công cụ, khung video mẫu, danh sách dự án.
Đây chỉ là **giao diện mẫu** (chưa xử lý video thật). Làm bằng TanStack Start + React + Tailwind + shadcn/ui.

Tên công cụ, dự án và ảnh là mẫu (ảnh tạm: nhân vật Sophia Nguyễn của Xưởng Skill AI; video mẫu là khung SVG
"Video của bạn"). Hãy thay bằng nội dung của bạn: `src/routes/index.tsx`, `src/assets/`.

## Chạy thử

```sh
npm install
npm run dev
npm run build
```

## Đưa lên mạng

Trang này là **trang tĩnh**, không cần máy chủ.

1. Chạy `npm install` (một lần) rồi `npm run build`.
2. Máy sinh ra thư mục `dist/client` (chỉ gồm html, css, js, ảnh).
3. Kéo-thả **thư mục `dist/client`** lên Netlify Drop (app.netlify.com/drop), hoặc Vercel, hoặc Cloudflare Pages (Upload assets). Không cần cài thêm công cụ nào.

## Hướng dẫn và hỗ trợ

Hướng dẫn từng bước và hỗ trợ có trong skill tương ứng trên sàn https://xuongskillai.vercel.app

## Ảnh và giấy phép

Ảnh nhân vật Sophia Nguyễn là của Xưởng Skill AI, chỉ để minh họa — thay bằng ảnh của bạn. Xem giấy phép trong file `LICENSE`.
