# UIUX_08
*Nhóm có các thành viên sử dụng các ngôn ngữ lập trình khác nhau nên phải chia thành các phần nhỏ và chạy nhiều server
*Rất xin lỗi vì sự bất tiện này.
## Hướng dẫn cách cài đặt
- Môi trường cần có: NodeJs
- Đối với ubuntu
1. Clone project
2. Mở terminal lần lượt chạy các lệnh: 
  * npm i http-server -g
  * cd Danh_sach_quy_trinh
  * http-server ./ -p 3003
3. Mở thêm 1 terminal khác lần lượt chạy các lệnh:
  * cd DxClanWorkList/coreui-free-vue-admin-template-main
  * npm i
  * npm run serve -- --port 3001
4. Mở thêm 1 terminal khác lần lượt chạy các lệnh:
  * cd UIUX_MauThu
  * npm i
  * npm run serve -- --port 3002
5. Mở thêm 1 terminal khác lần lượt chạy c lệnh:
  * cd UIUX_08
  * npm i
  * npm start
6. Mở browser truy cập: http://localhost:3000
