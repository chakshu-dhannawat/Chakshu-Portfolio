# Portfolio

Personal portfolio site for Chakshu Dhannawat, AI Engineer at Otsuka Corporation in Tokyo.

**Live:** https://chakshu-dhannawat.github.io/portfolio/

The site covers my work in production LLM systems: RAG pipelines on the ELK stack, multi-agent orchestration, and LLM fine-tuning (SFT, RLHF, LoRA/QLoRA), along with selected projects and background.

## Structure

- `index.html` — the single-page site (self-contained HTML/CSS, no build step)
- `ABOUT_ME.md` — source content: experience, education, skills, and projects
- `DESIGN.md` — the design system (color tokens, typography, layout notes)

## Running locally

It's a static page, so just open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

Then visit http://localhost:8000.
