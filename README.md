# n8n Automation — Daily Quote with Urdu Translation

## Description
This n8n workflow runs on a schedule, fetches a random quote from a public API, translates it into Urdu using OpenAI (GPT-4o-mini), and sends both the English quote and Urdu translation to Telegram automatically.

**Workflow:** Schedule Trigger → HTTP Request → OpenAI (Translation) → Telegram

## Full Documentation
Full write-up including screenshots of the canvas and a successful execution log:
🔗 [Google Doc](https://docs.google.com/document/d/1j55WeDRbnX2rxLHJy6RxwybBaOGzbumT_SZQ64Xa7ZY/edit?tab=t.0)

## Workflow JSON
See [`workflow.json`](./workflow.json) in this repo — importable directly into n8n.
