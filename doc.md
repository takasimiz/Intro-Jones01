Decrypt "A Taxonomy of Global Optimization Methods Based on Response Surfaces" by Donald [^jones01]
====

[^jones01]: Jones, Donald R. "A taxonomy of global optimization methods based on response surfaces." Journal of global optimization 21.4 (2001): 345-383.
Jones
Synopsis(TL;DR)
----------
* survey of surrogate-based opt 
* but mainly kriging (Gaussian process) surrogated

Contents
-----------

### 1. Introduction[^1]
[^1]: Sec.1
pp.345-

#### survey & invention of a bunch of **Infill Criterion (\#IC)**

### Minimizing a quadratic surface

pp.348-

#### \#1

#### $$\# \#\[Jones01\]

"A Taxonomy of Global Optimization Methods Based on Response Surfaces"
by Donald
Jones

## TL;DR

* Survey of surrogate-based opt methods.
* but mainly kriging (Gaussian process) surrogated.

## Contents

### 1. Introduction

pp.345-

#### survey & invention of a bunch of **Infill Criterion (\#IC)**

### 2. Minimizing a quadratic surface

pp.348-


 Mehod1: 
$$
\newcommand{\argmin}{\mathop{\mathrm{arg\,min}}}
\newcommand{\xstar}{\mathop{\mathbf{x}^{*}}}
\newcommand{\ystar}{\mathop{\mathbf{y}^{*}}}
$$

### Minimizing a interpolating surface

pp.349-

#### \#2

#### $$\xstar := \argmin_{\xstar} \ystar$$

### A gentle introduction to kriging

pp.356-

#### lessong of kriging ( \#GP )

### Minimizing a statistical lower bound

pp.362-

#### \#3

#### $$\\bold{x}^{next} :=\\ \\mathrm{argmin}\_{\\bold{x}^\*} \\hat{y}(\\bold{x}^\*) - a \\sigma(\\bold{x^\*})$$

### Maximizing the probability of improvement

pp.364-

#### \#4

#### $$x^{next} := \\mathrm{argmin}\_{\\bold{x}^\*} \\Pr(T

#### \!\[Fig.14\](https://cdn.pbrd.co/images/GQDU0gA.png)

### Maximizing Expected Improvement

pp.371-

#### \#5 (**EI**)

#### $$x^{next} := \\mathrm{argmin}\_{\\bold{x}^\*} \\Bbb{E} \[ \\text{u}(y^\*) \]$$ (eq.34,35 (p.371))

### One-stage approach for goal seeking

pp.
373-

#### \#6 = **GoalSeeking** $$\\ni$$ \#1-stage

#### \#1-stage + $$\\alpha = \\mathrm{LOIs}\\in$$ Bayes Estimation \#\[Syuuron\]

#### Cf. \#\[Syuuron\]

#### what about \#overfitting ?

### One-stage approach for optimization

pp. 375-{x}^{next} :=\ \mathrm{argmin}\_{\bold{x}^*} y^*$$

### Minimizing a interpolating surface

pp.349-

#### \#2

#### $$\\bold{x}^{next} :=\\ \\mathrm{argmin}\_{\\bold{x}^\*} y^\*$$

### A gentle introduction to kriging

pp.356-

#### lessong of kriging ( \#GP )

### Minimizing a statistical lower bound

pp.362-

#### \#3

#### $$\\bold{x}^{next} :=\\ \\mathrm{argmin}\_{\\bold{x}^\*} \\hat{y}(\\bold{x}^\*) - a \\sigma(\\bold{x^\*})$$

### Maximizing the probability of improvement

pp.364-

#### \#4

#### $$x^{next} := \\mathrm{argmin}\_{\\bold{x}^\*} \\Pr(T

#### \!\[Fig.14\](https://cdn.pbrd.co/images/GQDU0gA.png)

### Maximizing Expected Improvement

pp.371-

#### \#5 (**EI**)

#### $$x^{next} := \\mathrm{argmin}\_{\\bold{x}^\*} \\Bbb{E} \[ \\text{u}(y^\*) \]$$ (eq.34,35 (p.371))

### One-stage approach for goal seeking

pp.
373-

#### \#6 = **GoalSeeking** $$\\ni$$ \#1-stage

#### \#1-stage + $$\\alpha = \\mathrm{LOIs}\\in$$ Bayes Estimation \#\[Syuuron\]

#### Cf. \#\[Syuuron\]

#### what about \#overfitting ?

### One-stage approach for optimization

pp. 375-

> Written with [StackEdit](https://stackedit.io/).