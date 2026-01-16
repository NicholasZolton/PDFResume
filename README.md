# Set Up

## Typst (recommended)

This repo now includes a Typst source resume.

- Compile to PDF: `typst compile Nicholas_Zolton_Resume.typ Nicholas_Zolton_Resume.pdf`
- Watch + recompile on save: `typst watch Nicholas_Zolton_Resume.typ Nicholas_Zolton_Resume.pdf`

### Install Typst

- Windows (Chocolatey): `choco install typst`
- Other platforms: see https://typst.app

## PDF Parity (LaTeX vs Typst)

This repo includes a small Python tool to compare the LaTeX and Typst PDFs visually (rasterized via MuPDF) and by extracted text.

### Setup (uv)

- Create venv: `uv venv .venv`
- Install deps: `uv sync`

### Compare

- Compile Typst + compare against the existing LaTeX PDF:
	- `uv run python tools/regen_and_compare.py --write-diffs`
- Compare two PDFs directly:
	- `uv run python tools/pdf_compare.py Nicholas_Zolton_Resume.pdf Nicholas_Zolton_Resume_typst.pdf --write-diffs`

## Windows

If you are on Windows, I highly recommend doing the following:

First, install and setup chocolatey.

Next, install the following packages:

```bash

choco install strawberryperl

choco install miktex

```

Then, start the Miktex Console and switch to Administrator and run "check for updates".

Finally, I highly recommend the following VS Code extensions:

- LaTeX Workshop

## OSX / Linux

If you're on a non-windows platform, I still highly suggest the VSCode extension, but you can even use Nix/Devenv/Direnv to setup the dependencies automatically when you `cd` into the directory. Definitely check it out!

# Credits

Thank you to https://github.com/jakegut/resume for the original template, which is based on https://github.com/sb2nov/resume/.

This was originally generated entirely by https://www.chisl.it/ - check it out! We are improving it every day!
