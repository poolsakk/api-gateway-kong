# web-http-nginx:
- Docker Engine (v27.1.1)

# Container Images:
- kong:2.0.2-alpine
- postgres:9.6
- pantsel/konga
- products (NestJS v10)

# Config Project "web-http-nginx":
- 1.สร้าง folder ใหม่ "web-https-nginx/certs"
- 2.ออกใบรับรอง (self-signed certificate) WindowOS ใช้คำสั่ง "openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout scaleton.local.key -out - scaleton.local.crt"
- 3.เพิ่มบรรทัดใหม่ในไฟล์ hosts "127.0.0.1 devops.local"
- 4.รันคำสั่ง "docker compose up -d" หรือ rebuild "docker compose up -d --build"

# API:
- 

# Konga:
- 