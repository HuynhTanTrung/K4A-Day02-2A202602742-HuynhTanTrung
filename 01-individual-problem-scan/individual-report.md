# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Huỳnh Tấn Trung
- Mã học viên: 2A202602742
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): sinh viên năm cuối
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Học tập, làm assignment + project nhóm

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| #   | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                           | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
| --- | ---------------------------------------------------------------------------- | --------------------------------------------------------------- | ------------------ | ------------------------------- |
| 1   | Tốn thời gian                                                                | Không biết bắt đầu từ đâu khi có quá nhiều việc cùng lúc        | Cả team            | 15-20 phút/lần                  |
| 2   | Tốn thời gian                                                                | Tổng hợp bug report từ tester thành báo cáo chất lượng          | Cả team            | 1 giờ/lần                       |
| 3   | Pain từ người khác                                                           | Đợi team member báo cáo report, push code,...                   | Cả team            | 1-2 lần/tuần, 30-60 phút/lần    |
| 4   | Lặp lại                                                                      | Mơ hồ, thiếu thông tin, không đủ chi tiết, phải suy đoán        | Bản thân, team     | Không nắm được vấn đề           |
| 5   | AI có thể tốt hơn                                                            | Tốn thời gian tổng hợp thông tin từ nhiều nguồn để viết báo cáo | Cả team            | 30p-1h/ lần viết báo cáo        |
| 6   |                                                                              |                                                                 |                    |                                 |
| 7   |                                                                              |                                                                 |                    |                                 |
| 8   |                                                                              |                                                                 |                    |                                 |
| 9   |                                                                              |                                                                 |                    |                                 |
| 10  |                                                                              |                                                                 |                    |                                 |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**

- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan)                              | Vì sao chọn (2-3 ý)                                                                        | Điều còn chưa chắc                                       |
| ---- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------------------------------------------------------- |
| 1    | Không biết bắt đầu từ đâu khi có quá nhiều việc cùng lúc | Không những ảnh hưởng đến hiệu suất bản thân mà còn ảnh hưởng đến tiến độ của cả team      | Chưa đo được thời gian "chọn task" vì hay bị ngắt quãng  |
| 2    | Mơ hồ, thiếu thông tin                                   | Thiếu thông tin cần thiết, tốn thêm thời gian để hỏi lại, ảnh hưởng đến hiệu suất làm việc | Chưa chắc phân biệt được "task thiếu info" vs "task khó" |
| 3    | Tốn thời gian tổng hợp thông tin                         | Tốn thời gian liên tục. Có thể dùng AI tóm tắt, tạo workflow                               | Chưa chắc phân đoạn nào tốn thời gian nhất               |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Không biết bắt đầu từ đâu khi có quá nhiều việc cùng lúc

```text
Problem 1 câu:
Khi có nhiều việc cùng lúc, tôi chọn việc dễ trước và trì hoãn việc quan trọng, khiến tiến độ bản thân và team bị chậm

Actor:
Sinh viên năm cuối phải xử lý đồng thời task môn học, dự án và công việc cá nhân nhưng chưa có cách ưu tiên rõ ràng

Thời điểm / bối cảnh:
Vào cuối ngày hoặc trước deadline, khi có nhiều việc cần xử lý cùng lúc nhưng không biết nên bắt đầu từ đâu

Current workflow 3-7 bước:
1. Nhận danh sách việc cần làm từ course, dự án và công việc cá nhân
2. Cân nhắc ưu tiên nhưng không chắc task nào thực sự quan trọng nhất
3. Chọn task dễ làm trước để có cảm giác “đã làm việc”
4. Trì hoãn task khó hoặc cần nhiều suy nghĩ
5. Quay lại sau khi deadline gần, phải rush và làm vội

Bottleneck:
Bước 2: không xác định được task nào nên làm trước và cách bắt đầu task khó, nên tôi chọn việc dễ rồi trì hoãn việc quan trọng

Impact:
Mất khoảng 15-20 phút mỗi lần bắt đầu lại một task,2-3 task/tuần bị chậm, kéo dài tiến độ và làm team phải chờ

Success metric:
Giảm thời gian quyết định task cần bắt đầu từ 15-20 phút xuống dưới 5 phút, giảm số task bị trì hoãn và số lần phải rush trước deadline

Non-AI alternative:
Lập checklist, chia task thành từng bước nhỏ, dùng time-blocking, ưu tiên theo deadline và mức độ quan trọng

AI hypothesis:
AI có thể giúp tách task lớn thành các bước nhỏ, gợi ý thứ tự ưu tiên và đề xuất kế hoạch bắt đầu nhanh hơn khi task mơ hồ

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 20 phút

[1 Xem danh sách việc: 5']
 → [2 Chọn task “dễ” trước: 5']
 → [3 Trì hoãn task khó: 5']
 → [4 Rush cuối ngày: 5']  <-- bottleneck

FUTURE STATE — 8 phút

[1 AI tách task thành bước nhỏ: 2']
→ [2 AI gợi ý ưu tiên: 2']
→ [3 Tôi bắt đầu task khó đúng hướng: 3']
→ [4 Review & hoàn thành: 1']  <-- human boundary

Fallback: Nếu AI gợi ý sai hơn 2 lần/tuần hoặc task có context nhạy cảm, quay về checklist + time-blocking thủ công
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Mơ hồ, thiếu thông tin

```text
Problem 1 câu:
Khi task mơ hồ hoặc thiếu thông tin, tôi phải suy đoán và hỏi lại nhiều lần trước khi làm, khiến tiến độ chậm và dễ phải sửa lại

Actor:
Sinh viên năm cuối nhận task từ giảng viên hoặc team member

Thời điểm / bối cảnh:
Khi nhận task, brief hoặc yêu cầu nhưng thông tin chưa đầy đủ hoặc quá mơ hồ

Current workflow 3-7 bước:
1. Đọc yêu cầu ban đầu
2. Không xác định được thông tin còn thiếu
3. Tìm thêm context trong tài liệu hoặc chat
4. Gửi câu hỏi để làm rõ
5. Chờ phản hồi hoặc tự suy đoán.
6. Bắt đầu làm với nhiều mơ hồ và phải sửa lại

Bottleneck:
Bước 3: không nhận diện được ngay thông tin còn thiếu và câu hỏi cần hỏi, nên phải tìm context rồi hỏi lại nhiều vòng.

Impact:
Mỗi task mất khoảng 10-15 phút để tìm và làm rõ thông tin, thường phải hỏi lại 2-3 lần / task, làm chậm tiến độ và tăng sai sót.

Success metric:
Giảm thời gian làm rõ yêu cầu từ 10-15 phút xuống dưới 5 phút, giảm số lần hỏi lại và số lần sửa do hiểu sai yêu cầu.

Non-AI alternative:
Dùng checklist question template, viết brief rõ ràng hơn, yêu cầu đầu vào chuẩn trước khi làm.

AI hypothesis:
AI có thể tóm tắt task, liệt kê thông tin còn thiếu và gợi ý các câu hỏi cần hỏi để làm rõ yêu cầu trước khi bắt đầu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 15 phút

[1 Đọc task ban đầu: 3']
→ [2 Nhận ra thiếu thông tin: 3']
→ [3 Hỏi lại / tìm context: 5']
→ [4 Bắt đầu làm mơ hồ: 4']  <-- bottleneck

FUTURE STATE — 6 phút

[1 AI tóm tắt task & xác định thông tin thiếu: 2']
→ [2 AI gợi ý câu hỏi cần làm rõ: 2']
→ [3 Tôi hỏi/chốt yêu cầu rõ: 2']  <-- human boundary

Fallback: nếu AI không đủ context, tôi dùng checklist yêu cầu chuẩn và hỏi trực tiếp
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tốn thời gian tổng hợp thông tin

```text
Problem 1 câu:
Khi viết báo cáo, tôi mất 30-60 phút lọc và sắp xếp thông tin từ nhiều nguồn trước khi có bản đủ rõ để gửi

Actor:
Sinh viên năm cuối phải tổng hợp báo cáo, status update hoặc nội dung nhóm từ note, chat, tài liệu và meeting

Thời điểm / bối cảnh:
Mỗi tuần hoặc trước khi gửi báo cáo, cập nhật tiến độ, hoặc tổng hợp tiến độ từ nhiều nguồn như note, chat, tài liệu và meeting

Current workflow 3-7 bước:
1. Thu thập dữ liệu từ nhiều nguồn khác nhau
2. Đọc lại và chọn thông tin quan trọng
3. Gộp thông tin vào một nơi trung tâm
4. Viết lại bằng ngôn ngữ rõ ràng và dễ hiểu
5. Kiểm tra lại để tránh bỏ sót key point
6. Chỉnh sửa định dạng và gửi đi

Bottleneck:
Bước 2: lọc key point và chuyển các thông tin rời rạc thành bản tóm tắt có cấu trúc, rõ ràng và dễ đọc.

Impact:
Mỗi lần tổng hợp báo cáo mất khoảng 45 phút, nếu có nhiều nguồn và nhiều update, tổng thời gian có thể lên tới 1-2 giờ/tuần.

Success metric:
Giảm thời gian tổng hợp báo cáo từ 45 phút xuống dưới 20 phút, giảm thời gian đọc lại và chỉnh sửa cuối cùng mà vẫn đủ các ý chính.

Non-AI alternative:
Sử dụng template báo cáo, bảng tổng hợp dữ liệu và checklist nội dung cần có trước khi viết.

AI hypothesis:
AI có thể tổng hợp dữ liệu từ nhiều nguồn, trích xuất điểm chính và draft báo cáo nhanh, sau đó người dùng chỉnh sửa và loại bỏ sai sót.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 45 phút

[1 Thu thập thông tin từ nhiều nguồn: 10']
→ [2 Đọc lại và lọc ý chính: 15']
→ [3 Viết thành báo cáo: 15']
→ [4 Chỉnh sửa & kiểm tra: 5']  <-- bottleneck

FUTURE STATE — 18 phút

[1 AI gom dữ liệu & tóm tắt key point: 4']
→ [2 AI draft báo cáo theo template: 5']
→ [3 Tôi review & chỉnh sửa: 8']
→ [4 Gửi: 1']  <-- human boundary

Fallback: nếu AI tóm tắt thiếu đúng nuance, tôi giữ lại template và chỉnh sửa thủ công phần chính.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```Card #3 — Tốn thời gian tổng hợp thông tin từ nhiều nguồn để viết báo cáo

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```Workflow 6 bước rõ ràng: thu thập dữ liệu → lọc ý chính → gộp → viết → kiểm tra → gửi
    Bottleneck nằm đúng 1 bước — lọc ý chính (15 phút)
    Baseline đo được: 45 phút/lần, 2 lần/tuần = 1.5 giờ/tuần (đo 3 lần: 50', 40', 45')
    Impact thật: 2-3 task/tuần bị chậm vì mất thời gian tổng hợp thay vì làm việc chính

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```1. Nếu AI tóm tắt sai nuance hoặc bỏ sót key point từ nhiều nguồn, làm sao verify mà không tốn thêm thời gian đọc lại toàn bộ?
    2. Bottleneck "lọc ý chính" — có chắc AI làm tốt hơn người, hay chỉ nhanh hơn nhưng kém chính xác hơn?

```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
