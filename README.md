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

A single `index.html` with inline CSS and JavaScript — no build step, no framework, no
external requests. The design is a dark "darkroom" editorial: warm near-black canvas,
cream uppercase type, and one rendered object per section standing in for each paper
or project.

| Path | Purpose |
|---|---|
| `index.html` | The entire site |
| `assets/hero-*.webp` | Hero still life (1200w / 2400w), rendered from code |
| `assets/objects/*.webp` | Per-section objects — particle renders, one per paper / project |
| `assets/fonts/InterVariable.woff2` | Inter, self-hosted (SIL OFL, see `Inter-LICENSE.txt`) |
| `og.png` | Social preview card (1200×630) |
| `.nojekyll` | Serve files verbatim; skip the Jekyll pipeline |

Long-form text for each paper and project sits behind native `<details>` disclosures, so
everything stays readable without JavaScript. The script only adds the nav background on
scroll, the active-section underline and a quiet entrance fade (disabled under
`prefers-reduced-motion`).

To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
