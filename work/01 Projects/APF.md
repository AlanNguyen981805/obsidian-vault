

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
- [x] Hoàn thành các task CR trong hôm nay | 📅 2026-05-20 ✅ 2026-05-21

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

# APF Sprint Tasks

Status:: #doing Project:: [[APF]] Deadline:: 2026-05-25

---

## Tổng tiến độ

- Total: 17 CRs
- Done: 0/17
- Doing: 0
- Blocked: 0

---

## CR1 — CMS_Lệnh tích lũy / Danh sách APFV2-2386

- [ ] Bổ sung hiển thị trên danh sách: Nguồn khai thác, Tài khoản NĐT, Ngày cấp, Nơi cấp CCCD, Mã tài sản, Ngày đáo hạn, Số hợp đồng #waiting
- [x] Bổ sung xuất excel các trường trên ✅ 2026-05-21

**Note:**
- BE Chưa trả ra ngày đáo hạn

---

## CR3 — Lệnh rút tích lũy / APFV2-2388

- [x] Bổ sung hiển thị trên danh sách: Nguồn khai thác, Tài khoản NĐT, Ngày cấp, Nơi cấp CCCD, Mã tài sản, Số hợp đồng, Ngày mua HĐ, Số tiền thanh toán, Lãi suất tại thời điểm bán ✅ 2026-05-21
- [x] Bổ sung xuất excel các trường trên ✅ 2026-05-21

**Note:**

---

## CR6 — Import cập nhật NTV

- [x] Bổ sung thêm trường Nguồn khai thác trong import ✅ 2026-05-21

**Note:**
- BE cần sửa nguồn khai thác nhận trường mới
---

## CR8 — Chữ ký thay đổi NĐT APFV2-2354

- [ ] Bổ sung chữ ký cho loại thay đổi = Đăng ký #waiting 
- [ ] Bổ sung chữ ký cho loại thay đổi = Cập nhật thông tin NĐT #waiting 

**Note:**
- Đợi a Quyết bổ sung trường 
---

## CR5 — Duyệt thay đổi TT NĐT

- [ ] Nguồn khai thác bắt buộc nhập khi duyệt với Loại thay đổi = Cập nhật thông tin NĐT

**Note:**

---

## CR9 — Cột thay đổi chữ ký

- [x] Bổ sung cột "Thay đổi chữ ký" trên danh sách, hiển thị Có/Không #doing ✅ 2026-05-21

**Note:**

---

## CR10 — Chặn TK ngừng hoạt động

- [ ] Chặn Thêm/Sửa/Duyệt/Đối trừ với TK trạng thái = Ngừng hoạt động 📅 2026-05-21

**Note:**

---

## CR10 — Số dư khả dụng

- [ ] Thêm trường Số dư khả dụng trên ô số tiền (màn hình Thêm/Sửa GD)
- [ ] Chỉ hiển thị khi đã chọn NĐT và Loại GD = Rút tiền

**Note:**

---

## CR9 — Validate ngày đặt lệnh

- [x] Không cho Thêm/Sửa/Đối trừ nếu Ngày đặt lệnh >= Ngày hết hạn (Loại GD = Rút tiền về TK) ✅ 2026-05-21

**Note:**

---

## CR10 — Disable ngày GD

- [x] Disable trường Ngày GD khi Thêm/Sửa GD tiền ✅ 2026-05-21
- [x] Mặc định = Ngày hiện tại hệ thống ✅ 2026-05-21

**Note:**

---

## CR11 — Giao dịch tiền / Danh sách (APFV2-2391)

- [ ] Bổ sung trường Số tài khoản sau trường NĐT (danh sách + xuất file)
- [x] Xuất excel: tách cột ghép thành mỗi trường 1 cột (Common rule) ✅ 2026-05-21
- [x] Tách cột +/- khỏi giá trị tiền khi hiển thị và xuất file ✅ 2026-05-21

**Note:**
* BE chưa trả ra số tài khoản

---

## CR12 — Common / Xuất file excel (APFV2-2359)

- [x] Tất cả trường số phải theo định dạng số excel (dấu chấm phân cách) ✅ 2026-05-21
- [x] Fix lỗi đang xuất text số có dấu chấm thay vì số thật ✅ 2026-05-21

**Note:**

---

## CR13 — Phát hành Gói sản phẩm / Dừng huy động (APFV2-2362)

- [ ] Bổ sung tính năng Dừng huy động cho nhiều đợt PH
- [ ] Popup xác nhận hiển thị Ngày dừng huy động = Ngày T+1
- [ ] Auto update Ngày dừng huy động và chuyển trạng thái Ngừng huy động

**Note:**

---

## CR14 — Tài sản NĐT / Lịch trả lãi (APFV2-2363)

- [ ] Bổ sung dòng tổng: Tiền lãi trước thuế, Tiền thuế, Tiền lãi sau thuế
- [ ] Vị trí: trên bảng, ngang hàng nút Xuất file

**Note:**
- BE chưa trả ra data 
---

## CR15 — Danh mục NTV / Thêm Sửa (APFV2-2364)

- [x] Cảnh báo trùng Mã NTV ngay khi nhập xong ✅ 2026-05-21
- [x] Chặn lưu nếu Ngày hết hạn <= Ngày hiện tại ✅ 2026-05-21

**Note:**

---

## CR16 — Báo cáo BC02 (APFV2-2357)

- [ ] Thêm cột Ngày đặt lệnh (trước cột Ngày đáo hạn) #waiting 
- [ ] Thêm chia ô kẻ phần tổng số dư tài sản

**Note:**
* BE chưa trả ra trường ngày đặt lệnh
---

## CR17 — Quản lý tài sản / Lịch trả lãi (APFV2-2384)

- [ ] Bổ sung tiêu chí tìm kiếm: Gói sản phẩm, TCPH
- [ ] Bổ sung trường danh sách: Số tài khoản, Số ĐKSH, Ngày mua

**Note:**

---

## Ghi chú chung

- Jira filter: (paste link)
- Design: (paste link)
- Liên hệ BA:
- Liên hệ QA: