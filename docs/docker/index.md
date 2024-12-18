### Docker là một nền tảng mã nguồn mở giúp đóng gói ứng dụng và các thành phần phụ thuộc của nó vào các đơn vị có thể chạy được, gọi là container. Container là các môi trường chạy độc lập, có thể được triển khai trên nhiều hệ thống khác 1  nhau. Nói một cách đơn giản, Docker giúp bạn tạo ra những "hộp" chứa đựng ứng dụng của bạn cùng với tất cả những gì ứng dụng đó cần để chạy, bất kể bạn chạy nó ở đâu.

### Tại sao sử dụng Docker?
- Tính nhất quán: Đảm bảo ứng dụng chạy giống nhau trên các môi trường khác nhau, tránh các vấn đề liên quan đến môi trường.
- Hiệu suất: Container nhẹ hơn máy ảo truyền thống, giúp tiết kiệm tài nguyên.
- Mật độ: Có thể chạy nhiều container trên một máy chủ vật lý.
- Triển khai nhanh: Dễ dàng tạo, vận hành và phá hủy container.
- Chia sẻ: Có thể chia sẻ các container với cộng đồng thông qua Docker Hub.

### Các thành phần chính của Docker
- Docker Daemon: Là một tiến trình chạy trên máy chủ, chịu trách nhiệm xây dựng, chạy và quản lý các container.
- Docker Image: Là một bản snapshot tĩnh của một container. Image không thể chạy được, nhưng có thể được sử dụng để tạo ra các container mới.
- Docker Container: Là một instance đang chạy của một image. Container là đơn vị nhỏ nhất của Docker và có thể được khởi động, dừng, xóa bất kỳ lúc nào.
- Dockerfile: Là một tập tin văn bản chứa các lệnh để xây dựng một image. Dockerfile định nghĩa các bước cần thiết để tạo ra một môi trường chạy cho ứng dụng.
- Docker Hub: Là một registry công cộng, nơi bạn có thể tìm kiếm, chia sẻ và tải xuống các image Docker.