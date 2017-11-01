---
tags: koedo
---
[toc]

Reading Memo
===========

> [Jones01]  Jones, Donald R. "A taxonomy of global optimization methods based on response surfaces." Journal of global optimization 21.4 (2001): 345-383. 

EGO

jones

*[jones]:  jon
*[EGO]: Efficient Global Optimization

jones

$$
\newcommand{\argmin}{\mathop{\mathrm{arg\,min}}}
\newcommand{\xstar}{\mathop{\mathbf{x}^{\ast}}}
\newcommand{\ystar}{\mathop{\mathbf{y}^{\ast}}}
\newcommand{\xnext}{\mathop{\mathbf{x}^{n+1}}}
\newcommand{\E}{\mathop{\Bbb{E}}\nolimits}
\newcommand{\D}{\mathop{\mathcal{D}}\nolimits}
$$


1. Introduction (pp.345-)
--------------

* survey & invention of a bunch of **Infill Criterion (#IC)**

2. Minimizing a quadratic surface (p.348)
--------------
E[y*|x*,D^n]
 Method1: $$ \xnext := \argmin_{\xstar} \Bbb{E} $$

3. Minimizing a interpolating surface (pp.349-)
--------------

Method 2:  $$\xnext := \argmin_{\xstar} \ystar$$

4. A gentle introduction to kriging (pp.356-)
------------

* a brief lesson of **Kriging** ( $ \approx $ **GP**)

5. Minimizing a statistical lower bound (pp.362-)
---------------
 Method 3:
 $$ \xnext := \argmin_{\xstar} \{\hat{y}(\xstar) - a \sigma(\xstar) \}$$

6. Maximizing the probability of improvement
-----------------
pp.364-

Method 4:
$$
\xnext := \argmin_\xstar
$$

[Fig.14](https://cdn.pbrd.co/images/GQDU0gA.png)

7. Maximizing Expected Improvement
----------------------------
pp.371-

 Method 5 (**EI**):
$$x^{next} := \\mathrm{argmin}\_{\\bold{x}^\*} \\Bbb{E} \[ \\text{u}(y^\*) \]$$ (eq.34,35 (p.371))

8. One-stage approach for goal seeking
---------------------------
pp.
373-

Method 6 = **GoalSeeking** $$\\ni$$ \#1-stage
 \#1-stage + $$\\alpha = \\mathrm{LOIs}\\in$$ Bayes Estimation \#\[Syuuron\]

Cf. \#\[Syuuron\]

### what about \#overfitting ?

9. One-stage approach for optimization
-----------------------------
pp. 375-{x}^{next} :=\ \mathrm{argmin}\_{\bold{x}^*} y^*$$

10.  Minimizing a interpolating surface
-----------------------------
pp.349-

Method 2:
$$\\bold{x}^{next} :=\\ \\mathrm{argmin}\_{\\bold{x}^\*} y^\*$$


> Written with [StackEdit](https://stackedit.io/).