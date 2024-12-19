# Sử dụng Node.js runtime làm hình ảnh gốc
FROM node:20-alpine

# Thiết lập thư mục làm việc
WORKDIR /app

# Sao chép các file package.json và bun.lockb (nếu có)
COPY package*.json ./


# Cài đặt các phụ thuộc bằng npm
# Sao chép phần còn lại của ứng dụng
# làm sạch bộ nhớ đệm npm
RUN npm install --production && \
    npm rebuild bcrypt --build-from-source && \
    npm cache clean --force
    

COPY . .
COPY .env .

# Build ứng dụng
RUN npm run build

# Tiết lộ cổng để truy cập vào ứng dụng
EXPOSE 9999

# Khởi động ứng dụng
CMD ["npm", "start"]