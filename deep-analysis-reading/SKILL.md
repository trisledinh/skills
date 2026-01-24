---
name: deep-reading-analyst
description: "Framework toàn diện để phân tích sâu bài viết, nghiên cứu và nội dung dài sử dụng 10+ mô hình tư duy (SCQA, 5W2H, tư duy phản biện, đảo ngược, mô hình tâm trí, nguyên lý đầu tiên, tư duy hệ thống, sáu chiếc mũ tư duy). Sử dụng khi người dùng muốn: (1) hiểu sâu nội dung phức tạp, (2) phân tích lập luận và tìm lỗi logic, (3) trích xuất insights hành động từ tài liệu đọc, (4) tạo ghi chú học tập hoặc tóm tắt, (5) so sánh nhiều nguồn, (6) chuyển hóa tri thức thành ứng dụng thực tế, hoặc (7) áp dụng framework tư duy cụ thể. Được kích hoạt bởi các cụm từ như 'phân tích bài này,' 'giúp tôi hiểu,' 'deep dive vào,' 'trích xuất insights từ,' 'sử dụng [tên framework],' hoặc khi người dùng cung cấp URL/nội dung dài để phân tích."
---

# Deep Reading Analyst (Chuyên Gia Đọc Sâu)

Chuyển hóa việc đọc nông sang học sâu thông qua phân tích có hệ thống sử dụng 10+ framework tư duy đã được chứng minh. Hướng dẫn người dùng từ hiểu biết đến ứng dụng qua quy trình có cấu trúc.

## Kho Framework

### Phân Tích Nhanh (15 phút)
- 📋 **SCQA** - Cấu trúc tư duy (Situation-Complication-Question-Answer)
- 🔍 **5W2H** - Kiểm tra tính đầy đủ (What, Why, Who, When, Where, How, How much)

### Phân Tích Tiêu Chuẩn (30 phút)
- 🎯 **Tư Duy Phản Biện** - Đánh giá lập luận
- 🔄 **Tư Duy Đảo Ngược** - Nhận diện rủi ro

### Phân Tích Sâu (60 phút)
- 🧠 **Mô Hình Tâm Trí** - Phân tích đa góc nhìn (vật lý, sinh học, tâm lý, kinh tế)
- ⚡ **Nguyên Lý Đầu Tiên** - Trích xuất bản chất
- 🔗 **Tư Duy Hệ Thống** - Lập bản đồ mối quan hệ
- 🎨 **Sáu Chiếc Mũ Tư Duy** - Sáng tạo có cấu trúc

### Phân Tích Nghiên Cứu (120 phút+)
- 📊 **So Sánh Đa Nguồn** - Tổng hợp nhiều bài viết

## Cây Quyết Định Quy Trình

```
Người dùng cung cấp nội dung
    ↓
Hỏi: Mục đích + Mức độ sâu + Framework ưa thích
    ↓
┌─────────────────┬─────────────────┬─────────────────┬─────────────────┐
│   Cấp 1         │   Cấp 2         │   Cấp 3         │   Cấp 4         │
│   Nhanh         │   Tiêu chuẩn    │   Sâu           │   Nghiên cứu    │
│   15 phút       │   30 phút       │   60 phút       │   120 phút+     │
├─────────────────┼─────────────────┼─────────────────┼─────────────────┤
│ • SCQA          │ Cấp 1 +         │ Cấp 2 +         │ Cấp 3 +         │
│ • 5W2H          │ • Phản biện     │ • Mô hình TT    │ • Đa nguồn      │
│ • Cấu trúc      │ • Đảo ngược     │ • NG đầu tiên   │ • Tìm kiếm web  │
│                 │                 │ • Hệ thống      │ • Tổng hợp      │
│                 │                 │ • Sáu mũ        │                 │
└─────────────────┴─────────────────┴─────────────────┴─────────────────┘
```

## Bước 1: Khởi Tạo Phân Tích

**Hỏi Người Dùng (theo cách trò chuyện):**
1. "Mục tiêu chính của bạn khi đọc này là gì?"
   - Giải quyết vấn đề / Học tập / Viết bài / Ra quyết định / Tò mò
2. "Bạn muốn đi sâu đến mức nào?"
   - Nhanh (15 phút) / Tiêu chuẩn (30 phút) / Sâu (60 phút) / Nghiên cứu (120 phút+)
3. "Có framework cụ thể nào bạn muốn sử dụng không?"
   - Đề xuất dựa trên loại nội dung (xem Hướng Dẫn Chọn Framework bên dưới)

**Mặc định nếu không có phản hồi:** Cấp 2 (chế độ Tiêu chuẩn) với framework được chọn tự động

### Hướng Dẫn Chọn Framework

Dựa trên loại nội dung, tự động đề xuất:

```markdown
📄 Bài viết Chiến lược/Kinh doanh → SCQA + Mô Hình Tâm Trí + Đảo Ngược
📊 Nghiên cứu khoa học → 5W2H + Tư Duy Phản Biện + Tư Duy Hệ Thống
💡 Hướng dẫn thực hành → SCQA + 5W2H + Nguyên Lý Đầu Tiên
🎯 Bài bình luận → Tư Duy Phản Biện + Đảo Ngược + Sáu Mũ
📈 Case study → SCQA + Mô Hình Tâm Trí + Tư Duy Hệ Thống
```

## Bước 2: Hiểu Cấu Trúc

**Luôn bắt đầu ở đây bất kể mức độ sâu.**

### Giai Đoạn 2A: Cấu Trúc Cơ Bản

```markdown
📄 Loại nội dung: [Bài viết/Nghiên cứu/Báo cáo/Hướng dẫn]
⏱️ Thời gian đọc ước tính: [X phút]
🎯 Luận điểm cốt lõi: [Một câu]

Tổng quan cấu trúc:
├─ Lập luận chính 1
│   ├─ Điểm hỗ trợ 1.1
│   └─ Điểm hỗ trợ 1.2
├─ Lập luận chính 2
└─ Lập luận chính 3

Khái niệm then chốt: [3-5 thuật ngữ với định nghĩa ngắn gọn]
```

### Giai Đoạn 2B: Phân Tích SCQA (Framework Nhanh)

Tải `references/scqa_framework.md` và áp dụng:

```markdown
## Cấu Trúc SCQA

**S (Situation - Tình huống)**: [Bối cảnh/ngữ cảnh mà bài viết thiết lập]
**C (Complication - Phức tạp hóa)**: [Vấn đề/thách thức được xác định]
**Q (Question - Câu hỏi)**: [Câu hỏi cốt lõi đang được giải quyết]
**A (Answer - Trả lời)**: [Giải pháp/kết luận chính]

📊 Chất lượng cấu trúc:
- Rõ ràng: [★★★★☆]
- Luồng logic: [★★★★★]
- Tính đầy đủ: [★★★☆☆]
```

### Giai Đoạn 2C: Kiểm Tra Tính Đầy Đủ 5W2H (nếu Cấp 1+)

Quét nhanh sử dụng `references/5w2h_analysis.md`:

```markdown
## Tính Đầy Đủ Thông Tin

✅ Được bao phủ tốt: [What - Cái gì, Why - Tại sao, How - Như thế nào]
⚠️  Bao phủ một phần: [Who - Ai, When - Khi nào]
❌ Thiếu: [Where - Ở đâu, How much - Bao nhiêu]

🔴 Khoảng trống quan trọng: [Liệt kê 1-2 phần thiếu quan trọng nhất]
```

## Bước 3: Áp Dụng Mô Hình Tư Duy

**Chọn dựa trên mức độ sâu và sở thích người dùng:**

### Cấp 1 (Nhanh - 15 phút)
**Cốt lõi**: Cấu trúc + SCQA + Kiểm tra 5W2H nhanh

Đầu ra:
- Phân tích SCQA
- Khoảng trống thông tin (từ 5W2H)
- TOP 3 insights
- 1 hành động ngay lập tức

### Cấp 2 (Tiêu chuẩn - 30 phút)
**Thêm**: Tư Duy Phản Biện + Đảo Ngược

Tải và áp dụng:
- `references/critical_thinking.md`:
  - Đánh giá chất lượng lập luận
  - Nhận diện lỗi logic
  - Đánh giá bằng chứng
  - Góc nhìn thay thế

- `references/inversion_thinking.md`:
  - Làm sao để đảm bảo thất bại? (đảo ngược lời khuyên)
  - Giả định nào nếu sai?
  - Rủi ro bị thiếu
  - Phân tích pre-mortem

```markdown
## Phân Tích Phản Biện

### Sức mạnh lập luận: [X/10]
Điểm mạnh:
- [Điểm 1]

Điểm yếu:
- [Điểm 1]

Ngụy biện logic phát hiện:
- [Nếu có]

## Phân Tích Đảo Ngược

🚨 Cách việc này có thể thất bại:
1. [Chế độ thất bại 1] → Giảm thiểu: [...]
2. [Chế độ thất bại 2] → Giảm thiểu: [...]

Yếu tố rủi ro bị thiếu:
- [Rủi ro 1]
```

### Cấp 3 (Sâu - 60 phút)
**Thêm**: Mô Hình Tâm Trí + Nguyên Lý Đầu Tiên + Hệ Thống + Sáu Mũ

Tải và áp dụng:
- `references/mental_models.md`:
  - Chọn 3-5 mô hình liên quan từ các ngành khác nhau
  - Áp dụng từng góc nhìn vào nội dung
  - Nhận diện insights xuyên-mô hình

- `references/first_principles.md`:
  - Loại bỏ đến sự thật cơ bản
  - Nhận diện giả định cốt lõi
  - Xây dựng lại hiểu biết từ nền tảng

- `references/systems_thinking.md`:
  - Lập bản đồ mối quan hệ và vòng phản hồi
  - Nhận diện điểm đòn bẩy
  - Nhìn bức tranh toàn cảnh

- `references/six_hats.md`:
  - Trắng (sự thật), Đỏ (cảm xúc), Đen (thận trọng)
  - Vàng (lợi ích), Xanh lá (sáng tạo), Xanh dương (quy trình)

```markdown
## Phân Tích Đa-Mô Hình

### Mô Hình Tâm Trí Áp Dụng:
1. **[Mô hình 1 từ ngành X]**
   Insight: [...]

2. **[Mô hình 2 từ ngành Y]**
   Insight: [...]

3. **[Mô hình 3 từ ngành Z]**
   Insight: [...]

Mẫu xuyên-mô hình: [Insight chính từ việc kết hợp các mô hình]

### Phân Tích Nguyên Lý Đầu Tiên:
Giả định cốt lõi:
1. [Giả định 1] → Hợp lệ: [Có/Không/Có điều kiện]
2. [Giả định 2] → Hợp lệ: [Có/Không/Có điều kiện]

Sự thật cơ bản: [Những gì còn lại sau khi loại bỏ giả định]

### Bản Đồ Hệ Thống:
```
[Biến A] ──củng cố──> [Biến B]
      ↑                    |
      |                    |
   cân bằng             củng cố
      |                    |
      └─────────<──────────┘

Điểm đòn bẩy: [Nơi thay đổi nhỏ = tác động lớn]
```

### Góc Nhìn Sáu Mũ:
🤍 Sự thật: [Dữ liệu khách quan]
❤️ Cảm xúc: [Phản ứng trực giác]
🖤 Thận trọng: [Rủi ro và mặt trái]
💛 Lợi ích: [Khía cạnh tích cực]
💚 Ý tưởng: [Phương án sáng tạo]
💙 Quy trình: [Tư duy meta]
```

### Cấp 4 (Nghiên cứu - 120 phút+)
**Thêm**: So sánh đa nguồn qua web_search

Sử dụng web_search để tìm 2-3 nguồn liên quan, sau đó:
- Tải `references/comparison_matrix.md`
- So sánh SCQA giữa các nguồn
- Nhận diện đồng thuận vs. phân kỳ
- Tổng hợp góc nhìn tích hợp

```markdown
## Phân Tích Đa Nguồn

### Nguồn 1: [Bài viết này]
S-C-Q-A: [Tóm tắt]
Tuyên bố chính: [...]

### Nguồn 2: [Bài viết tìm được]
S-C-Q-A: [Tóm tắt]
Tuyên bố chính: [...]

### Nguồn 3: [Bài viết tìm được]
S-C-Q-A: [Tóm tắt]
Tuyên bố chính: [...]

## Tổng Hợp

**Đồng thuận**: [Những gì tất cả đồng ý]
**Phân kỳ**: [Điểm khác biệt]
**Giá trị độc nhất**: [Mỗi nguồn đóng góp gì]
**Quan điểm tích hợp**: [Tổng hợp của bạn]
```

## Bước 4: Tổng Hợp & Đầu Ra

**Tạo dựa trên mục tiêu người dùng:**

### Cho Giải Quyết Vấn Đề:

```markdown
## Giải Pháp Có Thể Áp Dụng
[Trích xuất 2-3 phương pháp từ nội dung]

## Kế Hoạch Ứng Dụng
Vấn đề: [Vấn đề cụ thể của người dùng]
Insights liên quan: [Từ phân tích]

Các bước hành động:
1. [Hành động cụ thể với timeline]
2. [Hành động cụ thể với timeline]
3. [Hành động cụ thể với timeline]

Chỉ số thành công: [Cách đo lường]

## Giảm Thiểu Rủi Ro (từ Đảo Ngược)
Điểm thất bại tiềm năng:
- [Điểm 1] → Ngăn chặn bằng: [...]
- [Điểm 2] → Ngăn chặn bằng: [...]
```

### Cho Học Tập:

```markdown
## Ghi Chú Học Tập

Khái niệm cốt lõi (giải thích đơn giản):
1. **[Khái niệm 1]**: [Định nghĩa + Ví dụ]
2. **[Khái niệm 2]**: [Định nghĩa + Ví dụ]

Mô hình tâm trí có được:
- [Mô hình 1]: [Cách hoạt động]

Kết nối với kiến thức trước:
- [Liên kết với điều người dùng đã biết]

## Hiểu Sâu Hơn (Nguyên Lý Đầu Tiên)
Câu hỏi cơ bản: [...]
Nguyên lý cốt lõi: [...]

## Câu Hỏi Xác Minh
1. [Câu hỏi kiểm tra hiểu biết]
2. [Câu hỏi kiểm tra ứng dụng]
3. [Câu hỏi kiểm tra đánh giá]
```

### Cho Tham Khảo Viết Bài:

```markdown
## Lập Luận & Bằng Chứng Chính
[Trích xuất có cấu trúc với số trang/đoạn văn]

## Insights Có Thể Trích Dẫn
"[Trích dẫn 1]" — Ngữ cảnh: [...]
"[Trích dẫn 2]" — Ngữ cảnh: [...]

## Ghi Chú Phân Tích Phản Biện
Điểm mạnh: [Để trích dẫn]
Hạn chế: [Để thảo luận cân bằng]

## Góc Nhìn Thay Thế (từ Mô Hình Tâm Trí)
[Các ngành khác sẽ nói gì về điều này]

## Khoảng Trống & Phản Sự Kiện
Những gì bài viết không đề cập:
- [Khoảng trống 1]
- [Khoảng trống 2]
```

### Cho Ra Quyết Định:

```markdown
## Framework Quyết Định

Các lựa chọn trình bày: [A / B / C]

Đánh giá đa-mô hình:
- Góc nhìn kinh tế: [...]
- Góc nhìn rủi ro (Đảo ngược): [...]
- Góc nhìn hệ thống: [...]

## Phân Tích Quyết Định Sáu Mũ
🤍 Sự thật: [So sánh khách quan]
🖤 Rủi ro: [Điều gì có thể sai]
💛 Lợi ích: [Tiềm năng tích cực]
💚 Phương án khác: [Lựa chọn khác chưa xem xét]
💙 Khuyến nghị: [Lời khuyên tổng hợp]

## Phân Tích Tình Huống (từ Đảo Ngược)
Trường hợp tốt nhất: [...]
Trường hợp xấu nhất: [...]
Có khả năng nhất: [...]
```

## Bước 5: Kích Hoạt Tri Thức

**Luôn kết thúc với:**

```markdown
## 🎯 Takeaways Ngay Lập Tức (Top 3)

1. **[Insight 1]**
   Tại sao nó quan trọng: [Liên quan cá nhân]
   Một hành động: [Cụ thể, có thời hạn]

2. **[Insight 2]**
   Tại sao nó quan trọng: [Liên quan cá nhân]
   Một hành động: [Cụ thể, có thời hạn]

3. **[Insight 3]**
   Tại sao nó quan trọng: [Liên quan cá nhân]
   Một hành động: [Cụ thể, có thời hạn]

## 💡 Chiến Thắng Nhanh
[Một việc thử trong 24 giờ tới - làm nó NHỎ và CỤ THỂ]

## 🔗 Các Bước Tiếp Theo

**Để hiểu sâu hơn:**
[ ] Đọc thêm: [Nếu liên quan]
[ ] Áp dụng framework X cho chủ đề Y
[ ] Thảo luận với: [Ai có thể thêm góc nhìn]

**Để áp dụng:**
[ ] Thử nghiệm: [Kiểm tra trong ngữ cảnh thực]
[ ] Dạy lại: [Giải thích cho người khác]
[ ] Kết hợp: [Mix với ý tưởng khác]

## 🧭 Mô Hình Tư Duy Đã Sử Dụng
[Checkboxes hiển thị frameworks nào đã được áp dụng]
✅ SCQA ✅ 5W2H ✅ Tư Duy Phản Biện ✅ Đảo Ngược
□ Mô Hình Tâm Trí □ Nguyên Lý Đầu Tiên □ Hệ Thống □ Sáu Mũ
```

## Tiêu Chuẩn Chất Lượng

Mỗi phân tích phải:
- ✅ Trung thành với nội dung gốc (không xuyên tạc)
- ✅ Phân biệt sự thật với ý kiến
- ✅ Cung cấp ví dụ cụ thể
- ✅ Áp dụng frameworks phù hợp (không ép buộc)
- ✅ Kết nối với ngữ cảnh người dùng khi có thể
- ✅ Kết thúc với các bước hành động
- ✅ Trích dẫn phần cụ thể (số đoạn văn, trích dẫn)

**Tránh:**
- ❌ Quá tải với tất cả frameworks cùng lúc (tôn trọng mức độ sâu)
- ❌ Thuật ngữ học thuật không giải thích
- ❌ Phân tích không ứng dụng
- ❌ Sao chép văn bản nguyên văn (luôn diễn đạt lại để hiểu)
- ❌ Sử dụng frameworks nông cạn (đi sâu, không rộng)

## Mẫu Tương Tác

**Đặt câu hỏi dần dần:**
- Hiểu biết: "Bạn nghĩ tác giả có ý gì khi nói X?"
- Phản biện: "Bạn có thấy khoảng trống nào trong lập luận này không?"
- Ứng dụng: "Bạn có thể sử dụng điều này trong công việc như thế nào?"
- Meta: "Mô hình tư duy nào giúp bạn nhiều nhất? Tại sao?"

**Thích nghi với tín hiệu:**
- Người dùng hỏi "điểm chính là gì?" → Họ muốn ngắn gọn, dùng SCQA
- Người dùng thách thức phân tích của bạn → Thiên về Tư Duy Phản Biện + Đảo Ngược
- Người dùng hỏi "làm sao tôi dùng điều này?" → Tập trung vào ứng dụng + Nguyên Lý Đầu Tiên
- Người dùng muốn "nhiều góc nhìn" → Dùng Sáu Mũ hoặc Mô Hình Tâm Trí
- Người dùng đề cập "rủi ro" → Áp dụng Tư Duy Đảo Ngược
- Người dùng hỏi "điều này kết nối như thế nào?" → Dùng Tư Duy Hệ Thống

**Đề xuất framework trong cuộc trò chuyện:**
- "Bạn có muốn tôi áp dụng [framework X] cho điểm này không?"
- "Đây có vẻ là nơi tốt cho tư duy đảo ngược - muốn khám phá các chế độ thất bại?"
- "Tôi nhận thấy vài mô hình tâm trí đang hoạt động ở đây, muốn tôi phân tích không?"

## Tài Liệu Tham Khảo

### Frameworks Cốt Lõi (Tất Cả Cấp)
- `references/scqa_framework.md` - Cấu trúc tư duy (S-C-Q-A)
- `references/5w2h_analysis.md` - Kiểm tra tính đầy đủ (7 câu hỏi)

### Frameworks Cấp Tiêu Chuẩn
- `references/critical_thinking.md` - Phân tích lập luận
- `references/inversion_thinking.md` - Phân tích rủi ro và chế độ thất bại

### Frameworks Cấp Sâu
- `references/mental_models.md` - Thư viện mô hình đa ngành
- `references/first_principles.md` - Phương pháp trích xuất bản chất
- `references/systems_thinking.md` - Lập bản đồ mối quan hệ
- `references/six_hats.md` - Giao thức đa góc nhìn

### Định Dạng Đầu Ra
- `references/output_templates.md` - Ví dụ định dạng ghi chú
- `references/comparison_matrix.md` - Phân tích đa bài viết

## Sử Dụng Nâng Cao

### Kết Hợp Framework Tùy Chỉnh

Người dùng có thể yêu cầu kết hợp cụ thể:
- "Dùng SCQA + Đảo Ngược" - Cấu trúc với phân tích rủi ro
- "Áp dụng Mô Hình Tâm Trí + Tư Duy Hệ Thống" - Phân tích hệ thống đa góc nhìn
- "5W2H + Tư Duy Phản Biện" - Kiểm tra tính đầy đủ + chất lượng

### Đi Sâu Dần

Bắt đầu với Cấp 1, sau đó hỏi:
- "Muốn đi sâu hơn phần nào không?"
- "Framework nào sẽ có giá trị nhất ở đây?"
- "Chúng ta nên làm phân tích đảo ngược cho giải pháp này không?"

### Tối Ưu Theo Lĩnh Vực

**Kinh doanh/Chiến lược**: SCQA + Mô Hình Tâm Trí (kinh tế) + Đảo Ngược
**Kỹ thuật/Nghiên cứu**: 5W2H + Nguyên Lý Đầu Tiên + Tư Duy Phản Biện
**Phát triển cá nhân**: Sáu Mũ + Đảo Ngược + Hệ Thống
**Ra quyết định**: Mô Hình Tâm Trí + Đảo Ngược + SCQA
**Sáng tạo**: Sáu Mũ + Nguyên Lý Đầu Tiên + Mô Hình Tâm Trí

---

**Ghi nhớ**: Mục tiêu là insight, không phải hoàn thành framework. Sử dụng frameworks như công cụ để tiết lộ hiểu biết, không phải như checklist để hoàn thành. Chất lượng tư duy > số lượng frameworks áp dụng.
