---
layout: post
mathjax: true
comments: true
title: test number 3
date: '2020-07-18 14:28'
---

# Want to quickly respond to Will's comment on priors

Our basic Bayesian context. Have an "observation space" $X$, and a space of "models" $Y$ (called the latent space in latent variable models).

Typically a "model" is an element of $\p(X)$, the space of probability distributions on $X$ (with what structure?). Typically the model is specified by a point $m \in \R^d$ for some $d$, the parameter space, by implicitly or explicitly defining a map $f: \R^d \to \p(X)$; $f(m)$ is the model determined by $m$. 

For a moment, let's take our model space to be $\p(X)$ itself (a different generalization would be to think about $f: Y \to \p(X)$ for more general $Y$'s).

So recall we have $X$ and $Y = \p(X)$. A prior is a distribution on $Y$, i.e. an element $\mu \in \p(Y) = \p(\p(X))$.

> **Comment**: this infinite regress of prior stuff feels a bit like infinite loop spaces; is there an actual relationship?
> **Related**: Express spaces as function spaces wrt other spaces, to enable canonical/standard operations, etc

A compact Lie group $G$ has a Haar measure, 

# "Maneesh stuff" meaning, among other things, how to formalize the idea that the DDC is "abstract" in an important sense