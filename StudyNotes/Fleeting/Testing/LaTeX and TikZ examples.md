## Some LaTeX examples

$$c = \sqrt{a^2 + b^2}$$

## Some TikZ examples

Please write me a Pullback diagram using [[TikZ]] with [[TikZJaX]] syntax

Certainly! Here's an example of a pullback diagram created using the TikZ package with TikZJax syntax:

```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
    P \times_Z Q \arrow[r, "g"] \arrow[d, "f"'] & Q \arrow[d, "\pi_Q"] \\
    P \arrow[r, "\pi_P"'] & Z
\end{tikzcd}
\end{document}
```

In this diagram, the objects `P`, `Q`, and `Z` are represented by nodes. The arrows between the nodes are specified using the `\arrow` command. The labels for the arrows are provided as arguments to the `\arrow` command.

The `r` option specifies that the arrow should be drawn from left to right, while the `d` option specifies that the arrow should be drawn from top to bottom.

The labels for the arrows are placed above or below the arrows using prime (`'`) notation: `"g"` is placed above `"f"`, and `"pi_P"` is placed below `"pi_Q"`.

You will need to include these lines within a LaTeX document in order to compile it successfully.

Please write the Euler Formulat

$$e^{i\pi} + 1 = 0$$


```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
A \arrow[r, "f"] \arrow[d, "g"'] & B \arrow[d, "h"] \\ C \arrow[r, "k"'] & D \\
\end{tikzcd}
\end{document}