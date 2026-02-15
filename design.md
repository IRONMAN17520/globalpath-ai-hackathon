# Design - GlobalPath AI

## Overview
AI navigator that parses docs → generates tailored bureaucracy plans for students/immigrants.

## High-Level Architecture
- Frontend: React/Streamlit (upload interface)
- Backend: Python/FastAPI
- Core AI: AWS Bedrock (LLM parsing/generation) + RAG (policy DB)
- Document Processing: OCR + extraction
- Output: Step-by-step markdown/plans + resource links

## User Flow
1. User registers/logs in
2. Uploads document(s)
3. AI analyzes → matches country/rules
4. Displays plan with steps, deadlines, links
5. User tracks progress

## Tech Stack (planned)
- AWS Bedrock, Lambda, S3
- LangChain/LlamaIndex for RAG
- Multilingual via AWS Translate


