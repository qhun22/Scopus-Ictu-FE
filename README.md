# Scopus-Ictu-FE

Giao diện web (React + TypeScript + Vite + Tailwind + Ant Design) của hệ thống quản lý và chuẩn hóa hồ sơ tác giả,
công bố khoa học Scopus cho ICTU. API ở repo [Scopus-Ictu-BE](https://github.com/qhun22/Scopus-Ictu-BE).

> Repo này được đồng bộ từ repo chính [Scopus-Ictu](https://github.com/qhun22/Scopus-Ictu) (commit `27db10f`). Mọi thay đổi mã nguồn làm ở repo chính.

## Chạy

```bash
npm ci
npm run dev        # Vite tại http://localhost:5173, chuyển /api sang backend (VITE_API_PROXY_TARGET)
npm run build      # kiểm tra kiểu + đóng gói
```

Biến môi trường: xem `.env.example` (`VITE_API_BASE_URL`, mặc định cùng nguồn).
