# Contributing Guidelines

Thank you for your interest in contributing to the **SuleimanRosalindBioinformatics** organization! We maintain an academic-grade knowledge base and optimal implementations for all 284 computational biology problems on the Rosalind platform.

---

## Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## Repository Ecosystem
1. **[`SuleimanRosalindBioinformatics`](https://github.com/SuleimanRosalindBioinformatics/SuleimanRosalindBioinformatics)**: Core Python 3 implementations, official datasets (`rosalind_*.txt`), verified outputs (`output.txt`), and the full Obsidian LLM Wiki (`wiki/`).
2. **[`SuleimanRosalindBioinformatics.github.io`](https://github.com/SuleimanRosalindBioinformatics/SuleimanRosalindBioinformatics.github.io)**: Interactive web application, master problems explorer, live bio-algorithms studio, and curriculum roadmap.
3. **[`SuleimanRosalindBioinformatics.github`](https://github.com/SuleimanRosalindBioinformatics/.github)**: Organization profile and community health standards.

---

## Coding & Architectural Standards

### Python 3 Implementations
- **Zero Heavy Dependencies**: Implementations in the core track should prioritize pure Python 3 standard library algorithms wherever possible, highlighting algorithmic fundamentals.
- **Biopython / Armory Track**: Standard scientific packages (`biopython`, `numpy`, `scipy`) are permissible where designated by the Bioinformatics Armory track.
- **Dataset Autodetection**: Each problem script `main.py` must auto-detect the local `rosalind_*.txt` input file in its directory, compute the solution, and write the verified result to `output.txt`.
- **Formatting**: Adhere to PEP 8 style standards with concise explanatory inline comments focusing on mathematical recurrences and time/space complexity bounds.

### Wiki & Documentation
- When creating or modifying pages in `wiki/`, follow the three-layer LLM Wiki architecture documented in `AGENTS.md`.
- Use standard double-bracket internal wiki links: `[[page-name]]`.
- Format mathematical expressions in KaTeX/LaTeX standard notation.
- Always log significant additions or linting passes in `wiki/log.md`.

---

## Submitting Pull Requests
1. Fork the target repository.
2. Create a clean feature branch: `git checkout -b feature/algorithm-optimization`.
3. Commit your changes with descriptive commit messages following the Conventional Commits specification.
4. Open a Pull Request referencing any related issues.
