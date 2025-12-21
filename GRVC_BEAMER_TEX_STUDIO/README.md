GRVC Beamer Template (16:9)

Files
- main.tex: example deck
- beamerthemeGRVC.sty: theme definition
- assets/: required images

Compile
- pdfLaTeX: pdflatex main.tex (twice)
- XeLaTeX/LuaLaTeX: xelatex main.tex (twice) for closer font match

Notes
- The title slide (first slide) places the GRVC logo at the lower-left corner automatically.
- To place a project logo at the top-right of a frame:
    \GRVCsetprojectlogo{assets/tema_logo.png}
  and clear it afterwards:
    \GRVCclearprojectlogo
