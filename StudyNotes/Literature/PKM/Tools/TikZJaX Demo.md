This diagram requires the plugin:[[Permanent/PKM/Tools/TikZJaX]]

```tikz 
\usepackage{tikz-cd} \begin{document} \begin{tikzcd}     T     \arrow[drr, bend left, "ABCDEFG"]     \arrow[ddr, bend right, "y"]     \arrow[dr, dotted, "{(x,y)}" description] & & \\     K & X \times_Z Y \arrow[r, "p"] \arrow[d, "q"]     & X \arrow[d, "f"] \\     & Y \arrow[r, "g"]     & Z \end{tikzcd} \quad \quad \begin{tikzcd}[row sep=2.5em] A' \arrow[rr,"f'"] \arrow[dr,swap,"a"] \arrow[dd,swap,"g'"] &&   B' \arrow[dd,swap,"h'" near start] \arrow[dr,"b"] \\ & A \arrow[rr,crossing over,"f" near start] &&   B \arrow[dd,"h"] \\ C' \arrow[rr,"k'" near end] \arrow[dr,swap,"c"] && D' \arrow[dr,swap,"d"] \\ & C \arrow[rr,"k"] \arrow[uu,<-,crossing over,"g" near end]&& D \end{tikzcd} \end{document} 

```


How to do LaTeX in the web
Translate this to Indonesian language: "Hello World"

"Halo Dunia"