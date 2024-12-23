1. Cơ Bản về GitHub Actions
- GitHub Actions là một dịch vụ CI/CD (Continuous Integration and Continuous Deployment) được tích hợp trực tiếp vào GitHub, cho phép bạn tự động hóa các tác vụ liên quan đến phát triển phần mềm ngay trong repository của mình.

#### Thành Phần Chính
- Workflows: Các quy trình tự động được định nghĩa trong file YAML nằm trong thư mục .github/workflows của repository. Một workflow chứa các jobs và các bước để thực thi tác vụ.

- Jobs: Một workflow có thể chứa nhiều job, và mỗi job sẽ chạy độc lập trên một runner. Các jobs có thể được cấu hình để chạy song song hoặc theo thứ tự phụ thuộc lẫn nhau.

- Steps: Mỗi job chứa một hoặc nhiều bước (steps). Mỗi bước là một tập lệnh hoặc một hành động được thực thi. Các bước này chạy tuần tự trong một job.

- Actions: Các bước thường là các hành động (actions). GitHub cung cấp nhiều hành động sẵn có mà bạn có thể sử dụng, hoặc bạn có thể tạo hành động riêng của mình.

- Runners: Môi trường để chạy workflows. GitHub cung cấp các runners sẵn có (GitHub-hosted runners), nhưng bạn cũng có thể sử dụng runners của riêng mình (self-hosted runners).