# 01 — Individual Problem Scan (Nguyễn Thành Đạt)

## Phase 1 — Scan rộng

Mình scan 10 problems từ trải nghiệm thật khi học VinAI Batch 02 và làm research / project nhóm.

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Tốn thời gian | Tóm tắt 1 paper AI 10-20 trang để quyết định có nên đọc kỹ hay không | Mình + nhiều bạn cùng học | Mỗi paper ~30-40 phút skim; có khi đọc xong vẫn không thấy điểm chính |
| 2 | Pain từ người khác | Hỏi lại thread Discord cũ để tìm câu trả lời của trainer | HV VinAI Batch 02 | Search keyword không trúng, mỗi lần ~10-15 phút; có khi trainer phải trả lời lại |
| 3 | Lặp lại | Viết weekly progress gửi mentor mỗi cuối tuần | Mình + HV có mentor | Mỗi tuần 20-30 phút, hay bị "không nhớ tuần này đã làm gì" |
| 4 | Tốn thời gian | Theo dõi 4-6 paper cùng lúc trong Zotero/Drive, không biết đọc cái nào trước | Mình | Bookmark stack ngày càng dài, mỗi lần mở lại mất 10' để nhớ context |
| 5 | Lặp lại | Ghi note tay sau lecture nhưng không revisit, đến lab thì quên | Mình | 70% note tay không được mở lại; phải đọc lại slide gần như từ đầu |
| 6 | Tốn thời gian | Ôn lại lý thuyết toán/ML trước mỗi lab (linear algebra, calculus, prob) | HV trong batch | Mỗi lab mới mất ~45 phút ôn warm-up; hay tra lại cùng concept |
| 7 | AI có thể tốt hơn | Tìm reference / source cho slide present trong nhóm | Mình + nhóm present | 30 phút tìm citation cho 1 claim; nhiều khi không có nguồn primary |
| 8 | AI có thể tốt hơn | Hiểu thuật ngữ AI mới trong paper (acronym, phrase paper-specific) | HV đọc paper | 5-10 phút/lần tra cứu, gây gián đoạn flow đọc |
| 9 | Lặp lại | Phân loại + tag bookmark / paper vào hệ thống personal knowledge | Mình | 15 phút/tuần dọn dẹp; thường skip nên cuối tháng rối |
| 10 | Tốn thời gian | Viết lại note cho rõ ràng sau khi học xong topic (rewrite for retention) | Mình | 30-45 phút/tuần; hay bỏ ngang vì không có template |

Nhận xét:
- Nhiều problem xoay quanh **đọc / tóm tắt / ghi nhớ thông tin từ tài liệu dài**.
- Cũng có một số problem là vấn đề **tra cứu** (#2, #6, #8) — đây là pattern có thể chung với các bạn khác trong nhóm.
- #5 và #10 là vấn đề kỷ luật cá nhân hơn là pain "AI giải được"; mình ghi để tự nhắc, không pitch.

## Phase 2 — Chọn Top 3 + Problem Cards

### Chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tóm tắt paper AI 10-20 trang để quyết định đọc kỹ (#1) | Pain rất rõ với mình, workflow lặp lại 3-5 paper/tuần, AI có lợi thế ngôn ngữ | "Tóm tắt tốt" định nghĩa thế nào? Đo bằng gì? |
| 2 | Hỏi lại thread Discord cũ (#2) | Lặp lại + nhiều bạn khác cùng đau (có thể là pattern chung trong nhóm) | Discord search có index được không, có quyền access không |
| 3 | Viết weekly progress gửi mentor (#3) | Lặp lại đúng tuần, có metric thời gian, có thể dùng AI để draft | Risk AI viết thay → mentor đọc thấy "fake" |

### Problem Card #1 — Tóm tắt paper AI để quyết định đọc kỹ

**Problem 1 câu:**
Mình mất 30-40 phút mỗi paper AI để skim và đánh giá có nên đọc kỹ không, dẫn đến chỉ skim được ~3 paper/tuần trong khi có ~6-8 paper trong stack.

**Actor:**
Học viên VinAI / researcher đang phải triage nhiều paper.

**Thời điểm / bối cảnh:**
Cuối tuần hoặc trước project, khi cần lựa paper để đọc kỹ hỗ trợ literature review hoặc làm lab.

**Current workflow:**

```text
1. Mở từng paper trong Zotero/Drive
2. Đọc abstract + intro
3. Skim figure, conclusion, related work
4. Tự hỏi "paper này có liên quan task mình không?"
5. Ghi note ngắn nếu giữ, đóng tab nếu bỏ
6. Quay lại sau 1 tuần thường quên mình đã đánh giá gì
```

**Bottleneck:**
Bước 3-4 — skim + tự đánh giá relevance. Vì không có template "câu hỏi cần trả lời", mình hay đọc dàn trải, dễ bị paper hay nhưng không liên quan task hiện tại.

**Impact:**
- 30-40 phút/paper × 6-8 paper/tuần = 3-5 giờ/tuần riêng cho triage.
- Nếu bỏ qua paper relevant → mất reference cho project/slide.
- Nếu đọc kỹ paper không liên quan → mất 2-3 giờ vô ích.

**Success metric:**
Giảm thời gian triage 1 paper từ 30-40 phút xuống dưới 10 phút, vẫn giữ recall ≥ 80% so với baseline (đo bằng: với 10 paper test, AI flag bao nhiêu paper mà mình confirm là cần đọc kỹ).

**Non-AI alternative:**
Template "5 câu hỏi cần trả lời" cho mỗi paper (problem, method, result, novelty, applicability) + Pomodoro 15' cho mỗi paper.

**AI hypothesis:**
AI đọc abstract + intro + conclusion → trả lời 5 câu hỏi + đề xuất "đọc kỹ / skim / bỏ". Mình review câu trả lời, không tin tuyệt đối.

**Quick gut:**
Workflow.

#### Draft current workflow (ASCII)

```text
CURRENT STATE — 30-40 phút mỗi paper

[1 Mở paper: 1']
→ [2 Đọc abstract + intro: 8']
→ [3 Skim figure / conclusion: 12']         <-- bottleneck
→ [4 Tự đánh giá relevance: 10']            <-- bottleneck phụ
→ [5 Ghi note ngắn / bỏ: 3']
→ [6 1 tuần sau quên đã đánh giá gì → mở lại]
```

#### Draft future workflow (ASCII)

```text
FUTURE STATE — dưới 10 phút mỗi paper

[1 Mình paste link/PDF + task context: 1']
→ [2 AI đọc abstract+intro+conclusion → trả lời 5 câu hỏi: 1']
→ [3 AI đề xuất "đọc kỹ / skim / bỏ" + lý do: 0']
→ [4 Mình đọc câu trả lời + spot-check 1-2 chỗ: 5']   <-- human boundary
→ [5 Quyết định và ghi note theo template: 3']

Boundary:
- AI KHÔNG đọc thay full paper; chỉ tóm tắt 3 phần (abstract / intro / conclusion).
- AI KHÔNG quyết định cuối; đề xuất chỉ là input.
- Mình phải spot-check ít nhất 1 claim quan trọng.

Fallback:
- AI tóm tắt nhạt → mình tự đọc.
- AI nói "không liên quan" nhưng mình nghi → đọc kỹ.
```

### Problem Card #2 — Hỏi lại thread Discord cũ

**Problem 1 câu:**
Khi cần tra lại câu trả lời / quyết định trainer từng post trong Discord, mình mất 10-15 phút search keyword mà nhiều khi không trúng, phải ping trainer lại.

**Actor:** HV VinAI Batch 02 đang làm lab, cần verify thông tin từ trainer.

**Current workflow:**

```text
1. Search keyword trong Discord
2. Đọc nhiều thread
3. Không chắc → hỏi lại trainer
4. Chờ phản hồi
5. Apply
```

**Bottleneck:** Bước 2-3 — Discord search không hiểu ngữ nghĩa, hay miss khi diễn đạt khác.

**Impact:** 10-15 phút/lần × 2-3 lần/tuần. Trainer bị ping câu trùng.

**Success metric:** Thời gian < 5 phút; ping trainer trùng giảm 50%.

**Non-AI alternative:** Pin thông báo + FAQ file.

**AI hypothesis:** Tool retrieve top-K message + tóm tắt + cite link. HV verify.

**Quick gut:** Workflow.

### Problem Card #3 — Weekly progress gửi mentor

**Problem 1 câu:**
Mỗi cuối tuần mình mất 20-30 phút viết weekly progress vì không nhớ tuần đã làm gì, dễ viết chung chung.

**Actor:** Mình (HV có mentor).

**Current workflow:**

```text
1. Mở Slack/Discord/Notion xem lại
2. Cố nhớ task tuần
3. Viết theo template
4. Self-review
5. Gửi mentor
```

**Bottleneck:** Bước 1-2 — nhớ + tổng hợp từ nhiều nguồn.

**Impact:** 20-30 phút/tuần. Mentor đọc thấy mơ hồ → ít insight cho 1:1.

**Success metric:** Thời gian < 15 phút; mentor không hỏi lại "tuần này cụ thể làm gì" trong 4 tuần liên tiếp.

**Non-AI alternative:** Ghi note hằng ngày 1-2 dòng + template progress cố định.

**AI hypothesis:** AI nhận note ngày + commit log + lab progress → draft progress note. Mình edit.

**Quick gut:** Workflow (có thể bắt đầu bằng process fix nếu kỷ luật ghi note tốt).

## Card mình muốn pitch nhất

**Card #1 — Tóm tắt paper AI để quyết định đọc kỹ.**

**Vì sao:**
- Mình tốn nhiều thời gian nhất ở đây (3-5 giờ/tuần riêng triage).
- AI có lợi thế rõ về ngôn ngữ.
- Có thể đo metric thời gian + recall.
- Workflow rõ, có thể vẽ before/after.

**Câu hỏi mình muốn nhóm challenge:**
- "Tóm tắt tốt" đo bằng cách nào? Có risk AI bias theo kiểu trả lời không?
- Pain này có phải pain rộng hay chỉ mình bị (mình đọc nhiều hơn các bạn khác)?
- Nếu Bá Đạt và Bách không bị pain này nặng, nhóm có nên chọn không?

## Self-check Phase 1+2

- [x] Có 10 problems (vượt mức 5).
- [x] Top 3 có Problem Card đầy đủ field.
- [x] Card #1 có draft current + future workflow.
- [x] Không bắt đầu bằng "xây chatbot" / "xây agent".
- [x] Đã ghi rõ điều còn chưa chắc cho mỗi top problem.
