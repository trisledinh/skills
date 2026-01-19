---
name: NotebookLM Mastery
description: Tổng quan về bộ kỹ năng NotebookLM và các kỹ thuật nâng cao. Xem các skill riêng biệt cho từng use case cụ thể.
---

# NotebookLM Mastery: Overview

> *"Công cụ tốt nhất là công cụ bạn biết cách sử dụng ở mức độ sâu nhất."*

Đây là tổng quan về bộ kỹ năng sử dụng NotebookLM. Mỗi use case có skill riêng với prompts chi tiết.

---

## Bộ Skills NotebookLM

| Skill | Mục đích | Link |
|-------|----------|------|
| **notebooklm-deep-reading** | Đọc sâu, phân tích phản biện, ứng dụng thực tế | [Link](../notebooklm-deep-reading/SKILL.md) |
| **notebooklm-learning** | Học tập tăng tốc, ghi nhớ, ôn tập | [Link](../notebooklm-learning/SKILL.md) |
| **notebooklm-content-creation** | Sáng tạo nội dung, viết bài, repurpose | [Link](../notebooklm-content-creation/SKILL.md) |
| **notebooklm-market-research** | Nghiên cứu thị trường, đối thủ, khách hàng | [Link](../notebooklm-market-research/SKILL.md) |
| **notebooklm-slide-deck** | Thiết kế thuyết trình, slide deck | [Link](../notebooklm-slide-deck/SKILL.md) |

---

## NotebookLM Là Gì?

### NotebookLM LÀ:
- **Grounded AI**: AI có căn cứ, chỉ trả lời dựa trên nguồn bạn cung cấp
- **Personal Research Assistant**: Trợ lý nghiên cứu cá nhân hóa
- **Cross-Source Synthesizer**: Công cụ tổng hợp thông tin từ nhiều nguồn
- **Audio Learning Tool**: Công cụ học tập qua âm thanh (Audio Overview)

### NotebookLM KHÔNG PHẢI:
- ChatGPT/Claude thông thường (không có internet access)
- Công cụ tạo nội dung từ không khí (luôn cần nguồn input)
- Database quản lý tài liệu (không thay thế Notion, Obsidian)

### Kiến Trúc Mental Model

```
┌─────────────────────────────────────────────────────────────┐
│                    YOUR NOTEBOOK                            │
├─────────────────────────────────────────────────────────────┤
│  ┌─────────┐  ┌─────────┐  ┌─────────┐  ┌─────────┐        │
│  │ Source 1│  │ Source 2│  │ Source 3│  │ Source N│        │
│  │  (PDF)  │  │ (Docs)  │  │  (URL)  │  │ (Text)  │        │
│  └────┬────┘  └────┬────┘  └────┬────┘  └────┬────┘        │
│       └────────────┴─────┬──────┴────────────┘              │
│                          │                                  │
│                    ┌─────▼─────┐                            │
│                    │  Gemini   │                            │
│                    │  Engine   │                            │
│                    └─────┬─────┘                            │
│                          │                                  │
│       ┌──────────────────┼──────────────────┐               │
│       ▼                  ▼                  ▼               │
│  ┌─────────┐      ┌─────────────┐      ┌─────────┐         │
│  │  Chat   │      │    Notes    │      │  Audio  │         │
│  │Interface│      │   (Saved)   │      │ Overview│         │
│  └─────────┘      └─────────────┘      └─────────┘         │
└─────────────────────────────────────────────────────────────┘
```

---

## Advanced Techniques

### Multi-Notebook Strategy

Khi nghiên cứu dự án lớn, sử dụng nhiều Notebook:

```
PROJECT: [Tên dự án lớn]

NOTEBOOK 1: "Background Research"
- Sources: Academic papers, foundational texts
- Purpose: Build theoretical foundation

NOTEBOOK 2: "Market Data"  
- Sources: Industry reports, competitor info
- Purpose: Market intelligence

NOTEBOOK 3: "Customer Voice"
- Sources: Interviews, surveys, reviews
- Purpose: Customer insights

NOTEBOOK 4: "Synthesis & Output"
- Sources: NOTES exported từ Notebook 1-3
- Purpose: Final analysis & content creation
```

### Prompt Chaining

Xâu chuỗi prompts để có output phức tạp:

```
STEP 1: "List all statistics mentioned in the document"
OUTPUT → Save as Note

STEP 2: "For each statistic, rate its reliability (1-10)"
OUTPUT → Save as Note

STEP 3: "Using only statistics rated 8+, create key messages"
OUTPUT → Final deliverable
```

### Source Quality Scoring

```
PROMPT:
"Đánh giá chất lượng của từng source đã upload:

| Source | Authority (1-10) | Recency | Bias Level | Best Used For |
|--------|------------------|---------|------------|---------------|
| [Name] | [Score] - [Why] | [Date] | [Low/Med/High] | [Use case] |

RECOMMENDATIONS:
- For factual claims, prioritize: [Sources]
- For opinions/analysis, cross-reference: [Sources]
- Treat with caution: [Sources] because [reasons]"
```

---

## Troubleshooting

### Khi NotebookLM Không Hoạt Động Tốt

| Vấn đề | Nguyên nhân | Giải pháp |
|--------|-------------|-----------|
| "Không tìm thấy thông tin" | PDF scan kém | Upload bản text hoặc PDF searchable |
| Trả lời sai lệch | Quá nhiều sources mâu thuẫn | Filter sources, chỉ tick cần thiết |
| Trả lời quá chung | Prompt mơ hồ | Thêm context, constraints, format |
| Citations sai | AI hallucinate nhẹ | Luôn click verify citation |
| Audio Overview không hay | Sources quá technical | Thêm case studies, ví dụ thú vị |

### Limitations

1. **No Internet Access**: Không truy cập thông tin ngoài sources
2. **Context Window**: Có giới hạn lượng text xử lý
3. **No Memory Between Sessions**: Mỗi Notebook độc lập
4. **Citation Accuracy**: ~95%, cần verify thủ công
5. **Language Mix**: Tốt nhất khi sources và prompts cùng ngôn ngữ

---

## Quick Reference Cards

### Daily Reading Session
```
1. Upload tài liệu
2. Prompt: "Tóm tắt 3 key takeaways + 5 câu hỏi thú vị"
3. Deep dive vào câu hỏi thú vị nhất
4. Save notes quan trọng
5. Tạo Audio Overview để nghe lại sau
```

### Content Creation Express
```
1. Upload research materials
2. Prompt: "Extract quotable stats + unique angles"
3. Prompt: "Create outline for [format]"
4. Prompt: "Write first draft"
5. Prompt: "Polish and add transitions"
6. Export + publish
```

### Research Sprint
```
1. Define research question
2. Upload 5-7 diverse sources
3. Prompt: "Create comparison matrix"
4. Prompt: "Identify consensus and conflicts"
5. Prompt: "Synthesize into executive summary"
6. Prompt: "What questions remain unanswered?"
```

---

## Pro Tips

1. **Ghim Citation**: Luôn nhấp vào số trích dẫn [1], [2] để verify nguồn
2. **Giới hạn Nguồn**: Chọn (tick) chỉ tài liệu cần thiết trước khi chat
3. **Saved Responses**: "Save to Note" để ghim câu trả lời hay
4. **Export Notes**: Giữ citation numbers khi export để trace back

---

*Xem các skill riêng biệt để có prompts chi tiết cho từng use case.*
