![Workflow thumbnail](assets/thumbnail.webp)

![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# AI-powered RAG configuration assistant: From form to email recommendations

Advanced n8n automation for AI-powered RAG configuration assistant: From form to email recommendations.

## Overview
- Category: Engineering, AI RAG
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
AI-powered RAG Configuration Assistant: submit a form and get deterministic recommendations on embeddings, chunking, vector stores & costs via email + n8n JSON.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.lmChatOpenRouter`
- `n8n-nodes-base.code`
- `n8n-nodes-base.formTrigger`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.if`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.set`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## Screenshots

![Screenshot](assets/5449-automate-sales-cold-calling-pipeline-with-apify--gpt-4o--and-whatsapp.webp)
![Screenshot](assets/Screenshot_2025_06_29_at_15_43_00_b539ee8b6f.png)
![Screenshot](assets/n8nworfklows.webp)
![Screenshot](assets/thumbnail.webp)

## License
MIT License. See `LICENSE`.