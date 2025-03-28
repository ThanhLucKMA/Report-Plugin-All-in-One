# Chuyển dữ liệu website WordPress bằng Plugin All-in-One WP Migration
- All-in-One WP Migration là một plugin rất phổ biến và mạnh mẽ dành cho WordPress, giúp người dùng dễ dàng di chuyển hoặc sao lưu toàn bộ dữ liệu website từ một nơi này sang nơi khác. Plugin này hỗ trợ di chuyển toàn bộ các yếu tố trong website, bao gồm:
    + **Cơ sở dữ liệu** (database)
    + **Các tệp tin media** (hình ảnh, video, tài liệu)
    + **Theme** (giao diện)
    + **Plugin** (tiện ích mở rộng)
    + **Các cài đặt** khác liên quan đến website
### Sao lưu dữ liệu website WordPress cũ
- Truy cập vào quản trị admin website WordPress để bắt đầu sao lưu (backup) dữ liệu: chọn `Plugins` → `Add New Plugin`.
- Search `All-in-One WP Migration` → `Install` → `Active Plugin`
#### 
![text](./Imagers/Cai_dat_All_in_One.png)
- Sau khi kích hoạt thành công, vào Plugin `All-in-One WP Migration` → `Export Site To`.
####
![text](./Imagers/ExportSiteTo.png)
- Tại `Export Site To` → `FILE` và chờ tiến trình sao lưu hoạt động (khoản 5 – 30 phút, tùy vào dung lượng website).
####
![text](./Imagers/Export-File.png)
- Quá trình export file 
#### 
![text](./Imagers/Qua_trinh_EpFile.png)
- Chọn `Close` để hoàn tất quá trình sao lưu toàn bộ dữ liệu trên website của bạn.
- Tại `Plugin All-in-One WP Migration` → `Backups` → `Download` để tải file backup về máy tính lưu trữ.
####
![text](./Imagers/Download_File_Backup.png)

---
### Restore website từ file backup 
### Cách 1: Ta có thể backup ngay trên bản backup còn lưu trên plugin: trong `All-in-One WP Migration` → `Backup` → `Restore`
![text](./Imagers/Download_File_Backup.png)
### Cách 2: Import file download mà ta đã download lúc backup về máy 
#### Bước 1: Trong `All-in-One WP Migration` → `Import` → `Import From` → `File` → Sau đó trở đến thư mục lưu file backup .wpress
![text](./Imagers/Import_file_bakup.png)
![text](./Imagers/Qua_trinh_import.png)
#### Bước 2: Chọn `PROCEED` → `FINISH` để hoàn thành 
![text](./Imagers/Screenshot%20from%202025-03-27%2021-16-16.png)
![text](./Imagers/Screenshot%20from%202025-03-27%2021-18-18.png)



