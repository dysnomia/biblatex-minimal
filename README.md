biblatex-minimal
================

Minimal example for using bibliographies. To compile execute
```Shell
pdflatex biblio
biber biblio
pdflatex biblio
```

Whenever your bibliography changes, you have to rerun
```Shell
biber biblio
```

I'd recommend a tool like (http://jabref.sourceforge.net) to edit
the bibliographic database ([a relative link](bibliography.bib) in this case).
For more information read the documentation of biblatex or biber:
```Shell
texdoc biblatex
texdoc biber
```
