# UB
LaTeX template for UB's syllabus document:

Template files:
- silabus.tex : a MWE (minimum working example) of LaTeX template file for UB's syllabus
- silabus.pdf : pdf result for silabus.tex
- UBCrestHorizontal.png : image file used in the silabus.tex template
- Makefile : makefile for creating silabus.pdf from silabus.tex

Samples pdf files:
- DSP-Syllabus.pdf : syllabus file for DSP Course @UB Informatics
- Syllabus_Calculus_02_v02.pdf : syllabus file for Calculus 02 course @UB Informatics

For *nix based, the pdf file can be created from the terminal in one of several ways:

- using "make" facility by typing

  >> make

- typing the latex command directly 

  >> pdflatex -synctex=1 -interaction=nonstopmode silabus

- use the LaTeX IDE (the same ones used in Windows-based environment below)

For Windows-based, you can use a LaTeX environment using MikTeX (for the LaTeX engine) and virtually any text editor. Recommended IDE for Windows-based LaTeX environment is TexMaker, TexShop, or TexStudio. Use the facility in the IDE to process the LaTeX file template to create the pdf file.

Other pathway in Windows-based OS to create LaTeX is by utilising cygwin. In the cygwin environment, the same methods of creating LaTeX file under *nix based apply.
