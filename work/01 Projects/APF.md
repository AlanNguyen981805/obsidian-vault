

## 📊 Status

Dự-án:: 🟡 Bàn giao UAT
Tôi:: Làm CR trong ngày 20 - 21


## 🎯 Milestones
- [ ]  Fix 30 bugs trong 2.5 ngày - deadline 📅 2026-05-22


## Daily Plan
- [x] Tạo các báo cáo 01, 02, 03, 04, 05 | ⏫ 📅 2026-05-15 ✅ 2026-05-15
- [x] Fix 10 bugs | ⏫ 📅 2026-05-14 ✅ 2026-05-14
- [x] Fix bugs UAT | #doing 📅 2026-05-18 ✅ 2026-05-19
- [x] Panning dự án 📅 2026-05-18 ✅ 2026-05-19
- [x] Fix 15 bugs | #doing 📅 2026-05-19 ✅ 2026-05-20
- [ ] Hoàn thành các task CR trong hôm nay | 📅 2026-05-20 

## Stuck bugs
- [ ] Tinh tức: trường published confrim Công trả ra dạng datetime, hiện tại đang nhận date
- [ ] https://jira.apecgroup.net/browse/APFV2-2201: block Công chưa trả đủ trường 
- [ ] https://jira.apecgroup.net/browse/APFV2-2331 block Công chưa có API 
- [ ] https://jira.apecgroup.net/browse/APFV2-2330 block do Công chưa có API
- [ ] https://jira.apecgroup.net/browse/APFV2-2361 block do Công chưa có sort
- [ ] https://jira.apecgroup.net/browse/APFV2-2360 block do Công chưa làm API
- [ ] https://jira.apecgroup.net/browse/APFV2-2233 block do BE chưa có API detail
- [ ] https://jira.apecgroup.net/browse/APFV2-1998 block do BE chưa có sort
- [ ] https://jira.apecgroup.net/browse/APFV2-2123 block do BE chưa cho search theo nhãn 
- [ ] https://jira.apecgroup.net/browse/APFV2-2201 block do BE chưa có trường lưu tên file
- [ ] https://jira.apecgroup.net/browse/APFV2-1213 BE chưa xử lý 
- [ ] https://jira.apecgroup.net/browse/APFV2-789 BE chưa có sort
- [ ] https://jira.apecgroup.net/browse/APFV2-1970 BE chưa có sort
- [ ] https://jira.apecgroup.net/browse/APFV2-1947 BE chưa có sort

# CR

### 🚀 Lệnh Tạo Task Hàng Loạt Cho Dự Án Bond (APF)

> [!NOTE]
> **Hướng dẫn:** Copy toàn bộ nội dung phía dưới vào Obsidian. Các task được phân nhóm theo màn hình và tính chất logic để bạn dễ dàng quản lý bằng Kanban hoặc Tracker.

---

## 📑 1. QUẢN LÝ DANH SÁCH & XUẤT EXCEL (UI & Common Rules)
- [ ] **Task 1.1:** [UI/List] Bổ sung các trường thông tin hiển thị trên danh sách (Nguồn khai thác, Tài khoản NĐT, Ngày cấp, Nơi cấp CCCD, Mã tài sản, Ngày đáo hạn, Số hợp đồng, Ngày mua, Số tiền thanh toán, Lãi suất tại thời điểm bán).
- [x] **Task 1.2:** [UI/Filter] Chuyển trường tìm kiếm `Ngày đặt` từ Bộ lọc nâng cao ra Bộ lọc bên ngoài. ✅ 2026-05-21
- [x] **Task 1.3:** [Excel] Áp dụng *Common Rule*: Tách các cột dữ liệu đang ghép nhiều giá trị thành các cột độc lập trên file Excel khi xuất bản. ✅ 2026-05-21
- [ ] **Task 1.4:** [Excel] Bổ sung các trường mới vào file xuất Excel tương ứng với danh sách hiển thị.

---

## 🛠️ 2. MÀN HÌNH THÊM / SỬA / XEM CHI TIẾT (Form Chi Tiết)
- [ ] **Task 2.1:** [UI/Form] Bổ sung hiển thị `Ngày cấp`, `Nơi cấp CCCD` của khách hàng vào Tooltip NĐT tại các màn Thêm/Xem/Sửa.
- [ ] **Task 2.2:** [UI/Form] Thêm trường `Nguồn khai thác` vào sau trường `NTV` tại màn Thêm/Sửa và bắt buộc nhập (Required).
- [ ] **Task 2.3:** [UI/Form] Cấu hình trường `Giá trị tích lũy tối thiểu/NĐT` thành trường **Bắt buộc nhập** (Hiện tại đang không bắt buộc).
- [ ] **Task 2.4:** [UI/UX] Bổ sung validate và hiển thị Cảnh báo trùng mã gói / Thứ tự hiển thị ngay khi `onBlur` (nhập xong mã gói), không đợi nhấn Lưu mới cảnh báo.
- [ ] **Task 2.5:** [UI/Form] Bổ sung hiển thị trường `Chữ ký` cho màn hình liên quan.

---

## 🧠 3. LOGIC & VALIDATION CHẶN LỆNH (Backend & Frontend Validation)
- [ ] **Task 3.1:** [Validation] Chặn toàn bộ hành động Thêm/Sửa/Duyệt/Hủy duyệt đối với các Tài khoản ở trạng thái = `Ngừng hoạt động`.
- [ ] **Task 3.2:** [Validation] Thêm/Sửa lệnh: Validate chặn không cho thực hiện nếu `Ngày đặt của lệnh >= Ngày hết hạn`.
- [ ] **Task 3.3:** [Validation] Thêm/Sửa/Duyệt lệnh: Bổ sung rule chặn nếu `Ngày đặt lệnh < Ngày đáo hạn của tài sản`.

---

## 🔄 4. DUYỆT THAY ĐỔI & IMPORT DATA
- [ ] **Task 4.1:** [Import] Cập nhật chức năng Import NTV: Bổ sung thêm trường `Nguồn khai thác`.
- [ ] **Task 4.2:** [Validation/Duyệt] Bổ sung `Chữ ký` cho Loại thay đổi = `Đăng ký` hoặc `Cập nhật thông tin NĐT`.
- [ ] **Task 4.3:** [Validation/Duyệt] Bắt buộc nhập `Nguồn khai thác` khi thực hiện Duyệt với Loại thay đổi = `Cập nhật thông tin NĐT`.