# Cardano Preview – SmartContract Practice

Giao diện học tập tiếng Việt cho bài Escrow và Scholarship.

## Phiên bản 0.1.0 đã có
- Giao diện responsive tiếng Việt.
- Kết nối ví Eternl theo CIP-30 để đọc địa chỉ và network ID.
- Phân tích hai tình huống Escrow 10+10 tADA và 20 tADA một lần.
- Kiểm tra ba điều kiện Scholarship ở phía trình duyệt.
- Xuất báo cáo JSON.

## Chưa có (không được coi là giao dịch thật)
- Chưa triển khai validator/SmartContract lên Cardano Preview.
- Chưa có Contract Address, Transaction Hash hoặc Transaction Fee.
- Chưa tạo, ký hay gửi giao dịch on-chain.
- Chưa kết nối dữ liệu học vụ được nhà trường xác thực.

Giao dịch thật cần validator/contract đã triển khai, logic được kiểm thử, giao dịch được xây dựng/ký/gửi bằng ví và xác minh trên Preview explorer.

## Đưa lên GitHub Pages
1. Mở repository `Nham-Pro/cardano-preview-smartcontract-practice`.
2. Chọn **Add file → Upload files**.
3. Tải lên `index.html`, `styles.css`, `app.js`, `README.md`.
4. Nhấn **Commit changes**.
5. Vào **Settings → Pages**.
6. Chọn **Deploy from a branch**, branch `main`, folder `/ (root)`, nhấn **Save**.
7. Chờ GitHub Pages hiển thị URL.

## An toàn
Không nhập seed phrase, private key hoặc spending password. Chỉ kết nối ví trên website bạn tin tưởng.
