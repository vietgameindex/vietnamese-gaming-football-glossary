# Bộ dữ liệu thuật ngữ trò chơi và bóng đá tiếng Việt

Bộ dữ liệu mở này do **Viet Game Index (VGI)** biên soạn để phân loại cách gọi tiếng Việt, tên tiếng Anh thường gặp, biến thể chính tả và thực thể liên quan trong các nhóm trò chơi trực tuyến, dữ liệu bóng đá, thương hiệu và nhà cung cấp game.

## Phạm vi phiên bản 1.0.0

- 2,485 ánh xạ thuật ngữ tới 199 hồ sơ hướng dẫn hoặc trò chơi.
- 84 hồ sơ tên thương hiệu.
- 69 hồ sơ nhà cung cấp game.
- 6 nhóm nội dung chính.
- Ngữ cảnh ngôn ngữ: tiếng Việt tại thị trường Việt Nam (vi-VN).

## Tệp dữ liệu

- `vietnamese_game_football_glossary.csv`: thuật ngữ và trang tham chiếu chuẩn.
- `brand_catalog.csv`: tên thương hiệu, biến thể tên và trạng thái phân loại.
- `provider_catalog.csv`: tên nhà cung cấp và nhóm nội dung.
- `category_catalog.csv`: danh mục nội dung cấp cao.
- `DATA_DICTIONARY.md`: mô tả từng trường dữ liệu.

## Phương pháp

Mỗi thuật ngữ được gắn với một thực thể chuẩn và một URL tham chiếu. Trường `normalized_term` chỉ phục vụ đối chiếu kỹ thuật: chữ thường, bỏ dấu tiếng Việt và chuẩn hóa khoảng trắng. Trường `ambiguous` đánh dấu khi cùng một cách viết có thể trỏ tới nhiều thực thể; người dùng dữ liệu phải đọc thêm ngữ cảnh thay vì tự động gộp.

Danh mục thương hiệu chỉ ghi nhận tên và trạng thái biên tập. Việc một thương hiệu xuất hiện trong dữ liệu **không phải** là xác nhận về giấy phép, độ an toàn, khả năng thanh toán hoặc lời khuyên sử dụng.

Đọc phương pháp và giới hạn đầy đủ tại [VGI Nghiên cứu](https://vietgameindex.com/nghien-cuu/). Xem dự án tại [Viet Game Index](https://vietgameindex.com/).

## Trích dẫn

> Đội ngũ biên tập Viet Game Index (2026), “Bộ dữ liệu thuật ngữ trò chơi và bóng đá tiếng Việt”, phiên bản 1.0.0.

## Giấy phép

Dữ liệu và tài liệu được phát hành theo [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). Khi sử dụng lại, vui lòng ghi tên Viet Game Index, liên kết tới bộ dữ liệu và nêu rõ nếu đã chỉnh sửa.
