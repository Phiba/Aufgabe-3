Aufgabe-3
Latex-Dokument von Aufgabe 5:


\documentclass[11pt,a4paper]{article}
\date{\today}
\author{Philipp Bastian}
\title{Informatik-\"Ubung 5}
\usepackage{multirow} 
\usepackage{amsmath}
\usepackage{amsthm}
\usepackage{amsbsy}
\usepackage{amssymb}
\begin{document}
\maketitle



\section{Das ist der erste Abschnitt} 
Hier beginnen die \LaTeX-\"Ubungen
\section{Tabelle} 
Tabelle \"uber die bisherigen Ergebnisse:


\begin{center} 
\begin{tabular}{c|c|c|c}

	& Punkte & Maximal & \Delta \\
\hline
\multirow{1}{*}{\"Ubung 1} & 9,00 & 10,00 & 1 \\ 
\multirow{1}{*}{\"Ubung 2} & 8,00  & 10,00 & 2 \\ 
\multirow{1}{*}{\"Ubung 3} & 10,00 & 10,00 & 0  \\ 

\end{tabular}
 
Tabelle 1: Bisherige \"Ubungsergebnisse 
\end{center}


\section{Formeln} 
\subsection{Pythagoras}
 
 
Der Satz des Pythagoras errechnet sich wie folgt: a^{2}+b^{2}=c^{2}.

Daraus k\"onnen wir die L\"ange der Hypothenuse wie folgt berechnen: 
 
c = \sqrt{{a^{2}+b^{2}}} 

\subsection{Summen}

Wir können auch eine Formel für die Summe angeben:

\begin{equation}
\[s= \sum_{i=1}^n i\ =\left(\frac{n(n+1)}{2}\right)
\end{equation}


\end{document}

