---
date: 2024-06-08
category:
  - topic
---
# Definition
## Formal
Formal definition of limits is the [Epsilon-Delta ($\epsilon$, $\delta$ ) Definition](https://math.libretexts.org/Bookshelves/Calculus/Calculus_3e_(Apex)/01%3A_Limits/1.02%3A_Epsilon-Delta_Definition_of_a_Limit)
## Informal
Make the value of a function $f(x)$ arbitrarily close to $L$ by taking $x$ to be close to $a$ as possible (on either side of $a$) without making $x = a$. Limit notation is like this:
$$\lim_{x\rightarrow a} f(x) = L$$
This is two sided limit therefore both [[#One-Sided Limit#Left sided limit|left side]] and [[#One-Sided Limit#Right sided limit|right side limit]] need to be equal. 
$$\lim_{x\rightarrow a} f(x) = L \Leftrightarrow \lim_{x\rightarrow a^-}f(x) = \lim_{x\rightarrow a^+}f(x)  $$
# One-Sided Limit
## Left sided limit
Make the values of a function $f(x)$ arbitrarily close to $L$ by taking $x$ to be sufficiently close to a with $x < a$, we write the notation like this:
$$ \lim_{x\rightarrow a^-} f(x)$$
## Right sided limit
While, make the values of a function $f(x)$ arbitrarily close to $L$ by taking $x$ to be sufficiently close to a with $x > a$, we write the notation like this:
$$ \lim_{x\rightarrow a^+} f(x)$$
# Properties of limit
## Sum/Difference Law
$$\lim_{x \rightarrow a } [f(x) \pm g(x)]=\lim_{x \rightarrow a } f(x) \pm \lim_{x \rightarrow a } g(x)$$

$$\lim_{x \rightarrow a } [cf(x)]=c\lim_{x \rightarrow a } f(x)$$

$$\lim_{x \rightarrow a } [f(x) g(x)]=\lim_{x \rightarrow a } f(x) \cdot \lim_{x \rightarrow a } g(x)$$

$$\lim_{x \rightarrow a } [\frac {f(x)} {g(x)}]= \frac{ \lim_{x \rightarrow a } f(x)}{\lim_{x \rightarrow a } g(x)}$$

$$\lim_{x \rightarrow a } [f(x)]^n=[\lim_{x \rightarrow a } f(x)]^n$$

$$\lim_{x \rightarrow a } [\sqrt[n]{f(x)}]=\sqrt[n]{\lim_{x \rightarrow a } f(x)}$$
# Squeeze theorem
If $f(x)\le g(x)\le h(x)$ when $x$ is near $a$ & $$\lim_{x\rightarrow a} f(x) = \lim_{x\rightarrow a} g(x) = L $$
then
$$\lim_{x\rightarrow a} g(x) = L $$
## Example
*Prove $\lim_{x \rightarrow 0} x^2 \sin \frac 1 x = 0$*
$$-1 \le \sin x \le 1$$
$$-1 \le \sin \frac1 x \le 1$$
$$-x^2 \le x^2\sin \frac1 x \le x^2$$
since $$\lim_{x \rightarrow 0} (-x^2) = \lim_{x \rightarrow 0} x^2 = 0$$
therefore $$\lim_{x \rightarrow 0} x^2sin\frac1 x = 0$$
