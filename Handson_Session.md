## title Page
```python
\begin{titlepage}
    \centering
    {\LARGE \textbf{Title of Your Thesis or Dissertation} \par}
    \vspace{2cm}
    {\includegraphics[width=0.25\textwidth]{figures/du_logo_new} \par}
    \vspace{2cm}
    {\Large \textbf{Author's Full Name} \par}
    \vspace{0.5cm}
    {\Large \underline{Name of Your Department} \par}
    {\Large \underline{Name of Your University or Institute} \par}
    \vspace{1.5cm}
    {\Large A thesis submitted in partial fulfillment of the requirements for the degree of \par}
    {\Large \textbf{Doctor of Philosophy} \par}
    {\Large in the \underline{Name of Faculty} \par}  
    \vspace{3cm}
    {\Large \monthyeardate{\today} \par} % Use the submission date here
\end{titlepage}
```
## Certificate
```python
\chapter*{Certificate of Originality}

\vspace*{3ex} \noindent {\large I herewith declare that the research work performed in the Ph.D. thesis entitled \textbf{``Title of your Thesis''}, has been carried out by me at the \textbf{\underline{Name of your department}}, \underline{Name of your university}, \underline{City Name}, \underline{Country Name}. The manuscript has been subjected to plagiarism check by using the \textbf{\underline{Software Name}} plagiarism detection software. My Ph.D. thesis is based on original research and may be considered for the award of Ph.D. degree by the \underline{Name of your university}.
\vspace{2cm}

\begin{flushright}
{\bf \underline{Author's Full Name}} 
\end{flushright}
```

## Dedication
```python
\chapter*{Dedication}
\vspace{1cm}
To my \underline{XYZ}, who has been my pillar of support throughout this incredible journey.
\vspace{1cm}
```

## Acknowledgement
```pyhton
\chapter*{Acknowledgement}
I would like to express my gratitude to... \\

\lipsum[1-5] %to generate filler text 
```
## Abstract
```python
\chapter*{Abstract}
\addcontentsline{toc}{chapter}{Abstract}
This thesis explores...\\


\lipsum[1-2] %to generate filler text
```

## Abbreviations
```python
\chapter*{Table of Abbreviations}
\addcontentsline{toc}{chapter}{Table of Abbreviations} %manually add to the table of contents. 
 \begin{acronym}
  \acro{QM}{Quantum Mechanics}
  \acro{EM}{Electromagnetism}
  \acro{GR}{General Relativity}
  \acro{AI}{Artificial Intelligence}
  \acro{ML}{Machine Learning}
  \acro{IT}{Information Technology}
  \acro{GPS}{Global Positioning System}
  \acro{CS}{Computer Science}
  \acro{EE}{Electrical Engineering}
  \acro{CV}{Computer Vision}
  \acro{AR}{Augmented Reality}
  \acro{VR}{Virtual Reality}
  \acro{IoT}{Internet of Things}
  \acro{DL}{Deep Learning}
  \acro{OS}{Operating System}
  \acro{DB}{Database}
  \acro{NW}{Network}
\end{acronym}
```

## Symbols
```python
\chapter*{Table of Symbols}
\addcontentsline{toc}{chapter}{Table of Symbols}
\begin{tabular}{ll} %use longtable if table is long and spans multiple pages.
    $c:$ & Speed of Light \\
    $G:$ & Gravitational Constant \\
    $R:$ & Ricci Scalar \\
    $E:$ & Energy \\
    $m:$ & Mass \\
    $h:$ & Planck's Constant \\
    $k:$ & Boltzmann Constant \\
    $\hbar:$ & Reduced Planck's Constant \\
    $F:$ & Force \\
    $q:$ & Charge \\
    $B:$ & Magnetic Field \\
    $E:$ & Electric Field \\
    $L:$ & Angular Momentum \\
    $I:$ & Moment of Inertia \\
    $T:$ & Temperature \\
    $P:$ & Momentum \\
    $V:$ & Voltage \\
    $A:$ & Area \\
    $\Phi:$ & Magnetic Flux \\
\end{tabular}
```

## Chapter 1
```python
\chapter{Introduction}\label{Chapter_1}
\section{Section-1}
\lipsum[1-5] %to generate filler text 
\subsection{Subsection-1}
\lipsum[1-2]
\begin{table}[ht]
  \centering
 \renewcommand{\arraystretch}{2}
  \begin{tabular}{|c|c|c|}
    \hline
    \textbf{Column 1} & \textbf{Column 2} & \textbf{Column 3} \\
    \hline
    Row 1, Cell 1 & Row 1, Cell 2 & Row 1, Cell 3 \\
    \hline
    Row 2, Cell 1 & Row 2, Cell 2 & Row 2, Cell 3 \\
    \hline
    Row 3, Cell 1 & Row 3, Cell 2 & Row 3, Cell 3 \\
    \hline
    Row 4, Cell 1 & Row 4, Cell 2 & Row 4, Cell 3 \\
    \hline
  \end{tabular}
  \caption{A Simple Table with 4 Rows and 3 Columns}
  \label{tab:simple-table} 
\end{table}

Here is an example of citing a paper \cite{sweinberg1989}.
\lipsum[1-3] %to generate filler text
```
## Chapter 2
```python
\chapter{Basics of Latex}\label{Chapter_2}
\section{Section-1}
\lipsum[1-4] %to generate filler text 
\subsection{Subsection-1}
\lipsum[1-2]
\lipsum[1-4] %to generate filler text 

\section{Section-2}
\lipsum[1-2]
\begin{figure}[ht]
  \centering
  \includegraphics[width=1.0\linewidth]{example-image}
  % \includegraphics[width=130mm]{Chapter_4/figure/str6.png}
  \caption{A Sample Figure}
  \label{fig:sample}
\end{figure}

How to use acronym here \ac{AI}. \\


\lipsum[1-5] %to generate filler text 
```
## Chapter 3
```python
\chapter{Latex and its usages}\label{Chapter_3}
\lipsum[1-4] %to generate filler text 


\begin{figure}[ht]
  \centering
  \includegraphics[width=1.0\linewidth]{example-image}
  % \includegraphics[width=130mm]{Chapter_4/figure/str6.png}
  \caption{A Sample Figure}
  \label{fig:sample2}
\end{figure}

How to use acronym here \ac{AI}. \\


\lipsum[1-5] %to generate filler text 
```
## Appendix
```pyhton
\addcontentsline{toc}{chapter}{Appendix}
\begin{appendices}
\chapter*{Appendix}
\section{Derivation of Friedmann Equations}
\lipsum[1-3]

\section{Inverse of Block Matrix}
\lipsum[1-2]

\end{appendices}
```
## Reference
```python
@article{sweinberg1989,
  title = {The cosmological constant problem},
  author = {Weinberg, Steven},
  journal = {Rev. Mod. Phys.},
  volume = {61},
  issue = {1},
  pages = {1--23},
  numpages = {0},
  year = {1989},
  month = {Jan},
  publisher = {American Physical Society},
  doi = {10.1103/RevModPhys.61.1},
  url = {https://link.aps.org/doi/10.1103/RevModPhys.61.1}
}
```
### Master File
```python
\documentclass[12pt,a4paper, twoside, openright]{book}
\usepackage{graphicx}
\usepackage{titlesec}
\usepackage{lipsum}
\usepackage{appendix}
\usepackage{natbib}
\usepackage{makeidx}
\usepackage{geometry}
\newgeometry{
    top=1in,
    bottom=1in,
    outer=1in,
    inner=1.3in,
}
%++++++++++++Hyperspace color++++++++++
\usepackage{hyperref}
\hypersetup{
  colorlinks,
  citecolor=blue,
  linkcolor=red,
  urlcolor=blue} %remove in the final version of thesis.


\usepackage{acronym}
\makeindex

\usepackage{datetime}
\newdateformat{monthyeardate}{%
  \monthname[\THEMONTH], \THEYEAR
}

\titleformat{\chapter}[display] 
  {\normalfont\bfseries\centering}{\chaptertitlename\ \thechapter}{0pt}{\huge}

% Define a command to add a blank page
\newcommand{\blankpage}{
  \clearpage
  \thispagestyle{empty}
  \mbox{} 
  \clearpage
}
 
\begin{document} 
\frontmatter
% Title Page
% \blankpage
\input{0_title_page.tex}

% Certificate
% \blankpage
\input{1_certificate.tex}

% Dedication
% \blankpage
\input{2_dedication.tex}

% Acknowledgement
% \blankpage
\input{3_acknowledgement.tex}

% Abstract
% \blankpage
\input{4_abstract.tex}

\tableofcontents
\listoffigures
\listoftables

% Table of Abbreviations
% \blankpage
\input{5a_abbreviation}

% Table of Notations
% \blankpage
\input{5b_symbol}

\mainmatter
% Chapter 1
% \blankpage
\input{6a_chapter_1.tex}

% Chapter 2
% \blankpage
\input{6b_chapter_2.tex}

% Chapter 3
% \blankpage
\input{6c_chapter_3.tex}

% Appendices
% \blankpage
\backmatter

\input{7_appendices.tex} 

% Bibliography
\addcontentsline{toc}{chapter}{\refname}
\bibliographystyle{plain}
\bibliography{reference}

% List of Acronyms
% \blankpage
% \input{8_acronyms.tex}

% Index
% \blankpage
% \input{9_index.tex}

\end{document}
```











