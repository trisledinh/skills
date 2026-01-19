---
name: NotebookLM Accelerated Learning
description: Kỹ thuật học tập tăng tốc với NotebookLM bao gồm Feynman Method, Spaced Repetition, Active Recall, Concept Mapping và Audio Overview optimization.
---

# NotebookLM Accelerated Learning: Expert Best Practices

> *"Nếu bạn không thể giải thích đơn giản, bạn chưa hiểu đủ tốt."* — Richard Feynman

Skill này tập trung vào việc sử dụng NotebookLM để **học nhanh hơn**, **nhớ lâu hơn**, và **hiểu sâu hơn**.

---

## The Feynman Method với NotebookLM

```
PROMPT SEQUENCE:

BƯỚC 1 - Expert Explanation:
"Giải thích khái niệm [X] từ tài liệu ở mức độ chuyên gia, đầy đủ chi tiết kỹ thuật."

BƯỚC 2 - ELI5 (Explain Like I'm 5):
"Bây giờ giải thích lại khái niệm [X] cho một học sinh lớp 5. 
Sử dụng ví dụ từ đời thường, tránh thuật ngữ chuyên ngành."

BƯỚC 3 - Gap Identification:
"So sánh 2 phiên bản giải thích trên. Những chi tiết quan trọng nào đã bị 
mất trong phiên bản đơn giản? Đó chính là những điểm tôi cần học kỹ hơn."

BƯỚC 4 - Middle Ground:
"Tạo phiên bản giải thích 'vừa phải' - đủ chính xác cho người có nền tảng 
cơ bản nhưng vẫn dễ hiểu. Đây sẽ là bản tôi dùng để dạy lại người khác."
```

---

## Spaced Repetition Question Bank

Tạo ngân hàng câu hỏi cho ôn tập:

```
PROMPT:
"Dựa trên tài liệu, tạo 20 câu hỏi ôn tập chia theo 3 level:

LEVEL 1 - RECALL (Nhớ lại) - 8 câu:
- Dạng: "... là gì?", "Ai đã...?", "Năm nào...?"
- Format: Q: [Câu hỏi] | A: [Đáp án ngắn] | Source: [Trích dẫn]

LEVEL 2 - UNDERSTAND (Hiểu) - 7 câu:
- Dạng: "Tại sao...?", "Giải thích cách...?", "So sánh X và Y"
- Format: Q: [Câu hỏi] | A: [Đáp án 2-3 câu] | Source: [Trích dẫn]

LEVEL 3 - APPLY (Áp dụng) - 5 câu:
- Dạng: "Nếu [tình huống], bạn sẽ...?", "Áp dụng [concept] vào [situation]"
- Format: Q: [Câu hỏi] | A: [Hướng tiếp cận] | Rubric: [Tiêu chí đánh giá]"
```

---

## Active Recall Sessions

```
PROMPT CHO SESSION HỌC:
"Hãy trở thành Socratic Tutor cho tôi. Quy tắc:

1. Hỏi tôi 1 câu hỏi về [Chương/Chủ đề] 
2. ĐỢI tôi trả lời (không đưa đáp án ngay)
3. Sau khi tôi trả lời, hãy:
   - Điểm mạnh trong câu trả lời
   - Điểm thiếu hoặc sai (trích dẫn nguồn chứng minh)
   - Câu hỏi follow-up để đào sâu
4. Tiếp tục cho đến khi tôi nói 'STOP'

Bắt đầu với câu hỏi đầu tiên."
```

---

## Concept Mapping

```
PROMPT:
"Tạo một CONCEPT MAP dạng text cho [Chương/Chủ đề] với format:

CENTRAL CONCEPT: [Khái niệm trung tâm]
    │
    ├── SUB-CONCEPT 1: [Tên]
    │   ├── Detail: [Chi tiết]
    │   ├── Example: [Ví dụ từ tài liệu]
    │   └── Connection to: [Liên kết với concept khác]
    │
    ├── SUB-CONCEPT 2: [Tên]
    │   ├── Detail: [Chi tiết]
    │   ├── Example: [Ví dụ từ tài liệu]
    │   └── Connection to: [Liên kết với concept khác]
    ...

CROSS-CONNECTIONS:
- [Concept A] ←→ [Concept B]: [Giải thích mối quan hệ]
- [Concept C] → [Concept D]: [Giải thích nhân quả]"
```

---

## Audio Overview Optimization

Tận dụng tối đa tính năng Audio Overview:

### Trước khi tạo Audio:
```
PROMPT CHUẨN BỊ:
"Tôi sắp tạo Audio Overview. Hãy tóm tắt 5 điểm quan trọng nhất mà tôi 
muốn 2 host AI nhấn mạnh khi thảo luận. Với mỗi điểm, cho biết:
- Tại sao điểm này quan trọng
- Câu hỏi thú vị có thể đặt ra xung quanh điểm này"
```

### Sau khi nghe Audio:
```
PROMPT FOLLOW-UP:
"Tôi vừa nghe Audio Overview. Có một số điểm tôi muốn làm rõ:
1. [Điểm host đề cập nhưng chưa rõ]
2. [Điểm hấp dẫn muốn đào sâu thêm]

Hãy giải thích chi tiết với trích dẫn từ nguồn."
```

---

## Glossary Generator

```
PROMPT:
"Tạo BẢNG THUẬT NGỮ cho tài liệu này:

| Thuật ngữ | Định nghĩa (ELI5) | Định nghĩa (Chuyên gia) | Ví dụ | Nguồn |
|-----------|-------------------|-------------------------|-------|-------|

Với mỗi thuật ngữ quan trọng:
1. Giải thích đơn giản (ELI5)
2. Giải thích chính xác (cho chuyên gia)
3. Ví dụ thực tế từ tài liệu
4. Trích dẫn nguồn"
```

---

## Knowledge Gap Finder

```
PROMPT:
"Phân tích tài liệu và tìm KNOWLEDGE GAPS của tôi:

1. PREREQUISITES (Kiến thức tiên quyết):
   - Tài liệu giả định người đọc đã biết: [List]
   - Tôi cần học thêm về: [Topics]

2. JARGON DECODER:
   - Thuật ngữ chưa được giải thích rõ: [List]
   - Giải thích từng thuật ngữ: [Definitions]

3. IMPLICIT KNOWLEDGE:
   - Những gì tác giả ngầm hiểu nhưng không nói: [List]
   - Tại sao điều này quan trọng: [Explanation]

4. NEXT READING:
   - Để hiểu sâu hơn, tôi nên đọc thêm: [Recommendations]"
```

---

## Study Schedule Generator

```
PROMPT:
"Tạo LỊCH HỌC cho tài liệu này:

Thời gian tôi có: [X giờ/ngày] trong [Y tuần]
Mục tiêu: [Mô tả mục tiêu học tập]

WEEK 1: Foundation
- Day 1: [Topic] - Time: [X min] - Method: [Read/Practice/Review]
- Day 2: ...
- Weekend: Review + Spaced Repetition

WEEK 2: Deep Dive
...

DAILY ROUTINE:
- Morning (15 min): [New concept]
- Afternoon (10 min): [Practice]
- Evening (5 min): [Quick review]

CHECKPOINTS:
- End of Week 1: Should be able to...
- End of Week 2: Should be able to..."
```

---

## Exam Preparation

```
PROMPT:
"Tôi đang chuẩn bị thi về nội dung này. Giúp tôi:

1. POTENTIAL EXAM QUESTIONS:
   - Multiple choice: [5 câu]
   - Short answer: [5 câu]
   - Essay: [2 câu]

2. KEY FORMULAS/FRAMEWORKS to memorize:
   | Formula/Framework | When to use | Common mistakes |
   
3. CHEAT SHEET (1 page summary):
   - Key concepts: [List with definitions]
   - Key dates/numbers: [If applicable]
   - Key relationships: [X → Y → Z]

4. LAST MINUTE REVIEW (5 min before exam):
   - 3 things to remember:
   - 3 common traps to avoid:"
```

---

## Teaching Others

```
PROMPT:
"Tôi cần dạy lại nội dung này cho [AUDIENCE]. Giúp tôi:

1. LESSON PLAN:
   - Warmup (5 min): [Hook/Question]
   - Main content (20 min): [Key points]
   - Practice (10 min): [Activity]
   - Wrap-up (5 min): [Summary + Q&A]

2. ANALOGIES & METAPHORS:
   - [Concept X] is like [Everyday thing] because...
   - [Concept Y] is like [Everyday thing] because...

3. COMMON MISCONCEPTIONS:
   | Misconception | Why it's wrong | Correct understanding |
   
4. QUESTIONS STUDENTS MIGHT ASK:
   - Q: [Question]
   - A: [Answer with citation]"
```

---

## Quick Learning Prompts

```
1. "Tóm tắt 3 key takeaways từ mỗi chương trong 1 câu."

2. "Nếu tôi chỉ có 10 phút để học, tập trung vào phần nào?"

3. "Tạo mnemonics (thủ thuật ghi nhớ) cho các khái niệm quan trọng."

4. "Liên kết nội dung này với kiến thức phổ thông mà ai cũng biết."

5. "Những sai lầm phổ biến nhất khi học chủ đề này là gì?"

6. "Tạo timeline/chronology của các sự kiện trong tài liệu."

7. "So sánh và đối chiếu [Concept A] với [Concept B] trong một bảng."

8. "Tạo 'elevator pitch' 30 giây về nội dung tài liệu."

9. "Những ứng dụng thực tế nào của kiến thức này trong đời sống?"

10. "Nếu phải dạy lại cho trẻ 10 tuổi, tôi sẽ nói gì?"
```
