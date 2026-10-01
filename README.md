# PHP Hello World - Docker

Project sederhana untuk menjalankan PHP menggunakan Docker Compose.

## Struktur
```text
php-docker-hello-world/
├── docker-compose.yml
└── src/
    └── index.php
```

## Menjalankan
Pastikan Docker Desktop sudah berjalan, lalu dari folder project jalankan:

```bash
docker compose up -d
```

Buka browser:
http://localhost:8080

Untuk menghentikan container:
```bash
docker compose down
```
