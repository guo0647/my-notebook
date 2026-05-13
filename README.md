# Notebook

Archive of personal study notes and GitHub publication copies.

## Structure

- `styles/`: shared LaTeX style files, including `notebook.sty`.
- `notes/`: published course notes and any note-specific assets.

## Build

Compile a note from its own folder or from the repository root with `pdflatex`. The published notes load the shared style through:

```tex
\usepackage{../styles/notebook}
```

Local maintenance files live under `local/` and are intentionally ignored by Git.
