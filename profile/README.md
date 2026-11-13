# Laitangtang Lab Workflows

Open-source workflows and infrastructure for simulation-driven research — maintained entirely by AI agents under human direction.

## What lives here

Nine agent skills (SKILL.md format — usable with Claude Code, DeepSeek Harness and compatible harnesses, or as plain documentation) covering the full research toolchain, plus one DSH (DeepSeek Harness) web-client plugin:

| Repository | Domain |
|---|---|
| [openfoam-research-init](https://github.com/Laitangtang-lab-workflows/openfoam-research-init) | Organizing OpenFOAM/CFD research projects (data discipline, case registries, auto-generated indexes, drift audits) |
| [openfoam-cluster-ops](https://github.com/Laitangtang-lab-workflows/openfoam-cluster-ops) | Running OpenFOAM on SLURM HPC clusters (deploy, patrol, harvest, quota, troubleshooting) |
| [paraview-pitfalls](https://github.com/Laitangtang-lab-workflows/paraview-pitfalls) | pvpython batch rendering without surprises (ParaView 5.6.3 + OpenFOAM 9) |
| [word-standards](https://github.com/Laitangtang-lab-workflows/word-standards) | Journal-style Word documents from Markdown (pandoc + raw-OOXML pipeline) |
| [academic-markup](https://github.com/Laitangtang-lab-workflows/academic-markup) | Inline markup markers for AI-assisted academic writing (generate, rewrite, translate, fact-check, cite) |
| [academic-manuscript](https://github.com/Laitangtang-lab-workflows/academic-manuscript) | The manuscript pipeline front door (write → markup → translate → cite → clean → export) |
| [note-gen](https://github.com/Laitangtang-lab-workflows/note-gen) | Curating a research literature library with an AI in the loop |
| [lit-symbol-translation](https://github.com/Laitangtang-lab-workflows/lit-symbol-translation) | The discipline for using formulas and numbers from the literature |
| [adobe-manual](https://github.com/Laitangtang-lab-workflows/adobe-manual) | Driving Illustrator and Photoshop from AI agents (MCP + COM + JSX) |
| [dsh-html-preview](https://github.com/Laitangtang-lab-workflows/dsh-html-preview) | Live HTML preview inside DSH chat (fenced html blocks auto-render in a sandboxed iframe) |

## All projects are AI-maintained

Every file in every repository here — code, documentation, issues triage — is written and updated by AI agents under human supervision. Humans set direction and make decisions; AI sessions do the writing, testing and maintenance, and every commit is machine-authored. The skills themselves exist because these AI sessions built and operate this research toolchain daily.

## License

Everything here is released under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Use it for anything, no attribution required (a nod is always appreciated). Pull requests are welcome; by submitting one you agree your contributions are dedicated under CC0 as well.
