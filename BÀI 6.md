


# Phần 1 :
## Sai lầm của Nam 
- Dùng định dạng trình bày cho kho lưu trữ mã nguồn`.docx` được thiết kế in ấn, không hiển thị trực tiếp trên GitHub  
=> nhóm không xem được nhanh. 
-  **Không biết tệp Word là dạng nhị phân** Sửa 1 dấu phẩy => Github  ghi nhận toàn file thay đổi => dễ xung đột,lỗi xảy ra 
 ## Bẫy Nam mắc phải 
 
 | Tình huống | File `.docx` | File `.md` | 
 |---|---|---| 
 | Mất 1 byte khi truyền |  Hỏng hoàn toàn cấu trúc nén bị vỡ, không mở được | Chỉ lỗi 1 ký tự, nội dung còn lại vẫn đọc bình thường |
  | Tại sao | Chứa siêu dữ liệu và cấu trúc gói nén phức tạp | Chỉ văn bản thuần, không đóng gói |
 
 ## Tại sao Markdown lại an toàn và nhẹ hơn.
- **Nhẹ**: Không có dữ liệu định dạng ẩn => kích thước nhỏ, truyền nhanh 
- **Bền bỉ**: Độc lập phần mềm, mọi trình duyệt đều mở được 
- **Git thân thiện**: `diff` chính xác từng dòng, dễ giải quyết xung đột 
-  **Hư hại**: hỏng một phần không ảnh hưởng toàn bộ tài liệu

# Phần 2 : 
 
 ##  Dự án GreenTech 
 ### Giới thiệu GreenTech . Hướng tới ứng dụng công nghệ vào bảo vệ môi trường => giúp cuộc sống xanh và bền vững 
 ### Mục tiêu 
 - [x] Phân loại rác tự động bằng AI bằng cảm biến => tái chế hiệu quả hơn, giảm chôn lấp 
 - [x] Công nghệ chuyển rác thành năng lượng => đốt rác tạo điện, giảm thể tích rác thải 
 - [x] Theo dõi vòng đời sản phẩm bằng mã QR => khuyến khích tái sử dụng, giảm đồ dùng một lần 
 - [x] Chất liệu thay thế: sinh học, dễ phân hủy => hạn chế nhựa khó phân hủy
### Cấu trúc 
 
 | Thành phần | Chức năng | 
 |---|---|
  | Cảm biến | Thu thập dữ liệu môi trường  | 
  | Bộ điều khiển | Xử lý & ra lệnh | 
  | Bơm nước | Thực thi  | 
  | Giao diện | Theo dõi & điều khiển từ xa | 







