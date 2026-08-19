# Đóng góp cho bản chuyển ngữ tiếng Việt của Selah

Cảm ơn bạn đã giúp bản chuyển ngữ này chính xác hơn, rõ ràng hơn, và
hợp với tiếng Việt hơn. Không cần phải là học giả: hãy nói điều bạn
thấy, đưa ra bằng chứng bạn có, và phân biệt điều chắc chắn với điều
đề xuất.

## Báo lỗi hoặc đề nghị sửa

- Mở **Issue** nếu đoạn văn cần thảo luận, nếu có hơn một cách đọc,
  hoặc nếu bạn không chắc việc sửa ảnh hưởng thế nào đến sự khớp hàng
  của các từ.
- Mở **Pull request** nếu cả lỗi lẫn cách sửa đều rõ ràng.
- Với vấn đề phần mềm, hoặc chuyện bảo mật/tài khoản/riêng tư, dùng
  [Selah Support](https://selahproject.com/support).

## Cần kèm những gì

Sách, chương, câu, đoạn Hípri liên quan; văn bản hiện tại; văn bản bạn
đề xuất; lý do thay đổi; và bằng chứng từ từ điển, ngữ pháp, ngữ cảnh
hoặc tài liệu xuất bản. Cũng cho biết bạn có phải người nói tiếng
Việt không và có đọc trực tiếp tiếng Hípri được không.

## Quy tắc sửa tệp

Các tệp có dạng `<book>/<chapter>/<verse>.json`.

- Nếu cả hai bị ảnh hưởng, sửa `translation` và `gloss` của đoạn
  liên quan cùng nhau.
- **Không bao giờ** đụng vào `book`, `chapter`, `verse`, `ref`, giá
  trị `surface` tiếng Hípri, hay thứ tự và số lượng các token — lỗi
  khớp hàng là lỗi đắt giá nhất.
- **Theo bảng Danh xưng**: יהוה → **Yahweh**; אלהים → **Elohim**;
  אדני → **Adonai**; שדי → **Shaddai**; שאול → **Sheol**; חסד →
  **Khesed**. Trên chỗ của Danh, **Đức Giê-hô-va**, **Chúa** và
  **Đức Chúa Trời** không được chấp nhận. (Với *elohim* thông thường,
  **Đức Chúa Trời** có thể đúng — xét từng token, không loại trừ
  hàng loạt.)
- Giữ nguyên các dấu **⟨את⟩** và phần thêm trong ⟨ngoặc⟩; không lặng
  lẽ xóa bỏ.
- Chỉ chữ Quốc ngữ bên ngoài ngoặc — không chữ Hán/CJK, không
  Cyrillic, không chữ Ả Rập, không Devanagari.

## Tiêu chuẩn

Hípri trước hết. Nếu hai cách đọc đều đứng vững, hãy trình bày sự
khác biệt — đừng trình bày lựa chọn như điều chắc chắn. Không sao chép
các bản dịch hiện đại có bản quyền.

## Làm việc với AI

Hãy khai rõ việc dùng nhiều mô hình ngôn ngữ hoặc dịch máy — kèm sự
kiểm tra của chính bạn. Đừng gửi khối lượng lớn văn bản chưa kiểm tra.
Mỗi từ được đề xuất là trách nhiệm của người đóng góp.

## Giấy phép, chứng tích và thẩm định

Bằng việc đóng góp, bạn xác nhận mình có quyền làm vậy và đồng ý rằng
mọi thứ được đưa vào sẽ phân phối theo [CC BY-SA 4.0](LICENSE.md).
Lịch sử Git giữ hồ sơ mở và chứng tích. Nhóm duy trì đối chiếu các đề
xuất với tiếng Hípri, các quy tắc, nguồn và sự khớp hàng — có thể
chấp nhận, cùng bạn giải quyết, chờ thêm bằng chứng, hoặc từ chối có
lý do. Thẩm định văn bản, không thẩm định con người.
