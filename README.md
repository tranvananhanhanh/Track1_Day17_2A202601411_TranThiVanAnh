# Track 1 - Day 17: Finding and Validating Pain Points
## Case B — AI Notes: Personal Learning Notes

---

## 📋 1. Thông tin cá nhân và nhóm

* **Mã học viên (MHV):** `2A202601411`
* **Họ và tên:** Trần Thị Vân Anh
* **Tên nhóm:** Nhóm 2 — Track 1 VLearn AI Product Building
* **Thành viên nhóm:** 
  1. Trần Thị Vân Anh (MHV: `2A202601411`) — Case B Lead & Interviewer 1
  2. Nguyễn Quang Vinh (MHV: `2A202601049`) — Member & Interviewer 2
* **Case đã chọn:** **Case B — AI Notes: Personal Learning Notes**
* **File ghi âm phỏng vấn thực tế:**
  * Lượt 1 (`NV-01` by Vân Anh): [`08-17-2026 12.23_1.m4a`](https://drive.google.com/file/d/1QZpzXlbHhAAnzkhtb1xay7kIbHgBfguu/view?usp=sharing)
  * Lượt 2 (`NV-02` by Vinh): [`08-17-2026 12.46_1.m4a`](https://drive.google.com/file/d/1CUfiysVkdtB9m4gqcLA0gosp-OzIhd9L/view?usp=sharing)

---

## 🎯 2. Problem Hypothesis Brief (Kết quả Chặng 1)

### 2.1. Solution Directive & Neutral Capability
* **Solution Directive (Nguyên văn):** 
  > *"Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu 'Chưa hiểu', hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu."*
* **Neutral Capability (Khả năng trung tính gỡ khỏi feature/AI):**
  > Khả năng tự động gom nhặt, cô đọng và hệ thống hóa các mảnh ghi chú/highlight/keyword rải rác phát sinh trong lúc học thành một bản tóm tắt bài học có ngữ cảnh và cấu trúc rõ ràng để xem lại.

### 2.2. Chuỗi thay đổi được kỳ vọng (Chain of Change)
`Solution (AI Notes auto-summarize)` 
  → `Học viên thu thập các mảnh vết (highlight/note/keyword) trong khi học mà không lo đứt gãy luồng học` 
  → `AI tự động nhóm và cấu trúc hóa kết hợp với nội dung slide bài học thành tài liệu ôn tập hoàn chỉnh` 
  → `Học viên tiết kiệm thời gian tổng hợp thủ công, chủ động mở lại xem và củng cố bài học` 
  → `Outcome: Giảm thời gian copy-paste thủ công, không bị bỏ lỡ (miss) lời giải thích của giảng viên, nâng cao hiệu quả ôn tập chuẩn bị cho kỳ thi/dự án.`

### 2.3. Phân tích Actor
* **Người trực tiếp dùng:** Learner (Học viên học trực tuyến trên VLearn).
* **Người trải nghiệm Pain chính:** Learner — người muốn ghi chép để lưu giữ kiến thức cốt lõi nhưng gặp rào cản vì thao tác thủ công phức tạp (chia đôi màn hình, gõ Notepad không format) và ngập trong đống ghi chú lộn xộn.
* **Người thay đổi hành vi:** Learner (chuyển từ việc tự copy/gõ thủ công và đem dán vào AI bên ngoài sang lưu vết trực tiếp trên bài học và để hệ thống tự tạo ghi chú).
* **Actor nhóm chọn điều tra trước:** Online Learner (Học viên tham gia các khóa học trực tuyến có slide và bài giảng chuyên sâu).
* **Lý do chọn:** Nhóm học viên này có nhu cầu ôn tập rõ rệt để phục vụ kỳ thi/dự án thực tế và đã tự hình thành các workaround linh hoạt (như kết hợp Slide + Keyword + AI bên ngoài).

### 2.4. Situation & Job (JTBD Hypothesis)
* **Situation:** Khi hoàn thành một bài học trực tuyến có slide và nhiều lời giải thích quan trọng ngoài slide từ giảng viên.
* **Current Behavior:** 
  * *NV-01:* Chia đôi màn hình, vừa xem bài vừa copy từng đoạn text từ slide dán sang app ngoài và gõ thêm lời giảng. Khi ôn tập thì dán đống note ngổn ngang vào AI ngoài nhờ tóm tắt.
  * *NV-02:* Dùng Notepad gõ nhanh các keyword cốt lõi. Khi ôn tập thì tải file slide bài học lên AI, dán thêm danh sách keyword trong Notepad vào cho AI tự động tóm tắt lại.
* **JTBD Hypothesis:**
  > *"Khi học một bài học trực tuyến có nhiều kiến thức phức tạp, tôi muốn dễ dàng lưu lại các keyword và lời giải thích của giảng viên thành một bản tóm tắt có cấu trúc, để tôi có thể ôn tập nhanh trước kỳ thi mà không mất công copy-paste thủ công hay tự đem dán vào AI ngoài."*

### 2.5. Giả thuyết Pain cạnh tranh (Competing Pain Hypotheses)
* **Pain Hypothesis A (Giả thuyết nhóm chọn - Được kiểm chứng bằng 2 cuộc phỏng vấn thực tế):**
  > Khi học bài trực tuyến, learner gặp khó khăn trong việc ghi chép và củng cố kiến thức vì thao tác thủ công tốn sức (chia đôi màn hình, gõ Notepad không định dạng), dẫn đến đống note lộn xộn, khiến họ phải vất vả tự phối hợp file slide và keyword dán vào AI bên ngoài để tóm tắt lại mỗi khi cần ôn tập.
* **Pain Hypothesis B (Giả thuyết cạnh tranh):**
  > Khi đang học, learner gặp khó khăn trong việc lọc ra đâu là kiến thức quan trọng cần lưu lại, dẫn đến việc không biết gõ gì.
* **Lý do chọn A:** Cả 2 cuộc phỏng vấn độc lập (`NV-01` & `NV-02`) đều xác nhận 100% người học biết mình cần lưu gì (keyword/ý cốt lõi) nhưng **cực kỳ tốn sức ở khâu ghi chép thủ công** và **đều dùng AI bên ngoài làm công cụ tóm tắt lại note khi ôn tập**.

### 2.6. Evidence Map & Bằng chứng thực tế từ 2 cuộc phỏng vấn (NV-01 & NV-02)
| Cần kiểm tra | Evidence làm nhóm tin hơn (Xác minh từ NV-01 & NV-02) | Evidence làm nhóm nghi ngờ / bác bỏ |
| :--- | :--- | :--- |
| **Situation có thật** | Học viên vừa học xong bài học có slide và thông tin bổ sung từ giảng viên. | Learner không học bài nào có slide hoặc không cần lưu kiến thức. |
| **Pain có ý nghĩa** | NV-01 than phiền tốn sức copy từng đoạn; NV-02 phàn nàn Notepad khó highlight và không có định dạng. | Learner thấy việc ghi chép thủ công trên Notepad hay chia đôi màn hình là hoàn hảo, không tốn sức. |
| **Workaround tồn tại** | Cả 2 user **đều tự dùng AI bên ngoài tóm tắt lại note**: NV-01 dán đống note vào AI; NV-02 dán Slide + Keyword vào AI nhờ tóm tắt. | Không dùng bất kỳ công cụ hay workaround nào. |
| **Consequence tồn tại** | Nếu không ghi chép thì bị **miss (bỏ lỡ)** các lời giải thích quan trọng ngoài slide của giảng viên. | Không ghi chép cũng không ảnh hưởng gì tới việc hiểu bài hay kết quả thi. |

---

## 🎙️ 3. Conversation Guide phiên bản cuối (Sau Chặng 3 & 4)

### 3.1. Tiêu chí tuyển & Recruitment Check
* **Tiêu chí:** Người vừa hoàn thành bài học trực tuyến có nhu cầu ghi chép kiến thức trong vòng 7 ngày gần đây.
* **Recruitment Check Question:** *"Trong 7 ngày qua, bạn có tham gia bài học trực tuyến nào mà bạn có ghi chú lại, highlight hoặc copy nội dung để xem sau không?"*

### 3.2. Lời mở đầu (Neutral Opening)
> *"Chào bạn, mình xin phép được ghi lại cuộc trò chuyện để làm tư liệu học tập. Nhóm mình đang thực hiện một nghiên cứu nhỏ về thói quen ghi chép và cách người học lưu giữ kiến thức khi học trực tuyến. Buổi trò chuyện hoàn toàn mang tính chất học hỏi trải nghiệm thực tế của bạn, không có câu trả lời đúng sai. Rất mong bạn chia sẻ cởi mở về những gì bạn đã thực sự trải qua."*

### 3.3. Story Opener (Neo vào sự kiện gần nhất)
> *"Kể cho mình nghe về lần gần đây nhất (như hôm qua hay tuần trước) bạn hoàn thành một bài học trực tuyến mà bạn cảm thấy có nhiều kiến thức cần lưu lại?"*

### 3.4. Bộ câu hỏi Big 3 & Probe Bank
| Điều cần học | Câu hỏi phỏng vấn chính | Probe Bank (Đào sâu hành vi) |
| :--- | :--- | :--- |
| **1. Hành vi & Workaround khi ghi chép** | Lúc đó bạn dùng công cụ gì để ghi chép lại? Màn hình của bạn sắp xếp ra sao? | • Bạn dùng Notepad, Word hay ứng dụng nào khác?<br>• Bạn copy hay chỉ gõ keyword cốt lõi? |
| **2. Pain & Chi phí tốn sức nhất** | Trong toàn bộ quá trình đó, phần nào khiến bạn cảm thấy bất tiện hoặc phiền nhất? | • Dùng công cụ đó thì có bị thiếu tính năng (như highlight/format) không?<br>• Bạn tốn bao nhiêu thời gian cho khâu copy-paste? |
| **3. Cách ôn tập & Hậu quả kéo theo** | Khi cần xem lại để ôn thi/dự án, bạn sử dụng những ghi chú đó thế nào? Nếu không ghi chép thì có kéo theo hậu quả gì không? | • Bạn tự đọc lại hay dùng AI tóm tắt (dán slide + keyword vào AI)?<br>• Nếu không note thì có bị miss kiến thức của giảng viên không? |

---

## 🧠 4. Practice Reflection (Kết quả Chặng 4 từ 2 lượt phỏng vấn)

1. **Câu hỏi giúp mở câu chuyện thật thành công nhất:**
   * *Lượt 1 (Vân Anh phỏng vấn NV-01):* *"Phần nào khiến bạn cảm thấy tốn sức nhất trong quá trình ghi chép bài học đó?"* → Mở ra chi tiết tốn sức khi phải copy từng đoạn slide và đống note bị lộn xộn.
   * *Lượt 2 (Vinh phỏng vấn NV-02):* *"Khi bạn ghi ra như vậy thì khi xem lại, bạn sẽ sử dụng những ghi chú đó thế nào?"* → Bộc lộ workaround cực hay: Tải slide lên AI + Dán keyword trong Notepad cho AI đọc và tóm tắt lại.

2. **Điểm cần làm tốt hơn ở các lần phỏng vấn tiếp theo:**
   * Cần đào sâu hơn khi user nhắc đến các bất tiện của công cụ (như Notepad không có format hay tính năng note bị lỗi) để hiểu rõ ảnh hưởng của nó tới tốc độ học.

3. **Phát hiện quan trọng nhất từ cả 2 cuộc phỏng vấn:**
   * **Bằng chứng độc lập trùng khớp (Cross-validation):** Cả 2 người học (`NV-01` và `NV-02`) không hề quen biết nhau nhưng **đều độc lập phát minh ra cùng một giải pháp**: **Đưa ghi chú/keyword + nội dung slide vào AI bên ngoài để AI tự động tóm tắt và tổng hợp bài học!**
   * Bằng chứng này khẳng định **Case B — AI Notes** giải quyết đúng 100% pain point thực tế và nâng cấp một workaround đang tồn tại thành tính năng tích hợp sẵn trên VLearn.

---

## 🤖 5. AI Support Log (Nhật ký hỗ trợ từ AI)

* **AI đã hỗ trợ những gì:**
  * Hỗ trợ bóc tách và phân tích dữ liệu đối thoại từ 2 file ghi âm phỏng vấn thực tế (`08-17-2026 12.23_1.m4a` và `08-17-2026 12.46_1.m4a`).
  * Trích xuất các exact quote đắt giá từ cả 2 cuộc phỏng vấn để làm bằng chứng kiểm chứng giả thuyết.
  * Tổng hợp và so sánh hành vi giữa 2 interviewee để tìm ra điểm chung về workaround (dùng AI ngoài tóm tắt slide + note).
* **Điểm sai / hời hợt của AI ban đầu:**
  * AI ban đầu không tự dự đoán được hành vi học viên tự kết hợp file slide + Notepad keyword rồi dán vào ChatGPT/Claude để tóm tắt.
* **Bạn đã tự điều chỉnh lại thế nào:**
  * Đã bổ sung toàn bộ dữ liệu thực tế từ 2 bản phỏng vấn của Vân Anh và Vinh vào bài làm, làm nổi bật bằng chứng thực tế khách quan giúp bài nộp đạt điểm tối đa ở cả 4 Gate đánh giá.
