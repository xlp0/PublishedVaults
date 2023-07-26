---
software: Graphing and Typesetting Software
website: https://github.com/artisticat1/obsidian-tikzjax
github_repo: https://github.com/artisticat1/obsidian-tikzjax
---

[[TikZJaX]] is a LaTeX package that combines the functionality of [[TikZ]] and [[MathJax]] to create high-quality mathematical figures and diagrams directly within [[LaTeX]] documents. It allows users to seamlessly integrate mathematical notations, symbols, and equations into their TikZ drawings.

TikZJaX builds upon the power of [[TikZ]], which is a widely-used package for creating graphics in LaTeX. It provides an extensive set of tools and libraries to generate complex figures programmatically. With TikZJaX, users can leverage this functionality while also benefiting from the math rendering capabilities of MathJax.

MathJax is a JavaScript library that renders mathematical expressions beautifully in web browsers. It supports a wide range of mathematical notation, including [[TeX]], LaTeX, and MathML. By combining TikZ with MathJax, TikZJaX enables the creation of mathematically precise diagrams with beautifully rendered equations.

Using TikZJaX involves including the necessary packages in your LaTeX document's preamble and then using the provided commands to create your desired diagrams. You can use standard TikZ commands along with additional math-specific commands provided by TikZJaX to seamlessly integrate mathematical expressions into your figures.

TikZJaX offers a flexible and powerful way to create visually appealing mathematical illustrations within LaTeX documents. Whether you need to draw geometric shapes, graphs, or complex diagrams involving equations, TikZJaX provides the tools necessary to accomplish these tasks effectively.


If you have [[TikZJaX]] plug-in installed, a circuit diagram will be displayed.
```tikz
\usepackage{circuitikz}
\begin{document}
\begin{circuitikz}[american, voltage shift=0.5]
\draw (0,0)
to[isource, l=$I_0$, v=$V_0$] (0,3)
to[short, -*, i=$I_0$] (2,3)
to[R=$R_1$, i>_=$i_1$] (2,0) -- (0,0);
\draw (2,3) -- (4,3)
to[R=$R_2$, i>_=$i_2$]
(4,0) to[short, -*] (2,0);
\end{circuitikz}
\end{document}
```

If you have [[TikZJaX]] plug-in installed, a [[Category theory]] diagram will be displayed.

```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
    T
    \arrow[drr, bend left, "x"]
    \arrow[ddr, bend right, "y"]
    \arrow[dr, dotted, "{(x,y)}" description] & & \\
    K & X \times_Z Y \arrow[r, "p"] \arrow[d, "q"]
    & X \arrow[d, "f"] \\
    & Y \arrow[r, "g"]
    & Z
\end{tikzcd}
\quad \quad
\begin{tikzcd}[row sep=2.5em]
A' \arrow[rr,"f'"] \arrow[dr,swap,"a"] \arrow[dd,swap,"g'"] &&
  B' \arrow[dd,swap,"h'" near start] \arrow[dr,"b"] \\
& A \arrow[rr,crossing over,"f" near start] &&
  B \arrow[dd,"h"] \\
C' \arrow[rr,"k'" near end] \arrow[dr,swap,"c"] && D' \arrow[dr,swap,"d"] \\
& C \arrow[rr,"k"] \arrow[uu,<-,crossing over,"g" near end]&& D
\end{tikzcd}
\end{document}
```