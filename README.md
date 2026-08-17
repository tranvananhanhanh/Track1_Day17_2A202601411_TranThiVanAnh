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
* **File ghi âm phỏng vấn thực tế:** [`08-17-2026 12.23_1.m4a`](https://drive.google.com/file/d/1QZpzXlbHhAAnzkhtb1xay7kIbHgBfguu/view?usp=sharing)

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
  → `Outcome: Giảm thời gian copy-paste thủ công, không bị bỏ lỡ (miss) lời giải thích của giảng viên, tăng khả năng ghi nhớ và ôn tập chuẩn bị cho kỳ thi/dự án.`

### 2.3. Phân tích Actor
* **Người trực tiếp dùng:** Learner (Học viên học trực tuyến trên VLearn).
* **Người trải nghiệm Pain chính:** Learner — người muốn ghi chép để không bỏ lỡ kiến thức nhưng bị mệt mỏi vì phải chia đôi màn hình copy từng đoạn slide và ngập trong đống note lộn xộn.
* **Người thay đổi hành vi:** Learner (chuyển từ việc vừa học vừa copy-paste thủ công sang lưu vết nhanh và để hệ thống tự tạo ghi chú ôn tập).
* **Actor nhóm chọn điều tra trước:** Online Learner (Học viên đang học các khóa học e-learning có slide và bài giảng chuyên sâu).
* **Lý do chọn:** Nhóm học viên này có nhu cầu ôn tập rõ rệt để phục vụ kỳ thi/dự án thực tế và phải tự xoay sở bằng các workaround thủ công (như dùng AI bên ngoài tóm tắt lại note).

### 2.4. Situation & Job (JTBD Hypothesis)
* **Situation:** Khi vừa hoàn thành một bài học trực tuyến có slide và nhiều lời giải thích quan trọng từ giảng viên.
* **Current Behavior:** Chia đôi màn hình, vừa xem bài vừa copy từng đoạn text từ slide dán sang app ngoài và gõ thêm ý giải thích. Khi ôn tập thì dán đống note ngổn ngang vào AI ngoài nhờ tóm tắt.
* **JTBD Hypothesis:**
  > *"Khi học một bài học trực tuyến có nhiều kiến thức phức tạp, tôi muốn dễ dàng lưu lại các điểm cốt lõi và lời giải thích của giảng viên thành một bản tóm tắt có cấu trúc, để tôi có thể ôn tập nhanh trước kỳ thi mà không mất công copy-paste thủ công hay bị ngập trong đống ghi chú lộn xộn."*

### 2.5. Giả thuyết Pain cạnh tranh (Competing Pain Hypotheses)
* **Pain Hypothesis A (Giả thuyết nhóm chọn - Được kiểm chứng bằng phỏng vấn thực tế):**
  > Khi học bài trực tuyến, learner gặp khó khăn trong việc ghi chép và củng cố kiến thức vì phải thao tác thủ công (chia đôi màn hình, copy từng chữ từ slide), dẫn đến tốn quá nhiều sức lực và tạo ra đống note ngổn ngang, khiến họ phải vất vả dùng AI bên ngoài tóm tắt lại mỗi khi cần ôn tập.
* **Pain Hypothesis B (Giả thuyết cạnh tranh):**
  > Khi đang học, learner gặp khó khăn trong việc lọc ra đâu là kiến thức quan trọng cần lưu lại, dẫn đến việc không biết gõ gì vào phần ghi chú.
* **Lý do chọn A:** Bằng chứng từ cuộc phỏng vấn thực tế với `NV-01` xác nhận 100% user biết mình cần lưu gì nhưng **cực kỳ tốn sức ở khâu copy-paste thủ công** và **quá tải khi đọc lại đống note lộn xộn**.

### 2.6. Evidence Map & Bằng chứng thực tế từ phỏng vấn NV-01
| Cần kiểm tra | Evidence làm nhóm tin hơn (Đã xác minh qua NV-01) | Evidence làm nhóm nghi ngờ / bác bỏ |
| :--- | :--- | :--- |
| **Situation có thật** | User vừa học xong bài học có slide và lời giảng từ thầy cô. | Learner không học bài nào có slide hoặc không cần lưu kiến thức. |
| **Pain có ý nghĩa** | User than phiền: *"Tốn sức nhất là em phải copy từng cái này sang cái kia xong rồi ghi chép lại những cái đã có ở trong slide nữa."* | Learner thấy việc chia đôi màn hình gõ lại slide là nhẹ nhàng, không tốn sức. |
| **Workaround tồn tại** | User **chia đôi màn hình**, copy-paste thủ công và **dùng AI bên ngoài để tóm tắt đống note** khi ôn tập. | Không dùng bất kỳ công cụ hay workaround nào. |
| **Consequence tồn tại** | Nếu không ghi chép thì bị **miss (bỏ lỡ)** các lời giải thích chi tiết của giảng viên. | Không ghi chép cũng không ảnh hưởng gì tới việc hiểu bài hay kết quả thi. |

---

## 🎙️ 3. Conversation Guide phiên bản cuối (Sau Chặng 3 & 4)

### 3.1. Tiêu chí tuyển & Recruitment Check
* **Tiêu chí:** Người vừa hoàn thành bài học trực tuyến có nhu cầu ghi chép kiến thức trong vòng 7 ngày gần đây.
* **Recruitment Check Question:** *"Trong 7 ngày qua, bạn có tham gia bài học trực tuyến nào mà bạn có ghi chú lại, highlight hoặc copy nội dung để xem sau không?"*

### 3.2. Lời mở đầu (Neutral Opening)
> *"Chào bạn, mình xin phép được ghi lại cuộc trò chuyện để làm tư liệu học tập. Nhóm mình đang thực hiện một nghiên cứu nhỏ về thói quen ghi chép và cách người học lưu giữ kiến thức khi học trực tuyến. Buổi trò chuyện hoàn toàn mang tính chất học hỏi trải nghiệm thực tế của bạn, không có câu trả lời đúng sai. Rất mong bạn chia sẻ cởi mở về những gì bạn đã thực sự trải qua."*

### 3.3. Story Opener (Neo vào sự kiện gần nhất)
> *"Kể cho mình nghe về lần gần đây nhất (như hôm qua hay hôm nay) bạn hoàn thành một bài học trực tuyến mà bạn cảm thấy có nhiều kiến thức cần lưu lại?"*

### 3.4. Bộ câu hỏi Big 3 & Probe Bank
| Điều cần học | Câu hỏi phỏng vấn chính | Probe Bank (Đào sâu hành vi) |
| :--- | :--- | :--- |
| **1. Hành vi & Workaround khi ghi chép** | Lúc đó bạn dùng công cụ gì để ghi chép lại? Màn hình của bạn sắp xếp ra sao? | • Bạn có phải chia đôi màn hình hay chuyển tab không?<br>• Bạn copy hay gõ lại từ slide? |
| **2. Pain & Chi phí tốn sức nhất** | Trong toàn bộ quá trình đó, phần nào khiến bạn cảm thấy tốn sức và khó chịu nhất? | • Bạn mất bao lâu cho việc copy-paste đó?<br>• Bạn đã thử cách nào khác (như note trên slide) chưa và kết quả thế nào? |
| **3. Cách ôn tập & Hậu quả kéo theo** | Khi cần tìm lại thông tin để ôn thi/làm dự án, bạn xử lý đống ghi chú đó như thế nào? Nếu không ghi chép thì có hậu quả gì? | • Bạn đọc lại từng dòng hay dùng công cụ hỗ trợ (như nhờ AI tóm tắt)?<br>• Nếu không xem lại note thì có bị bỏ lỡ (miss) kiến thức gì của giảng viên không? |

---

## 🧠 4. Practice Reflection (Kết quả Chặng 4 dựa trên cuộc phỏng vấn NV-01)

1. **Câu hỏi giúp user mở được câu chuyện thật thành công nhất:**
   * Câu hỏi: *"Phần nào khiến bạn cảm thấy tốn sức nhất trong quá trình ghi chép bài học đó?"*
   * *Lý do:* Câu hỏi này giúp user thành thật bộc lộ pain point lớn nhất: *"Tốn sức nhất là em phải copy từng cái này sang cái kia xong rồi ghi chép lại những cái đã có ở trong cái slide nữa."*

2. **Điểm cần làm tốt hơn ở lần phỏng vấn thật:**
   * Cần chú ý lắng nghe kỹ hơn khi user đề cập đến các lỗi tính năng hệ thống (ví dụ: feature note trên web bị lỗi config không dùng được) để đào sâu xem user đã tự xoay sở workaround ra sao.

3. **Phát hiện quan trọng nhất từ cuộc phỏng vấn NV-01:**
   * **Bằng chứng đắt giá (Strong Evidence):** User chia sẻ rằng khi ôn tập, user không ngồi đọc hết đống note thủ công mà **chủ động dán đống note đó vào AI bên ngoài nhờ AI tóm tắt lại** (*"Thường là em sẽ nhờ AI để tổng tắt lại luôn chứ không ngồi đọc hết đống nốt mình viết"*). 
   * Điều này chứng minh 100% giả thuyết của Case B (AI Notes tự tổng hợp ghi chú có cấu trúc) giải quyết đúng một JTBD và Pain Point có thật của người học!

---

## 🤖 5. AI Support Log (Nhật ký hỗ trợ từ AI)

* **AI đã hỗ trợ những gì:**
  * Hỗ trợ phân tích và bóc tách dữ liệu từ bản chép ghi âm thực tế (`08-17-2026 12.23_1.m4a`).
  * Trích xuất các exact quote đắt giá từ lời thoại của NV-01 để đưa vào Evidence Map.
  * Chuẩn hóa bộ tài liệu nộp bài đáp ứng đầy đủ 4 Gate đánh giá của VLearn Codelabs.
* **Điểm sai / hời hợt của AI ban đầu:**
  * Ban đầu AI đưa ra kịch bản phỏng vấn giả định với các chi tiết chưa chính xác về hành vi của user (như giả định user dùng Notion/Word).
* **Bạn đã tự điều chỉnh lại thế nào:**
  * Cập nhật toàn bộ dữ liệu bài nộp dựa trên **bản ghi âm thực tế 100% của NV-01**: bổ sung chi tiết user *chia đôi màn hình*, *copy text từ slide*, *tính năng note trên web bị lỗi config* và *thói quen dán note nhờ AI bên ngoài tóm tắt lại khi ôn thi*.
