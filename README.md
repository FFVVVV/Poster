% compile if you want a poster in landscape orientation

\documentclass[25pt, a0paper,landscape]{tikzposter} %orientation options: portrait, landscape
\usepackage[utf8]{inputenc}

\title{Rompiendo Codigos }
\author{Hector Fernando Vega Ortiz  \\
Supervisor: Santiago Correa}
\date{06-05-2025}
\institute{Unidad Educativa Computer World}

\usepackage[backend=biber, style=numeric, sorting=none, locallabelwidth]{biblatex}
\bibliography{ref}

\usetheme{Rays} % Options: Default, Simple, Basic, Rays, Wave, Envelope, Board, Autumn, Desert

\graphicspath{Images/}

%import necessary packages
\usepackage{blindtext}
\usepackage{graphicx}
\usepackage{caption}
\usepackage{subcaption}
\usepackage{comment}
\usepackage{amsmath,amssymb}

\begin{document}

\maketitle

\node[anchor=west, xshift = -1 cm ] at (TP@title.west) {\includegraphics[width=20cm]{descarga.png}}; %left logo, comment out if unnecessary
\node[anchor=east, xshift = -10 cm] at (TP@title.east) {\includegraphics[width=15cm]{Mi_código_QR_1-1024.png}}; %right logo, comment out if unnecessary




\begin{columns}

    \column{0.5}%set width of first column

   \block{1.¿Qué es el algoritmo de Shor?}{
    {\Huge El algoritmo de Shor es una técnica cuántica que permite descomponer números grandes en sus factores primos mucho más rápido que los métodos tradicionales.}


        
    }

    
    \block{2.Relación interdisciplinaria}{
\Huge
\\Apliacion en las asignaturas

\\Aplicaciones en Química
\\✅ Análisis de estructuras moleculares periódicas.
\\✅ Optimización de reacciones químicas en materiales cuánticos.
\\✅ Simulación de compuestos con algoritmos cuánticos.
\\Aplicaciones en Matemáticas
\\✅ Teoría de números: Estudio de primos y propiedades modulares.
\\✅ Algoritmos numéricos: Resolución eficiente de problemas de periodicidad.
\\✅ Optimización matemática: Aplicación de técnicas cuánticas en teoría de grafos y ecuaciones diofánticas.
\\Aplicaciones en Física
\\✅ Análisis de simetrías en sistemas físicos, ya que Shor explora periodicidad en sistemas cuánticos.
    }

    
    
    

    
    \column{0.3}%set width of second column

    \block{3.¿Como funciona?}{
    \Huge El algoritmo de Shor es un algoritmo cuántico para factorizar números grandes de manera eficiente, algo que es difícil para las computadoras clásicas. Utiliza superposición cuántica  cuántica para encontrar el orden de un número rápidamente, lo que permite calcular los factores primos de un número. Su eficiencia pone en riesgo la seguridad de sistemas criptográficos como RSA, que dependen de la dificultad de factorizar números grandes.  
    } 
    
    \block{4.Resultados}
    {
  \begin{tikzfigure}
            \includegraphics[scale=1]{Screenshot 2025-04-07 23.29.23.png}
        \end{tikzfigure}
    \begin{tikzfigure}
            \includegraphics[scale=2]{Screenshot 2025-04-07 23.29.39.png}
        \end{tikzfigure}
    }


    \column{0.2}%set width of third column

    \block{5. Conclucion}{
     \Huge La computación cuántica no solo acelera cálculos, sino que cambia paradigmas. Problemas antes imposibles (como factorización eficiente) ahora tienen solución, mostrando que la física cuántica redefine los límites de la computación.
    }
    
    \block{6. Ejemplo}{
   \begin{center}
    \Huge  1004
    \end{center}
        \begin{tikzfigure}
            \includegraphics[scale=0.8]{Screenshot 2025-04-07 23.17.43.png}
        \end{tikzfigure}
        
    }

    \block{References}{
    \nocite{*}
    \begin{minipage}{\linewidth}
        \begin{center}\mbox{}\vspace{-\baselineskip}
      \\ 1. OpenAI. (2023). ChatGPT (versión GPT-4) [Modelo de lenguaje].
        \\2.Anthropic. (2023). Claude 3 [Modelo de lenguaje].
        \\3.DeepSeek. (2024). DeepSeek Chat (versión V3) [Modelo de lenguaje].
    \end{center}
    \end{minipage}
    }

    %if necessary, add more columns, adjusting the widths
    %more columns may be necessary in landscape mode
    
\end{columns}



\end{document}
