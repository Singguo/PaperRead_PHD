# PhD Paper Reading Notes

> A living collection of paper-reading notes for my PhD research.

This repository records my ongoing reading, analysis, and reflections on two research directions: **security and privacy in LLM serving systems**, and **spelling correction for low-resource languages**. Each note is written in Markdown and focuses on the research question, method, experimental evidence, strengths, limitations, and follow-up ideas.

## Research Directions

| Direction | Focus | Notes |
| --- | --- | --- |
| **LLM side-channel security** | Information leakage through timing, cache sharing, hardware caches, networks, and related defenses in LLM inference and serving systems. | [Browse notes](Side-channel-attack-inLLMs-paperreading/README.md) |
| **Low-resource language spelling correction** | Error detection, correction, normalization, tokenization, and supporting resources for Persian, Vietnamese, Urdu, and other under-resourced languages. | [Browse notes](Low-resource-languages-spelling-correction-paperreading/README.md) |
| **AI-Sercurity** | AI-based security| [Browse notes](AI-Security-paperreading/README.md) |

## What You Will Find

- Structured reading notes for individual research papers.
- Summaries of key assumptions, methods, datasets, metrics, and findings.
- Critical reflections on contributions, limitations, and open problems.
- Pointers to useful tools, datasets, and possible research directions.

## Repository Structure

```text
.
├── Side-channel-attack-inLLMs-paperreading/
│   ├── README.md
│   └── notes/                             # LLM side-channel paper notes
├── Low-resource-languages-spelling-correction-paperreading/
│   ├── README.md
│   └── notes/
│       ├── Persian/                       # Persian spelling-correction notes
│       ├── Urdu/                          # Urdu spelling-correction notes
│       └── Vietnamese/                    # Vietnamese spelling-correction notes
└── README.md
```

## Reading-Note Framework

Most notes follow a consistent set of questions:

1. **What problem does the paper address, and why does it matter?**
2. **What are the core ideas, assumptions, and technical design?**
3. **How are the experiments set up, and what does the evidence show?**
4. **What are the contributions, limitations, and threats to validity?**
5. **What questions or ideas does this paper inspire for future work?**

## Intended Use

These materials are personal academic reading notes, created for learning and research discussion. They are not substitutes for the original papers; please cite the original work when using its ideas or results. Notes related to side channels are provided for research, analysis, and defensive understanding only.

## Roadmap

- Continue expanding coverage in both research directions.
- Add cross-paper topic summaries and comparative tables.
- Consolidate datasets, evaluation settings, and open research questions.
- Improve links and metadata as the reading collection grows.

## Contact

Issues and constructive discussions are welcome. If you find an incorrect interpretation, a broken reference, or a useful paper that should be included, please open an issue or submit a pull request.
