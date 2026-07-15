# fbterzioglu.github.io

Personal portfolio site — [fbterzioglu.github.io](https://fbterzioglu.github.io)

**Fatma Betül Terzioğlu** — AI / ML Research & Development Engineer.
Applied language-model systems for the Turkish legal domain: retrieval, multi-agent
architectures, and production LLM pipelines.

## Publications

- **RDP LoRA: Geometry-Driven Identification for Parameter-Efficient Adaptation in Large Language Models** — [arXiv:2604.19321](https://arxiv.org/abs/2604.19321) (2026)
- **Agentology: Ontology-Driven Operational Environments for Multi-Agent Systems** — [SSRN 6919461](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6919461) (2026)
- **TurkColBERT: A Benchmark of Dense and Late-Interaction Models for Turkish Information Retrieval** — [arXiv:2511.16528](https://arxiv.org/abs/2511.16528) (2025)
- **Turk-LettuceDetect: Hallucination Detection Models for Turkish RAG Applications** — [arXiv:2509.17671](https://arxiv.org/abs/2509.17671) (2025)

Full list on [Google Scholar](https://scholar.google.com/citations?user=vBzzx-MAAAAJ&hl=en).

## About this site

A single self-contained `index.html` — no build step, no dependencies, no external
requests. All CSS and JavaScript are inline; the only assets are the page itself and
an Open Graph card.

| File | Purpose |
|---|---|
| `index.html` | The entire site |
| `og.png` | Social preview card (1200×630) |
| `.nojekyll` | Serve files verbatim; skip the Jekyll pipeline |

Typography uses system serif and monospace stacks rather than web fonts, so the page
renders instantly and works offline. Light and dark themes follow the visitor's system
preference, with a manual toggle that persists to `localStorage`.

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
