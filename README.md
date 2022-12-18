# Group-3
Đề tài: Viết ứng dụng kết hợp nhiều docker với nhau

Thành viên:
  - Huỳnh Lê Huy    MSSV: 20110493
  - Nguyễn Đức Huy  MSSV: 20110332
  - K'kong Her      MSSV: 20110L01

Công nghệ sử dụng:
  - Docker
  - EC2
  - MySQL
  - Java
  - C#

Công cụ sử dụng:
  - Visual Studio Code
  - Intelij
  - Visual Studio 2022
  - Git

Cách sử dụng:
  + Cài đặt 4 instance EC2 để chạy project:
    ![image](https://user-images.githubusercontent.com/88545526/208293230-e7545c22-9b03-439b-b918-99412ec3d5eb.png)
  + Cấp địa chỉ Elastic IP cho từng instance:
    ![image](https://user-images.githubusercontent.com/88545526/208293380-8cd7f31b-ce4e-4cc2-a678-2efb9bf09bd0.png)
  + Thêm Inbound rules cho từng instance:
    ![image](https://user-images.githubusercontent.com/88545526/208293559-762c6a66-13d4-4c12-9cb4-52bf26174e85.png)
  + Sử dụng VScode để kết nối vào các máy EC2 thông qua extension Remote SSH
    ![image](https://user-images.githubusercontent.com/88545526/208293674-de06e9f8-f9d8-46ba-9549-b706368214d7.png)
  + Config file ssh để kết nối các máy EC2:
    ![image](https://user-images.githubusercontent.com/88545526/208293782-84a976f8-7d14-4b0b-ba4c-75b0491a3e5c.png)
  + Dùng git để clone project về máy EC2:
    ![image](https://user-images.githubusercontent.com/88545526/208293885-e1574513-83b9-428f-a72c-eecb4cd44cd3.png)
  + Cài đặt và chạy từng docker trên máy
    
