# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session15_Ex13
### Phần 1 – Thiết lập Hybrid Workflow

1. **Mất ổ cứng:** Không sao cả vì Auto Sync đã đẩy bản mới nhất lên Cloud theo thời gian thực.
2. **3 bước cài Auto Sync:**
* Cài app Google Drive/OneDrive lên máy.
* Kéo thư mục dự án vào thư mục Cloud vừa tạo.
* Bật đồng bộ tự động và đợi hiện tích xanh.


3. **Khôi phục file Word bị xóa 2 trang:** Click chuột phải vào file trên Cloud > Chọn *Lịch sử phiên bản (Version History)* > Chọn mốc 10 phút trước > Bấm *Khôi phục*.
4. **Sai lầm & Xử lý:**
* Đồng bộ `node_modules` (hàng vạn file nhỏ gây nghẽn): Cho vào danh sách bỏ qua (`.gitignore`).
* Kéo phim 4K nặng vào thư mục chung: Tách ra để lưu ở ổ cứng cá nhân.



---

### Phần 2 – Phân quyền chia sẻ an toàn

1. **Bảng phân quyền:**
* **Báo cáo gửi giảng viên:** Quyền `Viewer` - Phạm vi `Restricted` (Chỉ cho thầy đọc, tránh bị sửa đè).
* **Slide nhóm 5 người:** Quyền `Editor` - Phạm vi `Restricted` (Để cùng sửa chung nhanh chóng).
* **Góp ý bản nháp cho anh khóa trên:** Quyền `Commenter` - Phạm vi `Restricted` (Chỉ cho để lại nhận xét).
* **Thông tin cá nhân (CCCD, SĐT):** Quyền `Viewer` - Phạm vi `Restricted` (Bảo mật tuyệt đối).


2. **Quy tắc Cờ Đỏ:** Không bao giờ kết hợp *Anyone with the link* + *Editor* cho file nhạy cảm vì người lạ có thể vào sửa hoặc xóa sạch dữ liệu.
3. **2 thao tác chống rủi ro trong Settings:** Tắt quyền tự mời người lạ của Editor và chặn tải xuống/sao chép nếu cần.

---

### Phần 3 – Tổ chức giao tiếp nhóm

1. **3 lỗi trong chat:** Mắc bệnh No-Hello ("có ai rảnh không"), tin nhắn trôi vì thả ảnh mèo, và spam `@all` lúc nửa đêm.
2. **2 Channel trên Lark:** `#01-thong-bao` (Trưởng nhóm đăng lịch/deadline) và `#02-dev` (Trao đổi code chuyên môn).
3. **Viết lại tin nhắn của Lan:** *"Mọi người ơi, em đang làm phần viết báo cáo tổng quan. Em đang vướng đoạn sơ đồ khối, em gửi file nháp đính kèm đây nhé. Mọi người xem giúp em trước 15h chiều nay để em kịp nộp bài nha."*
4. **Hẹn giờ tin nhắn (Schedule Send):** Đặt lịch gửi lúc 8h sáng hôm sau và đổi `@all` thành tag tên bạn Nam, bạn Hoa.

---

### Phần 4 – Thông báo tổng hợp

 **[#thong-bao-chung]** 📢 Chào cả nhà, mình đã setup xong không gian làm việc:
 1. Đã bật **Auto Sync** thư mục dự án lên Cloud, dữ liệu an toàn 100%.
 2. Đã gửi file báo cáo cho giảng viên đúng quyền **Viewer / Restricted**.
 3. `@Nam` và `@Hoa` check lại tiến độ phần việc trong channel `#02-dev` để hoàn thành nốt trước deadline nhé!
 
