# Md Imam Ahasan — Academic CV

[![PDF](https://img.shields.io/badge/CV-Download%20PDF-1F4E79?style=flat-square&logo=adobeacrobatreader&logoColor=white)](./main.pdf)
[![Built with LaTeX](https://img.shields.io/badge/Built%20with-XeLaTeX-008080?style=flat-square&logo=latex&logoColor=white)](https://www.latex-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](./LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-June%202026-orange?style=flat-square)]()

---

## About

This repository contains the source and compiled PDF of my academic curriculum vitae, maintained for PhD applications targeting top-tier research universities in South Korea (KAIST, SNU, POSTECH) and internationally.

I am an M.Sc. candidate in Computer Science at **Chongqing University** (Sep 2023 – Jun 2026), advised by Dr. Guangchao Yang. My research sits at the intersection of **physics-informed deep learning** and **computational medical imaging** — developing principled generative models that integrate physical acquisition operators directly into the learning objective for low-dose CT reconstruction.

---

## Research Interests

- **Physics-Informed Generative Models** — cold diffusion, score-based, and Bayesian diffusion frameworks with Poisson-noise forward operators
- **Inverse Problems in Medical Imaging** — low-dose CT reconstruction, sinogram-domain processing, zero-shot cross-domain generalization
- **Trustworthy AI for Healthcare** — uncertainty-aware inference, explainability, and robustness under distribution shift
- **Medical Image Segmentation** — retinal vasculature, skin lesions, mammography

---

## Publication Highlights

| Type | Count | Top Venues |
|------|-------|-----------|
| Conference (Accepted) | 4 | IJCNN 2026 (CCF-C), PRCV 2025 (CCF-C), ICCNC 2026 (EI) |
| Journal (Accepted) | 1 | Computers, Materials & Continua (SCIE) |
| Under Review | 6 | IEEE BIBM 2026 (CCF-B), PeerJ CS (SCIE ×3), CMC (SCIE), CMES (SCIE) |

> **4 papers as first author**, including [C1] IJCNN 2026 (DACD) and [R1]–[R4] under review.

---

## Repository Structure

```
Academic_CV/
├── main.tex          # LaTeX source (XeLaTeX)
├── main.pdf          # Compiled CV (2 pages, A4)
├── .vscode/
│   └── settings.json # LaTeX Workshop build config
├── .gitignore        # Excludes LaTeX build artifacts
└── README.md
```

---

## How to Compile

### Requirements

- **XeLaTeX** (TeX Live 2024+ or MiKTeX)
- **TeX Gyre fonts** (included in TeX Live: `tex-gyre`, `tex-gyre-math`)
- **Packages:** `fontspec`, `unicode-math`, `fontawesome5`, `titlesec`, `enumitem`, `tabularx`, `microtype`

### Build

```bash
xelatex main.tex
```

Or with VS Code + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop): open `main.tex` and save — it auto-builds using the included `.vscode/settings.json`.

### Font Note (macOS)

If XeLaTeX cannot find TeX Gyre fonts, copy them to your font directory:

```bash
cp $(kpsewhich -var-value TEXMFDIST)/fonts/opentype/public/tex-gyre/*.otf ~/Library/Fonts/
cp $(kpsewhich -var-value TEXMFDIST)/fonts/opentype/public/tex-gyre-math/*.otf ~/Library/Fonts/
fc-cache -f
```

---

## Contact

| | |
|---|---|
| **Email** | [emamahasane@gmail.com](mailto:emamahasane@gmail.com) |
| **GitHub** | [@imamahasane](https://github.com/imamahasane) |
| **LinkedIn** | [imamahasane](https://www.linkedin.com/in/imamahasane) |
| **Institution** | College of Computer Science, Chongqing University, China |

---

<p align="center">
  <sub>Typeset in <a href="https://www.latex-project.org/">LaTeX</a> · TeX Gyre Termes · Last compiled June 2026</sub>
</p>