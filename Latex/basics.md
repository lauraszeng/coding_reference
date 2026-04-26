# Document Structure

Latex files are stored as .tex files.8

Here's the most basic structure of a latex doc:

```
\documentclass{article}
\begin{document}
First document. This is a simple example, with no 
extra parameters or packages included.
\end{document}
```
- `\documentclass{article}` declares what class the document type belongs to, which controls the overall appearance of the doc
    - for example, this class type is an article
- `\begin{document}` and `\end{document}` delimit the body of the doc
    - everything entered before `\begin{document}` is called the preamble

## Preamble
- this is the doc's setup section, in which we define the doc class, specify things such as languages to be used when writing the document, loading packages to be used, default configurations in general, etc
```
\documentclass[12pt, letterpaper]{article}
\usepackage{graphicx}
```