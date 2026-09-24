Kho linh kiện thay thế
Sinh viên:
Nguyễn Phước Thành - 2374802013578 - Track AI
Học phần:
Chuyên đề Tốt nghiệp 1, HK1 2026-2027
Luồng nghiệp vụ:
L5 – Kho linh kiện thay thế
## 1. Mục tiêu
Hệ thống hỗ trợ theo dõi và quản lý tồn kho linh kiện thay thế theo từng trung tâm. 
Hệ thống cho phép ghi nhận nhập kho, xuất linh kiện cho phiếu bảo hành, theo dõi số lượng tồn 
và cảnh báo khi số lượng linh kiện xuống dưới ngưỡng tối thiểu.
## 2. Yêu cầu môi trường
Python 3.11
SQLite
Biến môi trường: xem .env.example
## 3. Hướng dẫn chạy
(BT2 yêu cầu ≤ 4 bước)
cp .env.example .env và điền giá trị
npm install
npm run db:migrate
npm run dev → mở http://localhost:3000/health
## 4. Cấu trúc thư mục
Giải thích ngắn mỗi thư mục làm gì.
## 5. Kiểm thử
npm test → hiển thị số test PASS
## 6. Trạng thái hiện tại
☑ Khởi tạo project, smoke test chạy được (buổi 2)
□ Module tiếp nhận yêu cầu (buổi 8–10)
□ Module phân công kỹ thuật viên (buổi 10–12)
