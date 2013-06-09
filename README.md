# SPhDThesis #
*Saurabh Garg ([saurabhgarg@mysoc.net](mailto:saurabhgarg@mysoc.net "saurabhgarg@mysoc.net"))*

SPhDThesis is a latex document class for writing PhD thesis. It is based on the "NUS Guidelines on Format of Research Thesis Submitted For Examination" (http://www.nus.edu.sg/registrar/event/gd-thesisexam.html).

SPhDThesis document class can only be used with pdflatex and doesn't work with latex. This means that all figures should be either in pdf, png, or jpg format. If you have eps figures then they must be converted to pdf.

## Files ##
1. `SPhDThesis.cls` is the document class. You need to copy this to the same folder as the tex file which includes it.
2. `SPhDThesis.pdf` is the manual of the document class. It describes how to use the document class and provide some hints on how to customize it. It also lists some some useful tools for working with latex.
3. Example folder contains a complete example of a thesis written using SPhDThesis document class. The main file, `thesis.tex`, provides a template for writing thesis. You can copy this and modify according to your needs. `figure.tex`, `table.tex`, `algorithm.tex` shows how to format figures, tables, and algorithms, respectively. `thesis.pdf` shows how a thesis looks like using SPhDThesis document class. For convenience, below are some screenshots showing how a thesis looks like.

## Screenshots ##
![Title page](title.png)
<p align="center" style="font-weight:bold"><strong>Title Page</strong></p>
<br/>

![Title page](declaration.png)
<p align="center" style="font-weight:bold"><strong>Declaration</strong></p>
<br/>

![Title page](table-of-contents.png)
<p align="center" style="font-weight:bold"><strong>Table of Contents</strong></p>
<br/>

![Title page](chapter-title.png)
<p align="center" style="font-weight:bold"><strong>Chapter Title</strong></p>
<br/>

![Title page](chapter-header.png)
<p align="center" style="font-weight:bold"><strong>Chapter Header and Table</strong></p>