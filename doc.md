---
tags: koedo
---
[toc]

Notes of [Jones01]
===========

> [Jones01]  Jones, Donald R. "A taxonomy of global optimization methods based on response surfaces." Journal of global optimization 21.4 (2001): 345-383. 

$$
\newcommand{\argmin}{\mathop{\mathrm{arg\,min}}}
\newcommand{\xstar}{\mathop{\mathbf{x}^{\ast}}}
\newcommand{\ystar}{\mathop{y^{\ast}}\nolimits}
\newcommand{\xnext}{\mathop{\mathbf{x}^{n+1}}}
\newcommand{\E}{\mathop{\Bbb{E}}\nolimits}
\newcommand{\D}{\mathop{\mathcal{D}}\nolimits}
\newcommand{\M}{\mathop{\mathcal{M}}\nolimits}
$$



1. Introduction (pp.345-)
--------------

* survey & invention of a bunch of **Infill Criterion (#IC)**

2. Minimizing a quadratic surface (p.348)
--------------

### Method 1  {#m1}

$$ \begin{equation}
 \xnext := \argmin_{\xstar}\text{quad}(\xstar; \D^n) 
 \label{eq:m1}
\end{equation}  $$
where

$$
\D^n := \{ (\mathbf{x}^i, y^i)_i \}_{i\in\{1,..,n\}}
$$

the $f(\xstar; \D^n)$ can $ \eqref{eq:m1}$ can interpret as $\E[\ystar|\xstar,\D^n,\M_{quad}]$. So $\eqref{eq:m1}$ is

$$ \begin{equation}
   \argmin_{\xstar}\E[\ystar|\xstar,\D^n,\M_{quad}] 
\end{equation} $$ 


3. Minimizing a interpolating surface (pp.349-)
--------------

### Method 2 {#m2}

$$ \begin{equation}
\xnext := \argmin_{\xstar}\E[\ystar|\xstar,\D^n,\M_{GP}]
\label{eq:m2}
\end{equation}$$ 

The difference between the two methods is just $\M_{GP}$ and $\M_{quad}$.

4. A gentle introduction to kriging (pp.356-)
------------

* a brief lesson of **Kriging** ( $ \approx $ **GP**)

5. Minimizing a statistical lower bound (pp.362-)
---------------
### Method 3:
$$ \begin{equation}
\xnext := \argmin_{\xstar} \{\hat{y}(\xstar) - a \sigma(\xstar) \}
 \label{eq:m3}
\end{equation}  $$

6. Maximizing the probability of improvement (pp.364-)
-----------------

### Method 4:
$$ \begin{equation}
\xnext := \argmin_{\xstar} p(\ystar|\xstar,\D^n,\M)
\label{eq:m4}
\end{equation}  $$

[Fig.14](https://cdn.pbrd.co/images/GQDU0gA.png)

7. Maximizing Expected Improvement (pp.371-)
----------------------------

### Method 5 (**EI**):
$$ \begin{equation}
\xnext := \argmin_{\xstar} \E[\text{u}(\ystar))|\xstar,\D^n,\M ]
\label{eq:m5}
\end{equation}  $$

 (eq.34,35 (p.371))

8. One-stage approach for goal seeking (pp.373-)
---------------------------

### Method 6 (= **GoalSeeking**)

$$ \begin{equation}
\xnext := \argmin_{\xstar} \E[\ystar|\xstar,\D^n,y^{goal}]
\label{eq:mmmm}
\end{equation}  $$

 1-stage + $\alpha = \mathrm{LOIs}\in$ Bayes Estimation [Syuuron].
p(y*|x*,D,y^g) p(x^g, y^g) = p(y^gp(
but,

 $p(x^g,y^g) \neq$ prob of opt.[Syuuron]

### what about overfitting ?

9. One-stage approach for optimization (pp.375-)
-----------------------------

10.  Minimizing a interpolating surface (pp.349-)
-----------------------------

> Written with [StackEdit](https://stackedit.io/).