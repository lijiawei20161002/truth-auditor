# Truth Auditor: Small Models for Truth-Seeking

This project explores how small reasoning models (e.g. 1.5B parameter DeepScaleR) can act as **auditors** for large language models.  
Instead of trusting big opaque models as the sole arbiters of truth, the auditor model generates **counterarguments, probes assumptions, and highlights missing reasoning** — creating a more open, contestational process of inquiry.

---

## Why
Large LLMs increasingly shape our discourse, but they can also filter, frame, or silence dissenting perspectives.  
Small portable models, running on laptops or edge devices, can serve as independent watchdogs — surfacing challenges and keeping inquiry alive.

---

## Features
- **Auditor model**: critiques outputs from a larger model.
- **Transparent logging**: append-only log of all auditor responses (`JSON`), so critiques cannot be silently erased.
- **Demo notebook**: run side-by-side (large model vs auditor model).
- **Evaluation hooks**: collect feedback on whether auditor responses improved debate quality.

---

## Installation
```bash
git clone https://github.com/yourname/truth-auditor.git
cd truth-auditor
pip install -r requirements.txt
