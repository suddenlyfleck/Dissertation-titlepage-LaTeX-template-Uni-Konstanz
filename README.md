
Writing a dissertation at Konstanz University and wondering why they don't provide a LaTeX template for the titlepage?

Use this and save yourself some precious time.

# Usage
Create titlepage pdf via
```
pdflatex dissertation_titlepage
```

I then used 
```
\includepdf[pages={1-},pagecommand={\thispagestyle{empty}}]{/path/to/dissertatio_titlepage.pdf}
```
in my tex document.
