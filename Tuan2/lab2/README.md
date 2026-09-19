## Tóm tắt tổng kết Lab 02

_(Cập nhật lúc 22:40, 19/09/2026)_

Thông qua bài thực hành Lab 02 này, rút được những kiến thức cốt lõi sau:

1. **Làm chủ Tensor cơ bản:** Biết cách khởi tạo Tensor (`zeros`, `ones`, `rand`, `randn`), kiểm tra thông tin (`shape`, `size`, `ndim`) và định hình lại kích thước (`reshape`).
2. **Indexing & Slicing:** Biết cách trích xuất, "cắt lát" dữ liệu từ các khối, hàng, cột của ma trận.
3. **Phép toán Tensor:** Phân biệt rõ nhân từng phần tử (`*`) và nhân ma trận Đại số tuyến tính (`@`), hiểu được ý nghĩa của `dim=0` (cột) và `dim=1` (hàng).
4. **Cơ chế Autograd & Đạo hàm:** Nắm được khái niệm `requires_grad=True` để theo dõi biến và hiểu bản chất Gradient (đạo hàm) đóng vai trò như một "chiếc la bàn".
5. **Thuật toán Gradient Descent (Mô phỏng AI tự học):** Trải nghiệm thực tế quá trình máy tính tự học để tìm ra phương trình và giải hệ phương trình thông qua vòng lặp cốt lõi: `zero_grad()` (dọn nháp) -> tính `MSE` (chấm điểm) -> `backward()` (rút kinh nghiệm) -> `step()` (sửa sai).
