# Applied and Computational Linear Algebra Repository

This repository collects homework sets and lab write-ups from an applied and computational linear algebra course. The materials emphasize core topics such as eigenvalues/eigenvectors, matrix decompositions, numerical stability, and applications to least squares, Markov chains, and image processing. Most artifacts are distributed as PDFs with solution exports in plain text, RTF, or RTFD bundles that include figures.

## What each component covers

- **Homework sets (`HW1` – `HW8`)**: Progressive exercises on spectral theory, orthogonality, projections, LU/QR decompositions, and iterative methods. Many sets include console transcripts (e.g., `HW1pt1.txt`) showing eigen-computation workflows in MATLAB/Octave.
- **Least-squares lab**: A guided investigation of overdetermined systems, normal equations, and QR-based solvers, with accompanying figures for residual analysis.
- **Markov chain lab**: Explores stochastic matrices, steady-state behavior, and mixing times through worked examples.
- **Image-processing lab**: Applies linear algebra tools to filtering and image transformation tasks, pairing narrative explanations with TIFF figures that illustrate each step.

## How to view the materials

- **PDF files**: open with any PDF viewer. They contain the problem statements and, in some cases, typed solutions.
- **Plain text (`*.txt`)**: view directly in a text editor; many capture console output from numerical linear algebra routines.
- **RTF files (`*.rtf`)**: open with a rich-text editor (e.g., LibreOffice, Word, TextEdit) to preserve formatting.
- **RTFD bundles (`*.rtfd`)**: these are directories containing an `TXT.rtf` file and supporting TIFF images. On macOS, they open as a single rich-text document; on other platforms, open `TXT.rtf` directly and keep the associated images in the same folder for correct embedding.

## Tips for navigating the homework sets

- The homework folders are numbered chronologically. Each set builds on prior topics, moving from eigen-analysis to orthogonality and finally to applications like least squares and Markov chains.
- When solution exports are present, the file names ending in `pt1` or `pt2` correspond to different parts of the assignment. For example, `HW1/HW1pt1.txt` records eigenvalue and eigenspace computations.
- Some homework folders (e.g., `HW6`, `HW8`) include a single consolidated PDF for the entire set.

## Suggested tooling

- To read or convert RTF/RTFD content on non-macOS systems, use tools like `libreoffice --convert-to pdf *.rtf` or `textutil` (on macOS) to generate PDF or plain-text versions.
- If you prefer working purely in the terminal, `pandoc` can convert RTF files to Markdown or PDF while keeping math formatting when present.

## Contributing or extending

- When adding new homework solutions or lab notes, keep related files grouped in a dedicated folder (e.g., `HW9`) and mirror the naming convention used here.
- Prefer PDF or RTF for documents that rely on equation formatting, and place any supporting figures alongside the rich-text source (as done in the existing RTFD bundles).
- If you add computational notebooks or scripts to reproduce results, include a short usage note near the top of the new folder so others can run them easily.
