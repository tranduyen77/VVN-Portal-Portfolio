# VVN Portal — Hệ thống quản trị sản xuất tích hợp

**Dự án chuyển đổi số nhà máy Van Vina | 2025–2026**  
**Phiên bản Portfolio:** 1.0 · **Cập nhật:** 15/11/2026, 13:08 (GMT+7)

![Sơ đồ tổng quan VVN Portal](assets/vvn-portal-overview.svg)

> **Từ dữ liệu rời rạc đến một hệ thống vận hành thống nhất:** VVN Portal được xây dựng để hỗ trợ quản lý và theo dõi các hoạt động sản xuất cơ khí tại Van Vina, đồng thời tạo nền tảng cho kết nối thiết bị IoT và ứng dụng AI trong tương lai.

## Bài toán

Một nhà máy cơ khí cần liên kết dữ liệu giữa kinh doanh, kế hoạch, nguyên vật liệu, sản xuất, kiểm tra chất lượng và giao hàng. Nếu thông tin phân tán ở nhiều biểu mẫu, việc tra cứu, đối chiếu và theo dõi tiến độ sẽ tốn thời gian.

## Giải pháp VVN Portal

VVN Portal là hệ thống quản trị nội bộ theo hướng **một nền tảng – nhiều nghiệp vụ liên thông**, với các nhóm chức năng:

- **Kinh doanh & kế hoạch:** quản lý yêu cầu, đơn hàng và kế hoạch sản xuất.
- **Sản xuất:** theo dõi công việc, tiến độ và dữ liệu tại hiện trường.
- **Kho & vật tư:** quản lý nguyên vật liệu, thành phẩm, cấp phát và luân chuyển.
- **Chất lượng (QC):** hỗ trợ ghi nhận và truy xuất thông tin kiểm tra.
- **Mua hàng, giao hàng & thiết bị:** kết nối các công đoạn hỗ trợ vận hành.
- **IoT & truy xuất:** ứng dụng mã QR, thu thập dữ liệu từ thiết bị và định hướng kết nối dữ liệu thời gian thực.

## Công nghệ sử dụng

| Thành phần | Công nghệ |
|---|---|
| Giao diện | Vue 3 (SPA) |
| Backend / API | PHP, REST-style API |
| Cơ sở dữ liệu | MySQL / MariaDB |
| Hạ tầng | Ubuntu Linux, máy chủ nội bộ, NAS |
| Tích hợp hiện trường | QR, ESP32, giao tiếp thiết bị, HTTP/MQTT (theo từng hạng mục) |

## Giá trị và định hướng phát triển

- Chuẩn hóa luồng thông tin giữa các bộ phận và giảm phụ thuộc vào biểu mẫu rời rạc.
- Tăng khả năng truy xuất dữ liệu từ đơn hàng đến quá trình sản xuất.
- Xây dựng nền tảng dữ liệu phục vụ báo cáo quản trị.
- Mở rộng kết nối IoT, hỗ trợ nhận dạng hình ảnh và AI lập quy trình gia công CNC (các hướng phát triển/đề xuất, **không coi là chức năng đã triển khai hoàn chỉnh**).

## Vai trò và đóng góp

Dự án được phát triển từ các yêu cầu thực tế tại Van Vina, kết hợp phân tích quy trình nghiệp vụ, thiết kế luồng dữ liệu, xây dựng phần mềm và thử nghiệm kết nối thiết bị. Phạm vi đóng góp cá nhân cụ thể có thể bổ sung theo hồ sơ người nộp.

## Hình ảnh

Hình phía trên là **sơ đồ minh họa kiến trúc**, không phải ảnh chụp màn hình thật. Có thể bổ sung ảnh dashboard, quản lý kế hoạch, quản lý kho, QC và IoT sau khi ẩn thông tin khách hàng, nhân sự và dữ liệu nội bộ.

## Bảo mật và mã nguồn

Đây là portfolio giới thiệu dự án; mã nguồn, cơ sở dữ liệu và thông tin vận hành nội bộ không được công khai. Repository chỉ chứa tài liệu mô tả và hình minh họa được phép chia sẻ.

---

**Project:** VVN Portal · **Organization:** Van Vina · **Portfolio version:** 1.0
