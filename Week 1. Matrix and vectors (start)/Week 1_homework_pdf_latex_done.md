\documentclass{article}
\usepackage{graphicx} % Required for inserting images
\usepackage{amsmath}

\title{Home work 1}
\author{Dmitri Churikov}
\date{September 2026}

\begin{document}

\maketitle

\section{Task}
\[
A = \begin{bmatrix}
141 & 121 & 161 \\
262 & 232 & 292
\end{bmatrix}
\]
\[
B = \begin{bmatrix}
4 & -2 \\
-2 & 1 \\
-6 & 3
\end{bmatrix}
\]
\[
C = \begin{bmatrix}
1 & 0 & -4 \\
2 & 0 & -8
\end{bmatrix}
\]

Find: $(AB)^2C = ?$
\\
\\
\\
$(AB)^2C = AB * A * (B * C) 

(B * C) = \begin{bmatrix}
4*1-2*2 & 0 & 4*(-4)-2*(-8) \\
-2*1+1*2 & 0 & -2*(-4)-8 \\
-6*1+3*2 & 0 & -6*(-4)-3*8
\end{bmatrix} = 0
\]
\\
Answer:
(AB)^2C = 0

\section{Task}
\[
A = \begin{pmatrix}
12 & 23 & 47 \\
-5 & 31 & -6 \\
35 & 51 & -3
\end{pmatrix}
\]
\[
B = \begin{pmatrix}
3 & 0 & -3 \\
-4 & 2 & 7 \\
1 & -2 & -4
\end{pmatrix}
\]
\[
C = \begin{pmatrix}
-2 \\
3 \\
-2
\end{pmatrix}
\]
Find:  A^2B^3C = ?
\\
\[
B*C = \begin{pmatrix}
3*(-2) -3*(-2) & -4*(-2) +2*3+7*(-2) & -2-2*3-4*(-2)
\end{pmatrix}
\] 
\[ = \begin{pmatrix}
0 & 0 & 0
\end{pmatrix}
\]
Answer:
A^2B^3C = 0

\section{Task}
\[
A = \begin{pmatrix} 
10 & -4 \\ 
11 & -4 \\ 
-3 & 1 \\ 
-2 & 1 
\end{pmatrix}
\]
\[
B = \begin{pmatrix} 
-5 & 7 & 11 & -3 \\ 
-3 & 11 & 27 & 5 
\end{pmatrix}
\]
Find:  
Let C= AB. f(C)-?, where f (x) = x^2(x + I) and I = 1 matrix.

f(C)=x^3 + x^2 \\
= AB*AB*AB + AB*AB
= A * (BA) * BAB + A* (BA) * B
\\
\[
BA = 
\begin{pmatrix}
-5*10+7*11+11*(-3)-3*(-2) & -5*(-4)+7*(-4)+11-3\\
0 & 0
\end{pmatrix}
\] = 0
\\
\\
Answer:
f(C)=x^3 + x^2 = 0 + 0 = 0

\section{Task}
Let $x \in \mathbb{R}^{n \times 1}$ and $y \in \mathbb{R}^{n \times 1}$, and $A = x y^T$. Demonstrate, that you can find constant $\lambda \in \mathbb{R}$, for any $k \in \mathbb{N}$ performs $A^k = \lambda^{k-1} A$.

\section{Task}
Let $V$ be a linear real vector space. Recall that, by the definition of a linear space, there exists a vector $\theta \in V$ such that $x + \theta = \theta + x = x$ for any $x \in V$. Using the axioms of a linear real space, prove that $0 \cdot x = \theta$.

\textit{Hint:} Use the property that for each $x$ there exists a unique $-x$ such that $x + (-x) = \theta$, and $(\alpha + \beta) \cdot x = \alpha \cdot x + \beta \cdot x$.

let's proove that 0*x=\theta$
\\

1) Property of the additive identity element (zero) in the field of real numbers

Свойство нейтрального элемента по сложению нуля в поле вещественных или комплексных чисел

0 = 0 + 0

2) Аксиома дистрибутивности умножения
относительно сложения чисел
Axiom of distributivity of multiplication over scalar addition
(longread)



$(\alpha + \beta) \cdot x = \alpha \cdot x + \beta \cdot x$ means \\ 
0 * $x = (0 + 0) * x$ = 0 * $x + 0 * x$

3) 
let y = (0 * $x)  

got $y = $y + y$

4) 
add -y to both sides from 3

got y$ - y$ = $y + y$ - y$

5) Axiom of associativity of addition (applied to the right side)
Аксиома ассоциативности сложения для правой части

left side y - y = \theta$  

\theta$ = $y + $y - $y

6) 
because y - y = \theta$ 

got y$ + \theta$ = y$

then got \theta$ = y$ + \theta$ = y$ \\ 

Transitivity of equality
Транзитивность равенства

got $y=\theta$

got
0*x$=\theta$

Result: we approved what we need
\end{document}