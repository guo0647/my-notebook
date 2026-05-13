# Notebook

Archive of personal study notes and GitHub publication copies.

课程目录中的 `.tex` 文件是工作版本；本仓库保存整理完成后的发布副本。发布副本统一使用学校前缀命名，例如 `HKU COMP3278 Notes.tex`。

## Structure

- `styles/`: shared LaTeX style files, including `notebook.sty`.
- `notes/`: published course notes and any note-specific assets.

## Build

Compile a note from its own folder or from the repository root with `pdflatex`. The published notes load the shared style through:

```tex
\usepackage{../styles/notebook}
```

Local maintenance files live under `local/` and are intentionally ignored by Git.
