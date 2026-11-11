# Sổ Nhật ký Khảo sát Địa kỹ thuật & Bảng Tọa độ Lưu (WGS 84)

- **Tác tử điều phối**: `SurveyLogbookAgent` (`survey-logbook`) kết hợp `PhysicalQuarantineAgent` (`physical-quarantine`)
- **Hệ tọa độ**: EPSG:4326 (WGS 84 — Độ thập phân & Độ-Phút-Giây DMS)
- **Tổng hợp**: 8 điểm định vị (5 có tọa độ, 3 trong vùng cách ly) · **13 mục ghi chú nhật ký**.

## 1. Bảng Tọa độ Lưu các Điểm Định vị Khảo sát

| Mã ĐV | Mã Điểm | Xã / Khu vực | Vĩ độ (°B) | Kinh độ (°Đ) | Tọa độ DMS | Cao độ (m) | Số mục NK | Trạng thái QA |
|---|---|---|---:|---:|---|---:|---:|---|
| `WP-001` | `LS-QK-01` | **Quốc Khánh** (Khu vực Tàng Chang, thôn Phi Mỹ (Cốc Mười cũ)) | 22.357778 | 106.524722 | 22°21'28"B, 106°31'29"Đ | 338.0 | 2 | **pending** |
| `WP-002` | `LS-DD-02` | **Đồng Đăng** (Các thôn Tam Lung, Nhất Tâm, Phú Lộc) | 21.950833 | 106.698056 | 21°57'03"B, 106°41'53"Đ | 253.0 | 2 | **pending** |
| `WP-003` | `LS-KK-03` | **Khánh Khê** (Thôn Khuổi Mạ) | 21.868333 | 106.645000 | 21°52'06"B, 106°38'42"Đ | 351.0 | 2 | **pending** |
| `WP-004` | `LS-KX-04` | **Khuất Xá** (Xóm Còn Chè, thôn Tam Gia) | 21.747500 | 107.018333 | 21°44'51"B, 107°01'06"Đ | 281.0 | 2 | **pending** |
| `WP-005` | `LS-CL-05` | **Chi Lăng** (Thôn Hợp Tiến và thôn Hòa Bình 2) | 21.601389 | 106.534722 | 21°36'05"B, 106°32'05"Đ | 54.0 | 2 | **pending** |
| `WP-006` | `LS-DH-06` | **Điềm He** (Xóm Phai Duống, thôn Phù Huê) | — | — | — | — | 1 | **quarantined** |
| `WP-007` | `LS-TB-07` | **Thái Bình** (Thôn Hưng Thái, Bản Chu) | — | — | — | — | 1 | **quarantined** |
| `WP-008` | `LS-NH-08` | **Nhất Hòa** (Các thôn trên địa bàn) | — | — | — | — | 1 | **quarantined** |

## 2. Nhật ký Khảo sát Chi tiết theo Từng Điểm Tọa độ

### [WP-001 | LS-QK-01] Điểm định vị Quốc Khánh (LS-QK-01) — Xã Quốc Khánh
- **Vị trí**: Khu vực Tàng Chang, thôn Phi Mỹ (Cốc Mười cũ)
- **Tọa độ lưu**: `22.357778°B, 106.524722°Đ` (22°21'28"B, 106°31'29"Đ) · **Cao độ**: 338.0 m
- **Địa chất**: Đới tiếp xúc giữa Hệ tầng Nà Quản / Sông Hiến và khối đá vôi, gần đứt gãy phương TB–ĐN; nguy cơ sạt lở sườn kết hợp sụt lún karst.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-001-NOTE-01` | 2026-11-11T09:00:00+07:00 | Tác tử Dữ liệu & Đoàn khảo sát bước 1 | Định vị mốc & Hiện trạng | **Ghi nhận mốc tọa độ quy hoạch và hiện trạng Quốc Khánh**: Điểm định vị khảo sát sạt lở tại Khu vực Tàng Chang, thôn Phi Mỹ (Cốc Mười cũ) (Quốc Khánh). Quy mô: 1 điểm, 93 hộ dân. Ký hiệu bản đồ: Trái tim. | Nghiên cứu khu tái định cư tập trung tại thôn Long Thịnh, diện tích 6,7 ha; dự kiến khoảng 46,6 tỷ đồng. |
| `WP-001-NOTE-02` | 2026-11-11T09:00:00+07:00 | Tác tử Địa chất (geology-raster) | Địa chất & Địa tầng | **Đối chiếu cấu trúc địa chất 1:200.000 tại Quốc Khánh**: Đới tiếp xúc giữa Hệ tầng Nà Quản / Sông Hiến và khối đá vôi, gần đứt gãy phương TB–ĐN; nguy cơ sạt lở sườn kết hợp sụt lún karst. | Đo thế nằm đá gốc, bề dày vỏ phong hóa và xác nhận mặt trượt ngoài thực địa. |

### [WP-002 | LS-DD-02] Điểm định vị Đồng Đăng (LS-DD-02) — Xã Đồng Đăng
- **Vị trí**: Các thôn Tam Lung, Nhất Tâm, Phú Lộc
- **Tọa độ lưu**: `21.950833°B, 106.698056°Đ` (21°57'03"B, 106°41'53"Đ) · **Cao độ**: 253.0 m
- **Địa chất**: Nằm trong đới đứt gãy Cao Bằng – Tiên Yên cắt qua các trầm tích lục nguyên – phun trào Trias (Hệ tầng Khôn Làng T2a kl) và đá vôi Bắc Sơn (C-P bs); vỏ phong hóa dày dễ trượt khi mưa lớn.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-002-NOTE-01` | 2026-11-11T15:00:00+07:00 | Tác tử Dữ liệu & Đoàn khảo sát bước 1 | Định vị mốc & Hiện trạng | **Ghi nhận mốc tọa độ quy hoạch và hiện trạng Đồng Đăng**: Điểm định vị khảo sát sạt lở tại Các thôn Tam Lung, Nhất Tâm, Phú Lộc (Đồng Đăng). Quy mô: 3 điểm, 56 hộ dân. Ký hiệu bản đồ: Sao vàng (2 điểm đánh dấu trên bản đồ PDF). | Đánh giá mức độ nguy hiểm, khuyến cáo người dân và tham mưu hỗ trợ kinh phí. |
| `WP-002-NOTE-02` | 2026-11-11T15:00:00+07:00 | Tác tử Địa chất (geology-raster) | Địa chất & Địa tầng | **Đối chiếu cấu trúc địa chất 1:200.000 tại Đồng Đăng**: Nằm trong đới đứt gãy Cao Bằng – Tiên Yên cắt qua các trầm tích lục nguyên – phun trào Trias (Hệ tầng Khôn Làng T2a kl) và đá vôi Bắc Sơn (C-P bs); vỏ phong hóa dày dễ trượt khi mưa lớn. | Đo thế nằm đá gốc, bề dày vỏ phong hóa và xác nhận mặt trượt ngoài thực địa. |

### [WP-003 | LS-KK-03] Điểm định vị Khánh Khê (LS-KK-03) — Xã Khánh Khê
- **Vị trí**: Thôn Khuổi Mạ
- **Tọa độ lưu**: `21.868333°B, 106.645000°Đ` (21°52'06"B, 106°38'42"Đ) · **Cao độ**: 351.0 m
- **Địa chất**: Trầm tích lục nguyên xen cát bột kết, đá phiến sét Hệ tầng Khôn Làng (T2a kl), địa hình phân cắt mạnh (độ dốc SRTM ~16,6°), dễ phát sinh trượt đất tầng nông và trung bình.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-003-NOTE-01` | 2026-11-12T09:00:00+07:00 | Tác tử Dữ liệu & Đoàn khảo sát bước 1 | Định vị mốc & Hiện trạng | **Ghi nhận mốc tọa độ quy hoạch và hiện trạng Khánh Khê**: Điểm định vị khảo sát sạt lở tại Thôn Khuổi Mạ (Khánh Khê). Quy mô: 1 điểm, 21 hộ dân. Ký hiệu bản đồ: Ruy băng xanh ngọc. | Bố trí vốn xây dựng khu tái định cư, hỗ trợ di dời và hoàn thiện thủ tục đất đai, đầu tư. |
| `WP-003-NOTE-02` | 2026-11-12T09:00:00+07:00 | Tác tử Địa chất (geology-raster) | Địa chất & Địa tầng | **Đối chiếu cấu trúc địa chất 1:200.000 tại Khánh Khê**: Trầm tích lục nguyên xen cát bột kết, đá phiến sét Hệ tầng Khôn Làng (T2a kl), địa hình phân cắt mạnh (độ dốc SRTM ~16,6°), dễ phát sinh trượt đất tầng nông và trung bình. | Đo thế nằm đá gốc, bề dày vỏ phong hóa và xác nhận mặt trượt ngoài thực địa. |

### [WP-004 | LS-KX-04] Điểm định vị Khuất Xá (LS-KX-04) — Xã Khuất Xá
- **Vị trí**: Xóm Còn Chè, thôn Tam Gia
- **Tọa độ lưu**: `21.747500°B, 107.018333°Đ` (21°44'51"B, 107°01'06"Đ) · **Cao độ**: 281.0 m
- **Địa chất**: Trầm tích lục nguyên Hệ tầng Rinh Chùa (T2l rc) tiếp giáp Hệ tầng Na Dương / Mẫu Sơn; đá phiến sét, bột kết phong hóa mạnh tạo mặt trượt cung tròn.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-004-NOTE-01` | 2026-11-12T15:00:00+07:00 | Tác tử Dữ liệu & Đoàn khảo sát bước 1 | Định vị mốc & Hiện trạng | **Ghi nhận mốc tọa độ quy hoạch và hiện trạng Khuất Xá**: Điểm định vị khảo sát sạt lở tại Xóm Còn Chè, thôn Tam Gia (Khuất Xá). Quy mô: 4 điểm, 25 hộ dân. Ký hiệu bản đồ: Vali xanh lam. | Bố trí tái định cư, khoan khảo sát địa chất và đo vẽ ranh giới cung trượt. |
| `WP-004-NOTE-02` | 2026-11-12T15:00:00+07:00 | Tác tử Địa chất (geology-raster) | Địa chất & Địa tầng | **Đối chiếu cấu trúc địa chất 1:200.000 tại Khuất Xá**: Trầm tích lục nguyên Hệ tầng Rinh Chùa (T2l rc) tiếp giáp Hệ tầng Na Dương / Mẫu Sơn; đá phiến sét, bột kết phong hóa mạnh tạo mặt trượt cung tròn. | Đo thế nằm đá gốc, bề dày vỏ phong hóa và xác nhận mặt trượt ngoài thực địa. |

### [WP-005 | LS-CL-05] Điểm định vị Chi Lăng (LS-CL-05) — Xã Chi Lăng
- **Vị trí**: Thôn Hợp Tiến và thôn Hòa Bình 2
- **Tọa độ lưu**: `21.601389°B, 106.534722°Đ` (21°36'05"B, 106°32'05"Đ) · **Cao độ**: 54.0 m
- **Địa chất**: Đới tiếp xúc kiến tạo giữa vách núi đá vôi Hệ tầng Bắc Sơn (C-P bs) và các trầm tích lục nguyên – carbonat Hệ tầng Lạng Sơn (T1 ls) / Khôn Làng (T2a kl); nguy cơ cao lở đá, đá lăn từ vách karst dốc đứng.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-005-NOTE-01` | 2026-11-13T10:00:00+07:00 | Tác tử Dữ liệu & Đoàn khảo sát bước 1 | Định vị mốc & Hiện trạng | **Ghi nhận mốc tọa độ quy hoạch và hiện trạng Chi Lăng**: Điểm định vị khảo sát sạt lở tại Thôn Hợp Tiến và thôn Hòa Bình 2 (Chi Lăng). Quy mô: 2 điểm, 23 hộ dân. Ký hiệu bản đồ: Cờ xanh lá. | Phá dỡ khối đá nguy cơ sạt lở và bố trí khu dân cư tập trung cho các trường hợp khẩn cấp. |
| `WP-005-NOTE-02` | 2026-11-13T10:00:00+07:00 | Tác tử Địa chất (geology-raster) | Địa chất & Địa tầng | **Đối chiếu cấu trúc địa chất 1:200.000 tại Chi Lăng**: Đới tiếp xúc kiến tạo giữa vách núi đá vôi Hệ tầng Bắc Sơn (C-P bs) và các trầm tích lục nguyên – carbonat Hệ tầng Lạng Sơn (T1 ls) / Khôn Làng (T2a kl); nguy cơ cao lở đá, đá lăn từ vách karst dốc đứng. | Đo thế nằm đá gốc, bề dày vỏ phong hóa và xác nhận mặt trượt ngoài thực địa. |

### [WP-006 | LS-DH-06] Điểm bổ sung Điềm He (LS-DH-06) — Xã Điềm He
- **Vị trí**: Xóm Phai Duống, thôn Phù Huê
- **Tọa độ lưu**: **Chưa có tọa độ (Đang trong Vùng cách ly)** · **Cao độ**: Chưa đo m
- **Địa chất**: Cần đối chiếu tờ Bản đồ Địa chất 1:200.000 sau khi đo tọa độ GPS thực địa.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-006-NOTE-01` | 2026-11-11T10:26:32+07:00 | Tác tử Kiểm định Vật lý (physical-quarantine) | Cảnh báo khuyết tọa độ | **Cách ly điểm Điềm He chờ bổ sung tọa độ WGS 84**: UBND tỉnh đã công bố tình huống khẩn cấp về thiên tai. Quy mô: 1 điểm, 4 hộ dân. Chưa có tọa độ trong Công văn 6666 — đưa vào Vùng cách ly chờ đo định vị GPS thực địa. | Đề xuất phương án sắp xếp ổn định dân cư ra khỏi vùng thiên tai. |

### [WP-007 | LS-TB-07] Điểm bổ sung Thái Bình (LS-TB-07) — Xã Thái Bình
- **Vị trí**: Thôn Hưng Thái, Bản Chu
- **Tọa độ lưu**: **Chưa có tọa độ (Đang trong Vùng cách ly)** · **Cao độ**: Chưa đo m
- **Địa chất**: Cần đối chiếu tờ Bản đồ Địa chất 1:200.000 sau khi đo tọa độ GPS thực địa.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-007-NOTE-01` | 2026-11-11T10:26:32+07:00 | Tác tử Kiểm định Vật lý (physical-quarantine) | Cảnh báo khuyết tọa độ | **Cách ly điểm Thái Bình chờ bổ sung tọa độ WGS 84**: Đã triển khai xây kè tại thôn Hưng Thái (3 hộ). Quy mô: 2 điểm, 8 hộ dân. Chưa có tọa độ trong Công văn 6666 — đưa vào Vùng cách ly chờ đo định vị GPS thực địa. | Kiểm tra, đánh giá hiện trạng sụt, trượt đất. |

### [WP-008 | LS-NH-08] Điểm bổ sung Nhất Hòa (LS-NH-08) — Xã Nhất Hòa
- **Vị trí**: Các thôn trên địa bàn
- **Tọa độ lưu**: **Chưa có tọa độ (Đang trong Vùng cách ly)** · **Cao độ**: Chưa đo m
- **Địa chất**: Cần đối chiếu tờ Bản đồ Địa chất 1:200.000 sau khi đo tọa độ GPS thực địa.

| Mã Mục | Thời gian | Người ghi | Hạng mục | Nội dung Ghi chú Nhật ký | Kiến nghị / Hành động |
|---|---|---|---|---|---|
| `WP-008-NOTE-01` | 2026-11-11T10:26:32+07:00 | Tác tử Kiểm định Vật lý (physical-quarantine) | Cảnh báo khuyết tọa độ | **Cách ly điểm Nhất Hòa chờ bổ sung tọa độ WGS 84**: Bao gồm 17 điểm giao thông và khu vực hộ dân có vết nứt. Quy mô: 26 điểm, 12 hộ dân. Chưa có tọa độ trong Công văn 6666 — đưa vào Vùng cách ly chờ đo định vị GPS thực địa. | Đề nghị hướng dẫn, hỗ trợ đánh giá mức độ nguy hiểm tại khu vực hộ dân có nguy cơ thiên tai và phương án xử lý phù hợp. |

