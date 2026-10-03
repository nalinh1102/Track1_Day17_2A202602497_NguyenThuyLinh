# Track 1 - Day 17 - Lab 2

## 1. Thông tin cá nhân và nhóm

- MHV: 2A202602497
- Họ và tên: Nguyễn Thùy Linh
- Tên nhóm: Matcha
- Thành viên:
Trần Thị Thuý - 2A202602960
Lê Thị Duyên - 2A202602411
Nguyễn Thùy Linh - 2A202602497
- Case đã chọn: Case A — AI Tutor: Diagnostic Refresher

---

## 2. Problem Hypothesis Brief

### Solution Directive

Khi học viên bấm “Tôi vẫn chưa hiểu”, hệ thống sử dụng nội dung bài hiện tại, các câu trả lời gần đây và lịch sử học tập để đặt câu hỏi chẩn đoán, xác định một khái niệm nền cần ôn, giải thích ngắn và đưa học viên trở lại bài đang học.

### Capability trung tính

Hỗ trợ người học xác định nguyên nhân khiến họ bị kẹt trong một bài học, cung cấp phần kiến thức cần thiết để họ hiểu lại và tiếp tục bài đang học.

### Expected Change

1. Học viên xác định rõ hơn phần kiến thức khiến họ không theo kịp bài.
2. Học viên giảm việc thử nhiều nguồn hoặc cách xử lý khác nhau một cách ngẫu nhiên.
3. Học viên có thể tiếp tục bài hiện tại với ít gián đoạn hơn.

### Actor được chọn

Học viên.

Học viên là người trực tiếp trải nghiệm tình huống không hiểu bài, thực hiện workaround và chịu hậu quả nếu vấn đề không được giải quyết.

### Situation & Job

Khi đang học một bài và gặp một khái niệm không hiểu, học viên đang cố hiểu đủ nội dung để tiếp tục bài bằng cách đọc lại, tìm tài liệu khác, hỏi AI hoặc hỏi người khác.

### JTBD Hypothesis

Khi bị kẹt ở một khái niệm trong lúc học, tôi muốn nhanh chóng hiểu mình đang thiếu kiến thức gì để có thể tiếp tục bài hiện tại mà không bị gián đoạn quá lâu.

### Pain Hypothesis A

Khi đang học một nội dung khó, học viên gặp khó khăn trong việc tiếp tục bài vì họ không xác định được phần kiến thức nền mình đang thiếu, dẫn đến việc phải thử nhiều nguồn hoặc cách giải thích khác nhau và bị gián đoạn mạch học.

### Pain Hypothesis B

Khi đang học một nội dung khó, học viên gặp khó khăn trong việc tiếp tục bài không phải vì thiếu kiến thức nền, mà vì cách giải thích hiện tại chưa phù hợp với cách họ tiếp thu, dẫn đến việc phải tìm một cách diễn đạt, ví dụ hoặc nguồn học khác.

### Giả thuyết chọn để điều tra trước

Pain Hypothesis A.

Lý do: solution directive hiện tại ngầm giả định vấn đề cốt lõi là thiếu kiến thức nền, nên nhóm cần kiểm tra xem giả định này có thực sự xuất hiện trong các tình huống gần đây hay không.

### Problem Hypothesis

Khi đang học một bài và gặp một khái niệm không hiểu, học viên có thể khó xác định phần kiến thức nền mình đang thiếu. Họ phải thử nhiều cách như đọc lại, tìm nguồn khác hoặc hỏi người khác, dẫn đến gián đoạn mạch học và mất thêm thời gian trước khi có thể tiếp tục bài.

### Điều gì phải đúng để giả thuyết đứng vững

- Học viên thực sự gặp tình huống này gần đây.
- Họ không dễ tự xác định nguyên nhân.
- Họ đã dùng workaround để xử lý.
- Workaround tạo ra chi phí hoặc gián đoạn đáng kể.

### Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết

Nếu phần lớn người học chỉ cần một cách giải thích khác, tự xử lý rất nhanh hoặc không coi việc bị kẹt là vấn đề đáng kể, giả thuyết về thiếu kiến thức nền cần được sửa.

### Evidence Map

| Cần kiểm tra | Evidence làm nhóm tin hơn | Evidence làm nhóm nghi ngờ hoặc bác bỏ |
|---|---|---|
| Situation có thật | User kể được một lần gần đây bị kẹt khi học với trình tự cụ thể | User không nhớ được tình huống cụ thể hoặc tình huống xảy ra rất hiếm |
| Pain có ý nghĩa | User phải dừng bài, đổi nguồn, mất nhiều thời gian hoặc ảnh hưởng tiến độ học | User xử lý rất nhanh và không thấy ảnh hưởng đáng kể |
| Workaround tồn tại | User đọc lại bài, tìm Google, YouTube, hỏi ChatGPT, hỏi bạn hoặc mentor | User gần như không cần dùng cách hỗ trợ nào khác |
| Consequence tồn tại | User mất thời gian, mất mạch học, bỏ qua nội dung hoặc trì hoãn việc học | Tình huống không tạo ra hậu quả đáng kể |
| Pattern có lặp | User kể được nhiều lần tương tự gần đây | Đây chỉ là một trường hợp hiếm hoặc cá biệt |

### Big 3 — Ba điều quan trọng nhất cần học

| Điều cần học | Evidence cần tìm | Điều gì khiến nhóm xem lại giả thuyết? |
|---|---|---|
| 1. Người học có thật sự gặp tình huống bị kẹt trong một bài gần đây không? | Một sự kiện cụ thể trong 7 ngày gần đây | Không có sự kiện cụ thể hoặc tình huống rất hiếm |
| 2. Khi bị kẹt, người học thực sự đã làm gì? | Chuỗi hành động, nguồn, công cụ và workaround đã sử dụng | User xử lý gần như ngay lập tức mà không tốn công |
| 3. Nguyên nhân của việc bị kẹt là gì và hậu quả có đáng kể không? | Nguyên nhân user tự mô tả, thời gian bỏ ra và ảnh hưởng tới việc tiếp tục học | Nguyên nhân chủ yếu chỉ là cách diễn đạt chưa phù hợp hoặc đây chỉ là bất tiện nhỏ |

### Câu hỏi đáng sợ

Điều gì sẽ xảy ra nếu người học thực tế không bị kẹt vì thiếu kiến thức nền, mà chỉ cần một cách giải thích khác phù hợp hơn?

Nếu evidence cho thấy điều này lặp lại ở nhiều interview, nhóm cần xem lại Pain Hypothesis A và có thể chuyển trọng tâm sang Pain Hypothesis B.

## 3. Conversation Guide - Final Version

Sẽ được cập nhật sau khi hoàn thành practice interview.

---

## 4. Practice Reflection

Sẽ được cập nhật sau khi hoàn thành practice interview.

---

## 5. AI Support Log

AI was used to:
- help structure the problem hypothesis and JTBD hypothesis;
- review interview questions for leading language;
- improve wording and organization.

AI was not used to:
- generate interview evidence;
- fabricate participant quotes;
- create fake interview responses;
- infer facts that participants did not state;
- replace the student's own review of the interview recording.
