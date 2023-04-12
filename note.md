-	Ngắt = tạm dừng 1 tiến trình để ưu tiên những tiến trình khác
-	Khi kết thúc 1 ct phục vụ ngắt t trình đó sẽ dc t tục thực hiện
-	Mô tả các lệnh thực hiện chương trình phục vụ ngắt /77
-	Xử lí nhiều Y cầu phục vụ ngắt ( gọi nhiều c tr con p vụ ngắt)
+ Tuần tự
+ Ngẫu nhiên (Random)
* Hoạt động vào ra dữ liệu 
-I/0: hoạt động trao đổi dữ liệu giữa module I/0 với bên trong máy tính 
-Các kiểu hoạt động I/0
+ CPU trao đổi data vs module I/0
+ Module I/O trao đổi data trực tiếp vs bộ nhớ chính 
DMAC 
1.6 BUS
1. Luồng thông tin
- Các module trong máy tính 
+CPU
+Module nhớ
+Module I/O
	Cần được kết nối với nhau
Bus là đường truyền được thiết kế để kết nối các thành phần rời rạc với nhau tạo ra hệ thống máy tính hoàn chỉnh
//Tốc độ bus thể hiện tốc độ truyền data
 Có 3 kiểu BUS : 
+ bus địa chỉ (bus address) 
+ bus data 
+ bus control
![](https://i.imgur.com/E7nn7Xi.png)

	Chipset là chíp đk trung tâm trên bo mạch chủ, các mainboard có 2 chip set 
#### 

/90 
BT:
Hệ thống CPU32bit kết nối dc tới bộ nhớ có dung lg tối đa là bn 
CPU32BIT tương ứng bit rate 32bit tương ứng 32 đg truyền (độ rộng)
=> Bộ nhớ tối đa là 2^32 byte
Ttự vs hệ thống CPU64BIT => Bộ nhớ tối đa bằng 2^64 byte

### BUS data /91 
ngta mở rộng bus data nhằm mục đích gì, vì sao việc mở rộng có limit 
để xử lí dữ liệu nhanh hơn, truyề dữ liệu giữa các thành phần nhanh hơn đáp ứng dc tốc độ cao của CPU
Dựa trên công nghệ toán học việc mở rộng tính trên 2^n 
+ BUS CONTROL /92
 chuyển các tín hiệu điều khiển 
 -> các loại tín hiệu điều khiển đọc ghi, interrupt, bus
 1 số tín hiện đk cpu / t khảo trang 93
 Phân loại bus trong MT  - T 97 
 BUS in cpu 
 bus in ram 
 bus in i/o
 tham khảo 1 số bảng mạch chủ - công nghệ intel 
 99-103
 thiết kế dc truyền bus 
 - Kiểu bus - data, control, address
 - Phân xử bus: Uưu tiên - quyền dc truyền data trc 
 - Định thời: xung nhịp đồng hồ hệ thống 
