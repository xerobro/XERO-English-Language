# XERO English — media storage

Public media for the XERO English IELTS platform.

- `audio/` — neural text-to-speech audio (listening tests, examiner prompts, vocabulary). Served via jsDelivr.
- `recordings/` — learners' speaking recordings, **AES-256-GCM encrypted** (`.enc`); only the application server can decrypt them.
