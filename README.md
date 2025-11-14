# Thesieutoc

## Tính năng
- Nạp thẻ qua lệnh, click text trên chat hoặc menu
- Bảng xếp hạng top nạp thẻ
- Hệ thống mốc nạp thưởng

> **Có lỗi?**  
> Hãy liên hệ support Thesieutoc hoặc tạo [Issue trên GitHub](https://github.com/motcainit/Thesieutoc/issues)

---

## [TẢI VỀ](https://github.com/motcainit/Thesieutoc/releases)
> *Bấm vào nút tải ở trang Releases để lấy phiên bản mới nhất.*

---

## Yêu cầu hệ thống
- **Java**: 17 trở lên

---

## Phiên bản Spigot hỗ trợ
- Hỗ trợ hầu hết các phiên bản Spigot  
- **Lưu ý**: Tính năng nạp qua menu hiện chỉ hỗ trợ đến **1.21.10**

---

## Placeholder (PAPI)

> **Tùy chỉnh định dạng số**  
> Mở file `lang.yml` → sửa `value_format: '#,###'` thành `value_format: '#'` để hiển thị số nguyên (ví dụ: `10000` thay vì `10,000`).

> **Gợi ý**: Kết hợp với plugin như `ajLeaderboards` để tạo bảng xếp hạng nâng cao.

### Tổng tiền nạp của toàn server
| Phạm vi         | Placeholder              |
|-----------------|--------------------------|
| Toàn thời gian  | `%tst_total%`            |
| Trong năm       | `%tst_total_year%`       |
| Trong tháng     | `%tst_total_month%`      |
| Trong tuần      | `%tst_total_week%`       |
| Hôm nay         | `%tst_total_daily%`      |

### Tiền nạp của người chơi
| Phạm vi         | Placeholder                 |
|-----------------|-----------------------------|
| Toàn thời gian  | `%tst_player_total%`        |
| Trong năm       | `%tst_player_year%`         |
| Trong tháng     | `%tst_player_month%`        |
| Trong tuần      | `%tst_player_week%`         |
| Hôm nay         | `%tst_player_daily%`        |

### Top nạp thẻ (thay `<số thứ tự>` bằng 1, 2, 3...)
| Phạm vi         | Placeholder                        |
|-----------------|------------------------------------|
| Toàn thời gian  | `%tst_top_<số thứ tự>%`            |
| Trong năm       | `%tst_top_year_<số thứ tự>%`       |
| Trong tháng     | `%tst_top_month_<số thứ tự>%`      |
| Trong tuần      | `%tst_top_week_<số thứ tự>%`       |
| Hôm nay         | `%tst_top_daily_<số thứ tự>%`      |
