#Information

*Author*:    Kevin Jalbert  (kevin.j.jalbert@gmail.com)

*Copyright*: Copyright (c) 2011 Kevin Jalbert

*License*:   MIT License

This LaTeX file was created to provide an easy and expandable Curriculum vitae (CV) template. There is a section for the personal details, which are used to create the title of the CV. There exist helper commands that act like functions to produce formated entries. To add a new entry it becomes a simple matter of providing the new information, the formatting is already handled. In situation where a new format is desired it is quite easy to create a new helper command. There is bookmark support as well for each section created.

[_Example CV made with this template_](http://kevinjalbert.com/public/files/misc/kevin-jalbert-cv.pdf "kevin-jalbert-cv")

#Pre-Requirements

This program takes advantage of [LaTeX](http://www.latex-project.org/ "LaTeX") / [pdfLaTeX](http://www.tug.org/applications/pdftex/ "pdfLaTeX")

* The LaTeX [geometry](ftp://ftp.tex.ac.uk/tex-archive/macros/latex/contrib/geometry/geometry.pdf "geometry") package
* The LaTeX [ifthen](http://www.tug.org/texlive/devsrc/Master/texmf-dist/doc/latex/base/ifthen.pdf "ifthen") package
* The LaTeX [ulem](http://mirror.math.ku.edu/tex-archive/macros/latex/contrib/ulem/ulem.pdf "ulem") package
* The LaTeX [hyperref](http://www.tug.org/applications/hyperref/manual.html "hyperref") package

#Execution

1. Download the source code and place it into a directory of choice
2. Modify the .tex file to your own desire (should only need to adjust the personal details, and the content sections. Unless you want to add new sections.)
2. View the actions you can perform (compiling/cleaning) by using the following command ```rake``` while in the root directory.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/kevinjalbert/curriculum-vitae/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

