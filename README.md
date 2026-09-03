# 📄 Anastasia Repina CV

Welcome to the repository for my English version of CV! This document is compiled using LaTeX.

## 👁️ View / Download
You can view or download the latest version of my resume directly from this repository:
👉 **[Download `resume_cv.pdf`](./resume_cv.pdf)**

For a comprehensive look at my projects and technical background, please visit my portfolio: 
🌐 [arepina.github.io](https://arepina.github.io/)

## 🛠️ How to Compile Locally
This CV is built using the [Awesome-CV](https://github.com/posquit0/Awesome-CV) LaTeX template. To compile the PDF yourself, you will need a TeX distribution (like TeX Live or MiKTeX) installed.


Compile from the repository root with XeLaTeX:

```sh
xelatex -interaction=nonstopmode -halt-on-error resume_cv.tex
xelatex -interaction=nonstopmode -halt-on-error resume_cv.tex
```

The local class is tailored to this CV. `\cventry` accepts four arguments:
body, title, location, and dates. `\cventryeducation` uses the same argument order
with education-specific spacing. Pass a complete URL, including `https://`, to
`\homepage`.
