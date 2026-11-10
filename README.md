# bai6.4
# BÁO CÁO BÀI TẬP / ĐỒ ÁN

## THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Xuân Thịnh
- **Mã số sinh viên:** 24810320263
- **Lớp:** D19QTANM1
- **Tên môn học:** Lập trình C# / Windows Forms
- **Tên bài tập:** BÀI 6.4: HỆ THỐNG QUẢN LÝ GARAGE VÀ BẢO BƯỠNG XE Ô TÔ (GARAGE MANAGEMENT SYSTEM)
---

## KẾT QUẢ THỰC HÀNH
1. Màn hình Chính / Tổng quan hệ thống:
<img width="1162" height="794" alt="GD" src="https://github.com/user-attachments/assets/c7a83136-2689-4836-a0ea-9dab13765f8e" />

2. Màn hình Quản lý Danh mục (CRUD - Thêm/Sửa/Xóa):
<img width="1176" height="796" alt="CN1" src="https://github.com/user-attachments/assets/39c91321-4260-4f34-9de6-f316c24bdc43" />

3. Màn hình Thực thi Nghiệp vụ chính (Lập Hóa đơn / Bán hàng /Chấm công / Đặt phòng):
<img width="1178" height="792" alt="CN2" src="https://github.com/user-attachments/assets/b027f9a2-6472-4b38-8444-1b847a7339d0" />

4. Màn hình Báo cáo - Thống kê:
<img width="1189" height="789" alt="KQ1" src="https://github.com/user-attachments/assets/0cb5242a-639c-404e-aa1f-e8a0dcbeb118" />

5. Minh họa An toàn Dữ liệu (Phòng chống SQL Injection / Báo lỗi Transaction Rollback):
<img width="1175" height="436" alt="KQ2" src="https://github.com/user-attachments/assets/2746d42e-c6ea-429e-a9df-8a0b2e9d61c4" />


## HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN:
1. **Khởi tạo CSDL**:
   - Mở file `Database.sql` có sẵn trong thư mục dự án bằng SQL Server Management Studio (SSMS) hoặc Visual Studio.
   - Chạy toàn bộ script (Execute) để tự động tạo CSDL `SaleDB` cùng các bảng và dữ liệu mẫu.

2. **Cấu hình chuỗi kết nối**:
   - Mở file `Dbhelper.cs`.
   - Kiểm tra và đổi lại `Data Source` cho khớp với tên SQL Server trên máy chấm (Mặc định đang để kết nối tới `(localdb)\MSSQLLocalDB`).

3. **Chạy chương trình**:
   - Nhấn **F5** (hoặc nút Start) trên Visual Studio để chạy hệ thống.
