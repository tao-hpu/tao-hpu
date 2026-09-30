<div align="center">

# Hey, I'm Tao An 👋

**`Founder & CEO @ FIM Labs · MS AI · Enterprise AI Agents & Document Intelligence · China × Global`**

<a href="https://fim.ai">
  <img src="https://img.shields.io/badge/FIM%20Labs-AI%20Solutions-6366f1?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0wIDE4Yy00LjQxIDAtOC0zLjU5LTgtOHMzLjU5LTggOC04IDggMy41OSA4IDgtMy41OSA4LTggOHoiLz48L3N2Zz4=&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/tao-hpu">
  <img src="https://img.shields.io/badge/LinkedIn-tao--hpu-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</a>
<a href="https://tao-hpu.github.io">
  <img src="https://img.shields.io/badge/Portfolio-tao--hpu.github.io-blue?style=flat-square&logo=google-chrome&logoColor=white" />
</a>
<a href="https://arxiv.org/a/0009-0006-2933-0320">
  <img src="https://img.shields.io/badge/arXiv-Tao%20An-b31b1b?style=flat-square&logo=arxiv&logoColor=white" />
</a>
<a href="https://scholar.google.com/citations?user=HBIPWm4AAAAJ">
  <img src="https://img.shields.io/badge/Google%20Scholar-HBIPWm4AAAAJ-4285F4?style=flat-square&logo=googlescholar&logoColor=white" />
</a>
<a href="https://orcid.org/0009-0006-2933-0320">
  <img src="https://img.shields.io/badge/ORCID-0009--0006--2933--0320-A6CE39?style=flat-square&logo=orcid&logoColor=white" />
</a>
<a href="https://dblp.org/pid/10/2015-1">
  <img src="https://img.shields.io/badge/DBLP-Tao%20An%200001-004F9F?style=flat-square&logo=dblp&logoColor=white" />
</a>
<a href="mailto:tao@fim.ai">
  <img src="https://img.shields.io/badge/Email-tao%40fim.ai-EA4335?style=flat-square&logo=gmail&logoColor=white" />
</a>

<br/>

*Building cognitive architectures that give LLMs better memory than mine* 🧠

</div>

---

### 🔬 About Me

```python
class TaoAn:
    def __init__(self):
        self.location = "Singapore × Beijing"
        self.company = "FIM Labs"
        self.role = "Founder & CEO"
        self.education = "MS in Artificial Intelligence, Hawaii Pacific University (2026)"
        self.interests = ["RAG", "LLM Memory Architectures", "Knowledge Graphs", "Agentic Workflows"]
        self.current_focus = "Enterprise AI agents & document intelligence across the China × Global boundary"
        self.belief = "Most 'AI agents' should be workflows — fix the plumbing before buying a bigger pump."

    def say_hi(self):
        print("Thanks for dropping by! Let's build something cool together.")

me = TaoAn()
me.say_hi()
```

---

### 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

### 🌱 Selected contributions

**Product**

- **[fim-ai/fim-one](https://github.com/fim-ai/fim-one)** — open-source agent platform for Global × China enterprises (self-hosted, any LLM). Day-job / company product I build and ship.

**Upstream (external)**

- **[openai/openai-agents-python](https://github.com/openai/openai-agents-python)** ![stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat-square&label=&color=343b42) — two bugs in how a paused run is restored from serialized state:
  - [#5142](https://github.com/openai/openai-agents-python/pull/5142) (merged, [`ad93f54`](https://github.com/openai/openai-agents-python/commit/ad93f5420edfecb30c6d2bc3a1a22047918cba1a)): a nested agent-as-tool run serializes its agent references relative to the tool's own agent, but resumption resolved them against the parent, so with two same-named agents a pending approval silently never applied. Root cause, 7-line fix, 218 lines of regression tests.
  - [#3749](https://github.com/openai/openai-agents-python/pull/3749): a pending nested approval could bind to the wrong tool call once an earlier entry was filtered out. The maintainer re-landed it at source level as [#3753](https://github.com/openai/openai-agents-python/pull/3753) with [`Co-authored-by: Tao An`](https://github.com/openai/openai-agents-python/commit/60d3f95219654d68e0a43789ecbd600e38ee2606).
- **[eigenpal/docx-editor](https://github.com/eigenpal/docx-editor)** ![stars](https://img.shields.io/github/stars/eigenpal/docx-editor?style=flat-square&label=&color=343b42) — CJK typography in the OOXML layout engine, ~2k lines merged: resolved the `eastAsia` font slot so CJK runs measure and paint in their own face ([#539](https://github.com/eigenpal/docx-editor/pull/539)), and added kinsoku line breaking between ideographs ([#540](https://github.com/eigenpal/docx-editor/pull/540)).
- **[acmesh-official/acme.sh](https://github.com/acmesh-official/acme.sh)** ![stars](https://img.shields.io/github/stars/acmesh-official/acme.sh?style=flat-square&label=&color=343b42) — [#7278](https://github.com/acmesh-official/acme.sh/pull/7278) (merged, [`6467ca9`](https://github.com/acmesh-official/acme.sh/commit/6467ca9764f89b4a887142ee18b05219d1cf5f8a)): `_setopt()` and `_clear_conf()` redirected new content straight into the conf file, so a write that failed on a full disk truncated it to 0 bytes while `_save_conf` still returned 0, and the certificate could no longer renew ([#7247](https://github.com/acmesh-official/acme.sh/issues/7247)). Every conf write now goes through a temp copy in the same directory that is verified and then renamed over the original; symlinked or bind-mounted confs keep the in-place write. Checked under dash, bash, zsh and busybox ash, and on an ext4 loop mount filled to 0 free blocks.
- **[docling-project/docling](https://github.com/docling-project/docling)** ![stars](https://img.shields.io/github/stars/docling-project/docling?style=flat-square&label=&color=343b42) — [#4336](https://github.com/docling-project/docling/pull/4336) (merged, [`2682193`](https://github.com/docling-project/docling/commit/268219388f54b32e536c741e45c13591794142cd)): the DOCX backend treated any list level with an East Asian `w:numFmt` as a bullet list, so `第%1条`-style regulation numbering was dropped on conversion ([#4335](https://github.com/docling-project/docling/issues/4335)). Added nine formats (`chineseCounting`, `chineseLegalSimplified`, `japaneseCounting`, `decimalEnclosedCircle` and others) following ECMA-376 §17.18.59, with the cases the standard leaves open settled against Microsoft Word's own output: the converters match 525 Word-rendered markers except one documented glyph choice, backed by 176 parametrized boundary tests and an end-to-end DOCX test.
- **[docling-project/docling-core](https://github.com/docling-project/docling-core)** — the follow-up the docling reviewers asked for: [#799](https://github.com/docling-project/docling-core/pull/799) (merged, [`25ade75`](https://github.com/docling-project/docling-core/commit/25ade75406ab7a809b3296714a84080cf71d173e)): the Markdown serializer's `AUTO` marker mode kept an original list marker only if it matched `[a-zA-Z0-9]`, so the CJK markers docling now emits (第九条, （一）, ①) were replaced by `-` ([#798](https://github.com/docling-project/docling-core/issues/798)). The check now accepts any Unicode letter or digit, while bullet glyphs are still dropped; full suite 768 passed with ground-truth files unchanged.

**Original research / tools**

- **[cognitive-workspace](https://github.com/tao-hpu/cognitive-workspace)** — active memory / functional infinite-context architecture for LLMs.
- **[nano-spec](https://github.com/tao-hpu/nano-spec)** — lightweight task-spec format for AI-assisted development.
- **[cog-canvas](https://github.com/tao-hpu/cog-canvas)** — training-free long-term memory for LLM conversations.

---

### 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/tao-hpu/tao-hpu/snake/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/tao-hpu/tao-hpu/snake/snake-light.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/tao-hpu/tao-hpu/snake/snake-dark.svg" />
</picture>

</div>

---

### 📊 GitHub Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api?username=tao-hpu&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-eight-theta.vercel.app/api?username=tao-hpu&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="150" src="https://github-readme-stats-eight-theta.vercel.app/api?username=tao-hpu&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=tao-hpu&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=html,css,scss" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=tao-hpu&layout=compact&theme=default&hide_border=true&langs_count=8&hide=html,css,scss" />
  <img height="150" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=tao-hpu&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=html,css,scss" />
</picture>

</div>

---

### 📈 Activity Graph

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=tao-hpu&theme=tokyo-night&hide_border=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=tao-hpu&theme=github-light&hide_border=true" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=tao-hpu&theme=tokyo-night&hide_border=true" />
</picture>
</div>

---

### 🔥 Coding Heatmap

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ccmap.fim.ai/u/taotao.svg?theme=claude&anim=ember&weeks=53" />
    <source media="(prefers-color-scheme: light)" srcset="https://ccmap.fim.ai/u/taotao.svg?theme=claude-light&anim=ember&weeks=53" />
    <img src="https://ccmap.fim.ai/u/taotao.svg?theme=claude&anim=ember&weeks=53" alt="coding heatmap" />
  </picture>
</div>

---

<div align="center">

**📖 Selected Research**

For my latest papers and research, visit my website 👉 **[tao-hpu.github.io](https://tao-hpu.github.io/)**

[![Website](https://img.shields.io/badge/Research%20%26%20Publications-tao--hpu.github.io-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tao-hpu.github.io/)

</div>

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=tao-hpu&style=flat-square&color=blueviolet)

</div>
