# Disk Map

Ứng dụng macOS xem thư mục nào chiếm chỗ trên ổ đĩa và dọn an toàn: cache, log, node_modules, file cài đặt, app cũ kèm file sót, file trùng và file lớn trên Google Drive.

**Tải về:** [Disk-Map.dmg](https://github.com/SonDang09/disk-map/releases/latest/download/Disk-Map.dmg) · Trang giới thiệu: https://diskmap.sondang.online

Yêu cầu: Mac chip Apple (M1 trở lên), macOS 13 trở lên.

## Cài đặt

Bản 0.9 là bản thử, chưa được Apple công chứng (notarize), nên macOS chặn app tải từ mạng về. Gỡ chặn một lần sau khi cài:

1. Mở `Disk-Map.dmg`, kéo Disk Map vào thư mục Applications.
2. Mở Terminal, chạy:

   ```bash
   xattr -dr com.apple.quarantine "/Applications/Disk Map.app"
   ```

3. Mở Disk Map trong Applications như app bình thường.

Lệnh chỉ gỡ cờ "tải từ Internet" của riêng Disk Map, không đổi cài đặt bảo mật của máy. Đã thử trên macOS 26, MacBook M4.

## Quyền riêng tư

Disk Map chạy hoàn toàn trên máy, chỉ đo dung lượng, không đọc nội dung file và không gửi dữ liệu đi đâu. Chi tiết: [Chính sách quyền riêng tư](https://diskmap.sondang.online/privacy.html).

## Về repo này

Repo chỉ chứa trang giới thiệu (GitHub Pages) và các bản phát hành. Mã nguồn của app không công khai.

Góp ý, báo lỗi, mua bản Pro: sondang@genplusmedia.com
