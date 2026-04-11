# SQL_Server_2025_Duong_Kien
## Bài tập

1. Dowload và cài đặt SQL Server 2025, bản developer
   <img width="1919" height="1079" alt="Screenshot 2026-04-10 194244" src="https://github.com/user-attachments/assets/3e5c4b5a-4c51-4ae2-8937-1be83f381c80" />
2. Cấu hình cho SQL Server làm việc ở cổng động (Dynamic Port), TCP: enable+active yes cho 127.0.0.1, chọn cổng động là 56109
  <img width="1919" height="1074" alt="Screenshot 2026-04-10 194127bai_tap" src="https://github.com/user-attachments/assets/99a89e66-3a40-43d2-8bf0-a472c72635cb" />
  
3. Kiểm tra xem service SQL Server
   <img width="1911" height="1078" alt="image" src="https://github.com/user-attachments/assets/a73e47ec-62e5-45f0-b290-bab7698477c7" />
   <img width="1911" height="1078" alt="Screenshot 2026-04-10 201749(1)" src="https://github.com/user-attachments/assets/e1c043fb-7790-4ca0-a6aa-53336240981c" />
4. Cài đặt SQL Server Management Studio 22
  <img width="1906" height="1072" alt="Screenshot 2026-04-10 202600" src="https://github.com/user-attachments/assets/a6b9f599-e2da-4b6c-9136-25832c4d7375" />
5. Chạy phần mềm ssms đăng nhập vào SQL Server bằng 2 cách:
   -  Windows Authentication:
     <img width="1904" height="1078" alt="Screenshot 2026-04-11 004917(1)" src="https://github.com/user-attachments/assets/412ec35c-6c94-4558-a597-a212c0abd06e" />
    - SQL Server Authentication:
      <img width="1912" height="1078" alt="Screenshot 2026-04-11 005102(1)" src="https://github.com/user-attachments/assets/eac9eec0-dd1d-4381-8e6d-5bebf6c323e1" />
6. Sử dụng giao diện đồ hoạ của ssms: Tạo cơ sở dữ liệu mới (create database)
   <img width="1897" height="1074" alt="Screenshot 2026-04-10 211944" src="https://github.com/user-attachments/assets/2c9280ec-6685-4968-93bd-794891e9628c" />
7. Sử dụng giao diện đồ hoạ của ssms: Tạo bảng dữ liệu (create and design table)
   <img width="1910" height="1076" alt="image" src="https://github.com/user-attachments/assets/664815b5-cb9c-4509-a8b0-99cfe31ee86c" />

8. Sử dụng giao diện đồ hoạ của ssms: Import dữ liệu từ file mẫu vào trong bảng
   <img width="1910" height="1078" alt="image" src="https://github.com/user-attachments/assets/30ebb1a6-ceff-4fa8-b737-f5114827cde5" />
9. Mở cửa sổ mới để gõ lệnh trong ssms: GÕ lệnh để kiểm tra xem số dòng của bảng dữ liệu sau khi import, kết quả ok sẽ khoảng 12020 dòng.
    <img width="1916" height="1075" alt="image" src="https://github.com/user-attachments/assets/56b1c8f5-9246-4c47-8618-5107c30e8e1d" />

10. Trong cửa sổ mới để gõ lệnh: Gõ lệnh để thêm (insert) 1 row vào bảng, với dữ liệu là thông tin cá nhân của sv đang làm bài
   <img width="1911" height="1076" alt="image" src="https://github.com/user-attachments/assets/abac0805-f94b-4722-9311-f140802bbe86" />

11. Trong cửa sổ mới để gõ lệnh: Gõ lệnh để cập nhật(update) trường noisinh thành 'Sao Hoả' cho những dòng có noisinh và diachi đều là NULL.
    (Có 1438 dòng nơi sinh và địa chỉ = NULL, đã được update nơi sinh thành 'Sao Hỏa')
    <img width="1914" height="1077" alt="image" src="https://github.com/user-attachments/assets/8fd681c7-0d9e-4d1d-9895-20ce83e718ca" />
    







