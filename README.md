# Hệ Thống Quản Lý Điều Phối Giao Hàng (TMS & Hub Logistics)

Hệ thống quản lý giao hàng đa vai trò (Admin, Trưởng bưu cục/Manager, Tài xế/Driver) dành cho bưu cục và kho vận logistics.

## 🚀 Hướng Dẫn Tải Code Lên GitHub & Deploy Vercel

### Cách 1: Xuất Trực Tiếp Bằng AI Studio (Nhanh Nhất)
1. Trong giao diện AI Studio, bấm vào menu **Settings / Export** ở góc trên bên phải.
2. Chọn **Export to GitHub** hoặc **Download ZIP**.
3. Nếu chọn **Export to GitHub**, hệ thống sẽ tự động khởi tạo repository trên tài khoản GitHub của bạn.

### Cách 2: Push Thủ Công Lên GitHub Từ Máy Tính
1. Giải nén file ZIP (hoặc tải mã nguồn về máy).
2. Mở terminal tại thư mục dự án và chạy các lệnh:
```bash
git init
git add .
git commit -m "Initial commit - Logistics TMS"
git branch -M main
git remote add origin https://github.com/TênTàiKhoản/TênRepo.git
git push -u origin main
```

---

## ⚡ Hướng Dẫn Deploy Lên Vercel

1. Đăng nhập vào [Vercel.com](https://vercel.com).
2. Bấm nút **Add New...** -> **Project**.
3. Kết nối với tài khoản **GitHub** và chọn Repository vừa tạo.
4. Tại phần **Framework Preset**, Vercel sẽ tự động nhận diện là **Vite**.
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
5. Bấm **Deploy**. Vercel sẽ tự động build và cấp cho bạn đường link (domain) công khai chính thức!

---

## 💻 Chạy Local Trên Máy Tính

1. Cài đặt dependencies:
```bash
npm install
```

2. Khởi động môi trường phát triển:
```bash
npm run dev
```
Truy cập tại: `http://localhost:3000` hoặc port được chỉ định trong console.

3. Kiểm tra build trước khi deploy:
```bash
npm run build
```
