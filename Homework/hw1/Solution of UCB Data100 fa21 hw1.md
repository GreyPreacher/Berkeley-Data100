# Solution of UCB Data100 fa21 hw1

### 1

(a)

$\sigma(-x)=\frac{1}{1+e^{x}}$

$1-\sigma(x)=1-\frac{1}{1+e^{-x}}=\frac{1+e^{-x}-1}{1+e^{-x}}=\frac{e^{-x}}{1+e^{-x}}=\frac{1}{1+e^{x}}$

So, $\sigma(-x)=1-\sigma(x)$



(b)

$\frac{d}{dx}\sigma(x)=\frac{e^{-x}}{(1+e^{-x})^{2}}=\frac{1}{2+e^{x}+e^{-x}}$

$\sigma(x)(1-\sigma(x))=\frac{1}{1+e^{-x}}\cdot\frac{1}{1+e^{x}}=\frac{1}{2+e^{x}+e^{-x}}$

So, $\frac{d}{dx}\sigma(x)=\sigma(x)(1-\sigma(x))$



### 2

$\frac{d}{dc}f(c)=-\frac{2}{n}\sum_{i=1}^{n}(x_{i}-c)=\frac{2}{n}[nc-(x_{1}+x_{2}+...+x_{n})]$

when $c=\frac{1}{n}\sum_{i=1}^{n}x_{i},\frac{d}{dc}f(c)=0$

when $c<\frac{1}{n}\sum_{i=1}^{n}x_{i},\frac{d}{dc}f(c)<0$

when $c>\frac{1}{n}\sum_{i=1}^{n}x_{i},\frac{d}{dc}f(c)>0$

so, when $c=\frac{1}{n}\sum_{i=1}^{n}x_{i}$, f(c) is a minimum



### 3

I choose 2, there no information about religious leaders



### 4

Suppose A: a woman has breast cancer

​				B: a woman of 40-year-old tested positive

then, $P(B|A)=0.8, P(B|\overline A)=0.096, P(A)=0.01, P(\overline A)=0.99$

$P(B)=P(B|A)P(A)+P(B|\overline A)P(\overline A)=0.10304$

$P(AB)=P(B|A)P(A)=0.08$

$P(A|B)=\frac{P(AB)}{P(B)}=0.078$



### 5

choose B

this is a Normal Distribution, mathematical expectation is 150 

$\frac{1}{\sqrt{2\pi}\sigma}=0.063$

then we have $\sigma^{2}=6.38$, so choose B



### 6

(a)

​	r(A)=2, A is full rank



(b)

​	r(B)=1, $\overrightarrow{v_{2}}=0\overrightarrow{v_{1}}$



(c)

​	r(C)=2, C is full rank



(d)

​	r(D)=2, $\overrightarrow{v_{3}}=\overrightarrow{v_{1}}-\overrightarrow{v_{2}}$











