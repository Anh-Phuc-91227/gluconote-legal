# Chính sách quyền riêng tư — GlucoNote

**Cập nhật lần cuối:** 26/05/2026

GlucoNote ("ứng dụng", "chúng tôi") là ứng dụng theo dõi sức khỏe dành cho người tiểu đường. Chính sách này mô tả cách ứng dụng xử lý dữ liệu của bạn.

## Tóm tắt nhanh

- **Toàn bộ dữ liệu lưu nội bộ trên thiết bị của bạn.**
- **Không có tài khoản, không đồng bộ đám mây, không gửi dữ liệu ra ngoài.**
- **Chúng tôi không thu thập, không truy cập, không bán dữ liệu của bạn.**

## 1. Dữ liệu được thu thập và lưu trữ

Ứng dụng cho phép bạn ghi lại các thông tin sức khỏe sau, được lưu **chỉ trên thiết bị của bạn** trong cơ sở dữ liệu SQLite nội bộ:

- Chỉ số đường huyết (giá trị, đơn vị, bối cảnh đo, ghi chú, thời gian).
- Chỉ số huyết áp (tâm thu, tâm trương, nhịp tim, ghi chú, thời gian).
- Cân nặng, chiều cao, BMI.
- Bữa ăn (tên, carb, calo, loại bữa, ghi chú).
- Lịch nhắc thuốc (tên thuốc, liều, giờ, ngày trong tuần).
- Cài đặt cá nhân (đơn vị đo, ngưỡng cảnh báo).

## 2. Cách dữ liệu được sử dụng

Dữ liệu chỉ được sử dụng để:

- Hiển thị lại cho chính bạn trong ứng dụng (lịch sử, biểu đồ, thống kê).
- Tạo báo cáo PDF khi bạn yêu cầu (báo cáo được tạo trên thiết bị, không upload).
- Gửi thông báo nhắc thuốc cục bộ (thông qua API `flutter_local_notifications`).

## 3. Quyền truy cập (permissions)

Ứng dụng có thể yêu cầu các quyền sau:

- **Thông báo (Notifications)**: để hiển thị nhắc nhở uống thuốc theo lịch bạn cài đặt.
- **Bộ nhớ (Storage)**: chỉ khi bạn xuất / chia sẻ báo cáo PDF.

Ứng dụng **không** yêu cầu: vị trí, danh bạ, camera, microphone, internet (app hoạt động offline 100%).

## 4. Chia sẻ dữ liệu với bên thứ ba

**Không.** Vì dữ liệu không bao giờ rời khỏi thiết bị, chúng tôi không chia sẻ với bất kỳ ai — không quảng cáo, không phân tích, không nhà cung cấp dịch vụ, không cơ quan nào.

Khi bạn chủ động **xuất báo cáo PDF và chia sẻ** (qua email, Zalo, in ấn...), bạn hoàn toàn kiểm soát đối tượng nhận. Chúng tôi không can thiệp.

## 5. Lưu trữ và xoá dữ liệu

- Dữ liệu được lưu **vô thời hạn** trên thiết bị cho đến khi bạn xoá thủ công.
- **Để xoá toàn bộ dữ liệu**: gỡ cài đặt ứng dụng, hoặc vào Cài đặt hệ thống → Ứng dụng → GlucoNote → Xoá dữ liệu (Android) / xoá ứng dụng (iOS).
- Vì dữ liệu chỉ ở trên máy bạn, chúng tôi không thể khôi phục nếu bạn xoá hoặc đổi máy. Bạn nên xuất báo cáo PDF định kỳ để lưu trữ ngoài nếu cần.

## 6. Trẻ em

Ứng dụng **không nhắm đến trẻ em dưới 13 tuổi**. Chúng tôi không thu thập có chủ ý dữ liệu của trẻ em dưới 13 tuổi. Nếu bạn là phụ huynh và cho con dùng ứng dụng, bạn chịu trách nhiệm giám sát.

## 7. Bảo mật

Vì dữ liệu chỉ lưu trên thiết bị của bạn, mức độ bảo vệ phụ thuộc vào bảo mật hệ điều hành (mã PIN, vân tay, mã hoá ổ đĩa của máy). Chúng tôi khuyến cáo:

- Bật khoá màn hình trên thiết bị.
- Không cho người khác mượn thiết bị nếu lo ngại quyền riêng tư.

## 8. Thay đổi chính sách

Chính sách có thể được cập nhật. Ngày cập nhật mới nhất hiển thị ở đầu trang. Phiên bản hiện hành luôn được công bố tại URL này.

## 9. Liên hệ

Nếu có câu hỏi về chính sách hoặc ứng dụng:

- Email: phucdang868@gmail.com

---

*GlucoNote không phải là thiết bị y tế. Mọi thông tin chỉ mang tính tham khảo, không thay thế ý kiến của bác sĩ.*
