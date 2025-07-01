# jmeter
# 📊 Load Testing of APIs with JMeter

## 🗓️ Ngày Kiểm Thử
7/01/2025

## 👤 Người Kiểm Thử
Phạm Thị Vân Anh

---

## 🎯 1. Mục Tiêu Kiểm Thử
Sử dụng Apache JMeter để kiểm tra hiệu năng cơ bản của một trang web và xác minh khả năng hoạt động của công cụ JMeter.

---

## 🧪 2. Môi Trường Kiểm Thử
- Công cụ: Apache JMeter
- Hệ điều hành: [Tùy hệ điều hành đang dùng: Windows/macOS/Linux]
- Phiên bản JMeter: 5.6.3 (khuyến nghị ghi rõ nếu biết)

---

## 🔧 3. Phương Pháp Kiểm Thử
- **Kiểm thử tự động**: thông qua các kịch bản cấu hình sẵn trong JMeter (.jmx)
- **Kiểm thử thủ công**: quan sát, cấu hình và theo dõi kết quả test trực tiếp

---

## 📑 4. Kịch Bản Kiểm Thử Lần 1

### 🔹 Tên Kịch Bản
Kiểm thử cơ bản của 1 trang WEB

### 🔹 Mục Đích
- Kiểm tra phản hồi HTTP khi truy cập website
- Xác minh công cụ JMeter hoạt động đúng

### 🔹 Cấu Hình HTTP Request

| Thông số         | Giá trị                   |
|------------------|---------------------------|
| **Server Name**  | www.simplilearn.com       |
| **Phương thức**  | GET                       |
| **Tham số**      | Resouces, Business        |
| **Số người dùng (threads)** | 1              |
| **Ramp-up (giây)**         | 1              |
| **Loop count**             | 1              |

### 🔹 Kết Quả

| Mục                  | Giá trị                 |
|----------------------|-------------------------|
| **Kết quả mong đợi** | Gửi yêu cầu thành công  |
| **Kết quả thực tế**  | Đã gửi yêu cầu thành công |
| **Trạng thái**       | ✅ Thành công            |

---

## 📈 5. Kết quả sau khi test

> ✅ Website phản hồi với mã trạng thái HTTP thành công (200 OK)  
> ✅ Không có lỗi xảy ra trong quá trình gửi yêu cầu  
> ✅ JMeter thực hiện đúng với cấu hình (1 user, 1 request)

---

## 📂 File đính kèm (nếu có)
- `loadTest_01.jmx` – Kịch bản test
- `result_01.csv` – Kết quả test (từ Summary Report)
