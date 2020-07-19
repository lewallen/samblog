---
layout: post
mathjax: true
comments: true
title: Test markdown
subtitle: Each post also has a subtitle
tags: [test]
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

## Test Latex

Test $ \alpha $ $\beta$

$ test $

$$\frac{a}{b}$$

$$ 2 + x^2 = 11 $$

You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
