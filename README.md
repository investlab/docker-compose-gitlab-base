# Sử dụng
- docker-compose up
- docker-compose restart

# Update
- Giả sử cần update từ ver 13.2.1 lên ver 14.5.2. Trì cần update các version trung gian.
- Stop và remove container đang chạy.
- Sửa image trong docker-compose.yml lên phiên bản cuối cùng của version hệ tại là 13.2.8.
- Chạy "docker-compose up" để update lên phiên bản cuối cùng của v13 là 13.2.8.
- Pull bản 14.5.2 (hoặc latest)
- Sửa lại image trong docker-compose.yml về 14.5.2 (hoặc latest)
- Stop và remove container đang chạy.
- Chạy "docker-compose up" - Done.
