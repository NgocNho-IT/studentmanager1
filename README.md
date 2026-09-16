# Hướng Dẫn Kiểm Thử Ứng Dụng

Sau khi chạy dự án Spring Boot (port 8080), bạn kiểm thử hệ thống qua 2 phần dưới đây:

---

## 1. Test API bằng Swagger UI

* **Đường dẫn:** `http://localhost:8080/swagger-ui/index.html` (hoặc `http://localhost:8080/swagger-ui.html`)
* **Cách thực hiện:**
  1. Chọn API cần test (`GET`, `POST`, `PUT`, `DELETE`).
  2. Bấm nút **Try it out**.
  3. Nhập dữ liệu (JSON body hoặc ID/keyword).
  4. Bấm **Execute** và xem kết quả trả về (`Response body` và HTTP Code `200 OK`).

---

## 2. Test Giao Diện Web

* **Đường dẫn:** `http://localhost:8080/index.html`
* **Cách thực hiện:**
  1. Mở trình duyệt web bất kỳ.
  2. Dán link trên vào thanh địa chỉ rồi nhấn **Enter**.
  3. Thao tác trực tiếp trên giao diện: thêm mới, tìm kiếm, sửa và xóa sinh viên.