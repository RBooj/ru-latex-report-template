# Rutgers LaTeX Report Template

A personal LaTeX template for technical reports at Rutgers University.

This repository includes a ready-to-use template with a custom title page, table of contents, headers, and common engineering/reporting packages.

## 📁 Included Files

- `ru-latex-report-template.tex` – Main LaTeX document  
- `inputs/titlePage.tex` – Custom title page include  
- `inputs/images/titlepage_graphic.jpg` – Graphic shown on title page  
- `.gitignore` – Ignores build artifacts like `.aux`, `.log`, `.toc`, etc.

## 🧰 Key Features

- **Custom title page** with course metadata and logo  
- **Automatic table of contents**  
- **Header with author/title/date** on every page after title page  
- Fully configured with commonly used packages for reports

## 📦 Included Packages

**Formatting & Editing**
- `fancyhdr`, `titling`, `geometry`, `indentfirst`, `multicol`, `listings`, `xcolor`, `hyperref`

**Math & Units**
- `amsmath`, `amssymb`, `siunitx`

**Graphics & Diagrams**
- `graphicx`, `float`, `caption`, `tikz`, `circuitikz`

**Code Listings**
- `matlab-prettifier` for pretty-printed MATLAB code

## ⚙️ Custom Commands

The following can be set at the top of your document:

- `\courseName{}` – course name  
- `\instructorName{}` – instructor  
- `\LIName{}` – lab instructor  
- `\courseRoom{}` – room/section

The template also defines:
```
\mathLabel{A}{label}
```
for upright text in math mode.

## 📘 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/RBooj/ru-latex-report-template.git
   ```
2. Edit the metadata at the top of `ru-latex-report-template.tex`
3. Add or modify sections after the provided example
4. Compile with `pdflatex` or on Overleaf

## 📌 Compilation

Run:
```
pdflatex ru-latex-report-template.tex
```
twice to ensure the table of contents is generated correctly.

## 🤝 Contribute

If you improve this template (e.g., add bibliography support or example sections), feel free to open a PR!

```
::contentReference[oaicite:13]{index=13}
