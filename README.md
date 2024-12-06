# NFT Marketplace and Auction Platform

## Mục lục
1. [Giới thiệu](#giới-thiệu)  
2. [Tính năng chính](#tính-năng-chính)  
   - [Mua bán và đấu giá NFT](#1-mua-bán-và-đấu-giá-nft)  
   - [Quản lý bộ sưu tập NFT](#2-quản-lý-bộ-sưu-tập-nft)  
   - [Hồ sơ người dùng](#3-hồ-sơ-người-dùng)  
   - [Quản lý và điều hướng giao diện](#4-quản-lý-và-điều-hướng-giao-diện)  
   - [Quản lý dữ liệu NFT](#5-quản-lý-dữ-liệu-nft)  
3. [Công nghệ sử dụng](#công-nghệ-sử-dụng)  
4. [Hướng dẫn triển khai](#hướng-dẫn-triển-khai)  

---

## Giới thiệu
Dự án này là một nền tảng mua bán và đấu giá NFT, cung cấp các tính năng quản lý bộ sưu tập NFT, hồ sơ người dùng, và giao diện thân thiện với người dùng. Được xây dựng để đáp ứng nhu cầu ngày càng cao của cộng đồng blockchain, nền tảng tập trung vào hiệu suất, bảo mật, và trải nghiệm sử dụng.

---

## Tính năng chính

### 1. Mua bán và đấu giá NFT
**Thành phần liên quan:**
- **Bid (Đấu giá):**
  - Hiển thị và quản lý các phiên đấu giá NFT.
  - Thông tin bao gồm avatar của người đấu giá và chi tiết NFT.

- **Card (Thẻ sản phẩm):**
  - Hiển thị từng NFT dưới dạng thẻ.
  - Bao gồm hình ảnh, tên NFT, giá cả, và trạng thái đấu giá.

- **Trending (Xu hướng):**
  - Danh sách các NFT nổi bật hoặc được quan tâm nhiều nhất trên thị trường.

### 2. Quản lý bộ sưu tập NFT
**Thành phần liên quan:**
- **Collection (Bộ sưu tập):**
  - Tạo và quản lý các bộ sưu tập NFT của người dùng hoặc marketplace.

### 3. Hồ sơ người dùng
**Thành phần liên quan:**
- **Profile (Hồ sơ):**
  - Quản lý thông tin người dùng như avatar, xác thực 2FA, và trạng thái tài khoản.

- **Dashboard (Bảng điều khiển):**
  - Hiển thị tổng quan tài khoản, các giao dịch, NFT sở hữu, và bộ sưu tập.

### 4. Quản lý và điều hướng giao diện
**Thành phần liên quan:**
- **Header (Tiêu đề):**
  - Thanh điều hướng chính, bao gồm thông báo, chế độ sáng/tối, và avatar.

- **Sidebar (Thanh bên):**
  - Menu truy cập nhanh các mục:
    - Dashboard
    - Hồ sơ
    - Đấu giá
    - Bộ sưu tập
    - Cài đặt tài khoản

- **Settings (Cài đặt):**
  - Tùy chỉnh giao diện và thay đổi thông tin tài khoản.

### 5. Quản lý dữ liệu NFT
**Thành phần liên quan:**
- **API Route:**
  - Xử lý và cung cấp dữ liệu NFT giữa client và server.
  - Ví dụ: Lấy thông tin giá, tên, và trạng thái đấu giá.

---

## Công nghệ sử dụng
- **Ngôn ngữ:** TypeScript, JavaScript.  
- **Frontend:** Next.js, React.js, Tailwind CSS.  
- **Backend:** Node.js, API Routes.  
- **Công cụ hỗ trợ:** PostCSS, Docker, Fly.io.  
- **Quản lý mã nguồn:** Git.  

---

## Hướng dẫn triển khai

### Yêu cầu hệ thống
- **Node.js:** >= 16.x  
- **Git:** >= 2.30  

### Các bước triển khai
1. **Clone dự án:**
   ```bash
   git clone https://github.com/ZATS2/solanamarketplace.git
   cd solanamarketplace
2. **Cài đặt dependencies:**
   ```bash
   npm install
3. **Khởi động ứng dụng:**
    ```bash
   npm run dev
