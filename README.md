## Business Question
Why are customers churning? What are the top complaints in product reviews? How do sentiment and themes differ between high-LTV and low-LTV customers?

## What This Agent Does
- Ingests customer reviews, support tickets, NPS responses (PDF/CSV)
- Uses RAG (Retrieval-Augmented Generation) to answer strategic questions
- Cites exact source documents for every answer (no hallucination)
- Supports bilingual analysis (English + Chinese reviews)

## Evaluation Harness
- Retrieval precision: [X]% (measured against ground truth)
- Groundedness score: [X]/5 (answers cite actual sources)
- Hallucination rate: [X]% (answers without citations)

## Technical Stack
LlamaIndex + OpenAI/DeepSeek API + DuckDB for document metadata

## Decision Log
[Link explaining: When does RAG fail? Why this evaluation metric?]

## 3-Minute Pitch
"I built an AI agent that reads thousands of customer reviews and support tickets, then answers strategic questions like 'What are the top 3 reasons customers churn?' Unlike a chatbot, it cites exact source reviews for every claim, so we can verify the insights. It found that 40% of negative reviews mention 'shipping delays' — a fixable operational issue. Marketing can now prioritize fixing logistics over redesigning the product."
