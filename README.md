GIỚI THIỆU CHUNG:
Game được viết bằng ngôn ngữ C++ và sử dụng thư viện SDL2

LUẬT CHƠI:
Người chơi sẽ được cấp cho một bảng kích cỡ 4x4 với 2 ô số mở đầu (mặc định là 2 số 2) những ô có cùng giá trị sẽ sát nhập vào nhau và tạo ra một ô có giá trị gấp đôi. Nhiệm vụ của người chơi là sát nhập các ô một cách khéo léo để tạo ra ô chiến thắng 2048. Bằng cách

Nhấn UP để dồn các ô lên phía trên

Nhấn DOWN để dồn các ô xuống phía dưới

Nhấn LEFT để dồn các ô sang trái

Nhấn RIGHT để dồn các ô sang bphải

Nhấn M để bật/tắt nhạc

Mỗi khi 2 ô cùng giá trị và được sát nhập điểm của người chơi sẽ được công thêm bằng đúng giá trị của ô mới được tạo ra từ việc sát nhập

CÁCH CÀI ĐẶT:
Truy cập 

Tải xuống các file và bật 2048 project.sln

Ctril F5 hoặc khởi chạy code

MÔ TẢ CHỨC NĂNG
Có nút Newgame để bắt đầu/ chơi lại ván game:
Có hệ thống âm thanh sinh động:
Lưu điểm cao mỗi lần chơi
Có nút M để tắt bật âm
Có bảng thông báo mỗi khi thắng hoặc thua
Có bảng Score cập nhập điểm liên tục và Best cập nhập điểm cao kể cả khi tắt chương trình

CÁC KĨ THUẬT LẬP TRÌNH ĐƯỢC SỬ DỤNG
Con trỏ
Class/Struct
Bắt sự kiện bàn phím, chuột
Stringstream
Cắm cờ
Sinh số ngẫu nhiên
Đọc, ghi file
Vector
Âm thanh trong SDL
Tải hình ảnh, clip trong máy lên màn hình của SDL
Tạo hình ảnh từ một text của SDL
Giải phóng bộ nhớ
String
