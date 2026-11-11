# BÀI LÀM – HACKATHON 01

- **Mã đề:** 20
- **Họ tên:** TRần Thái Huy
- **Lớp:** KS26_CNTT1
- **Link repository:** https://github.com/IT101-CNTT-KS26/HCM_KS26_CNTT1_Nhap_mon_CNTT_Hackathon02
- **Hệ điều hành (Windows/macOS):** WINDOWS

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
pwd 
ls -Force
mv huong_dan_van_hanh.txt .\docs\
mkdir backup
rm *.tmp
cd D:\starter-kit\bai-xe-website\logs
ls -Force
cd ..
Get-ChildItem -Recurse -Force


```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
 Directory: D:\starter-kit\bai-xe-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/11/2026   8:27 AM                backup
d-----        11/11/2026   8:05 AM                data
d-----        11/11/2026   8:12 AM                docs
d-----        11/11/2026   8:03 AM                evidence
d-----        11/11/2026   8:06 AM                logs
d-----        11/11/2026   7:49 AM                web
------         11/3/2026   7:06 AM             73 .env
-a----        10/27/2026   1:32 AM           2230 bai_lam.md


    Directory: D:\starter-kit\bai-xe-website\backup


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         11/3/2026   7:06 AM           6132 Luot_Gui_Xe_Thang 2.xlsx


    Directory: D:\starter-kit\bai-xe-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         11/3/2026   7:06 AM           6132 Luot_Gui_Xe_Thang 2.xlsx


    Directory: D:\starter-kit\bai-xe-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         11/3/2026   7:06 AM            155 huong_dan_van_hanh.txt


    Directory: D:\starter-kit\bai-xe-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         11/3/2026   7:06 AM            977 Gate.log


    Directory: D:\starter-kit\bai-xe-website\web


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11/11/2026   7:49 AM                images
------         11/3/2026   7:06 AM            600 app.js
------         11/3/2026   7:06 AM            533 index.html
------         11/3/2026   7:06 AM            460 style.css


    Directory: D:\starter-kit\bai-xe-website\web\images


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
------         11/3/2026   7:06 AM           3089 logo-parkeasy.png


```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
Select-String "status=500" .\logs\Gate.log > .\logs\loi_500.txt
Get-Content logs/loi_500.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
logs\Gate.log:3:2026-02-28 08:08:39 POST /api/cho-trong status=500
logs\Gate.log:7:2026-02-28 08:23:23 POST /api/cho-trong status=500

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/hoa_don_salon_thang_11.xlsx`, không cần ghi vào đây.
