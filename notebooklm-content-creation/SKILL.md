---
name: NotebookLM Content Creation
description: Kỹ thuật sáng tạo nội dung với NotebookLM bao gồm Research Pipeline, Style Transfer, Multi-Format Transformation và Ideation Engine.
---

# NotebookLM Content Creation: Expert Best Practices

> *"Biến research thành content trong tích tắc."*

Skill này tập trung vào việc sử dụng NotebookLM để **khai thác tài liệu** thành **nội dung sáng tạo** chất lượng cao.

---

## The "Research → Outline → Draft → Polish" Pipeline

### Stage 1: Research Synthesis

```
PROMPT:
"Dựa trên tất cả nguồn đã upload, tổng hợp thông tin về [Chủ đề] theo format:

KEY FACTS (Số liệu/Sự kiện quan trọng):
1. [Fact] - Source: [Citation]
2. ...

KEY INSIGHTS (Nhận định/Phân tích):
1. [Insight] - Supporting evidence: [Citation]
2. ...

UNIQUE ANGLES (Góc nhìn độc đáo/ít người biết):
1. [Angle] - Why it's interesting: [Lý do]
2. ...

QUOTABLE QUOTES (Trích dẫn hay có thể dùng):
1. "[Quote]" - [Người nói/Nguồn]
2. ..."
```

### Stage 2: Content Outline

```
PROMPT:
"Tôi muốn viết một [loại content: blog/video script/thread] về [Chủ đề].
Đối tượng: [Mô tả audience]
Mục tiêu: [Họ sẽ biết/cảm thấy/làm gì sau khi đọc?]
Tone: [Formal/Casual/Educational/Entertaining]

Hãy tạo OUTLINE chi tiết:

HOOK (Mở đầu cuốn hút):
- Option 1: [Dạng câu hỏi provocative]
- Option 2: [Dạng số liệu gây sốc]
- Option 3: [Dạng câu chuyện cá nhân]

BODY STRUCTURE:
Section 1: [Tiêu đề]
  - Main point:
  - Supporting evidence: [Citation]
  - Transition to next:

Section 2: [Tiêu đề]
  ...

CONCLUSION:
- Key takeaway:
- Call to action:
- Memorable closing line:"
```

### Stage 3: First Draft

```
PROMPT:
"Dựa trên outline trên, viết FIRST DRAFT hoàn chỉnh.
Độ dài: [X words]
Yêu cầu:
- Sử dụng ít nhất 3 trích dẫn/số liệu từ nguồn
- Mỗi trích dẫn phải có [Citation number]
- Viết theo tone [X]
- Tránh cụm từ generic như 'trong thế giới ngày nay', 'như chúng ta đều biết'"
```

### Stage 4: Polish & Optimize

```
PROMPT:
"Review và cải thiện draft trên theo các tiêu chí:

1. CLARITY: Có câu nào khó hiểu không? Viết lại đơn giản hơn.
2. FLOW: Các đoạn văn nối với nhau mượt mà chưa? Thêm transition nếu cần.
3. ENGAGEMENT: Đánh dấu 3 điểm 'boring' nhất và đề xuất cách làm hấp dẫn hơn.
4. ACCURACY: Kiểm tra lại các số liệu/trích dẫn có khớp với nguồn không.
5. CTA: Call-to-action cuối có đủ mạnh không? Đề xuất 2 phiên bản khác."
```

---

## Style Transfer & Voice Matching

```
PROMPT:
"Tôi đã upload:
- Source A: Tài liệu nghiên cứu về [Chủ đề]
- Source B: Một bài viết mẫu thể hiện văn phong của tôi

Phân tích văn phong của Source B:
- Sentence structure (câu dài/ngắn, đơn/phức):
- Vocabulary level (đơn giản/học thuật):
- Tone (formal/casual/humorous):
- Signature phrases (cụm từ đặc trưng):
- Paragraph rhythm (nhịp điệu đoạn văn):

Sau đó, viết một bài về [Chủ đề] từ Source A nhưng HOÀN TOÀN theo văn phong Source B."
```

---

## Multi-Format Transformation

```
PROMPT:
"Chuyển đổi nội dung [Chương X] thành các format sau:

1. LINKEDIN POST (300 words):
   - Hook mạnh
   - 3-5 bullet points
   - CTA engage

2. TWITTER/X THREAD (10 tweets):
   - Tweet 1: Hook + promise
   - Tweet 2-8: Main content (1 idea/tweet)
   - Tweet 9: Summary
   - Tweet 10: CTA + save/retweet

3. YOUTUBE VIDEO SCRIPT (5 min):
   - 0:00-0:30: Hook + intro
   - 0:30-4:00: Main content with timestamps
   - 4:00-5:00: Recap + CTA subscribe

4. PODCAST TALKING POINTS:
   - Opening story/hook
   - 5 discussion points with transitions
   - Closing thought"
```

---

## Ideation Engine

```
PROMPT:
"Dựa trên tất cả nguồn tài liệu, hãy brainstorm content ideas:

EVERGREEN CONTENT (Nội dung không lỗi thời):
1. [Idea] - Angle: [Góc tiếp cận] - Format: [Blog/Video/...]
2. ...

TRENDING HOOKS (Kết nối với xu hướng hiện tại):
1. [Trend] + [Your topic] = [Idea]
2. ...

CONTRARIAN TAKES (Quan điểm ngược dòng):
1. "Mọi người nghĩ [X] nhưng thực ra [Y]" - Evidence: [Citation]
2. ...

STORYTELLING OPPORTUNITIES:
1. [Case study/Ví dụ] có thể kể thành story như thế nào?
2. ...

SERIES IDEAS (Nội dung nhiều phần):
1. "[Series name]" - Part 1: ... Part 2: ... Part 3: ..."
```

---

## Headline Generator

```
PROMPT:
"Tạo 10 HEADLINES cho bài viết về [Chủ đề] từ tài liệu:

CURIOSITY GAP (Tạo tò mò):
1. [Headline]
2. [Headline]

NUMBER-BASED (Dựa trên số liệu):
3. [Headline]
4. [Headline]

HOW-TO (Hướng dẫn):
5. [Headline]
6. [Headline]

CONTRARIAN (Ngược dòng):
7. [Headline]
8. [Headline]

EMOTIONAL (Gợi cảm xúc):
9. [Headline]
10. [Headline]

TOP 3 RECOMMENDATIONS và lý do:"
```

---

## Hook Library

```
PROMPT:
"Dựa trên tài liệu, tạo HOOKS cho các định dạng:

STORY HOOKS (Mở đầu bằng câu chuyện):
1. "[Quote/Scene từ tài liệu]..."
2. ...

STATISTIC HOOKS (Mở đầu bằng số liệu):
1. "[Số liệu shocking] - Source: [Citation]"
2. ...

QUESTION HOOKS (Mở đầu bằng câu hỏi):
1. "[Câu hỏi provocative]?"
2. ...

CONTRARIAN HOOKS (Mở đầu bằng quan điểm ngược):
1. "Mọi người tin rằng [X]. Họ sai. Đây là lý do..."
2. ...

PROMISE HOOKS (Mở đầu bằng lời hứa):
1. "Sau khi đọc bài này, bạn sẽ [result]..."
2. ..."
```

---

## Content Repurposing

```
PROMPT:
"Tôi đã viết [loại content gốc] về [Chủ đề]. Hãy repurpose thành:

1. EMAIL NEWSLETTER:
   - Subject line (3 options):
   - Preview text:
   - Body (shortened):
   - CTA:

2. INSTAGRAM CAROUSEL (10 slides):
   - Slide 1: Hook
   - Slides 2-9: Key points (1 point/slide)
   - Slide 10: CTA

3. INFOGRAPHIC OUTLINE:
   - Title:
   - Section 1: [Visual + Text]
   - Section 2: [Visual + Text]
   - Source credits:

4. QUOTE GRAPHICS (5 quotes to visualize):
   1. "[Quote 1]"
   2. ..."
```

---

## SEO Content Optimization

```
PROMPT:
"Tối ưu nội dung cho SEO:

1. KEYWORD EXTRACTION:
   - Primary keyword: [Từ tài liệu]
   - Secondary keywords: [List]
   - Long-tail keywords: [List]

2. META ELEMENTS:
   - Title tag (60 chars): 
   - Meta description (155 chars):
   - URL slug:

3. CONTENT STRUCTURE:
   - H1: [Main title]
   - H2s: [List of subheadings]
   - Featured snippet opportunity: [Question + Answer]

4. INTERNAL LINKING OPPORTUNITIES:
   - Link to [related topic] when mentioning [concept]
   - ..."
```

---

## Content Calendar Generator

```
PROMPT:
"Dựa trên tài liệu, tạo CONTENT CALENDAR cho 1 tháng:

WEEK 1: [Theme]
- Monday: [Content type] - [Topic] - [Platform]
- Wednesday: [Content type] - [Topic] - [Platform]
- Friday: [Content type] - [Topic] - [Platform]

WEEK 2: [Theme]
...

CONTENT MIX:
- 40% Educational: [Topics]
- 30% Engagement: [Topics]
- 20% Promotional: [Topics]
- 10% Behind-the-scenes: [Topics]

REPURPOSING PLAN:
- Blog post → Thread → Carousel → Video"
```

---

## Quick Content Prompts

```
1. "Tạo 5 tweet standalone từ insights trong tài liệu."

2. "Viết email subject lines (10 options) cho newsletter về chủ đề này."

3. "Tạo Q&A section với 10 câu hỏi thường gặp từ tài liệu."

4. "Viết bio/about section dựa trên expertise trong tài liệu."

5. "Tạo 5 CTAs khác nhau cho các mục đích khác nhau."

6. "Viết testimonial template dựa trên case studies trong tài liệu."

7. "Tạo comparison table cho [Product/Concept A] vs [Product/Concept B]."

8. "Viết FAQ schema cho SEO từ nội dung tài liệu."

9. "Tạo 'listicle' với format '10 điều bạn chưa biết về [Topic]'."

10. "Viết script cho Instagram/TikTok Reel 60 giây."
```
