# Crawl-data-TopCV-Airflow
Thu thập dữ liệu trên trang web https://www.topcv.vn, bao gồm các thông tin:
Thu thập dữ liệu trên trang web https://www.topcv.vn, bao gồm các thông tin:

- job_url: Địa chỉ URL công việc
- title: Tiêu đề công việc
- salary_range: Khoảng lương
- location: Địa chỉ công ty
- description: Mô tả công việc
- requirements: Yêu cầu công việc
- benefit: Quyền lợi
- company_url: Địa chỉ URL công ty
- company_name: Tên công ty
- company_avatar: Ảnh công ty
- company_scale: Quy mô công ty
- company_address: Địa chỉ công ty
- position: Vị trí công việc
- experience: Yêu cầu kinh nghiệm
- quantity: Số lượng cần tuyển
- gender: Giới tính yêu cầu
- branch: Lĩnh vực công việc
- # Cách sử dụng

_Để có thể chạy dự án này, bạn sẽ cần cài đặt Docker_

git clone thu mục này về 

Điều hướng đến `docker-compose.yml`:

```bash
cd contents/code/docker
```
```bash
docker-compose -f "docker-compose.yml" up -d --build
```
Sau khi khởi động, truy cập qua địa chỉ:

- Giao diện airflow: http://localhost:8080 hoặc http://localhost:8080/home
  
- Thông tin đăng nhập:
  - username: **admin**
  - password: **admin**
- MySQL: http://localhost:6205
