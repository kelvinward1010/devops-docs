### Docker Images và Containers

1. docker build
```bash
docker build -t image_name:tag .
```
- Giải thích: Build một image từ Dockerfile trong thư mục hiện tại (.).

2. docker images
```bash
docker images
```
- Giải thích: Liệt kê tất cả các Docker images trên máy của bạn.

3. docker pull
```bash
docker pull image_name:tag
```
- Giải thích: Tải một image từ Docker Hub về máy của bạn.

4. docker run
```bash
docker run -d --name container_name -p 80:80 image_name:tag
```
- Giải thích: Chạy một container từ image với các tùy chọn như detach mode (-d), đặt tên container (--name), và ánh xạ cổng (-p).

5. docker ps
```bash
docker ps
```
- Giải thích: Liệt kê các container đang chạy.

6. docker ps -a
```bash
docker ps -a
```
- Giải thích: Liệt kê tất cả các container, bao gồm cả container đã dừng.

7. docker stop
```bash
docker stop container_name
```
- Giải thích: Dừng một container đang chạy.

8. docker stop
```bash
docker stop container_name
```
- Giải thích: Khởi động lại một container đã dừng.

9. docker restart
```bash
docker restart container_name
```
- Giải thích: Khởi động lại một container đang chạy.

10. docker rm
```bash
docker rm container_name
```
- Giải thích: Xóa một container đã dừng.

11. docker rmi
```bash
docker rmi image_name:tag
```
- Giải thích: Xóa một Docker image.


### Docker Volumes và Networks
12. docker volume create
```bash
docker volume create volume_name
```
- Giải thích: Tạo một Docker volume.

13. docker volume ls
```bash
docker volume ls
```
- Giải thích: Liệt kê tất cả các Docker volumes.

14. docker volume rm
```bash
docker volume rm volume_name
```
- Giải thích: Xóa một Docker volume.

15. docker network create
```bash
docker network create network_name
```
- Giải thích: Tạo một Docker network.

16. docker network ls
```bash
docker network ls
```
- Giải thích: Liệt kê tất cả các Docker networks.

17. docker network rm
```bash
docker network rm network_name
```


### Docker Compose
18. docker-compose up
```bash
docker-compose up
```
- Giải thích: Khởi động tất cả các services được định nghĩa trong docker-compose.yml.

19. docker-compose up -d
```bash
docker-compose up -d
```
- Giải thích: Khởi động tất cả các services trong chế độ nền (detached mode).

20. docker-compose down
```bash
docker-compose down
```
- Giải thích: Dừng và loại bỏ tất cả các container, networks, volumes, và images được tạo bởi docker-compose up.

21. docker-compose build
```bash
docker-compose build
```
- Giải thích: Build hoặc rebuild các images của services được định nghĩa trong docker-compose.yml.


### Docker Logs và Stats
22. docker logs
```bash
docker logs container_name
```
- Giải thích: Xem logs của một container.

23. docker stats
```bash
docker stats
```
- Giải thích: Xem thông tin tài nguyên đang sử dụng của các container đang chạy (CPU, memory, network, I/O).


### Tổng Kết
- Images và Containers: Câu lệnh để quản lý Docker images và containers.
- Volumes và Networks: Câu lệnh để quản lý Docker volumes và networks.
- Docker Compose: Câu lệnh để làm việc với Docker Compose.
- Logs và Stats: Câu lệnh để xem logs và thông tin tài nguyên của các container.