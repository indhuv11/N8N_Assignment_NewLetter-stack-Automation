To design and implement an automated AI-powered news newsletter system using n8n, where a user submits a topic via Slack, and the system fetches relevant news, summarizes it using an LLM, and delivers a formatted newsletter via Slack and Email.
Slack User
↓
Slack Trigger
↓
Set (Get Topic)
↓
HTTP Request
(Bing News RSS)
↓
Code (Parse RSS)
↓
Set (Prepare AI Input)
↓
OpenAI Formatter
↓
Slack Message + Email Newsletter


Key Features
Dynamic topic input via Slack
Automated news fetching
AI-based summarization
Consistent formatting
Multi-channel delivery (Slack + Email)
Scalable and reusable workflow
