# PROJECT DETAILS SPECIFICATION

## 1. Tên dự án
* **Tên dự án:** Hệ thống Quản lý Phòng trọ và Căn hộ cho thuê (Rental & Dormitory Management System)
* **Tên viết tắt:** StayEasy

---

## 2. Bối cảnh dự án (Project Context / Background)
Hiện nay, việc tìm kiếm phòng trọ và quản lý thông tin thuê phòng của sinh viên, người đi làm vẫn gặp nhiều bất tiện (hợp đồng giấy dễ rách/thất lạc, ghi số điện nước thủ công dễ sai sót, chuyển tiền trọ khó đối soát). Về phía chủ nhà, việc quản lý nhiều phòng và cư dân cùng lúc tốn nhiều thời gian. 
Dự án được xây dựng nhằm số hóa quy trình tìm phòng, ký hợp đồng điện tử và quản lý thu chi tiền trọ minh bạch, tiện lợi trên nền tảng web.

---

## 3. Mục tiêu dự án (Project Objectives)
* **Đối với người thuê:** Tìm phòng phù hợp theo khu vực/giá cả, đặt lịch hẹn xem phòng và theo dõi hóa đơn tiền phòng/điện nước hàng tháng trực quan.
* **Đối với chủ trọ:** Quản lý danh sách phòng trống, tự động tính tiền điện nước dựa trên chỉ số nhập vào và gửi thông báo hóa đơn tự động.
* **Về mặt kỹ thuật:** Đảm bảo dữ liệu bảo mật, hệ thống phản hồi mượt mà và áp dụng đúng quy trình CI/CD, kiểm thử tự động.

---

## 4. Phạm vi dự án (Project Scope)
* **Trong phạm vi (In-Scope):**
  * Quản lý tài khoản (Người thuê, Chủ trọ/Quản lý, Admin).
  * Đăng tin cho thuê, tìm kiếm và lọc phòng theo khoảng giá, vị trí, tiện ích.
  * Đặt lịch hẹn xem phòng online.
  * Quản lý hợp đồng thuê và danh sách thành viên trong phòng.
  * Chức năng ghi chỉ số điện, nước và tự động tính tổng tiền hóa đơn hàng tháng.
  * Gửi yêu cầu phản ánh sự cố (hỏng bóng đèn, đường ống nước...) từ người thuê tới chủ trọ.
* **Ngoài phạm vi (Out-of-Scope):**
  * Tích hợp khóa cửa thông minh (Smart Lock IoT).
  * Tích hợp hợp đồng có chữ ký số điện tử pháp lý cấp bộ ngành.

---

## 5. Các bên liên quan (Stakeholders)
| Vai trò | Đối tượng | Trách nhiệm / Kỳ vọng |
| :--- | :--- | :--- |
| **Người thuê trọ** | Sinh viên, người đi làm | Tìm phòng nhanh, minh bạch chi phí điện nước, gửi báo hỏng dễ dàng. |
| **Chủ nhà trọ** | Người cho thuê | Quản lý tình trạng phòng trống, chốt tiền phòng hàng tháng nhanh chóng. |