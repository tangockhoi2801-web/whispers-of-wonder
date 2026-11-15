# WHISPERS OF WONDER — Miền Kỳ Diệu

Bản MVP game 3D khám phá thiên nhiên chạy trên trình duyệt, tập trung vào khu vực **Moonlight Lake**.

## Chơi game
Sau khi GitHub Actions hoàn tất lần triển khai đầu tiên, mở:
https://tangockhoi2801-web.github.io/whispers-of-wonder/

## Điều khiển
| Phím / thao tác | Chức năng |
|---|---|
| W A S D | Di chuyển |
| Shift | Chạy |
| Space | Nhảy |
| E | Tương tác / lên xuống thuyền / rời vị trí ngồi |
| F | Nghỉ tại ghế gần nhất |
| Chuột kéo | Xoay camera |
| Cuộn chuột | Zoom |
| P | Bật / tắt Photo Mode |
| H | Ẩn / hiện HUD |
| Esc | Menu / đóng bảng |

## Nội dung MVP
- Nhân vật 3D procedural và camera góc nhìn thứ ba.
- Khu rừng, hồ nước, cây cối, hoa, cầu/bến gỗ và đèn lồng.
- Xích đu, ghế nghỉ, kính thiên văn và thuyền có thể tương tác.
- Chu kỳ thời gian, mưa, sương, gió, tuyết, đom đóm, sao và cực quang.
- Ambient audio tổng hợp bằng Web Audio API.
- Bản đồ, cài đặt, Photo Mode và điều khiển cảm ứng cơ bản.

## Chạy local
```bash
python -m http.server 8080
```
Mở http://localhost:8080. Cần kết nối Internet để tải Three.js và phông chữ từ CDN.

## Phạm vi
Đây là MVP tập trung vào Moonlight Lake, chưa phải bản hoàn thiện của toàn bộ master prompt. Các khu vực Enchanted Forest, Mountain of Dreams, Starlight Beach và Floating Sky Islands chưa được triển khai thành màn chơi riêng.
