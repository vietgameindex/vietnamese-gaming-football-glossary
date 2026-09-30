# Từ điển dữ liệu

## vietnamese_game_football_glossary.csv

| Trường | Ý nghĩa |
|---|---|
| term_id | Mã dòng ổn định trong bản phát hành. |
| term | Cách viết được ghi nhận. |
| normalized_term | Dạng chữ thường, bỏ dấu và chuẩn hóa khoảng trắng để đối chiếu. |
| canonical_label | Tên thực thể chuẩn trong VGI. |
| slug | Định danh URL của thực thể. |
| category_slug | Nhóm nội dung cấp cao. |
| provider_slugs | Nhà cung cấp liên quan, phân cách bằng ký tự `|`. |
| canonical_url | Trang tham chiếu công khai. |
| locale_context | Thị trường/ngữ cảnh ngôn ngữ của bản ghi. |
| reviewed_at | Ngày rà soát gần nhất của lớp dữ liệu này. |
| ambiguous | `true` nếu dạng chuẩn hóa được gắn với nhiều thực thể. |
| mapped_entity_count | Số thực thể dùng cùng dạng chuẩn hóa. |

## brand_catalog.csv

`catalog_status` chỉ cho biết tình trạng phân loại nội dung. `unverified` nghĩa là danh mục sản phẩm hoặc thực thể chưa đủ nguồn trực tiếp; `catalogued-not-endorsed` không có nghĩa là VGI bảo chứng thương hiệu.

## provider_catalog.csv

Danh sách giúp tách nhà cung cấp nội dung khỏi thương hiệu vận hành hoặc phân phối.

## category_catalog.csv

Danh mục dùng để nhóm các hồ sơ và không đại diện cho mức độ phổ biến hoặc độ an toàn.
