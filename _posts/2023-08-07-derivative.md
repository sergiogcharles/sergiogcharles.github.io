---
layout: post
title: A Neat Derivative Trick
date: 2023-08-07 06:00:00-0000
description: An interesting brainteaser.
tags: derivatives
categories: mathematics
giscus_comments: false
related_posts: false
---

Which is larger $$\pi^e$$ or $$e^{\pi}$$? 
Hint: consider $$\log x/x$$.

Suppose $$\alpha>\beta$$. The key observation is if we take the natural logarithm of both sides, then $$\log \alpha > \log \beta$$ would imply $$\alpha>\beta$$ since the logarithm is montonically increasing (and concave). 

Hence, let $$y=\frac{\log x}{x}$$. Consider the first derivative:
\begin{equation}
\frac{dy}{dx}=\frac{1}{x^2}-\frac{\log}{x^2}=\frac{1-\log x}{x^2}.
\end{equation}

Note that $$y'(e)=\frac{1-\log e}{e^2}=0$$ and $$y'(\pi)=\frac{1-\log \pi}{\pi^2}<0$$, as $$\pi > e$$. Indeed, $$y'(x)<0$$ on $$[e,\pi]$$. Notice that $$y(x)$$ has a maximum at $$x=e$$ since $$y'(e)=0$$. Thus,
\begin{equation}
\frac{\log e}{e} > \frac{\log \pi}{\pi}.
\end{equation}

It follows that $$\pi \log e>e\log \pi$$ or $$e^\pi>\pi^e$$. 

One can also use a Taylor series for $$e^x=\sum_{n=0}^{\infty}\frac{x^n}{n!}$$, substituting $$x=\frac{\pi}{e}-1$$ to see this, albeit less intutivie.