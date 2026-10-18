# Niềng răng trả góp quận 10 / TPHCM — Nha khoa AVA (niengrangtphcm.vn)

Site tĩnh (HTML/CSS/JS), deploy thẳng lên Vercel, không cần build.

## Trang
| URL | Nội dung |
|---|---|
| `/` | Landing page chính (từ khóa: niềng răng trả góp quận 10, niềng răng trả góp tphcm) |
| `/bang-gia-nieng-rang-tra-gop/` | Bảng giá chỉnh hình răng |
| `/hinh-anh-nieng-rang-truoc-sau/` | 144 ca trước/sau (hiện 24 ảnh, nút "Xem thêm") |
| 3 bài kiến thức | trả góp, mắc cài vs Invisalign, thời gian/đau/kiêng |
| `/gioi-thieu/`, `/bac-si-pham-viet-hung/` | giới thiệu, hồ sơ bác sĩ |

## Ảnh trước/sau
`assets/images/nieng-rang/nieng-rang-quan-10-truoc-sau-NN.{webp,jpg}` (rộng 900px) và `-thumb` (420px). Đã bỏ EXIF. Đã loại ảnh không phải niềng răng (trám răng, cười hở nướu...) và ảnh ghép chất lượng thấp.

## Việc cần làm tiếp
1. **Gói trả góp:** chưa có thông tin kỳ hạn/lãi suất/giấy tờ nên website chỉ mô tả chung. Bổ sung khi có chính sách thật (mục `#tra-gop` trong `index.html`, bài `nieng-rang-tra-gop-dieu-kien-thu-tuc`).
2. Nộp `sitemap.xml` lên Google Search Console, khai báo domain `niengrangtphcm.vn`.
3. Ảnh có sẵn banner/chữ `benhvienthammy.com.vn` từ file gốc; nếu muốn bỏ cần xuất lại ảnh gốc không banner.
