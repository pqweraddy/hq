+++
date = '2025-03-17T16:43:35+08:00'
draft = false
title = 'LaTeX 模板'
categories = ["study","tools"]
+++


```latex
\documentclass{article}
\usepackage[colorlinks=true, allcolors=blue]{hyperref}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usepackage{xeCJK}
\usepackage[letterpaper,top=2cm,bottom=2cm,left=2cm,right=2cm,marginparwidth=1.75cm]{geometry}
\usepackage{fancyhdr}
\usepackage{algpseudocode}
\usepackage{blindtext}
\usepackage{titlesec}
\usepackage{amsmath}
\usepackage{graphicx}
\usepackage{xcolor}
\usepackage{listings}
\usepackage{graphicx}
\usepackage{tikz}
\usepackage{circuitikz}
\usetikzlibrary{shapes.geometric}
\usetikzlibrary{arrows, shapes.gates.logic.US, calc}
\usetikzlibrary{calc,shadows,patterns,angles,quotes}
\usetikzlibrary{datavisualization.formats.functions}
\tikzstyle{branch}=[fill, shape=circle, minimum size=3pt, inner sep=0pt]

\setCJKmainfont[BoldFont=HaranoAjiMincho-Bold.otf]{HaranoAjiMincho-Regular.otf}
\setCJKfallbackfamilyfont{\CJKrmdefault}{gulim.ttf}
\renewcommand{\footrulewidth}{0.4pt}% default is 0pt

%%%%%%%%%%%%%%%%%% configure course and hw name
\newcommand{\name}{Yu-Syuan Lee 李育烜}
\newcommand{\course}{Foundation of Artificial Intellgence 2025}
\newcommand{\homework}{Homework 2}
%%%%%%%%%%%%%%%%%% configure course and hw name

\begin{document}
\pagestyle{fancy}
\fancyhead{}\fancyfoot{}
\fancyhead[L]{\course}
\fancyhead[R]{\homework}
\fancyfoot[L]{\name}
\fancyfoot[C]{Page \thepage}
\fancyfoot[R]{B12902072}


%%%%%%%%%%%%%%%%%% content written below

\section*{Problem 1}

Some Solution

\end{document}
```