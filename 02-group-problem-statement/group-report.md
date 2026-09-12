# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Đức Đồng | 2A202602367 | Lên ý tưởng; làm báo cáo (report) |
| 2   | Mai Huy Hoàng | 2A202602685 | Lên ý tưởng; xây dựng bản trình bày chi tiết bối cảnh (context) |
| 3   | Trần Nguyễn Trí Dũng | 2A202602784 | Lên ý tưởng; thiết kế quy trình (workflow: before – after) |
| 4   | Nguyễn Thùy Linh | 2A202602497 | Lên ý tưởng; làm bản mẫu sản phẩm (prototype) |
| 5   | Nguyễn Thị Hải Mi | 2A202602667 | Lên ý tưởng; phân chia công việc; làm báo cáo (report) |

**Candidate problem nhóm chọn (1 câu):**
Gom và tổng hợp context (ticket, code liên quan, lịch sử thay đổi) khi review PR để nhận ra rủi ro kỹ thuật.


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Đức Đồng | Debug runtime error & đọc tài liệu framework khi làm bài tập lập trình | Sinh viên CNTT | Đảo 15-20 tab StackOverflow không khớp phiên bản | Pain rất thật, xảy ra hằng ngày, thời gian lãng phí cực lớn |
| 2 | Nguyễn Đức Đồng | Tra từ vựng chuyên ngành ngữ cảnh kép khi đọc tài liệu tiếng Anh | Sinh viên kỹ thuật | Chuyển tab 30+ lần/buổi tra từ điển thô | Tốt nhưng đã có một số tiện ích tra từ điển hỗ trợ |
| 3 | Nguyễn Đức Đồng | Lên kế hoạch task tuần thiếu Definition of Done (DoD) gây nghẽn bài tập nhóm | Nhóm đồ án | Task mô tả chung chung, trễ hạn ghép code | Đau chung cho cả nhóm, ảnh hưởng trực tiếp tiến độ môn học |
| 4 | Mai Huy Hoàng | Gom và hiểu context (ticket, code, lịch sử) khi review PR | Reviewer / Engineer | Đọc ticket, code liên quan và lịch sử ở nhiều nơi thủ công | Tốn nhiều thời gian nhất tuần theo ghi nhận cá nhân, bottleneck khâu gom context rất rõ |
| 5 | Mai Huy Hoàng | Đánh giá khả năng ảnh hưởng của cảnh báo dependency vulnerability | Dev / Security Team | Đọc từng advisory, kiểm tra dependency có dùng và đánh giá rủi ro thủ công | Cảnh báo lặp lại hằng ngày, khoanh vùng ở bước đánh giá tác động tốt |
| 6 | Mai Huy Hoàng | Thu thập context và phân loại (triage) bug production | Team Dev / Triage Team | Đọc log, tái hiện lỗi, xác định severity và tìm owner thủ công | Đầu việc hằng tuần, ảnh hưởng nhiều vai trò, bug thiếu context làm triage kéo dài |
| 7 | Trần Nguyễn Trí Dũng | Tìm kiếm và lọc tài liệu tham khảo phù hợp yêu cầu bài tập | Sinh viên / Developer | Mở từng nguồn đọc và lọc thủ công vì không có giới hạn tìm kiếm | Tốn nhiều thời gian mở từng nguồn xác định độ phù hợp |
| 8 | Trần Nguyễn Trí Dũng | Tìm lại thông tin task và deadline cũ bị trôi trên Discord | Thành viên nhóm đồ án | Phải lội lại các tin nhắn cũ trên Discord để xác định task, deadline | Phổ biến, gây gián đoạn công việc và dễ hiểu sai yêu cầu |
| 9 | Trần Nguyễn Trí Dũng | Đánh giá và sắp xếp tài liệu học tập theo mức độ liên quan | Sinh viên cá nhân | Đọc và đánh giá từng tài liệu để xác định chủ đề, độ khó và thứ tự học | Có vấn đề nhưng mức độ ảnh hưởng chưa lớn bằng 2 bài toán trên |
| 10 | Nguyễn Thùy Linh | Trả lời các câu hỏi lặp lại của khách hàng về giá, sản phẩm và chính sách | Nhân viên CSKH | Trả lời lặp đi lặp lại cùng các câu hỏi giống nhau thủ công | Vấn đề xảy ra lặp lại nhiều lần, actor CSKH rõ ràng, đo được số câu hỏi |
| 11 | Nguyễn Thùy Linh | Đọc từng tin nhắn khách hàng và tìm thông tin trả lời thủ công | Nhân viên CSKH / Sales | Nhận tin nhắn, tra cứu thông tin và phản hồi từng yêu cầu thủ công | Workflow rõ ràng từ nhận tin nhắn đến xử lý yêu cầu |
| 12 | Nguyễn Thùy Linh | Khách hàng phải chờ phản hồi lâu khi nhân viên bận hoặc ngoài giờ | Khách hàng / CSKH | Phản hồi chậm khi nhân viên ngoài giờ hoặc bận việc khác | Actor và pain rõ ràng, ảnh hưởng trực tiếp tới trải nghiệm khách hàng |
| 13 | Nguyễn Thị Hải Mi | Lọc báo GP/PR hằng tháng theo số (traffic, vendor, giá) và chủ đề | Nhân viên Marketing / SEO | Lọc báo thủ công theo tiêu chí số và gán chủ đề trên 5 dự án | Lặp lại hằng tháng, workflow 5 bước rõ ràng, so sánh R/W/A rất rõ |
| 14 | Nguyễn Thị Hải Mi | Kiểm tra chất lượng nội dung (QC content) theo guideline riêng của client | Nhân viên QC / Content | Đọc và kiểm tra giọng văn/brand voice theo guideline riêng của client | Mất ~10 giờ/tháng, cần hiểu ngữ cảnh sâu của từng client |
| 15 | Nguyễn Thị Hải Mi | Chèn và quản lý Internal link bài viết cho dự án content | Nhân viên SEO / Editor | Đánh giá và chèn thủ công link bài viết liên quan theo keyword | Tốn ≥10 giờ/tháng cho 2 dự án book content |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A | Candidate 1, 4, 5, 6 | Kỹ thuật phần mềm: gom context, đánh giá lỗi & rủi ro code | Reviewer/dev phải tự gom thông tin rải rác (ticket, log, advisory, lịch sử code) trước khi đánh giá; thời gian đo được bằng phút |
| B | Candidate 2, 3, 7, 8, 9 | Học tập & làm việc nhóm đồ án: tra cứu tài liệu, làm rõ task | Sinh viên mất thời gian lọc tài liệu và tìm lại/làm rõ task, deadline; nhiều bài phụ thuộc thói quen, quy trình nhóm |
| C | Candidate 10, 11, 12 | CSKH: trả lời tin nhắn & câu hỏi lặp lại của khách hàng | Câu hỏi lặp lại, tra cứu thủ công, phản hồi chậm ngoài giờ; đo được số câu hỏi và thời gian phản hồi |
| D | Candidate 13, 14, 15 | Vận hành SEO/Content: lọc, kiểm tra, liên kết theo tiêu chí | Việc lặp lại theo tiêu chí/guideline có sẵn; phần lớn giải được bằng Rule, AI chỉ ở bước cần hiểu ngữ cảnh |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| 1. Gom và hiểu context (ticket, code, lịch sử) khi review PR | Là việc tốn nhiều thời gian nhất tuần theo ghi nhận cá nhân; bottleneck rõ ở bước gom và hiểu context; có thể đo phút chuẩn bị context/PR và thời gian engineer chờ review. | Chưa đo thời gian trên từng PR; cần phân biệt thời gian tìm context với thời gian đọc và đánh giá code. |
| 2. Debug runtime error & đọc tài liệu framework khi làm bài tập lập trình | Tần suất gặp cực cao (2-3 lần/tuần/người), mất 90-120 phút/buổi; actor rõ (sinh viên IT); workflow 5 bước đo lường chính xác. | Rủi ro AI giải thích sai ngữ cảnh sâu của codebase lớn hoặc phụ thuộc vào phiên bản thư viện nội bộ. |
| 3. Tra từ vựng chuyên ngành ngữ cảnh kép khi đọc tài liệu tiếng Anh | Hành động lặp lại tần suất cao (30+ lần/buổi đọc); giảm ngắt quãng luồng tư duy khi tự đọc tài liệu chuyên ngành. | Đã có một số tiện ích mở rộng tra từ điển pop-up trên trình duyệt đáp ứng một phần nhu cầu. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| 1. Gom và hiểu context khi review PR | 5 | 5 | 3 | 3 | 5 | 5 | 4 | **30** |
| 2. Debug runtime error & đọc tài liệu framework | 5 | 4 | 4 | 4 | 4 | 4 | 4 | **29** |
| 3. Tra từ vựng chuyên ngành tiếng Anh | 4 | 4 | 4 | 4 | 4 | 3 | 4 | **27** |

**Ghi chú chấm điểm:**
- Review PR được 5 ở "Workflow rõ" vì các bước đọc PR → gom context → hỏi tác giả → review diff → approve đi thẳng một đường và ai cũng mô tả giống nhau; 5 ở "So sánh R/W/A" vì có sẵn phương án Rule (PR template) để so với Workflow có AI.
- Review PR chỉ được 3 ở "Pain có evidence" và "Impact đo được" vì pain mới dựa trên ghi nhận cá nhân của thành viên đề xuất, chưa có số đo — nhóm ghi nhận đây là điểm cần kiểm chứng ở Phase 4. Dù vậy tổng điểm vẫn cao nhất (30 so với 29 và 27).
- Tra từ vựng chỉ được 3 ở "So sánh R/W/A" vì giải pháp gần như chỉ là tiện ích tra từ có sẵn, ít chỗ để so sánh các mức.

**Candidate nhóm chọn (1 bài duy nhất):** Gom và hiểu context khi review PR

```text
Problem 1 — Gom context trước khi review PR: reviewer phải tìm và đọc ticket, code liên quan và lịch sử thay đổi ở nhiều nơi trước khi hiểu đủ bối cảnh để đánh giá rủi ro của PR.
```

**Vì sao chọn (4-5 câu):**

```text
Đây là vấn đề thực tế gắn với hoạt động review code thường xuyên trong quá trình phát triển phần mềm; reviewer luôn cần hiểu mục đích và bối cảnh thay đổi để đánh giá đúng.
Khi thông tin nằm rải rác hoặc mô tả PR chưa đầy đủ, reviewer phải mất thêm công tìm kiếm và hỏi lại, còn tác giả PR phải chờ phản hồi để tiếp tục công việc.
Problem có người gặp và điểm nghẽn rõ, nên nhóm có thể tập trung vào bước gom và hiểu context trước khi đánh giá code, với phạm vi phù hợp để kiểm chứng trong lab.
Nhóm có thể đo thời gian chuẩn bị context, số lượt hỏi bổ sung và tổng công sức của tác giả lẫn reviewer để đánh giá mức cải thiện; hiện các con số vẫn là giả định cần kiểm chứng.
Bài toán cũng cho phép so sánh cách cải thiện quy trình bằng PR template với workflow có AI tóm tắt và dẫn nguồn, trong khi reviewer vẫn chịu trách nhiệm đánh giá code và quyết định approve.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Candidate 2 — Debug runtime error và đọc tài liệu framework khi làm bài tập lập trình: đây là vấn đề thiết thực, nhưng đang gộp hai hoạt động khá rộng; nhóm cần làm rõ sinh viên mắc ở bước hiểu lỗi, tìm tài liệu hay áp dụng cách sửa trước khi chọn hướng can thiệp.
Thời gian giải quyết còn phụ thuộc vào kiến thức nền, độ khó của lỗi và phiên bản framework, nên khó so sánh hiệu quả giữa các ca; nếu dùng AI, cũng cần kiểm tra sinh viên có hiểu cách sửa hay chỉ làm cho code chạy được.
Vì vậy, nhóm tạm chưa chọn candidate này và ưu tiên gom context khi review PR vì điểm nghẽn đã được khoanh rõ hơn, có thể đo riêng thời gian chuẩn bị context và số lượt hỏi bổ sung trong phạm vi lab.

Candidate 3 — Tra từ vựng chuyên ngành ngữ cảnh kép khi đọc tài liệu tiếng Anh: pain có thật và lặp lại nhiều (30+ lần/buổi đọc), nhưng mỗi lần tra chỉ mất vài giây nên impact khó đo bằng thời gian.
Các tiện ích tra từ pop-up trên trình duyệt đã đáp ứng một phần nhu cầu, nên phần còn lại để cải thiện hẹp và khó so sánh Rule / Workflow / Agent (điểm thấp nhất ở tiêu chí này).
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Không có bất đồng lớn. Nhóm thống nhất chọn Review PR dựa trên bảng điểm 3.4.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Kế hoạch: 2-3 reviewer + tác giả của cùng 3-5 PR gần đây có trao đổi bổ sung context. **Chưa thực hiện** | Chưa có (chưa phỏng vấn). Câu hỏi dự kiến: "Ở PR này bạn thiếu thông tin gì?", "Bạn tìm nó ở đâu?", "Thông tin nào nếu có sẵn sẽ giúp review nhanh hơn?" | Chưa có | — |
| Survey / poll | Không thực hiện | — | — | Nhóm ưu tiên quan sát thực tế và PR thật thay vì survey, vì lời kể dễ lệch so với thời gian thực. |
| Log / ticket / review (nếu có) | Kế hoạch: quan sát trực tiếp 2-3 phiên review, bấm giờ từng bước; đọc comment hỏi bổ sung context trong PR. **Chưa thực hiện** | Chưa có | Lưu ý từ khâu thiết kế đo: thời gian từ mở PR đến approve còn gồm thời gian chờ và sửa code, nên không dùng riêng để kết luận thời gian gom context | Nhóm bỏ mốc giả định 75 phút/PR (cho toàn bộ việc review) và tách riêng metric "thời gian reviewer gom và hiểu context" |
| Nghiên cứu đã công bố (bằng chứng thứ cấp) | 1 nghiên cứu: Bacchelli & Bird, *Expectations, Outcomes, and Challenges of Modern Code Review*, ICSE 2013, Microsoft Research — [link](https://www.microsoft.com/en-us/research/publication/expectations-outcomes-and-challenges-of-modern-code-review/) | Nhóm tác giả quan sát, phỏng vấn, khảo sát developer/manager và phân loại thủ công hàng trăm comment review ở nhiều team tại Microsoft. Kết luận: *"code and change understanding is the key aspect of code reviewing and that developers employ a wide range of mechanisms to meet their understanding needs"*, và các nhu cầu hiểu này phần lớn chưa được công cụ hiện có đáp ứng | Nghiên cứu năm 2013, tại một công ty lớn; chưa đo riêng thời gian gom context, và chưa chắc đúng với team nhỏ hoặc repo của nhóm | Xác nhận bottleneck nằm ở bước **hiểu thay đổi / hiểu context**, không phải đọc diff → giữ trọng tâm vào bước gom và hiểu context; thời gian thực tế vẫn cần đo trên PR của team |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Nghiên cứu của Microsoft (Bacchelli & Bird, 2013) xác nhận hướng của problem: hiểu
thay đổi / hiểu context là khía cạnh then chốt của code review và công cụ hiện có chưa
đáp ứng tốt nhu cầu này. Tuy vậy nhóm chưa phỏng vấn hay đo trên PR của chính team, nên
mức độ (bao nhiêu phút, bao nhiêu lượt hỏi) vẫn chưa được kiểm chứng. Giả thuyết hiện tại:
reviewer mất công chủ yếu ở phần context "vì sao" (mục đích, ràng buộc, lý do
thiết kế nằm ở ticket, PR/commit cũ và thread trao đổi), không phải ở việc đọc diff.
Từ giả thuyết này, nhóm thu hẹp problem vào PR chạm module lạ hoặc có context nằm ở
nhiều nguồn (không phải mọi PR), và tập trung vào gom – nối – tóm tắt context trước khi
reviewer đánh giá code, thay vì xây dựng một AI tự review code.
```

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| CodeRabbit — linked issue validation | [docs.coderabbit.ai/issues/pr-validation](https://docs.coderabbit.ai/issues/pr-validation) | Đọc issue được link (GitHub, GitLab, Jira, Linear, Azure DevOps) và đánh giá PR có đáp ứng yêu cầu không (Addressed / Not Addressed / Unclear); comment trực tiếp trên PR | Nối ticket với diff tự động, không cần reviewer tự mở ticket | Output là nhận xét về code / mức đáp ứng yêu cầu, không phải bản tóm tắt context để reviewer đọc trước; theo tài liệu chỉ dùng tiêu đề + mô tả issue, không đọc comment/thread thảo luận — nơi thường chứa lý do thiết kế | Link ticket là input nên bắt buộc (Rule); phần "vì sao" nằm trong thread thì cần nguồn khác ngoài ticket |
| Codex code review (OpenAI) | [developers.openai.com/codex/integrations/github](https://developers.openai.com/codex/integrations/github) | Review diff PR theo hướng dẫn trong `AGENTS.md`, chỉ flag lỗi P0/P1; gọi bằng `@codex review` hoặc bật tự động | Tập trung lỗi nghiêm trọng nên ít nhiễu; guideline nằm trong repo | Trả lời "code có lỗi không", không trả lời "vì sao chọn cách sửa này" | Giới hạn output để giảm nhiễu; lưu guideline trong repo là cách cấp context ổn định cho AI |
| PR-Agent (Qodo Merge bản open source) | [docs.pr-agent.ai](https://docs.pr-agent.ai/) | `/describe` tự sinh mô tả PR (tiêu đề, loại, tóm tắt, walkthrough); `/review`, `/improve`, `/ask`; có khả năng lấy ticket context | Gần nhất với ý tưởng của nhóm: có tóm tắt + walkthrough trước khi mở file; open source, tự host được | Theo tìm hiểu của nhóm, tóm tắt dựng chủ yếu từ diff + ticket; chưa thấy dẫn nguồn tới PR/commit cũ, thread quyết định, và đánh dấu phần tác giả chưa ghi lại (cần thử để xác nhận) | Nếu pilot, nên thử dựa trên `/describe` thay vì tự build từ đầu |
| GitHub Copilot — PR summary | [docs.github.com/.../create-a-pr-summary](https://docs.github.com/en/copilot/how-tos/copilot-on-github/copilot-for-github-tasks/create-a-pr-summary) | Tóm tắt thay đổi của PR vào phần mô tả hoặc comment để reviewer nhanh chóng hiểu PR thay đổi gì | Giảm thời gian đọc ban đầu; summary được tạo trực tiếp trong PR | GitHub khuyến nghị review kỹ bản tóm tắt và tự bổ sung context; Copilot không dùng nội dung mô tả PR đã có | Có thể dùng AI để tóm tắt context, nhưng không coi output là nguồn sự thật cuối cùng |
| GitHub Copilot — Explore pull requests | [docs.github.com/.../explore-pull-requests](https://docs.github.com/en/copilot/tutorials/explore-pull-requests) | Hỏi Copilot Chat về PR: commits, thay đổi theo file/dòng, comment và review đã có | Hỏi trực tiếp trên PR, dùng chính context của PR để giải thích thay đổi | Chủ yếu làm việc với context đã nằm trong PR/repository; vẫn cần reviewer kiểm chứng | Học cách cho AI kết nối nhiều nguồn context và giải thích lại cho reviewer |
| GitHub — Pull request template | [docs.github.com/.../creating-a-pull-request-template](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/creating-a-pull-request-template-for-your-repository) | Tự điền sẵn khung mô tả khi tạo PR để tác giả cung cấp related issue, mục đích, ghi chú test | Giảm context bị thiếu ngay từ đầu; đơn giản, dễ triển khai | Phụ thuộc vào việc tác giả điền đầy đủ và chính xác | Trước khi dùng AI, cần chuẩn hóa input bằng PR template (Rule) |
| Graphite — AI code review false positives | [graphite.com/guides/ai-code-review-false-positives](https://graphite.com/guides/ai-code-review-false-positives) | Bài hướng dẫn về tỷ lệ false positive của AI code review | Đưa ra mức tham chiếu: "5–15%" false positive với các tool AI review hiện nay | Nguồn từ nhà cung cấp tool (có thể thiên vị); đo trên review diff, không đo tóm tắt context | Thêm AI mà không đo chất lượng có thể làm reviewer mất thêm thời gian kiểm tra → phải đo "thông tin sai" trong pilot |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Thị trường đã có nhiều tool AI review diff (CodeRabbit, Codex, PR-Agent) và đã nối
được ticket với code; GitHub Copilot PR summary / Explore PR cũng đã giúp reviewer hiểu
nhanh nội dung thay đổi, còn PR template giúp giảm context thiếu ngay từ lúc tạo PR.
Vì vậy nhóm không build AI tự review code hoặc tự approve PR. Khoảng trống còn lại là
bản tóm tắt context "vì sao" có dẫn nguồn (ticket + PR/commit cũ + thread quyết định)
và đánh dấu phần tác giả chưa ghi lại. Hướng build: PR template chuẩn hóa input → AI
gom và tóm tắt context, dẫn nguồn, chỉ ra phần thiếu → reviewer kiểm chứng và quyết
định; thử PR template trước, dựa trên tool có sẵn và đo trên mẫu nhỏ.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Workflow vẽ dạng ASCII bên dưới.

```text
  [1. Đọc PR: Reviewer]
→ [2. Tìm và nối context từ ticket/code/lịch sử: Reviewer] ← BOTTLENECK
→ [3. Hỏi tác giả phần còn thiếu: Reviewer + Author]
→ [4. Review diff và test: Reviewer]
→ [5. Comment hoặc Approve: Reviewer]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Reviewer | PR, PR description, diff | Hiểu sơ bộ PR thay đổi gì | Chưa đo / mỗi PR | Bắt đầu quá trình review |
| 2 | Reviewer | Ticket, code liên quan, lịch sử thay đổi | Context đủ để hiểu mục đích và phạm vi PR | Chưa đo / mỗi PR | Bottleneck chính: phải tự tìm và nối thông tin từ nhiều nguồn |
| 3 | Reviewer + Author | Câu hỏi / phần context còn thiếu | Thông tin bổ sung từ author | Chưa đo / khi cần | Handoff, có thể phải chờ author |
| 4 | Reviewer | PR diff, test + context đã có | Findings / feedback / đánh giá thay đổi | Chưa đo / mỗi PR | Reviewer thực hiện đánh giá code |
| 5 | Reviewer | Kết quả review | Comment / Request changes / Approve | Chưa đo / mỗi PR | Quyết định cuối cùng thuộc reviewer |

**Bottleneck chính (2-3 câu):**

```text
Bottleneck nằm ở bước 2: reviewer phải tự tìm và nối context
từ ticket, code liên quan và lịch sử thay đổi trước khi có thể
đánh giá PR đầy đủ.

Hiện nhóm chưa đo riêng thời gian của bước này, vì vậy sẽ ghi nhận
phút thực tế trên 10 PR để xác định thời gian chuẩn bị context và
phân biệt nó với thời gian review diff/test.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
  [1. Tác giả bổ sung PR Template và link nguồn — HUMAN]
→ [2. Gom dữ liệu từ các nguồn được cung cấp — RULE/MACHINE]
→ [3. AI tóm tắt context, dẫn nguồn và đánh dấu phần thiếu — AI]
→ [4. Reviewer kiểm chứng, hỏi bổ sung và review diff/test — HUMAN / BOUNDARY]
→ [5. Reviewer Comment hoặc Approve — HUMAN]

Fallback: tóm tắt sai hoặc thiếu nguồn → reviewer đọc nguồn gốc và hỏi tác giả theo workflow hiện tại; không dùng bản tóm tắt làm căn cứ duy nhất để approve.
```

**Đầu ra của bước 3 (AI tóm tắt) — trả lời 5 câu hỏi, mỗi ý có link tới nguồn:**
1. PR này giải quyết vấn đề gì? — link ticket và yêu cầu liên quan.
2. Vì sao chọn cách sửa này? — quyết định hoặc ràng buộc kỹ thuật cần biết.
3. Thay đổi ảnh hưởng đến đâu? — module, luồng xử lý và nơi gọi liên quan.
4. Reviewer cần chú ý gì? — rủi ro dự kiến, giả định và phần chưa đủ thông tin.
5. Đã kiểm tra gì? — test đã chạy, trường hợp chưa được kiểm tra.

Nếu tác giả chưa ghi lại lý do thiết kế, AI không tự đoán mà **đánh dấu phần thiếu** để tác giả bổ sung; tác giả xem và xác nhận bản tóm tắt trước khi gửi reviewer.

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian reviewer gom và hiểu context | 30 phút/PR (giả định, cần đo trên 10 PR) | ≤20 phút/PR | Bấm giờ tìm/đọc ticket, code liên quan và lịch sử thay đổi, tính cả thời gian kiểm chứng tóm tắt AI; tách riêng đọc diff và thời gian chờ trả lời |
| Tổng công sức chuẩn bị context | 40 phút/PR (giả định, cần đo trên 10 PR) | ≤30 phút/PR | Cộng thời gian tác giả viết/kiểm tra mô tả + reviewer gom và kiểm chứng context; không tính thời gian review diff/test |
| Số lần reviewer hỏi bổ sung context | 3 lần/PR (giả định, cần đo trên 10 PR) | ≤1 lần/PR | Đếm số comment/tin nhắn hỏi thêm context trên mỗi PR |
| Số bước | 5 | 5 | Đếm số bước trong workflow |
| Số bước thủ công | 5 | 3 | Đếm các bước cần người trực tiếp tìm, đọc và xử lý (future: bước 1, 4, 5) |
| Bottleneck chính | Reviewer tự tìm và nối context từ ticket/code/lịch sử | AI hỗ trợ gom, tóm tắt và chỉ ra context còn thiếu | So sánh thời gian chuẩn bị context trước/sau |
| Risk mới | Context phân tán, thiếu thông tin | AI tóm tắt sai hoặc bỏ sót context; mục tiêu 0 lỗi nghiêm trọng / 10 PR thử nghiệm | Reviewer đối chiếu nguồn gốc và ghi nhận thông tin sai/thiếu trên từng PR |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Technical Leader, OSS Maintainer hoặc engineer phụ trách review PR, đặc biệt khi PR chạm vào module chưa quen thuộc. Author cũng bị ảnh hưởng vì phải bổ sung context và chờ feedback từ reviewer. |
| **Workflow** | Reviewer đọc PR, sau đó tìm và nối context từ ticket, code liên quan và lịch sử thay đổi. Nếu context chưa đủ, reviewer hỏi author rồi mới tiếp tục review diff và test. |
| **Bottleneck** | Reviewer phải tự tìm và kết nối thông tin từ nhiều nguồn trước khi hiểu đủ context để review. Đây là bước cần được đo riêng để xác định thời gian thực tế dành cho việc gom và hiểu context. |
| **Impact** | Việc chuẩn bị context làm tăng thời gian trước khi reviewer có thể đánh giá code và có thể làm chậm feedback cho author. Nếu context thiếu hoặc hiểu sai, reviewer có thể khó đánh giá đầy đủ mục đích, ràng buộc và phạm vi ảnh hưởng của thay đổi. |
| **Success Metric** | Giảm tổng công sức chuẩn bị context (author viết/kiểm tra mô tả + reviewer gom và kiểm chứng context) từ 40 xuống ≤30 phút/PR trong thử nghiệm. Đồng thời giảm số lần reviewer phải hỏi bổ sung context từ 3 xuống ≤1 lần/PR, với 0 lỗi nghiêm trọng do AI tóm tắt sai trên 10 PR thử nghiệm. Baseline 40 phút và 3 lần/PR hiện là giả định, sẽ đo thực tế trên 10 PR. |
| **Boundary** | AI chỉ hỗ trợ gom, tóm tắt, dẫn nguồn và chỉ ra context còn thiếu. Reviewer vẫn phải kiểm chứng nguồn gốc, đọc diff/test, đánh giá rủi ro và đưa ra quyết định comment hoặc approve cuối cùng. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ:
  - Success Metric: baseline 40 phút/PR và 3 lần hỏi/PR chưa có nguồn đo, trong khi bảng 5.1 ghi "Chưa đo" ở mọi bước.
  - Success Metric: "tổng thời gian" (bảng impact) và "tổng công sức chuẩn bị context" (PS v0) đang là hai định nghĩa khác nhau.
  - Success Metric: "AI không tạo ra thông tin sai nghiêm trọng" chưa đo được.
  - Actor: đang gộp nhiều vai trò (Technical Leader, OSS Maintainer, engineer).
  - Số bước thủ công sau cải thiện ghi "2–3" trong khi future workflow có 3 bước HUMAN.
- Tôi sửa gì:
  - Ghi rõ baseline 40 phút và 3 lần/PR là giả định, sẽ đo thực tế trên 10 PR.
  - Thống nhất định nghĩa "tổng công sức chuẩn bị context/PR" (tác giả + reviewer), không tính thời gian review diff/test; tách số lần hỏi bổ sung thành metric riêng. Ở PS v1, nhóm chọn thời gian reviewer gom context làm metric chính, tổng công sức làm metric phụ.
  - Đổi tiêu chí sai thành "0 lỗi nghiêm trọng / 10 PR thử nghiệm", reviewer ghi nhận khi đối chiếu nguồn.
  - Sửa số bước thủ công sau cải thiện thành 3.
  - Actor sẽ được thu hẹp về một vai trò chính ở Problem Statement v1.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: mục tiêu xử lý đã rõ — bản tóm tắt phải trả lời đúng 5 câu hỏi cố định và mỗi ý phải khớp với nguồn; phần không có nguồn thì đánh dấu thiếu, không để AI tự diễn giải.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: reviewer phải thu thập và nối context từ 3+ nguồn (ticket, diff, code liên quan, PR/commit cũ, thread trao đổi) và bước review phụ thuộc vào context gom được trước đó.

**Bài toán nhóm nằm ở ô nào:**

```text
Bài toán nằm ở ô độ mơ hồ thấp và độ phức tạp cao — theo ma trận: "Workflow điều phối
nhiều bước rõ ràng, chưa chắc cần Agent".
```

**Vì sao (2-3 câu):**

```text
Bài toán nằm ở ô độ mơ hồ thấp và độ phức tạp cao vì mục tiêu xử lý đã khá rõ nhưng
reviewer phải thu thập và kết nối context từ nhiều nguồn. Các bước chính có thể xác
định trước, nhưng cần AI hỗ trợ đọc, tổng hợp và chỉ ra phần context còn thiếu.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | PR template bắt buộc + check tự động: PR có link ticket, mục lý do thay đổi, mục test chưa; nếu thiếu thì nhắc tác giả bổ sung | Khi context thiếu chủ yếu vì tác giả không ghi, và reviewer chỉ cần đọc đủ các mục trong template | Tác giả điền cho có; không giúp nối PR/commit cũ và thread quyết định; reviewer vẫn phải tự mở từng nguồn | **Có** — làm nền bắt buộc ở bước 1 (tác giả điền template + gắn link) |
| **Workflow** | Pipeline cố định: lấy diff + ticket + link nguồn tác giả cung cấp → AI tóm tắt theo 5 câu hỏi, có dẫn nguồn, đánh dấu phần thiếu → tác giả xác nhận → reviewer kiểm chứng và review | Khi nguồn đã được gắn link và reviewer mất thời gian chủ yếu ở việc đọc và nối nhiều nguồn | AI tóm tắt sai hoặc bịa lý do thiết kế; reviewer tin tóm tắt mà không kiểm chứng; công kiểm chứng có thể ăn hết thời gian tiết kiệm được | **Có (đề xuất)** — bước 2-3 (gom dữ liệu + AI tóm tắt) |
| **Agent** | AI tự tìm nhiều vòng: tự lần ticket, PR cũ, thread, code liên quan mà không cần tác giả gắn link | Khi nguồn không được gắn link, repo lớn, và nhu cầu đã được xác nhận bằng số đo | Phạm vi và độ chính xác khó kiểm soát; khó kiểm chứng nguồn; chi phí cao; nhiễu / false positive tăng | **Không** ở giai đoạn đầu |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? — Chưa biết. Nếu phần lớn context thiếu vì tác giả không ghi, PR template có thể giải được phần lớn; vì vậy nhóm thử Rule trước và dùng nó làm mốc so sánh cho AI.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? — Đi thẳng: tác giả điền template → gom nguồn → AI tóm tắt → tác giả xác nhận → reviewer kiểm chứng. Nhánh duy nhất là khi thiếu thông tin thì quay lại hỏi tác giả, giống workflow hiện tại.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? — Không, vì nguồn do tác giả cung cấp qua link; AI chỉ cần đọc và tóm tắt các nguồn đó, không cần tự quyết định tìm ở đâu.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? — Tác giả phát hiện đầu tiên khi xác nhận bản tóm tắt trước khi gửi; nếu lọt, reviewer phát hiện khi mở nguồn đối chiếu ở bước 4, ngay trong phiên review đó.
5. Có hạ được từ Agent → Workflow → Rule không? — Đã hạ từ Agent xuống Workflow. Có thể hạ tiếp xuống Rule (chỉ dùng PR template) nếu pilot cho thấy template đã đạt metric mà không cần AI.

**Mức chọn:**

```text
Workflow (có Rule làm nền)
```

**Vì sao chọn (3-4 câu):**

```text
Bottleneck nằm ở việc đọc và nối nhiều nguồn thành một bức tranh "vì sao" — việc
cần hiểu ngôn ngữ, là chỗ AI có thể giúp. Các bước đi thẳng một đường, nguồn do tác
giả cung cấp nên không cần AI tự lập kế hoạch. Workflow giữ được boundary rõ: AI chỉ
tóm tắt có dẫn nguồn, tác giả xác nhận, reviewer vẫn đọc code và quyết định approve.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
PR template (Rule) chỉ đảm bảo tác giả có ghi, nhưng không nối được PR/commit cũ và
thread quyết định, reviewer vẫn phải tự mở từng nguồn. Tuy vậy nhóm chưa có số đo
chứng minh Rule không đủ, nên pilot sẽ so sánh "chỉ template" với "template + AI";
chỉ giữ AI nếu giảm được tổng công sức.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Engineer phụ trách review PR (thường là Technical Leader) trong một repo của team, khi PR chạm vào module họ ít quen thuộc. Tác giả PR là người bị ảnh hưởng thứ cấp vì phải bổ sung context và chờ phản hồi. |
| **Workflow** | Tác giả mở PR → reviewer đọc mô tả PR → tự tìm và nối context từ ticket, code liên quan, PR/commit cũ và thread trao đổi → nếu thiếu thì hỏi tác giả và chờ → review diff/test → comment hoặc approve. |
| **Bottleneck** | Bước tìm và nối context "vì sao" (mục đích, ràng buộc, lý do thiết kế, phạm vi ảnh hưởng) từ nhiều nguồn, cộng vòng hỏi – chờ khi tác giả chưa ghi lại lý do thiết kế. |
| **Impact** | Reviewer mất thời gian trước khi thực sự đánh giá code, feedback cho tác giả bị chậm; nếu context thiếu hoặc hiểu sai, reviewer có thể đánh giá thiếu rủi ro của thay đổi. Mức impact bằng số chưa đo (xem Success Metric). |
| **Success Metric** | **Metric chính:** thời gian reviewer gom và hiểu context 30 → ≤20 phút/PR (tính cả thời gian kiểm chứng tóm tắt AI; tách riêng đọc diff và thời gian chờ). **Metric phụ:** số lượt hỏi bổ sung context 3 → ≤1 lượt/PR; tổng công sức chuẩn bị context của tác giả + reviewer 40 → ≤30 phút/PR (để tránh chỉ chuyển việc sang tác giả); chất lượng: 0 thông tin sai nghiêm trọng trong mẫu thử. Baseline là giả định, sẽ đo trên 10 PR; so sánh trung vị. |
| **Boundary** (làm / không làm) | **Làm:** 1 repo, PR có link ticket; AI tóm tắt theo 5 câu hỏi, mỗi ý có dẫn nguồn, đánh dấu phần thiếu. **Không làm:** AI không review diff, không comment hay approve; không tự tìm nguồn ngoài các link được cung cấp; không tự đoán lý do thiết kế chưa được ghi lại. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Sau khi tác giả điền PR template và gắn link nguồn (bước 1), trước khi reviewer kiểm chứng và review diff/test (bước 4). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow (Rule làm nền): các bước cố định, nguồn do tác giả cung cấp nên không cần AI tự lập kế hoạch tìm kiếm. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: AI tóm tắt sai hoặc bịa lý do thiết kế và reviewer tin theo. Kiểm tra: tác giả xác nhận bản tóm tắt trước khi gửi; reviewer mở nguồn đối chiếu từng ý và ghi lại thông tin sai/thiếu trên mỗi PR. Rủi ro phụ: chuyển việc sang tác giả — kiểm soát bằng metric tổng công sức. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Workflow 5 bước đã mô tả rõ và actor đã được thu hẹp về engineer review PR trong một repo. |
| Baseline + metric đo được chưa? | Not Yet | Metric đã có cách đo, nhưng baseline (30 phút, 3 lượt, 40 phút) đều là giả định, chưa đo trên PR thật. |
| Data/input đủ dùng chưa? | Not Yet | Workflow phụ thuộc vào việc tác giả gắn link ticket và lý do thiết kế; nhóm chưa biết bao nhiêu PR hiện có đủ các link này. |
| AI sai, hậu quả chấp nhận được không? | Yes | AI không approve và không review code; reviewer luôn đối chiếu nguồn, nên sai sót chủ yếu làm tốn thêm thời gian chứ không trực tiếp gây merge sai — với điều kiện reviewer không tin mù. |
| Có người review/owner không? | Yes | Tác giả xác nhận tóm tắt, reviewer kiểm chứng; owner của pilot là Technical Leader của repo thử nghiệm. |
| Có cách non-AI đơn giản hơn không? | Yes | PR template + check tự động (Rule) có thể giải được một phần; chưa thử nên chưa biết đã đủ hay chưa. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Workflow và boundary đã rõ, research cho thấy PR template và GitHub Copilot đã hỗ trợ
từng phần của bài toán, nhưng vẫn còn khoảng trống thật (các tool hiện có review diff
hoặc tóm tắt thay đổi, chưa tóm tắt context "vì sao" có dẫn nguồn). Nhưng pain mới dựa trên ghi
nhận cá nhân, baseline đều là giả định và nhóm chưa phỏng vấn hay quan sát phiên review
nào. Phương án non-AI (PR template) cũng chưa được thử, nên chưa thể chứng minh cần AI.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Áp dụng khi các bước Not Yet bên dưới cho kết quả tốt:
- Data: 1 repo; 10 PR chỉ dùng PR template, sau đó 10 PR dùng template + tóm tắt AI;
  chọn PR tương đương về độ lớn và mức quen thuộc của reviewer.
- Chạy tay: tác giả điền template + gắn link → dùng tool có sẵn (vd PR-Agent /describe
  hoặc prompt cố định) sinh tóm tắt 5 câu hỏi → tác giả xác nhận → reviewer bấm giờ.
- Đo 3 số: (1) thời gian reviewer gom + hiểu context/PR, (2) số lượt hỏi bổ sung/PR,
  (3) số thông tin sai/thiếu trong tóm tắt. Theo dõi thêm tổng công sức tác giả + reviewer.
- So sánh trung vị giữa 2 nhóm PR; ghi riêng các PR bất thường.
```

**Nếu Not Yet — cần validate gì trước:**

```text
1. Quan sát 2-3 phiên review và bấm giờ từng bước để có baseline thật cho bước gom context.
2. Phỏng vấn reviewer + tác giả của 3-5 PR gần đây có trao đổi bổ sung context
   (thiếu thông tin gì, tìm ở đâu, thông tin nào nếu có sẵn sẽ giúp nhanh hơn).
3. Đếm trên các PR đó: bao nhiêu PR có link ticket, bao nhiêu PR có ghi lý do thiết kế.
4. Thử PR template (Rule) trên 10 PR trước khi thêm AI.
```

**Nếu No-Go — làm gì thay AI:**

```text
Nếu validation cho thấy thời gian gom context không đáng kể, hoặc PR template đã đạt
metric: dừng ở Rule — PR template bắt buộc + check tự động link ticket, mục lý do và
mục test; không thêm AI.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng AI và quay về chỉ dùng PR template nếu trong pilot: tổng công sức tác giả + reviewer
không giảm (tính cả công kiểm chứng tóm tắt), hoặc có thông tin sai nghiêm trọng trong
tóm tắt, hoặc số lượt hỏi bổ sung không giảm so với nhóm PR chỉ dùng template.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được) — research đã có link; validation có bằng chứng thứ cấp từ nghiên cứu đã công bố, phỏng vấn/quan sát trên PR của team chưa thực hiện
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback — đã có handoff, bottleneck, boundary, fallback; thời gian từng bước chưa đo
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
