# Velrim

**Turn documents into typed objects.** Velrim is a document extraction API: describe the output you want as a JSON Schema (or a Zod / Pydantic model via the SDKs), send a document, and get back data that already fits your code — with calibrated per-field confidence scores and source anchors pointing at where on the page each value came from.

- **Website** — [velrim.com](https://velrim.com)
- **Docs** — [velrim.com/docs](https://velrim.com/docs) · agent-readable index at [velrim.com/llms.txt](https://velrim.com/llms.txt)
- **Reliability** — published calibration curves at [velrim.com/reliability](https://velrim.com/reliability)
- **TypeScript SDK** — [`@velrim/sdk` on npm](https://www.npmjs.com/package/@velrim/sdk)
- **Python SDK** — [`velrim` on PyPI](https://pypi.org/project/velrim/)
- **Eval CLI** — [`velrim-eval`](https://github.com/velrimhq/velrim-eval): eval-as-code for document extraction, with adapters for Velrim, OpenAI, Gemini, LlamaExtract, and Mistral
- **Scoring library** — [`@velrim/scoring` on npm](https://www.npmjs.com/package/@velrim/scoring): the same per-field scoring math the API's reliability curves use

Flat $0.02 per page. Open beta — [velrim.com](https://velrim.com).
