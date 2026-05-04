# Known Issues · Buổi 1

Ghi lại lỗi chưa xử lý được hoặc đã xử lý xong.

| STT   |              Lỗi gặp phải                | Lệnh gây lỗi               | Cách đã thử                                    | Trạng thái    |
|---:   |------------------------------------------|----------------------------|------------------------------------------------|---------------|
| 1     |Lỗi không tìm thấy file hoặc lệnh         |scripts/smoke_test.sh       |Thêm tiền tố bash vào trước lệnh                |   Đã xử lý    |
| 2     |Terminal bị treo, không gõ được tiếp      |bash scripts/smoke_test.sh  |Nhấn Ctrl + C và khởi động lại Git Bash         |   Đã xử lý    |
| 3     |Lỗi kết nối Docker API (failed to connect)|bash scripts/pull_all.sh    |Bật Docker Desktop và đợi trạng thái "Running"  |   Đã xử lý    |
| 4     |Một số Docker Images báo [WARN]|          |bash scripts/smoke_test.sh  |Chạy lệnh pull_all.sh để tải bổ sung tài nguyên |   Đã xử lý    |

