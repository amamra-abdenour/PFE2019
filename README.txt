Roque's Phd thesis template (for LaTeX)


INTRODUCTION
------------
This collection of LaTeX files is a Phd (or habilitation) thesis
template intended to work with PDFLatex 2e. It includes the official
title page from Universit� de Toulouse and relies on an extensible
structure. The sample files are written in French but can be easily
changed to another language thanks to UTF-8 encoding and redefining
few variables.


REQUIREMENTS
------------
 A full LaTeX distribution such as TexLive (>2012) or MikTex (>2012).
 An UTF-8 aware text editor such as TexMaker, TexWorks, Emacs...
 Optionally: a bibliography manager such as JabRef can be used in order
to edit the .bib file.


USAGE
-----
 Edit the {.tex,.bib} files using UTF-8 encoding.
 Rename the .tex files according to your report structure. Update the
links accordingly in "isae-report-template.tex".
 Put your figures in the "images" subdirectory.

The compilation process is the following:
1) Compile the main file "phdthesis.tex" using PDFLatex.
2) Compile the "phdthesis.aux" using BibTeX.
3) Compile twice the main file "phdthesis.tex" using PDFLatex.

Files from the subdirectories are used during the compilation process
(the subdirectory structure is described below).


FILES MANIFEST
--------------
  0-configuration: packages loading and user's macros definitions.
  1-opening: title pages, acknowledgements, acronym tables. 
  2-chapters: introduction, chapters and conclusion.
  3-appendices: one or several appendix chapters.
  4-closing: abstract.
  doc: include documentation on the style files.
  images: includes images and illustrations.
  templates: includes the style files.

  references.bib: an example of a BiBTeX database.
  phdthesis.pdf: the main output file.
  phdthesis.tex: the main LaTeX file of the project.
  README.txt: this file.


EXTERNAL DOCUMENTATION
----------------------
Discovering the language with "A not so short introduction to LaTeX":
<http://ctan.mines-albi.fr/info/lshort/english/lshort.pdf>

Doing you own figures in LaTeX using "TikZ for the impatient":
<http://math.et.info.free.fr/TikZ/bdd/TikZ-Impatient.pdf>

Getting inspired by already on-the-shelf figures via "TikZ examples":
<http://www.texample.net/tikz/examples/>

Doing math plotting using "PGFPlots":
<http://pgfplots.sourceforge.net/pgfplots.pdf>

Exporting you Matlab plots thanks to "Matlab2TikZ":
<https://github.com/nschloe/matlab2tikz>


CREDITS
-------
This template has been created by Damien Roque (ISAE Supaero)
<damien.roque_AT_isae-supaero.fr>.

The author would like to thank Tristan Gr�goire who designed
the official title page for the University of Toulouse.
<tlsflyleaf_AT_onada.fr>


CHANGELOG
--------
 03/08/13 v0.1 Initial version (from the University of Grenoble)
 10/12/14 v0.2 Modification for the University of Toulouse.
 11/12/14 v0.3 Small changes in the README.txt file.  
 15/07/15 v0.4 Change logo and use version 1.7 of tlsflyleaf.
