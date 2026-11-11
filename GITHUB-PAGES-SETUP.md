# FastWeb96 - GitHub Pages

این پروژه برای GitHub Pages آماده شده است.

## Deploy
- Repository name: `fastweb96`
- Branch: `main`
- Workflow: `.github/workflows/deploy.yml`
- Build command: `npm run build`
- Output: `dist/`

## نکته دامنه
در اولین Deploy، مسیر Repository به شکل `https://USERNAME.github.io/fastweb96/` است.
Workflow فعلی با `VITE_BASE_PATH=/fastweb96/` برای همین آدرس تنظیم شده است.

وقتی دامنه اختصاصی `.ir` را متصل کردید، مقدار `VITE_BASE_PATH` را به `/` تغییر دهید و دوباره Deploy کنید.
