# 03 — Individual Reflection (Nguyễn Thành Đạt)

> Reflection được mình tự viết. AI chỉ dùng để gợi câu hỏi tự soi.

## Phase 7.1 — Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ thói quen đọc paper + viết progress | Đóng góp 3 candidate paper/Discord/progress; cluster paper-summary và "tra cứu thông tin" cùng vào shortlist |
| Pitch Problem Card | Pitch Card #1 — Tóm tắt paper AI | Card vào shortlist nhưng không được chọn cuối vì metric "tóm tắt tốt" khó định nghĩa trong 4 tiếng |
| Challenge bài của bạn khác | Hỏi Bá Đạt: "Success metric 'thời gian giảm 50%' đo bằng cách nào? 50% của bao nhiêu?" Hỏi Bách: "Nếu tìm code mẫu mở rộng tới repo + Stack Overflow, có làm hết trong 4 tiếng không?" | Bá Đạt đổi metric thành "median < 5 phút"; Bách thu hẹp lại candidate Discord |
| Gom trùng / cluster | Đề xuất cluster B "tổng hợp / tóm tắt nhiều nguồn" gộp paper (#4 của mình) + ôn lab (#2 của Bá Đạt) | Nhóm có 3 cluster rõ |
| Chọn candidate problem | Tham gia chấm điểm; mình chấm cluster A cao nhất sau khi thấy 3/3 thành viên đều có evidence | Đồng thuận chọn cluster A |
| Validation / research | Đề xuất quan sát Discord 1 tuần để có dấu hiệu thật + tìm nguồn Slack AI làm pattern tham khảo | Có insight "đính chính trainer" → chỉnh PS |
| Workflow nhóm | Review workflow Bá Đạt vẽ; đề xuất thêm fallback "tool die → quay về current" | Workflow future có fallback rõ |
| Problem Statement | Đề xuất tách metric thành 3 dòng cụ thể thay vì 1 dòng chung | PS v1 có metric đo được |
| Rule / Workflow / Agent | Đồng ý với phân tích chọn Workflow; ép nhóm trả lời "Rule giải bao nhiêu %?" | Cả nhóm tự kiểm xem Rule có đủ không |
| Decision | Đề xuất thêm "trainer review 10 câu/tuần" làm điều kiện Go | Pilot có người chấm chất lượng AI |

## Phase 7.2 — Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi Claude "problem hay gặp khi đọc nhiều paper AI" | Nhắc mình về pain "phân loại bookmark" mà mình chưa nghĩ tới | Gợi ý "AI agent tự đọc toàn bộ paper rồi report" — phi thực tế trong scope HV | Bỏ ý "AI agent full paper"; giữ scope "tóm tắt 3 phần + đề xuất" |
| Problem Card | Hỏi Claude phản biện Card #1 paper-summary | Chỉ ra metric "recall ≥ 80%" cần định nghĩa cách đo (10 paper test) | Đề xuất thêm "AI tự rate quality of paper" — không khả thi, dễ bias | Giữ đề xuất "đọc / skim / bỏ" thôi, không rate |
| Workflow | Dùng Mermaid để vẽ workflow paper-summary cá nhân | Syntax check | — | Tự vẽ |
| Research | Hỏi Claude "có tool nào tóm tắt paper AI có cite không" | Gợi ý Elicit, SciSpace | Có ý "nhiều paper đã có summary trong abstract rồi, không cần AI" — chưa hiểu pain là triage chứ không phải summary | Giữ vì pain là triage relevance, không phải summary nội dung |
| Problem Statement (nhóm) | Hỏi Claude check 6 field PS v0 nhóm | Phát hiện metric cần đo bằng log thật, không chỉ self-report | Đề xuất thêm field "AI confidence threshold" — đúng nhưng quá technical cho PS giai đoạn này | Ghi vào Boundary thay vì thêm field mới |
| Rule / Workflow / Agent | Không dùng AI trong phase này | — | — | Tự lập luận |
| Decision | Không dùng AI | — | — | Nhóm tự chốt |
| Reflection (phần này) | Chỉ dùng AI để gợi câu hỏi tự soi | Gợi câu "lần nào tôi đã thay đổi ý kiến sau khi bị challenge" | — | Viết tay phần trả lời |

## Phase 7.3 — Reflection câu hỏi mở

**Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Mình hay nghĩ pain của mình là pain chung. Khi Bá Đạt nói về "trainer đính chính" mình mới nhận ra mình cũng từng miss vài lần đính chính nhưng không gọi tên được pattern. Lúc Bách nói về "tìm code mẫu cũ" mình thấy cả 3 đứa đều có cùng meta-pattern "thông tin có sẵn nhưng khó tìm lại" — chỉ là kênh khác nhau (Discord, repo, Stack Overflow). Đây là insight mà 1 mình mình scan không thấy được.

**Nhóm có lúc nào bị solution-first không?**

Có. Lúc đầu mình tự pitch "build tool tóm tắt paper với GPT-4" — đó là solution-first. Bá Đạt hỏi: "Tóm tắt cho ai? Để làm gì? Mỗi tuần bao nhiêu paper?" Mình mới nhận ra bản thân chưa nói rõ actor và workflow. Sau đó pitch lại bằng workflow triage paper, không phải "build tool".

Bách cũng có pha solution-first khi đề xuất Agent vì "demo đẹp". Mình challenge: "Agent ở đây tự quyết bước nào? Có nhiều bước phụ thuộc nhau không?" — sau đó nhóm thấy không có nhánh nên đồng ý Workflow.

**Tôi có thay đổi ý kiến sau khi bị challenge không?**

Có 2 lần.
- Lần 1: ban đầu mình giữ quan điểm cluster B (paper summary) đáng chọn nhất vì AI có lợi thế ngôn ngữ. Sau khi nhóm so sánh evidence: cluster A có 4/9 candidates và 3/3 thành viên cùng đau, cluster B chỉ 2/9 → mình đồng ý cluster A có cross-team pain mạnh hơn.
- Lần 2: ban đầu mình nghĩ pilot nên test với 15-20 HV để có data tốt. Bá Đạt nhắc "scope nhỏ để fail nhanh" → mình đồng ý 5-7 người là đủ cho 2 tuần đầu.

**Tôi đóng góp gì thật sự vào artifact cuối?**

- Giúp tách metric thành 3 dòng cụ thể (thời gian + ping trùng + 0 case submit nhầm).
- Đề xuất research Slack AI làm pattern tham khảo cho "AI summary + cite source".
- Đề xuất thêm "trainer review 10 câu/tuần" — biến pilot thành đo được, không chỉ chạy.
- Ép nhóm trả lời "Rule giải bao nhiêu %" trước khi chọn Workflow → tránh chọn Workflow theo cảm tính.

**Điều khó nhất khi viết Problem Statement là gì?**

Phần Boundary. Mình quen viết PS kiểu "AI sẽ làm tốt việc X" nhưng worksheet (và lab này) bắt buộc nói rõ "AI KHÔNG làm gì". Mình mất 10-15 phút mới viết ra được 4 dòng boundary cụ thể: không tự trả lời, không truy cập DM, phải cite link, fallback khi confidence thấp. Đây là phần dễ thiếu nhưng quan trọng nhất để tool không trượt sang chatbot tự ý.

**Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?**

Mình sẽ ép nhóm validate metric thật sớm hơn. Hiện baseline "15-25 phút" chỉ là self-report; nếu có log Discord thật của bản thân 1 tuần thì decision sẽ vững hơn. Mình cũng sẽ challenge mạnh hơn ở câu hỏi "AI có hallucinate khi trainer chưa từng trả lời câu đó không?" — boundary "không tự trả lời câu hỏi mới" cần kiểm thử bằng prompt cụ thể, không chỉ ghi trong PS.

## Phase 7.4 — Tự kiểm cuối bài

- [x] [12đ cá nhân] Có 10 problems và top 3 Problem Cards.
- [x] [12đ cá nhân] Đã pitch card paper-summary và challenge bạn đúng trọng tâm (hỏi metric Bá Đạt, hỏi scope Bách).
- [x] Nhóm có nhật ký hội tụ từ 9 candidates về 1 bài.
- [x] [15đ nhóm] Nhóm có workflow trước/sau (ASCII inline + 2 file Mermaid).
- [x] [20đ nhóm] Problem Statement v0/v1 với metric + boundary cụ thể.
- [x] [15đ nhóm] So sánh Rule / Workflow / Agent.
- [x] [10đ nhóm] Decision Go với pilot nhỏ.
- [x] [10đ cá nhân] Reflection nói rõ vai trò, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [x] [6đ cá nhân] Mạch problem → workflow → metric → boundary → R/W/A đã thông.

## Một câu chốt cho bản thân

> Mình hay rơi vào "AI có lợi thế ngôn ngữ → chọn problem ngôn ngữ" mà quên hỏi: pain đó có evidence rộng không, có đo được không. Lần sau, mình sẽ bắt đầu bằng "ai cùng đau với mình?" trước khi pitch.
