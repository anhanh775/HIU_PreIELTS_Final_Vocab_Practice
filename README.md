# Học Từ Vựng Pre-A1 - HIU_DBP_PRE_2601

Trang web tĩnh (một file `index.html`), không cần build.

## Đưa lên GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<tên-bạn>/<tên-repo>.git
git push -u origin main
```

## Deploy lên Netlify
1. Vào https://app.netlify.com → **Add new site** → **Import an existing project**.
2. Chọn GitHub và chọn repo vừa tạo.
3. Build command: để trống. Publish directory: `.` (đã cấu hình sẵn trong `netlify.toml`).
4. Bấm **Deploy**.
