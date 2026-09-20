# Stor566_Deep_Learning_Project

## Project proposal

`main.tex` is a self-contained LaTeX proposal comparing ResNet-50,
EfficientNet-B0, standard non-distilled DeiT-Small, and Swin-Tiny for four-class
brain MRI classification. References are included in the same file.

Open this folder in VS Code and edit `main.tex`. Use **Ctrl+Shift+B** to run
the included **Build proposal PDF** task. It uses the bundled Tectonic
installation on this Windows computer and writes `main.pdf` alongside the
source. On another computer, update the Windows executable path in
`.vscode/tasks.json`, or install Tectonic and run:

```sh
tectonic --synctex --keep-logs main.tex
```

Alternatively, run `pdflatex main.tex` twice with a full LaTeX installation.
Tectonic may download standard TeX packages during its first build.

Fill in `\teamauthors` and `\groupnumber` near the top of `main.tex` when
the team details are available. Empty values are omitted from the PDF.
The proposal body is limited to two pages; references start on a separate page.

The dataset files and experiments are not included in this repository yet.
Record the downloaded dataset version and actual class counts before training.
