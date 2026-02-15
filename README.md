# sciclaw-skills

Skills catalog for [sciClaw](https://github.com/drpedapati/sciclaw), the scientific research AI agent.

## Skills

### Science & Research
| Skill | Description | Source |
|-------|-------------|--------|
| `scientific-writing` | Draft and revise scientific manuscript sections with claim-evidence alignment | local |
| `quarto-authoring` | Author and render Quarto manuscript documents (.qmd) | local |
| `pubmed-cli` | Search PubMed, fetch articles, citation graphs, MeSH lookup | [drpedapati/pubmed-cli](https://github.com/drpedapati/pubmed-cli) |
| `biorxiv-database` | Search and summarize preprints from bioRxiv/medRxiv | local |
| `experiment-provenance` | Capture experiment provenance with reproducible run metadata | local |
| `benchmark-logging` | Define benchmark runs and log outcomes with consistent metrics | local |
| `beautiful-mermaid` | Build publication-grade Mermaid diagrams for manuscript assets | local |

### Office & Documents
| Skill | Description | Source |
|-------|-------------|--------|
| `docx-review` | Word documents with tracked changes, comments, diff (Open XML SDK) | [henrybloomingdale/docx-review](https://github.com/henrybloomingdale/docx-review) |
| `pptx` | Create, edit, summarize, or analyze .pptx slide decks | local |
| `xlsx` | Create, edit, clean, analyze, or convert spreadsheet files | local |
| `pdf` | Create, read, merge, split, transform, or extract data from PDFs | local |

### Development & Utilities
| Skill | Description |
|-------|-------------|
| `github` | Interact with GitHub using the gh CLI |
| `tmux` | Remote-control tmux sessions for interactive CLIs |
| `summarize` | Summarize or extract text/transcripts from URLs and files |
| `humanize-text` | Rewrite AI-generated text to sound naturally human-written |
| `weather` | Get current weather and forecasts |
| `skill-creator` | Create or update AgentSkills |

## Installing a skill

```bash
sciclaw skills install drpedapati/sciclaw-skills/<skill-name>
```

## Searching available skills

```bash
sciclaw skills search <query>
```

## License

MIT
