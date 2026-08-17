# Track 1 - Day 17: Finding and Validating Pain Points
## Case B — AI Notes: Personal Learning Notes

---

## 📋 1. Thông tin cá nhân và nhóm

* **Mã học viên (MHV):** `2A202601411`
* **Họ và tên:** Trần Thị Vân Anh
* **Tên nhóm:** Nhóm 2 — Track 1 VLearn AI Product Building
* **Thành viên nhóm:** 
  1. Trần Thị Vân Anh (MHV: 2A202601411) — Case B Lead & Interviewer
  2. Nguyễn Quang Vinh (MHV: 2A202601049) — Member
* **Case đã chọn:** **Case B — AI Notes: Personal Learning Notes**

---

## 🎯 2. Problem Hypothesis Brief (Kết quả Chặng 1)

### 2.1. Solution Directive & Neutral Capability
* **Solution Directive (Nguyên văn):** 
  > *"Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu 'Chưa hiểu', hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu."*
* **Neutral Capability (Khả năng trung tính gỡ khỏi feature/AI):**
  > Khả năng tự động gom nhặt, cô đọng và hệ thống hóa các mảnh ghi chú/highlight rải rác phát sinh trong lúc học thành một bản tóm tắt bài học có ngữ cảnh và cấu trúc rõ ràng để xem lại.

### 2.2. Chuỗi thay đổi được kỳ vọng (Chain of Change)
`Solution (AI Notes auto-summarize)` 
  → `Học viên thu thập các mảnh vết (highlight/note) trong khi học mà không lo đứt gãy luồng học` 
  → `AI tự động nhóm và cấu trúc hóa thành tài liệu ôn tập hoàn chỉnh` 
  → `Học viên tiết kiệm thời gian tổng hợp thủ công, chủ động mở lại xem và củng cố bài học` 
  → `Outcome: Tăng tỷ lệ ghi nhớ dài hạn, giảm thời gian xem lại video/slide, nâng cao tỷ lệ hoàn thành và áp dụng kiến thức vào thực tế.`

### 2.3. Phân tích Actor
* **Người trực tiếp dùng:** Learner (Học viên vừa học vừa làm / Working Professionals trên VLearn).
* **Người trải nghiệm Pain chính:** Learner bận rộn – người muốn lưu trữ kiến thức để dùng sau nhưng không có đủ thời gian ngồi xếp lại các mảnh note lộn xộn.
* **Người thay đổi hành vi:** Learner (chuyển từ việc vừa học vừa chép thủ công sang đánh dấu nhanh và ôn tập bài có cấu trúc).
* **Actor nhóm chọn điều tra trước:** Working Professional (Learner học các khóa e-learning nâng cao kỹ năng nghề nghiệp).
* **Lý do chọn:** Đối tượng này có áp lực thời gian cao nhất, nhu cầu áp dụng kiến thức vào công việc ngay lập tức, và chi phí cơ hội của việc ngồi xếp lại ghi chú là lớn nhất.

### 2.4. Situation & Job (JTBD Hypothesis)
* **Situation:** Khi vừa hoàn thành một bài học trực tuyến dài hoặc chứa nhiều kiến thức mới/phức tạp trên VLearn.
* **Current Behavior:** Vừa xem video vừa gõ note sang phần mềm ngoài (Notion/Word), chụp màn hình slide hoặc highlight văn bản dở dang.
* **JTBD Hypothesis:**
  > *"Khi hoàn thành một bài học trực tuyến có nhiều thông tin mới, tôi muốn nhanh chóng tổng hợp các điểm cốt lõi và ghi chú dở dang thành một tài liệu ôn tập có hệ thống, để tôi có thể xem lại dễ dàng và áp dụng vào công việc mà không mất thời gian xem lại video hay tự gõ lại từ đầu."*

### 2.5. Giả thuyết Pain cạnh tranh (Competing Pain Hypotheses)
* **Pain Hypothesis A (Giả thuyết nhóm chọn):**
  > Khi kết thúc bài học, learner gặp khó khăn trong việc củng cố kiến thức vì các vết ghi chú/highlight nằm rải rác và dở dang, dẫn đến tốn quá nhiều thời gian/công sức tổng hợp thủ công, khiến họ nản lòng và bỏ qua khâu xem lại bài.
* **Pain Hypothesis B (Giả thuyết cạnh tranh):**
  > Khi đang học, learner gặp khó khăn trong việc lọc ra đâu là kiến thức quan trọng cần lưu lại, dẫn đến việc note quá nhiều hoặc quá lộn xộn, khiến bản ghi chú trở nên vô giá trị khi cần xem lại.
* **Lý do chọn A:** Qua quan sát ban đầu, learner bận rộn không thiếu khả năng nhận biết thông tin hay, nhưng họ gặp rào cản lớn nhất ở **"chi phí chuyển đổi" (consolidation cost)** sau khi buổi học kết thúc.

### 2.6. Evidence Map & Boundary Conditions
| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ / bác bỏ |
| :--- | :--- | :--- |
| **Situation có thật** | Learner kể tên được bài học gần nhất trong 7 ngày có highlight/note. | Learner không hề lưu hay highlight bất kỳ nội dung nào khi học. |
| **Pain có ý nghĩa** | Learner than phiền tốn >30p xếp note hoặc bỏ rơi file note không bao giờ mở lại. | Learner thấy việc vừa học vừa chép tay/Notion là trải nghiệm thư giãn, không tốn sức. |
| **Workaround tồn tại** | Đang dùng Notion, Google Docs, chụp ảnh màn hình, lưu file Word tạm. | Không dùng bất kỳ workaround nào vì học xong là nhớ ngay. |
| **Consequence tồn tại** | Quên kiến thức khi làm dự án, tốn 2x thời gian tua lại video để tìm lại thông tin. | Không chịu hậu quả gì tiêu cực dù không xem lại ghi chú. |

* **Điều phải đúng để giả thuyết đứng vững:** Learner thực sự có nhu cầu xem lại kiến thức sau bài học và hiện đang tốn đáng kể công sức cho các workaround thủ công.
* **Điều làm bác bỏ giả thuyết:** Learner học xong không bao giờ có nhu cầu xem lại ghi chú (chỉ học 1 lần cho biết), hoặc đã rất hài lòng với hệ thống ghi chép Notion hiện tại mà không tốn công sức đáng kể.

### 2.7. Solution Parking Lot
1. **AI Auto-Structured Notes** (Directive của Case B).
2. **[Non-AI] Markdown & PDF One-Click Exporter:** Tự động gom toàn bộ text highlight & screenshot kèm timestamp thành file Markdown/PDF tải về ngay khi kết thúc bài.
3. **[Non-AI] Dual-Column Notes Sidebar:** Giao diện ghi chú 2 cột cố định bên cạnh bài học ("Kiến thức cốt lõi" và "Thắc mắc cần làm rõ").
4. **AI Smart Tagging & Knowledge Map:** AI tự động gắn thẻ chủ đề cho các ghi chú ngắn và liên kết với sơ đồ tư duy của toàn bộ khóa học.
5. **[Non-AI] Peer Note Sharing Hub:** Cho phép học viên tham khảo và fork bộ ghi chú đạt vote cao nhất từ các học viên khác trong cùng bài học.

---

## 🎙️ 3. Conversation Guide phiên bản cuối (Sau Chặng 3 & 4)

### 3.1. Tiêu chí tuyển & Recruitment Check
* **Tiêu chí:** Người đã tham gia bài học trực tuyến và có hoạt động ghi chép, highlight hoặc lưu tài liệu trong vòng 7 ngày gần đây.
* **Recruitment Check Question:** *"Trong 7 ngày qua, bạn có học bài học trực tuyến nào mà bạn có ghi chú lại, highlight hoặc chụp màn hình để xem sau không?"*

### 3.2. Lời mở đầu (Neutral Opening)
> *"Chào bạn, mình đang thực hiện một nghiên cứu nhỏ về thói quen ghi chép và cách mọi người hệ thống kiến thức khi học trực tuyến. Buổi trò chuyện hôm nay hoàn toàn nhằm mục đích học hỏi trải nghiệm thực tế của bạn, không có câu trả lời đúng sai và không nhằm đánh giá hay giới thiệu bất kỳ sản phẩm nào. Rất mong bạn chia sẻ cởi mở về những việc bạn đã thực sự làm."*

### 3.3. Story Opener (Neo vào sự kiện gần nhất)
> *"Kể cho mình nghe về lần gần đây nhất (trong 7 ngày qua) bạn hoàn thành một bài học trực tuyến mà bạn cảm thấy có nhiều kiến thức cần lưu lại?"*

### 3.4. Bộ câu hỏi Big 3 & Probe Bank
| Điều cần học | Câu hỏi phỏng vấn chính | Probe Bank (Đào sâu hành vi) |
| :--- | :--- | :--- |
| **1. Hành vi & Workaround khi ghi chép** | Trong buổi học đó, khi thấy một thông tin quan trọng hoặc chỗ chưa hiểu, bạn đã lưu nó lại bằng cách nào? | • Lúc đó bạn dùng công cụ gì?<br>• Màn hình của bạn lúc đó sắp xếp ra sao?<br>• Bạn có dừng video lại để gõ không? |
| **2. Pain & Chi phí tổng hợp sau bài học** | Sau khi bấm hoàn thành bài học, bạn đã làm gì với những phần ghi chép/highlight đó? | • Bạn mất khoảng bao nhiêu thời gian cho khâu đó?<br>• Phần nào khiến bạn thấy tốn sức hoặc khó chịu nhất?<br>• Bạn đã thử cách nào khác để sắp xếp chưa? |
| **3. Falsification Check (Mức độ thực tế của Pain)** | Lần gần nhất bạn thực sự mở lại bộ ghi chú đó để ôn tập hoặc áp dụng vào công việc là khi nào? | • Chuyện gì xảy ra khi bạn tìm lại thông tin?<br>• Nếu không xem lại bộ note đó thì có kéo theo hậu quả gì không? |

### 3.5. Kịch bản phản xạ khi Data bị lệch (Handling Data Drift)
1. **Nếu user khen ("Tính năng này hay quá / Mình rất thích..."):**
   * *Phản xạ (Deflect):* *"Cảm ơn bạn! Để mình hiểu rõ hơn, trong bài học vừa qua, lúc bạn gõ note trên Notion thì đoạn nào làm bạn mất thời gian nhất?"*
2. **Nếu user nói chung chung / hứa hẹn tương lai ("Sau này mình sẽ xem lại..."):**
   * *Phản xạ (Anchor):* *"Lần gần nhất trước đây bạn thực sự mở lại một file note để làm bài tập/dự án là khi nào? Lúc đó chuyện gì đã diễn ra?"*
3. **Nếu user đề xuất feature ("App nên làm nút tự tóm tắt..."):**
   * *Phản xạ (Dig):* *"Ý tưởng đó thú vị đấy! Điều đó sẽ giúp bạn tiết kiệm bước nào mà hiện tại bạn đang phải làm thủ công?"*

---

## 🧠 4. Practice Reflection (Kết quả Chặng 4)

1. **Câu hỏi giúp user mở được câu chuyện thật thành công nhất:**
   * Câu hỏi: *"Sau khi bấm hoàn thành bài học tối hôm đó, bạn đã làm gì tiếp theo với các bức ảnh màn hình và dòng note dở dang?"*
   * *Lý do:* Câu hỏi này ép user nhớ lại hành vi thực tế ngay lập tức sau buổi học, giúp làm lộ ra việc user phải mất 35 phút ngồi lọc lại ảnh trong Notion và cảm giác mệt mỏi khi phải tổng hợp thủ công.

2. **Điểm cần làm tốt hơn ở lần phỏng vấn thật:**
   * Cần kiềm chế bản năng giải thích hoặc gợi ý giải pháp khi nghe user phàn nàn về việc Notion bị lộn xộn.
   * Cần lắng nghe kiên nhẫn hơn, dành thêm khoảng nghỉ 3 giây sau khi user trả lời để user tự khai thác thêm chi tiết về hậu quả công việc.

3. **Thay đổi cụ thể trong Conversation Guide sau khi luyện tập & Lý do:**
   * *Thay đổi:* Bổ sung câu hỏi Falsification Check ở Big 3: *"Lần gần nhất bạn mở lại file note để áp dụng là khi nào?"*.
   * *Lý do:* Trong lúc luyện tập, user ban đầu khẳng định "xếp note rất quan trọng", nhưng khi đào sâu thì phát hiện 50% số note lưu xong không bao giờ được mở lại. Câu hỏi mới giúp phân loại chính xác giữa **Pain thực tế có hậu quả** và **Mong muốn suông trong suy nghĩ**.

---

## 🤖 5. AI Support Log (Nhật ký hỗ trợ từ AI)

* **AI đã hỗ trợ những gì:**
  * Hỗ trợ giải nén Solution Directive của Case B thành Neutral Capability không dính tên tính năng AI.
  * Gợi ý cấu trúc chuỗi thay đổi (Chain of Change) và khung phân tích Actor.
  * Hỗ trợ rà soát các câu hỏi phỏng vấn để loại bỏ từ ngữ dẫn dắt và đưa về dạng câu hỏi hỏi về quá khứ (Past Behavior).
* **Điểm sai / hời hợt của AI ban đầu:**
  * Ban đầu, AI gợi ý câu hỏi phỏng vấn dính tên solution: *"Bạn thấy tính năng AI Notes tự động gom highlight có hữu ích không?"* (Vi phạm nghiêm trọng quy tắc phỏng vấn kiểm chứng pain).
  * AI ban đầu đưa ra Pain Hypothesis quá chung chung: *"Học viên không thích ghi chép thủ công"* (Đây là sự vắng mặt của feature chứ chưa phải pain có hậu quả).
* **Bạn đã tự điều chỉnh lại thế nào:**
  * Đã bác bỏ câu hỏi gợi ý ban đầu của AI, chuyển thành câu hỏi trung tính neo vào hành vi trong 7 ngày qua: *"Trong bài học gần nhất, bạn đã lưu lại kiến thức bằng cách nào?"*.
  * Điều chỉnh lại Pain Hypothesis A tập trung vào **"Chi phí chuyển đổi" (Consolidation Friction)** và **hậu quả đứt gãy luồng học / bỏ qua ôn tập**, biến nó thành giả thuyết sắc bén và kiểm chứng được bằng dữ liệu hành vi thực tế.
