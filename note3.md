## Chuong 3 
### 3.1 Cấu trúc cơ bản của CPU
- 5 chu kỳ
- Nhiệm vụ của CPU:
  +  Nhận lệnh (Fetch Instruction): CPU đọc lệnh từ bộ nhớ.
  +  Giải mã lệnh (Decode Instruction): xác định thao tác mà lệnh yêu cầu.
  +  Nhận dữ liệu (Fetch Data): nhận dữ liệu từ bộ nhớ hoặc các cổng vào-ra.
  +  Xử lý dữ liệu (Process Data): thực hiện phép toán số học hay phép toán logic với các dữ liệu.
  +  Ghi dữ liệu (Write Data): ghi dữ liệu ra bộ nhớ hay cổng vào-ra
- FI - DI - FD - PD - WD
- Cấu trúc khối của CPU Slide 219 
// giải thích các thành phần 
- Các thành phần của CPU
  + Đơn vị điều khiển (Control Unit - CU)
  + Đơn vị số học và logic (Arithmetic and Logic Unit - ALU)
  + Tập thanh ghi (Register Set - RS)
  + Đơn vị nối ghép bus (Bus Interface Unit – BIU)
  + Bus bên trong (Internal Bus)
- Các phương pháp thiết kế đơn vị điều khiển
  + Đơn vị điều khiển vi chương trình (Microprogrammed Control Unit)
  + Đơn vị điều khiển nối kết cứng (Hardwired Control Unit)
  + Đơn vị điều khiển vi chương trình 
- Tập thanh ghi 8/16/32/64 bit
- Phân loại thanh ghi
  + Thanh ghi địa chỉ: quản lý địa chỉ của ngăn nhớ hay cổng vào-ra.
  + Thanh ghi dữ liệu: chứa tạm thời các dữ liệu.
  + Thanh ghi đa năng: có thể chứa địa chỉ hoặc dữ liệu.
  + Thanh ghi điều khiển/trạng thái: chứa các thông tin điều khiển và trạng thái của CPU.
  + Thanh ghi lệnh: chứa lệnh đang được thực hiện
