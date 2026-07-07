# arXiv Submission Package

## Paper Title
**p-adic AdS/CFT as a Discovery Tool: Reverse Inspiration and the Berkovich Bridge**

## Author
Tianqi Liu  
School of Materials and Chemical Engineering, Zhengzhou University of Light Industry  
136 Science Avenue, High-Tech Zone, Zhengzhou, China  
Email: tianqi689@gmail.com

## Files
- `main.tex` — LaTeX source file (single file, self-contained)
- `README.md` — This file

## Compilation Instructions

### Option 1: Local LaTeX Installation
```bash
cd arxiv
pdflatex main.tex
pdflatex main.tex   # run twice for cross-references
```

### Option 2: Overleaf
1. Upload `main.tex` to Overleaf
2. Set compiler to `pdfLaTeX`
3. Compile

## arXiv Classification
- **Primary category**: `hep-th` (High Energy Physics - Theory)
- **Secondary categories**: `math.NT` (Number Theory), `gr-qc` (General Relativity and Quantum Cosmology)

## Abstract
p-adic AdS/CFT is not a toy model---it is a discovery tool. We systematize eight cases where p-adic computations preceded and illuminated their real-theoretic counterparts (1988--2024), extract five mathematical mechanisms (M1--M5) that explain why p-adic methods simplify hard problems, and construct a mechanism--case matrix that serves as a diagnostic framework for identifying future opportunities.

The Berkovich-space bridge between p-adic and Archimedean physics has been partially validated (two rigorously proven results, two conceptual proposals) but faces four concrete obstacles (O1--O4) that we identify and analyze. We trace the genealogy Stoica(2018) → Huang–Mao–Stoica(2020) → Goldfarb(2023) and provide a candid assessment of what is proven versus proposed.

We propose one new conjecture: the **bulk-sum obstruction**---a criterion for when the adelic product formula holds in flat-space AdS/CFT. Otherwise, this is a survey with original synthesis.

## Key Original Contributions
1. **Bulk-sum obstruction conjecture** (Conjecture 1, §5.5): The adelic product $\prod_\nu A_\nu = 1$ holds if and only if the observable does not involve a bulk sum.
2. **$n+1$ $\zeta_p$ factor formula** (proven for all $n$): p-adic $n$-point contact diagrams produce $n+1$ $\zeta_p$ factors (1 radial + $n$ branch), verified by tree recursion for $n = 4, 5$ and proven generally.
3. **Exchange diagram structural analysis** (§5.5, §7 Problem 3B): Propagator factorization suggests exchange diagrams may partially evade the obstruction.
4. **Mechanism–case matrix** (§4.5): A diagnostic framework validated by retrodictive test against [HJ24].
5. **Five mechanisms M1–M5** (§4.4): Ultrametricity, total disconnectedness, BT tree symmetry, zeta universal scaffolding, adelic product.

## Dependencies
The LaTeX file uses only standard CTAN packages:
- `amsmath`, `amssymb`, `amsthm`, `mathtools`
- `graphicx`, `booktabs`, `array`
- `hyperref`, `cleveref`
- `enumitem`, `float`, `caption`

No external bibliography file needed — references are in `thebibliography` environment.

## Notes
- No figures (external image files) are required; all figures are text-based placeholders.
- The file is self-contained and ready for direct arXiv submission.
- For arXiv submission: upload `main.tex` as a single .tar.gz or directly upload the .tex file.
