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
