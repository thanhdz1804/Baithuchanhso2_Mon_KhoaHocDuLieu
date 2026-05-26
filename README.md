# Phân cụm sinh viên bằng thuật toán KMeans

## Giới thiệu
Chương trình sử dụng thuật toán KMeans trong Python để phân cụm sinh viên thành 3 nhóm học lực gồm:
- Học lực cao
- Học lực trung bình
- Học lực thấp

Dữ liệu được đọc từ file Excel tổng hợp điểm của sinh viên. Sau khi xử lý dữ liệu và tính điểm trung bình, thuật toán KMeans sẽ tự động chia các sinh viên vào những nhóm có mức điểm tương đồng.

---

## Công nghệ sử dụng
- Python
- Pandas
- Scikit-learn
- OpenPyXL

---

## Chức năng chương trình
- Đọc dữ liệu từ file Excel
- Tính điểm trung bình sinh viên
- Phân cụm dữ liệu bằng KMeans
- Hiển thị kết quả phân nhóm
- Xuất file Excel kết quả

---

## Thuật toán KMeans
KMeans là thuật toán học máy không giám sát dùng để phân cụm dữ liệu. Thuật toán hoạt động bằng cách:
1. Chọn số cụm cần phân chia
2. Khởi tạo tâm cụm
3. Gán dữ liệu vào cụm gần nhất
4. Cập nhật lại tâm cụm
5. Lặp lại cho đến khi ổn định

Trong chương trình này, số cụm được chọn là 3 để phân chia sinh viên theo học lực.

---

## Kết quả
Sau khi chạy chương trình, hệ thống sẽ tạo file Excel gồm:
- MSSV
- Họ tên
- Điểm trung bình
- Nhóm học lực

---

## Video demo

## Link video thuyết trình https://youtu.be/nhy8nw7pN6c
