article_preample
================

My LaTeX preample, to be used used with the document class IEEEtran. The file *article_preample.sty* should be placed to the same folder with the project, or somewhere else where the compiler can find it.

main.tex:
---------

	\documentclass[10pt,final,conference,letterpaper]{IEEEtran}
	\newcommand{\mytitle}{this-is-the-title-of-this-article}
	\newcommand{\myauthor}{Mika Kutila}
	\newcommand{\myauthors}{Mika Kutila}
	\newcommand{\mysubject}{\mytitle}
	\usepackage{article_preample}
	\begin{document}
	
	\end{document}

List of some packages used:
---------------------------

- Pgfplots
- Circuitikz
