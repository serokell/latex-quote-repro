# LaTeX dollar repro

A _minimal_ (yes, really) reproduction for a LaTeX error.

Build with `latex main.latex` (or `xelatex`, or `lualatex`) to get:

```text
! Missing $ inserted.
<inserted text> 
                $
l.1 %'
```

Delete any (not critical for the structure) line and it will start to work.
