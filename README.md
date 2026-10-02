# Inventory-Management
Xây dựng hệ thống quản lý kho hàng và xuất nhập hàng
Giới thiệu

Các cửa hàng và doanh nghiệp nhỏ thường quản lý kho bằng bảng tính, dẫn đến sai lệch tồn kho, xuất vượt số lượng hiện có và khó truy vết ai đã thao tác. WMS giải quyết các vấn đề đó bằng:

Quản lý tập trung sản phẩm, phiếu nhập, phiếu xuất và điều chỉnh kho.
Ràng buộc nghiệp vụ chặt chẽ (tồn kho không bao giờ âm, SKU không trùng).
Lưu lịch sử mọi giao dịch kho để đối chiếu.
Phân quyền theo vai trò.


Tính năng
-Xác thực và phân quyền: đăng nhập, đăng xuất, giới hạn chức năng theo vai trò.
-Quản lý sản phẩm: mã SKU duy nhất, danh mục, đơn vị tính, giá, ngưỡng tồn tối thiểu.
-Nhập kho: tạo phiếu nhập, tự động cộng tồn.
-Xuất kho: tạo phiếu xuất, kiểm tra tồn trước khi xuất, chặn xuất vượt tồn.
-Điều chỉnh kho (kiểm kê): cập nhật tồn thực tế kèm lý do.
-Tồn kho: xem tồn hiện tại, cảnh báo sắp hết hàng.
-Lịch sử giao dịch: ai thao tác, thời điểm, số lượng trước và sau.
-Báo cáo: tồn kho, nhập/xuất theo kỳ, xuất ra Excel/CSV.


Vai trò và phân quyền
-Chức năng	Admin	Thủ kho	Nhân viên xem
-Quản lý người dùng	✅	❌	❌
-Quản lý sản phẩm	✅	✅	❌
-Nhập / xuất / điều chỉnh kho	✅	✅	❌
-Xem tồn kho và lịch sử	✅	✅	✅
-Xem và xuất báo cáo	✅	✅	✅


Công nghệ sử dụng

-Thành phần	Công nghệ
-Frontend	(ví dụ: React, Vite)
-Backend	(ví dụ: Node.js + Express / Spring Boot)
-Cơ sở dữ liệu	(ví dụ: PostgreSQL)
-Kiểm thử	Jest/JUnit, Postman/Newman, Playwright, k6, Lighthouse
-Triển khai	(ví dụ: Docker Compose)

Yêu cầu
(Node.js ≥ 20 / JDK 17 ...)
(PostgreSQL ≥ 15 hoặc Docker)
Git
