# Infrastructure as Code (IaC):
- Docker Engine (v27.1.1)

# Container Services:
- kong: kong:2.0.2-alpine
- kong_db: postgres:9.6
- konga: pantsel/konga
- konga_db: postgres:9.6
- prometheus: prom/prometheus:latest
- products: NestJS(v10)

# Config Projects:
- 1.สร้าง folder ใหม่ "web-https-nginx/certs"
- 2.ออกใบรับรอง (self-signed certificate) WindowOS ใช้คำสั่ง "openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout scaleton.local.key -out - scaleton.local.crt"
- 3.เพิ่มบรรทัดใหม่ในไฟล์ hosts "127.0.0.1 devops.local"
- 4.รันคำสั่ง "docker compose up -d" หรือ rebuild "docker compose up -d --build"

# API:
- 

# Konga:
- 