# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thị Hải Mi
- Mã học viên: 2A202602667
- Vai trò / bối cảnh: SEO Specialist tại agency, phụ trách khoảng 5 dự án SEO cùng lúc.
- Công việc hằng tuần:
  - Quản lý tiến độ các dự án SEO
  - Lên plan SEO (onpage, offpage, content)
  - Xử lý các task SEO: lọc/mua báo GP/PR, internal link, QC content
  - Làm report tuần gửi client

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại, Tốn thời gian | **Lọc báo GP/PR:** tra cứu domain thủ công qua 2-3 file báo giá của supplier (Excel/PDF, mỗi file một định dạng), đối chiếu DR/traffic trên Ahrefs để chọn báo theo yêu cầu từng dự án | Tôi (SEO specialist, 5 dự án) | 1-2 lần/dự án/tháng × 5 dự án; 30-40 phút/lần → khoảng 2,5-6,5 giờ/tháng; mỗi lần 2-3 file supplier |
| 2 | Tốn thời gian, AI có thể tốt hơn | **Internal link:** với mỗi bài mới, tự tìm bài liên quan trên site, chọn anchor và chèn internal link thủ công | Tôi | 2 dự án book content × ~20 bài/tháng; tối thiểu 15 phút/bài → ≥ 10 giờ/tháng |
| 3 | Lặp lại | **Report tuần cho client:** đổ data vào template có sẵn, viết insight theo khung của template | Tôi; client là người nhận report | 1 report/tuần/dự án × 5 dự án = 5 report/tuần; 15 phút/report nếu làm tay → 75 phút/tuần |
| 4 | Pain từ người khác, Lặp lại | **Trích xuất content top 10:** copy tay nội dung từng trang trong top 10 kết quả tìm kiếm để vendor content viết outline | Chị content SEO; vendor content chờ input | Tối đa 20 content/tuần; 5 phút cho 10 trang/content → khoảng 100 phút/tuần |
| 5 | AI có thể tốt hơn, Pain từ người khác | **QC content:** đọc từng bài và đối chiếu thủ công với brand guideline riêng của từng client | Tôi hoặc chị content SEO | 2 dự án có QC × ~5 bài/tuần × 15 phút/bài → 150 phút/tuần (~10 giờ/tháng); lỗi hay gặp nhất: bài không đúng chuẩn brand guideline của client |

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Nhờ Claude đối chiếu 5 problems tôi tự scan với yêu cầu đề bài, chỉ ra thông tin còn thiếu.
- Ý dùng được: AI chỉ ra bảng scan còn thiếu số liệu (tần suất, thời gian, số dự án, ai chịu ảnh hưởng); problem Internal link đang viết như một task ("xây dựng mô hình") chứ chưa phải pain; problem Report tuần trùng chủ đề với ví dụ mẫu Weekly Report.
- Ý bỏ vì không phải pain thật: AI ban đầu giả định cả 5 dự án đều có QC content (~6 giờ/tuần). Thực tế chỉ 2 dự án có QC → tôi sửa lại còn ~150 phút/tuần.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính (dùng cả 4)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #1 Lọc báo GP/PR | Lặp lại đều hằng tháng trên cả 5 dự án; workflow rõ 5 bước; phần lọc theo số (traffic, vendor, giá) giải được bằng Rule nên so sánh Rule / Workflow / Agent rất rõ | Chưa rõ việc gán chủ đề cho từng báo khó tới đâu; định dạng file supplier có ổn định giữa các lần gửi không |
| 2 | #5 QC content | ~10 giờ/tháng, 2 người cùng làm; guideline mỗi client khác nhau nên cần hiểu ngữ cảnh — đúng kiểu bài cần cân nhắc AI | Chưa đo tỷ lệ lỗi lọt qua QC tới client; phần "giọng văn / brand voice" khó có đúng/sai rõ |
| 3 | #2 Internal link | ≥ 10 giờ/tháng cho 2 dự án book content; có sẵn phương án Rule (map keyword → URL) để so với AI | Chưa đo việc bỏ sót link ảnh hưởng thế nào tới bài mới |

**Vì sao không chọn:**
- **#3 Report tuần:** trùng chủ đề với ví dụ mẫu Weekly Report, dễ bị xem là copy ví dụ; mỗi report chỉ 15 phút nên impact nhỏ hơn.
- **#4 Trích xuất top 10:** mỗi content chỉ mất 5 phút; giải pháp gần như chắc chắn là tool scrape đổ vào Google Sheet (No AI / Rule) nên ít chỗ để so sánh; đây là workflow của chị content SEO, tôi không trực tiếp làm nên hiểu chưa đủ sâu.

### 2.2. Problem Cards chi tiết

> Ghi chú: thời gian từng bước trong workflow là **ước lượng** của tôi; tổng thời gian mỗi lần là số thực tế.

---

#### Problem Card #1 — Lọc báo GP/PR

```text
Problem 1 câu: Mỗi lần lên plan offpage, tôi phải lọc tay qua 2-3 file báo giá của
supplier (Excel/PDF khác định dạng) và tra DR/traffic trên Ahrefs để chọn báo GP/PR
theo yêu cầu dự án, mất 30-40 phút mỗi lần.

Actor: SEO specialist (tôi) tại agency, phụ trách 5 dự án.

Thời điểm / bối cảnh: 1-2 lần/dự án/tháng, khi lên plan mua báo GP/PR
(Guest Post / PR = mua bài đăng trên báo khác để có backlink về site client).

Current workflow 3-7 bước:
1. Lấy file báo giá mới nhất từ 2-3 supplier (~5', ước lượng)
2. Mở từng file, đọc cấu trúc cột — mỗi file đặt tên cột, đơn vị giá khác nhau (~5', ước lượng)
3. Lọc báo theo chủ đề dự án — đọc tên báo/chuyên mục để đoán chủ đề (~10', ước lượng)
4. Tra DR, traffic trên Ahrefs cho các domain còn lại (~10', ước lượng)
5. Tổng hợp danh sách báo đạt vào sheet đề xuất (~5', ước lượng)

Bottleneck: Bước 2-3. Dữ liệu nằm rải rác ở nhiều file khác định dạng, không có một
nơi để tra cứu chung. Mỗi yêu cầu kiểu "báo chủ đề X, traffic trên 2000, vendor
Ánh Tuyết" lại phải mở từng file và lọc từ đầu.

Impact: 5 dự án × 1-2 lần/tháng × 30-40 phút ≈ 2,5-6,5 giờ/tháng. Thời gian này
lặp lại mỗi tháng và tăng theo số dự án/supplier.

Success metric: Thời gian mỗi lần lọc 30-40 phút → ≤ 10 phút (bấm giờ 3 lần lọc tiếp
theo). Danh sách lọc ra đúng yêu cầu ≥ 90% (tôi kiểm tay từng báo trong danh sách).

Non-AI alternative: Gộp tất cả file supplier vào 1 Google Sheet master với cột chuẩn
(domain, vendor, chủ đề, giá, DR, traffic); lấy DR/traffic hàng loạt bằng Ahrefs
Batch Analysis; lọc bằng Filter view theo từng yêu cầu.

AI hypothesis: AI hỗ trợ 2 chỗ: (1) đọc file PDF/Excel khác định dạng và map về cột
chuẩn khi supplier gửi file mới; (2) gán chủ đề cho domain và hiểu yêu cầu viết bằng
câu tự nhiên để chuyển thành bộ lọc. Phần lọc theo số (traffic, vendor, giá) là
Rule, không cần AI. Nếu AI gán sai chủ đề → tôi phát hiện khi review danh sách cuối.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow   (Rule là nền; AI chỉ chuẩn hóa file + gán chủ đề)
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — 30-40 phút/lần

[1 Lấy file supplier: 5'] → [2 Đọc cấu trúc từng file: 5'] → [3 Lọc theo chủ đề: 10']  <-- bottleneck
→ [4 Tra Ahrefs từng domain: 10'] → [5 Tổng hợp sheet đề xuất: 5']

FUTURE STATE — ~10 phút/lần

[1 Supplier gửi file mới → AI chuẩn hóa vào Sheet master: tự động]
→ [2 Ahrefs batch cập nhật DR/traffic: tự động]
→ [3 Tôi nhập yêu cầu → Rule filter: 1']
→ [4 Tôi review danh sách: 7']  <-- human boundary
→ [5 Xuất sheet đề xuất: 2']

Fallback: nếu AI map sai cột hoặc gán sai chủ đề → tôi sửa trực tiếp trên Sheet
master, hoặc quay về lọc tay trên file gốc của supplier.
```

---

#### Problem Card #2 — QC content theo brand guideline

```text
Problem 1 câu: Mỗi tuần, mỗi dự án có QC có khoảng 5 bài cần kiểm theo brand
guideline riêng của client; người QC phải đọc từng bài và đối chiếu thủ công,
mất khoảng 15 phút/bài.

Actor: SEO specialist (tôi) và chị content SEO.

Thời điểm / bối cảnh: Sau khi vendor/writer nộp bài, trước khi gửi client hoặc đăng
bài; hiện có 2 dự án cần QC.

Current workflow 3-7 bước:
1. Mở brand guideline của client tương ứng (~2', ước lượng)
2. Đọc bài, check từng tiêu chí: giọng văn, từ cấm, format, keyword... (~10', ước lượng)
3. Ghi lỗi, comment cho writer (~3', ước lượng)
4. Writer sửa → QC lại lần 2 (chưa đo)

Bottleneck: Bước 2. Mỗi client một guideline nên phải vừa đọc bài vừa tra lại
guideline; QC nhiều bài liên tiếp dễ sót tiêu chí. Lỗi hay gặp nhất là bài không
đúng chuẩn brand guideline.

Impact: 2 dự án × 5 bài/tuần × 15 phút = 150 phút/tuần (~10 giờ/tháng), chia cho
2 người. Lỗi lọt qua QC có thể khiến client trả bài (chưa đo tỷ lệ).

Success metric: Thời gian QC 15 phút/bài → ≤ 7 phút/bài (bấm giờ 10 bài).
Tỷ lệ bài bị client trả về vì sai guideline: ghi log 2 tuần để có baseline,
mục tiêu không tăng khi rút ngắn thời gian QC.

Non-AI alternative: Chuyển guideline mỗi client thành checklist 10-15 mục dạng tick;
các tiêu chí đo được bằng máy (độ dài, heading, keyword, từ cấm) thì check bằng
tool/Rule.

AI hypothesis: AI đọc bài cùng checklist guideline, đánh dấu vi phạm theo từng tiêu
chí kèm trích dẫn đoạn vi phạm; người QC chỉ xác nhận và quyết định. Phần giọng
văn / brand voice là phần mơ hồ: AI chỉ gợi ý, người chốt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~15 phút/bài

[1 Mở guideline: 2'] → [2 Đọc + check từng tiêu chí: 10']  <-- bottleneck
→ [3 Comment cho writer: 3'] → [4 QC lại: ?']

FUTURE STATE — ~7 phút/bài

[1 Rule check tiêu chí đo được (độ dài, heading, từ cấm): <1']
→ [2 AI check theo checklist guideline + trích đoạn lỗi: 1']
→ [3 Người QC xác nhận / sửa comment: 5']  <-- human boundary
→ [4 Gửi writer: 1']

Fallback: nếu AI báo sai hoặc bỏ sót → người QC vẫn đọc lướt toàn bài và quay về
checklist thủ công; nếu tỷ lệ AI báo sai cao, dừng dùng AI cho dự án đó.
```

---

#### Problem Card #3 — Internal link cho dự án book content

```text
Problem 1 câu: Với dự án book content (~20 bài/tháng), mỗi bài mới tôi phải tự tìm
bài liên quan trên site, chọn anchor và chèn internal link, tối thiểu 15 phút/bài.

Actor: SEO specialist (tôi).

Thời điểm / bối cảnh: Mỗi khi có bài mới, trước khi đăng; hiện có 2 dự án book content.

Current workflow 3-7 bước:
1. Đọc bài mới, xác định chủ đề / keyword chính (~3', ước lượng)
2. Tìm bài liên quan trên site (site: search, sitemap, sheet danh sách bài) (~5', ước lượng)
3. Chọn anchor text và vị trí chèn trong bài (~4', ước lượng)
4. Chèn link; thêm link từ bài cũ về bài mới nếu cần (~3', ước lượng)

Bottleneck: Bước 2. Tìm bài liên quan phụ thuộc trí nhớ; site càng nhiều bài càng
lâu và càng dễ bỏ sót bài phù hợp.

Impact: 2 dự án × 20 bài/tháng × ≥ 15 phút ≈ ≥ 10 giờ/tháng. Bỏ sót link khiến bài
mới thiếu hỗ trợ từ bài cũ (giả định, chưa đo).

Success metric: Thời gian 15 phút/bài → ≤ 5 phút/bài (bấm giờ 10 bài).
Tỷ lệ link được đề xuất mà tôi chấp nhận ≥ 70%.

Non-AI alternative: Sheet mapping keyword chính → URL cho toàn bộ bài trên site;
hoặc plugin tự chèn link theo keyword (dạng Link Whisper, Internal Link Juicer nếu
site dùng WordPress) — tức là Rule.

AI hypothesis: AI đọc bài mới cùng danh sách bài hiện có, đề xuất 3-5 bài liên quan
theo search intent kèm anchor và vị trí chèn. Rule khớp keyword chính xác dễ bỏ sót
bài cùng intent nhưng khác từ khóa — đây là chỗ AI có thể tốt hơn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow   (Rule mapping keyword làm nền, AI gợi ý bổ sung)
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ≥ 15 phút/bài

[1 Đọc bài: 3'] → [2 Tìm bài liên quan: 5']  <-- bottleneck
→ [3 Chọn anchor + vị trí: 4'] → [4 Chèn link: 3']

FUTURE STATE — ~5 phút/bài

[1 Rule: match keyword → URL từ sheet mapping: tự động]
→ [2 AI đề xuất thêm bài cùng intent + anchor + vị trí: 1']
→ [3 Tôi duyệt, bỏ link không hợp: 3']  <-- human boundary
→ [4 Chèn link: 1']

Fallback: nếu AI đề xuất link không liên quan → bỏ qua, dùng danh sách từ Rule hoặc
tìm tay. AI chỉ đề xuất, không tự chèn link lên site.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Lọc báo GP/PR
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là việc tôi trực tiếp làm, lặp lại đều 1-2 lần/dự án/tháng trên cả 5 dự án,
mỗi lần 30-40 phút (khoảng 2,5-6,5 giờ/tháng). Workflow rõ 5 bước, bottleneck cụ
thể: dữ liệu báo nằm rải rác ở 2-3 file supplier khác định dạng, không có nơi tra
cứu chung. Bài này so sánh Rule / Workflow / Agent rất rõ vì phần lọc theo số chỉ
cần Rule, AI chỉ cần ở bước chuẩn hóa file và gán chủ đề.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Chỉ cần gộp file vào 1 Sheet master + dùng filter (Rule) đã giải được 80% chưa?
   AI có thật sự cần không?
2. Chỗ nghẽn thật là gom dữ liệu từ nhiều file, hay là gán chủ đề cho từng báo?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
  - Card Lọc báo GP/PR: AI hỏi "ngưỡng từng ngành" cụ thể là gì. Thực tế không có ngưỡng cố định — tôi chỉ cần một nơi để đưa ra yêu cầu (chủ đề, traffic, vendor) và nhận lại danh sách báo.
  - Card Internal link: AI chỉ ra "xây dựng mô hình internal linking cho cả site" quá rộng cho lab và chưa phải pain.
- Tôi sửa gì:
  - Đổi bottleneck của card Lọc báo GP/PR từ "đối chiếu ngưỡng Ahrefs" thành "không có nơi tra cứu chung, mỗi yêu cầu phải lọc lại từ đầu".
  - Thu hẹp card Internal link về pain cụ thể: thời gian tìm bài liên quan và chèn link cho từng bài mới (≥ 15 phút/bài).

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
