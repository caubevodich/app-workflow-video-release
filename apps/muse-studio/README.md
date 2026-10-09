# MUSE STUDIO

Thư mục phát hành riêng của MUSE STUDIO trong repo dùng chung nhiều ứng dụng.

- `update.json`: thông tin phiên bản stable mới nhất của MUSE STUDIO.
- `update.sig`: chữ ký Ed25519 nhị phân của chính xác byte update.json.
- EXE portable được đính kèm tại release có tag `muse-studio-vVERSION`.

Không commit EXE, source code, token hoặc khóa riêng vào thư mục này.
Đăng EXE vào release trước, rồi commit update.json và update.sig cùng một lượt.
Mỗi phiên bản dùng tag riêng; không thay tài sản của một release đã phát hành.
Các app khác dùng thư mục và tiền tố tag riêng của chúng.
