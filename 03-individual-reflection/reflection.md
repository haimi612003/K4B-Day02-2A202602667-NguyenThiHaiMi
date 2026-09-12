# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thị Hải Mi
- Mã học viên: 2A202602667
- Nhóm: Nguyễn Đức Đồng, Mai Huy Hoàng, Trần Nguyễn Trí Dũng, Nguyễn Thùy Linh, Nguyễn Thị Hải Mi
- Candidate problem nhóm chọn: Gom context trước khi review PR — reviewer phải tìm và đọc ticket, code liên quan và lịch sử thay đổi ở nhiều nơi trước khi hiểu đủ bối cảnh để đánh giá rủi ro của PR.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 5 problems từ công việc SEO specialist ở agency (lọc báo GP/PR, internal link, report tuần, trích xuất content top 10, QC content), bổ sung số liệu thật: tần suất, phút/lần, số dự án | Có 5 problems đủ actor + số đo; chọn top 3: Lọc báo GP/PR, QC content, Internal link |
| Pitch Problem Card | Pitch card Lọc báo GP/PR: 1-2 lần/dự án/tháng × 5 dự án, 30-40 phút/lần, bottleneck là dữ liệu nằm rải rác ở 2-3 file supplier khác định dạng | Card được đưa vào bảng 3.1; nhóm nhận xét "lặp lại hằng tháng, workflow rõ, so sánh R/W/A rất rõ" |
| Challenge bài của bạn khác | Khi tổng hợp báo cáo, chỉ ra bài nhóm chọn (Review PR) chưa có trong bảng 3.1 và cluster cũ không khớp số thứ tự candidate | Nhóm bổ sung bảng 3.1 lên 15 candidate (đủ 3 bài/người), bài được chọn có nguồn gốc rõ trong nhật ký hội tụ |
| Gom trùng / cluster | Gom lại 15 candidate thành 4 cluster theo người gặp vấn đề: kỹ thuật phần mềm, học tập/đồ án, CSKH, vận hành SEO/Content | Nhật ký hội tụ liền mạch: 15 candidate → 4 cluster → shortlist → score → 1 bài |
| Chọn candidate problem | Tham gia chấm điểm; chấp nhận để nhóm chọn Review PR thay vì bài GP/PR của mình | Nhóm chọn bài có tổng điểm cao nhất ở bảng 3.4; điểm "pain có evidence" và "impact đo được" được hạ xuống 3 vì chưa có số đo |
| Validation / research | Kiểm tra nguồn cho các con số trên slide nhóm; tìm tài liệu chính thức của CodeRabbit, Codex, PR-Agent, Graphite | Phát hiện con số "4-10 giờ/tuần" chưa có nguồn và "false positive 15-25%" không khớp nguồn (5-15%) → không dùng làm bằng chứng |
| Workflow nhóm | Rà bảng before/after: sửa số bước thủ công 2-3 → 3, thống nhất định nghĩa metric "tổng công sức chuẩn bị context" | Workflow trước/sau và bảng impact nhất quán với nhau |
| Problem Statement | Ghi lại phần phản biện PS v0 (baseline chưa đo, metric lệch định nghĩa, actor quá rộng) và đưa vào PS v1 | PS v1 thu hẹp actor, dùng metric chính "thời gian reviewer gom context 30 → ≤20 phút/PR" |
| Rule / Workflow / Agent | Tổng hợp nội dung slide 5 vào bảng so sánh R/W/A và 5 câu hỏi chốt | Nhóm chốt Workflow, có Rule (PR template) làm nền |
| Decision | Tổng hợp lý do dẫn tới Not Yet: baseline đều là giả định, chưa validate, chưa thử PR template | Quyết định Not Yet kèm kế hoạch validate, pilot 10 PR và điều kiện rollback |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người tổng hợp bản báo cáo nhóm: gom bản của các thành viên, chỉ ra chỗ mâu thuẫn
(bài được chọn không có trong bảng 3.1, cluster lệch số, con số trên slide chưa có nguồn)
để nhóm sửa, và giữ cho metric, workflow và quyết định Not Yet khớp với nhau.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ Claude đối chiếu 5 problems với yêu cầu đề bài, chỉ ra thông tin còn thiếu | Chỉ ra bảng scan thiếu số liệu; problem Internal link đang viết như task; Report tuần trùng ví dụ mẫu | Giả định cả 5 dự án đều có QC content (~6 giờ/tuần) | Sửa lại: chỉ 2 dự án có QC → ~150 phút/tuần; bổ sung số dự án book content, thời gian report, đơn vị "5 phút/10 trang" |
| Problem Card | Nhờ AI trình bày top 3 thành Problem Card + workflow trước/sau | Giúp card đủ field, có fallback và human boundary | Tự chia thời gian từng bước; đề xuất pitch card QC content | Tôi chọn pitch card Lọc báo GP/PR vì đây là việc tôi trực tiếp làm và hiểu rõ nhất |
| Workflow | Nhờ AI rà workflow nhóm và bảng before/after | Phát hiện số bước thủ công ghi "2-3" trong khi future workflow có 3 bước HUMAN; metric dùng 2 định nghĩa khác nhau | — | Thống nhất metric và sửa số bước theo workflow thật của nhóm |
| Research | Nhờ AI tìm tài liệu về các tool AI review PR và kiểm tra con số trên slide | Tìm được tài liệu chính thức có link; chỉ ra CodeRabbit không đọc thread thảo luận của issue | Nhận định "chưa tool nào nối ticket" trên slide ban đầu chưa chính xác — CodeRabbit và PR-Agent đều đọc được ticket | Sửa khoảng trống thành phần "vì sao" (thread quyết định, PR/commit cũ, đánh dấu phần thiếu); bỏ các con số không có nguồn |
| Problem Statement | Nhờ AI phản biện PS v0 | Chỉ ra baseline 40 phút và 3 lượt hỏi chưa có nguồn, actor gộp nhiều vai trò | — | Ghi rõ baseline cần đo trên 10 PR; thu hẹp actor ở PS v1 |
| Rule / Workflow / Agent | Nhờ AI chuyển nội dung slide 5 của nhóm thành bảng so sánh và 5 câu hỏi chốt | Giải thích được vì sao bài rơi vào ô phức tạp cao/mơ hồ cao mà vẫn chọn Workflow | — | Giữ lựa chọn Workflow và điều kiện "thử PR template trước" theo slide nhóm |
| Decision | Nhờ AI tổng hợp các câu hỏi quyết định | Chỉ ra chưa thể Go vì chưa có số đo và chưa thử cách non-AI | — | Chốt Not Yet và đưa kế hoạch validate lên trước pilot |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Nghe top 3 của các bạn, tôi thấy mỗi người nhìn vấn đề từ đúng công việc của mình: các
bạn khác nói về lập trình, tài liệu học tập và CSKH, còn tôi mang vào các bài SEO ở agency.
Bài của tôi (lọc báo GP/PR) có số đo khá rõ, nhưng nhóm chọn bài review PR vì bài này có
tổng điểm cao nhất ở bảng chấm; tôi đồng ý vì phần lớn candidate của các bạn là bài về lập
trình, nên bài review PR gần với công việc của nhiều thành viên hơn bài SEO của tôi.

Tôi có thay đổi ý kiến sau khi bị chỉ ra điểm yếu: ở bài cá nhân, tôi tưởng internal link
là một bài "xây dựng mô hình", nhưng khi viết lại thì pain thật là mất ≥15 phút cho mỗi
bài mới; con số QC content tôi cũng phải sửa từ ước lượng sang số dự án thật.

Điều khó nhất khi viết Problem Statement là metric: nhóm đưa ra các con số 40 phút/PR,
3 lượt hỏi/PR nhưng bảng workflow lại ghi "chưa đo" ở mọi bước, và cùng một con số 40
phút lại được gọi bằng hai tên khác nhau. Việc tách "thời gian reviewer gom context" khỏi
thời gian đọc diff và chờ phản hồi giúp metric đo đúng bottleneck hơn.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở bước chấm điểm: lúc đầu bài review PR được
chấm 5 điểm "pain có evidence" dù chưa phỏng vấn hay đo PR nào, đến khi rà lại báo cáo nhóm
mới hạ xuống 3. Tôi sẽ đề nghị nhóm quan sát ít nhất
2-3 phiên review thật trước khi chấm, để quyết định cuối không phải dừng ở Not Yet chỉ vì
thiếu bằng chứng.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
