# Set Up

## Mise En Place

If you have [mise installed](https://github.com/jdx/mise) then you can simply run `mise trust && mise install` to get started.

## Typst (recommended)

This repo now includes a Typst source resume.

- Compile to PDF: `typst compile Nicholas_Zolton_Resume.typ Nicholas_Zolton_Resume.pdf`
- Watch + recompile on save: `typst watch Nicholas_Zolton_Resume.typ Nicholas_Zolton_Resume.pdf`

### Install Typst

- Windows (Chocolatey): `choco install typst` or `winget install typst`
- MacOS: `brew install typst`
- Other platforms: see https://typst.app/open-source/#download

## VSCode / Live Preview

If you are using VSCode or a derivative, you can install the recommended extensions (see `.vscode/extensions.json`) and then run `>Typst Preview: Preview Opened File in Browser` to get started with a live reloading web version of your PDF.

If you are using a different editor (for example, Neovim), you can use the following commands to get a live reloading PDF: `mise watch` or `typst watch <your_resume>.typ <your_resume>.pdf`.

# Credits

Thank you to https://github.com/jakegut/resume for the original template, which is based on https://github.com/sb2nov/resume/.

This was originally generated entirely by https://www.chisl.it/ - check it out! We are improving it every day!
