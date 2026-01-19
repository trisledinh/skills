---
name: NotebookLM Slide Deck Creation
description: Kỹ thuật tạo slide thuyết trình chuyên nghiệp với NotebookLM bao gồm Pyramid Principle, Data Storytelling, Visual Hierarchy, Audience-Specific Slides và nhiều templates cho các loại presentation khác nhau.
---

# NotebookLM Slide Deck Creation: Expert Best Practices

> *"Từ văn bản dày đặc sang slide súc tích, thuyết phục."*

Skill này tập trung vào việc sử dụng NotebookLM để **thiết kế**, **viết nội dung**, và **chuẩn bị thuyết trình** chuyên nghiệp.

---

## 1. The "Pyramid Principle" Slide Structure

Barbara Minto's Pyramid Principle áp dụng vào slides:

```
PROMPT:
"Tạo cấu trúc slide theo Pyramid Principle cho chủ đề [X]:

EXECUTIVE SUMMARY SLIDE (Slide 1):
- Headline (Kết luận chính): [1 câu]
- 3 Supporting points: [3 gạch đầu dòng]

SECTION SLIDES:
Section 1: [Tên]
  - Slide 1.1: [Title] - Key message: [1 câu] - Visual: [Đề xuất]
  - Slide 1.2: [Title] - Key message: [1 câu] - Visual: [Đề xuất]
  
Section 2: [Tên]
  ...

APPENDIX SLIDES (Chi tiết backup):
- Slide A1: [Data table cho câu hỏi chi tiết về...]
- Slide A2: [Methodology cho người muốn biết cách tính...]

FLOW CHECK:
- Nếu chỉ đọc tiêu đề các slide, người xem có hiểu story không? [Y/N]
- Có slide nào không cần thiết không?"
```

---

## 2. Data Storytelling

```
PROMPT:
"Tôi có dữ liệu sau từ tài liệu: [Mô tả data]

Hãy đề xuất cách trình bày VISUAL cho từng điểm:

DATA POINT 1: [Số liệu]
  - Story angle: [Số này đáng chú ý vì...]
  - Chart type recommended: [Bar/Line/Pie/...] vì [lý do]
  - Headline for slide: [Câu kết luận, không phải mô tả]
  - Annotation: [Điểm cần highlight trên chart]

DATA POINT 2: ...

COMPARISON DATA:
  - Before/After visualization suggestion:
  - Benchmark comparison suggestion:

WARNING:
- Dữ liệu nào có thể bị hiểu sai nếu trình bày không cẩn thận?
- Caveats cần đề cập:"
```

---

## 3. Speaker Notes Generator

```
PROMPT:
"Viết speaker notes chi tiết cho mỗi slide:

SLIDE [X]: [Title]
Content on slide: [3 bullet points]

SPEAKER NOTES:
Opening (10 sec): [Câu mở đầu tự nhiên]
Main content (60 sec):
  - Point 1: [Giải thích sâu hơn bullet 1] + [Ví dụ/anecdote]
  - Point 2: [Giải thích sâu hơn bullet 2] + [Data point cụ thể]
  - Point 3: [Giải thích sâu hơn bullet 3] + [So sánh/tương phản]
Transition (10 sec): [Câu chuyển sang slide tiếp]

TIMING CUE: ~90 seconds
POTENTIAL QUESTIONS: [Câu hỏi audience có thể hỏi về slide này]
BACKUP DATA: [Nếu hỏi chi tiết, refer to Appendix slide X]"
```

---

## 4. Q&A Preparation (Hostile Audience)

```
PROMPT:
"Đóng vai [stakeholder type: CFO/Investor/Skeptic/Competitor] đang nghe 
presentation này. Hãy:

1. Tạo 10 câu hỏi hóc búa nhất có thể hỏi:
   - 3 câu về methodology/data
   - 3 câu về assumptions
   - 2 câu về risks
   - 2 câu về alternatives

2. Với mỗi câu hỏi, suggest:
   - Best response (câu trả lời tốt nhất)
   - Bridge statement (câu chuyển hướng nếu không biết trả lời)
   - Data to cite (số liệu/nguồn cần trích dẫn)

3. RED FLAGS: Điểm yếu nào trong presentation sẽ bị tấn công đầu tiên?"
```

---

## 5. Presentation Critique

```
PROMPT:
"Review outline/draft presentation với góc nhìn của:

AS AN AUDIENCE MEMBER:
- Điểm nào confusing?
- Điểm nào boring?
- Điểm nào memorable?
- Call-to-action có clear không?

AS A DESIGN CONSULTANT:
- Slide nào quá nhiều text?
- Slide nào cần visual thay vì text?
- Flow có logic không?
- Có redundancy không?

AS A SKEPTIC:
- Claim nào cần thêm evidence?
- Logic nào có thể bị challenge?
- Data nào cần source rõ ràng hơn?

PRIORITY FIXES (Top 5 improvements):"
```

---

## 6. Slide Design Fundamentals

```
PROMPT:
"Đánh giá và tối ưu thiết kế slide theo các nguyên tắc:

TEXT-TO-VISUAL RATIO:
- Slide nào có quá nhiều text (>30 words)?
- Đề xuất: [Cách chuyển thành visual]

ONE IDEA PER SLIDE:
- Slide nào có >1 ý chính?
- Đề xuất: [Cách tách slide]

TITLE AS TAKEAWAY:
- Slide nào có title mô tả thay vì kết luận?
- Ví dụ: "Sales Data" → "Sales Increased 40% YoY"
- Đề xuất titles mới: [List]

VISUAL HIERARCHY:
- Slide nào thiếu focal point?
- Đề xuất: [Cách tạo hierarchy]

COLOR & CONTRAST:
- Đề xuất color palette phù hợp với [tone/brand]:
- Primary: [Color]
- Accent: [Color]
- Background: [Color]"
```

---

## 7. Presentation Types & Templates

### A. PITCH DECK (Investor/Fundraising)

```
PROMPT:
"Tạo PITCH DECK OUTLINE từ tài liệu:

SLIDE 1: Title
- Company name + Tagline

SLIDE 2: Problem
- Pain point: [From document]
- Impact: [Statistics/Evidence]

SLIDE 3: Solution
- Your product/service: [Description]
- Key differentiator: [From document]

SLIDE 4: Market Opportunity
- TAM/SAM/SOM: [Numbers from document]

SLIDE 5: Traction
- Key metrics: [From document]
- Growth: [From document]

SLIDE 6: Business Model
- Revenue streams: [From document]

SLIDE 7: Competition
- Competitive landscape: [From document]

SLIDE 8: Team
- Key members: [From document]

SLIDE 9: Financials
- Projections: [From document]

SLIDE 10: Ask
- Funding amount:
- Use of funds:"
```

### B. BOARD REPORT

```
PROMPT:
"Tạo BOARD REPORT OUTLINE:

EXECUTIVE SUMMARY (1 slide):
- Key achievements this period:
- Critical issues requiring attention:
- Decisions needed:

PERFORMANCE SECTION:
- Financial performance: [From document]
- Operational metrics: [From document]
- YoY/QoQ comparison: [From document]

STRATEGIC UPDATES:
- Progress on initiatives: [From document]
- Market developments: [From document]

RISK SECTION:
- Current risks: [From document]
- Mitigation actions: [From document]

OUTLOOK:
- Forecast: [From document]
- Key assumptions: [From document]

APPENDIX:
- Detailed financials
- Supporting data"
```

### C. SALES PRESENTATION

```
PROMPT:
"Tạo SALES PRESENTATION OUTLINE:

HOOK (90 sec):
- Pain point opener: [From prospect research]
- Credibility statement: [From case studies]

PROBLEM AMPLIFICATION (2 min):
- Current challenges: [From document]
- Cost of inaction: [Statistics]

SOLUTION INTRODUCTION (3 min):
- Product overview: [From document]
- Key features → Benefits: [Table]
- Demo points: [Key moments]

PROOF (2 min):
- Case study 1: [From document]
- Case study 2: [From document]
- ROI data: [From document]

OBJECTION HANDLING (built-in):
| Objection | Response | Evidence |
|-----------|----------|----------|
| [O1] | [R1] | [Citation] |

CLOSE (1 min):
- Pricing slide
- Next steps
- Urgency driver"
```

### D. TRAINING/WORKSHOP

```
PROMPT:
"Tạo TRAINING DECK OUTLINE:

OPENING (5 min):
- Icebreaker question:
- Learning objectives:
- Agenda overview:

MODULE 1: [Topic]
- Concept introduction: [Slide]
- Example: [Slide]
- Exercise: [Slide with instructions]
- Debrief: [Discussion points]

MODULE 2: [Topic]
...

PRACTICE SESSION:
- Case study: [From document]
- Group activity instructions:
- Time allocation:

WRAP-UP:
- Key takeaways (recall from earlier):
- Resources for further learning:
- Action planning template:"
```

### E. CONFERENCE TALK

```
PROMPT:
"Tạo CONFERENCE TALK OUTLINE (20 min):

HOOK (1 min):
- Opening story/question: [From document]
- Why this matters: [Stakes]

CONTEXT (3 min):
- Background: [From document]
- Current state: [Statistics]

INSIGHT 1 (5 min):
- Key finding: [From document]
- Evidence: [Data/Story]
- Implication: [So what?]

INSIGHT 2 (5 min):
- Key finding: [From document]
- Evidence: [Data/Story]
- Implication: [So what?]

INSIGHT 3 (4 min):
- Key finding: [From document]
- Evidence: [Data/Story]
- Implication: [So what?]

CLOSE (2 min):
- Summary: 3 key takeaways
- Call to action:
- Memorable last line:"
```

---

## 8. Storytelling Frameworks

### Hero's Journey

```
PROMPT:
"Cấu trúc presentation theo HERO'S JOURNEY:

1. ORDINARY WORLD: [Current state/problem]
2. CALL TO ADVENTURE: [Why change is needed]
3. REFUSAL OF THE CALL: [Common objections]
4. MEETING THE MENTOR: [Your solution/guide]
5. CROSSING THE THRESHOLD: [Taking action]
6. TESTS, ALLIES, ENEMIES: [Implementation challenges]
7. THE ORDEAL: [Key transformation moment]
8. THE REWARD: [Success/outcomes]
9. THE RETURN: [New normal/sustainable results]

Content from document for each stage: [Map content to stages]"
```

### Problem-Agitate-Solve

```
PROMPT:
"Cấu trúc theo PROBLEM-AGITATE-SOLVE:

PROBLEM (Slides 1-3):
- What's the problem: [From document]
- Who's affected: [Data]
- Visual: [Suggestion]

AGITATE (Slides 4-6):
- What happens if ignored: [From document]
- Emotional impact: [Stories/Examples]
- Cost of inaction: [Statistics]

SOLVE (Slides 7-10):
- Your solution: [From document]
- How it works: [Step by step]
- Proof it works: [Evidence]
- Next steps: [CTA]"
```

### SCQA Framework (McKinsey)

```
PROMPT:
"Cấu trúc theo SCQA:

SITUATION: [What is the current state?]
- Slide content: [From document]
- Data/context: [From document]

COMPLICATION: [What changed? What's the problem?]
- Slide content: [From document]
- Why it matters: [Impact]

QUESTION: [What's the key question to answer?]
- Implied or explicit question:
- This frames the rest of the presentation

ANSWER: [What's your recommendation?]
- Key message (upfront):
- Supporting arguments:
- Evidence from document:
- Next steps:"
```

---

## 9. Visual Hierarchy & Layout

```
PROMPT:
"Đề xuất VISUAL LAYOUT cho từng loại slide:

TITLE SLIDE:
- Layout: [Suggestion]
- Image: [From document theme]
- Typography: [Suggestion]

DATA SLIDE:
- Chart type: [Recommendation]
- Placement: [Left/Right/Center]
- Key number to highlight: [From document]
- Annotation placement: [Suggestion]

QUOTE SLIDE:
- Quote: [From document]
- Attribution: [Source]
- Visual treatment: [Suggestion]

COMPARISON SLIDE:
- Layout: [Side-by-side / Before-After]
- Visual elements: [Icons/Images]

PROCESS SLIDE:
- Number of steps: [X]
- Visual flow: [Horizontal/Vertical/Circular]
- Icons for each step: [Suggestions]

TEAM SLIDE:
- Layout for [X] people: [Grid/Row]
- Photo placement: [Suggestion]"
```

---

## 10. Audience-Specific Slides

### For C-Suite

```
PROMPT:
"Adapt content for C-SUITE AUDIENCE:

WHAT THEY CARE ABOUT:
- Strategic impact
- ROI/Financial implications
- Risks
- Timeline to results

SLIDE MODIFICATIONS:
- Lead with: [Recommendation/Bottom line]
- Remove: [Tactical details]
- Add: [Strategic context]

LANGUAGE ADJUSTMENTS:
- Replace: "[Technical term]" → "[Business impact]"
- Metrics to highlight: [From document]

APPENDIX NEEDS:
- Detail slides for drill-down questions:"
```

### For Technical Audience

```
PROMPT:
"Adapt content for TECHNICAL AUDIENCE:

WHAT THEY CARE ABOUT:
- How it works
- Technical specifications
- Implementation details
- Edge cases

SLIDE MODIFICATIONS:
- Add: [Technical diagrams]
- Include: [Code samples/Architecture]
- Detail: [Methodology]

Q&A PREPARATION:
- Technical questions they'll ask: [List]
- Technical backup slides needed: [List]"
```

### For Investors

```
PROMPT:
"Adapt content for INVESTOR AUDIENCE:

WHAT THEY CARE ABOUT:
- Market opportunity
- Traction/Growth
- Unit economics
- Team capability
- Exit potential

SLIDE MODIFICATIONS:
- Emphasize: [Growth metrics from document]
- Add: [Competitive moat]
- Include: [Use of funds]

QUESTIONS TO PREPARE:
- On valuation:
- On competition:
- On burn rate:
- On market timing:"
```

---

## 11. Opening & Closing Slides

### Powerful Openings

```
PROMPT:
"Tạo 5 cách MỞ ĐẦU ấn tượng từ tài liệu:

1. SHOCKING STATISTIC:
   "[Số liệu từ document]" - Visual: [Suggestion]

2. PROVOCATIVE QUESTION:
   "[Câu hỏi từ theme của document]?"

3. STORY HOOK:
   "[Câu chuyện/case study từ document]..."

4. CONTRAST:
   "Most people think [X]. The data says [Y]."

5. FUTURE VISION:
   "Imagine a world where [outcome from document]..."

RECOMMENDED: [Best option for this content] because [reason]"
```

### Memorable Closings

```
PROMPT:
"Tạo 5 cách KẾT THÚC memorable:

1. CALLBACK:
   Return to opening story/statistic with resolution

2. CHALLENGE:
   "The question is: Will you [action]?"

3. VISION:
   "When we do this, [future state from document]"

4. THREE WORDS:
   Summary in exactly 3 words: "[Word1]. [Word2]. [Word3]."

5. QUOTE:
   "[Relevant quote from document or related source]"

CTA SLIDE:
- Primary action: [What you want them to do]
- Contact info: [Where to reach you]
- Resources: [Links/Downloads]"
```

---

## 12. Handout & Leave-behind

```
PROMPT:
"Tạo ONE-PAGER HANDOUT từ presentation:

HEADER:
- Title: [From presentation]
- Date/Contact:

KEY TAKEAWAYS (3 bullets):
1. [From presentation]
2. [From presentation]
3. [From presentation]

KEY DATA:
| Metric | Value | Source |
|--------|-------|--------|
| [From presentation] | | |

NEXT STEPS:
1. [Action item]
2. [Action item]

RESOURCES:
- [Link/Download]
- [Contact information]

NOTES SECTION:
[Space for audience notes]"
```

---

## 13. Presentation Rehearsal

```
PROMPT:
"Tạo REHEARSAL SCRIPT cho presentation:

TIMING BREAKDOWN:
| Section | Slides | Time | Key Points to Hit |
|---------|--------|------|-------------------|
| Opening | 1-2 | 2 min | [Points] |
| Main | 3-10 | 15 min | [Points] |
| Close | 11-12 | 3 min | [Points] |

TRANSITIONS BETWEEN SECTIONS:
- From Opening to Main: "[Transition sentence]"
- From Main to Close: "[Transition sentence]"

PAUSE POINTS:
- After slide [X]: Pause for questions
- After slide [Y]: Check audience engagement

ENERGY MARKERS:
- High energy needed: Slides [X, Y]
- Slower, thoughtful: Slides [Z]

BACKUP PLANS:
- If running long: Skip slides [X, Y]
- If audience disengaged: Jump to [interactive slide]"
```

---

## 14. Quick Slide Prompts

```
1. "Tóm tắt toàn bộ nội dung thành 10 slide tiêu đề + 1 key message mỗi slide."

2. "Tạo executive summary slide với 3 bullet points quan trọng nhất."

3. "Chuyển đoạn văn [X] thành slide với visual suggestion."

4. "Tạo agenda slide cho presentation 30 phút."

5. "Đề xuất 5 chart/graph ideas từ data trong tài liệu."

6. "Viết slide titles cho mỗi section (kết luận, không mô tả)."

7. "Tạo 'Thank You / Q&A' slide với 3 key takeaways."

8. "Đề xuất icons cho mỗi key concept trong presentation."

9. "Tạo timeline slide cho project/process trong tài liệu."

10. "Viết 1 quote slide từ insight mạnh nhất trong tài liệu."

11. "Tạo comparison slide: [Option A] vs [Option B]."

12. "Đề xuất cách chunking thông tin phức tạp thành multiple slides."

13. "Tạo 'Key Numbers' slide với 3-5 statistics quan trọng."

14. "Viết disclaimer/caveat slide cho data sensitive."

15. "Tạo 'Meet The Team' slide outline cho [X] người."
```

---

## Presentation Checklist

```
PRE-PRESENTATION:
□ All slides follow Pyramid Principle (conclusion in title)
□ <30 words per slide on average
□ Every chart has a clear takeaway
□ Speaker notes written for each slide
□ Q&A answers prepared
□ Backup slides ready
□ Timing rehearsed

DESIGN:
□ Consistent fonts/colors
□ Visual hierarchy clear
□ One idea per slide
□ Proper contrast/readability

CONTENT:
□ Opening hooks attention
□ Flow is logical
□ Evidence supports claims
□ CTA is clear
□ Closing is memorable
```
