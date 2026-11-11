
Hướng dẫn Chức năng 1: Tìm điểm trung tâm & Đường đi
Phân tích đồng thời danh sách nhiều thửa bản đồ con từ file Excel (map.thuamia.xlsx), xác định tâm tập hợp và tính khoảng cách từ điểm gốc (19.896058, 105.403892).

Nhập danh sách Excel: Tải lên file .xlsx / .xls có cột External ID, Mã số và Geom.
Tâm Ngôi Sao Đỏ: Tự động tính tọa độ trung tâm trọng lượng của toàn bộ các thửa đang bật và ghim ngôi sao đỏ nhấp nháy trên bản đồ.
Định tuyến từ Tọa độ gốc: Nhập tọa độ gốc hoặc bấm "Chấm trên bản đồ" để vẽ đường đi thực tế (OSRM) và đường chim bay.
Hướng dẫn Chức năng 2: Chỉnh sửa bản đồ đa thửa
Cho phép nhập file Excel nhiều thửa, chọn từng thửa để sửa ranh giới và tính toán lại diện tích (m², ha), chu vi (m) tức thì.

Chọn thửa cần sửa: Bấm nút "Sửa" ở danh sách bên trái hoặc click trực tiếp vào hình đa giác của thửa đó trên bản đồ.
Kéo thả & Chèn đỉnh: Giữ chuột vào các mốc đánh số (1..N) để dịch chuyển, hoặc bấm dấu (+) ở giữa cạnh để tách cạnh.
Lưu & Xuất Excel: Nhấn "Lưu thửa" sau khi sửa xong, sau đó bấm "Xuất Excel (5 Cột)" để tải toàn bộ danh sách đã cập nhật.
Quy chuẩn Xuất File Excel & Điều khiển Menu Trượt
File Excel xuất ra tuân thủ đúng cấu trúc 6 cột chuẩn hóa để phục vụ báo cáo quản lý vùng nguyên liệu và hành chính đất đai:

Cột A (External ID):
Mã định danh hệ thống
Cột B (Mã số):
TCT014240, TCT015975...
Cột C (Tên):
Điểm canh tác / Tên chủ
Cột D (Geom):
Chuỗi GeoJSON Polygon
Cột E (Centerpoint):
Vĩ độ, Kinh độ tâm
Cột F (Quãng đường):
km (Làm tròn 1 số, VD: 1.4)
Cột G (Diện tích):
m² (VD: 6479.8)
