# Kill Switch Audit

CURRENT SETUP
Primary provider: OpenAI
Integration depth: Thin wrapper
Time to switch today: 3 days

STRESS TEST
If pricing doubles: Gross margins on power users instantly go negative due to high token costs from processing long OCR legal contracts. We must immediately limit daily scans and shift to Google Gemini Flash within 3 days.
If ToS restricts use case: OpenAI restricting financial risk apps halts our core logic overnight. We will execute our kill switch, copy-pasting our raw Thai prompts over to Claude or Llama 3 within 48 hours.
Risk level (from integration): Medium-high risk

THREE ACTIONS
This week: Catalog every direct OpenAI SDK call in our codebase. Isolate prompt text assets from the core code to lay the structural foundation for an internal Abstraction Layer.
This month: Build a prototype Abstraction Layer and spike Google Gemini Flash alongside OpenAI. This ensures our interface can ingest OCR data independent of any single foundational AI provider.
This quarter: Deploy a basic Multi-Provider Router to automatically shift traffic between models. Execute a live staging drill to operationally prove we can failover within 48 hours.
