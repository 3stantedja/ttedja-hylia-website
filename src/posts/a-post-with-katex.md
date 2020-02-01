---
title: A post with KaTeX
metaDesc: This is a post with some maths expressions to test with.
date: '2019-11-01'
tags:
  - hello world!
  - test
  - math equations
  - katex
---

This is a post with some math equations.

This is the quadratic equation for a polynomial of the form $ax^2 + bx + c^2 = 0$ where $a \neq 0$.
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

```latex
\[ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \]
```

Here is a form of Maxwell's equations, in a `\begin{aligned}` environment.

$$ \begin{aligned}
    \nabla \cdot \mathbf{E} &= \frac{\rho}{\epsilon_0} \\
    \nabla \cdot \mathbf{B} &= 0 \\
    \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
    \nabla \times \mathbf{B} &= {\mu_0} \left( \mathbf{J} + {\epsilon_0} \frac{\partial \mathbf{E}}{\partial t} \right)
\end{aligned} $$

```latex
\begin{aligned}
    \nabla \cdot \mathbf{E} &= \frac{\rho}{\epsilon_0} \\
    \nabla \cdot \mathbf{B} &= 0 \\
    \nabla \times \mathbf{E} &= -\frac{\partial \mathbf{B}}{\partial t} \\
    \nabla \times \mathbf{B} &= {\mu_0} \left( \mathbf{J} + \epsilon_0} \frac{\partial \mathbf{E}}{\partial t} \right)
\end{aligned}
```

Here's another form of Maxwell's equations:

$$
\begin{aligned}
  \oiint_{\partial\Omega} \mathbf{E} \cdot \mathrm{d}\mathbf{S} &= \frac{1}{\epsilon_0} \iiint_\Omega \rho \mathrm{d} V \\
  \oiint_{\partial\Omega} \mathbf{B} \cdot \mathrm{d} \mathbf{S} &= 0 \\
  \oint_{\partial\Sigma} \mathbf{E} \cdot \mathrm{d} \boldsymbol{l} &= - \frac{\mathrm{d}}{\mathrm{d} t} \iint_\Sigma \mathbf{B} \cdot \mathrm{d} \mathbf{S} \\
  \oint_{\partial\Sigma} \mathbf{B} \cdot \mathrm{d} \boldsymbol{l} &= \mu_0 \left( \iint_\Sigma \mathbf{J} \cdot \mathrm{d} \mathbf{S} + \epsilon_0 \frac{\mathrm{d}}{\mathrm{d} t} \iint_\Sigma \mathbf{E} \cdot \mathrm{d} \mathbf{S} \right)
\end{aligned}
$$

```latex
\begin{aligned}
  \oiint_{\partial\Omega} \mathbf{E} \cdot \mathrm{d}\mathbf{S} &= \frac{1}{\epsilon_0} \iiint_\Omega \rho \mathrm{d} V \\
  \oiint_{\partial\Omega} \mathbf{B} \cdot \mathrm{d} \mathbf{S} &= 0 \\
  \oint_{\partial\Sigma} \mathbf{E} \cdot \mathrm{d} \boldsymbol{l} &= - \frac{\mathrm{d}}{\mathrm{d} t} \iint_\Sigma \mathbf{B} \cdot \mathrm{d} \mathbf{S} \\
  \oint_{\partial\Sigma} \mathbf{B} \cdot \mathrm{d} \boldsymbol{l} &= \mu_0 \left( \iint_\Sigma \mathbf{J} \cdot \mathrm{d} \mathbf{S} + \epsilon_0 \frac{\mathrm{d}}{\mathrm{d} t} \iint_\Sigma \mathbf{E} \cdot \mathrm{d} \mathbf{S} \right)
\end{aligned}
```

Here is a logical argument (in the form $\mathrm{predicate}_1, \ \cdots, \ \mathrm{predicate}_n \ \therefore \ \mathrm{conclusion}$).

$$ \begin{array}{l}
    p \rightarrow \neg q \\
    r \rightarrow (p \wedge q) \\ \hline
    \neg r
\end{array} $$

```latex
\begin{array}{l}
    p \rightarrow \neg q \\
    r \rightarrow (p \wedge q) \\ \hline
    \neg r
\end{array}
```
