# Chew-Mandestam of high orbital angular momemtum.

Analytic expression for Chew-Mandestam functions with Blatt-Weisskopf form-factor of high orbital angular momemtum.

**keywords**: dispesion integrals.

Using dispersion relation we compute an analytic function from a known imaginary part, $i \rho F_L^2$ as follows,

$$
I_L(s) = \frac{s}{\pi}\int_{s_0}^{\infty} \frac{\rho(s')}{s'(s'-s-i0)} F_L^2((pR)^2)\,\mathrm{d} s'
$$

where
- $s$ is squared mass variables, $s'$ is an integration variable.
- $\rho(s)$ is the phase space function, $\rho(s) = 2p(s)/\sqrt{s}$
- The momentum $p(s)$ is computed as follows, $p(s) = \sqrt{(s-s_0)(s-s_1)}/(2\sqrt{s})$,
- with the threshold variables $s_0 = (m_a+m_b)^2$, and $s_1 = (m_a-m_b)^2$.
- Functions $F_L^2(z^2)$ are rational functions of $z^2$, and $R$ is a numerical constant.

Example of $F$ functions:
```math
\begin{align}
F_0^2(z) &= 1\,,\\
F_1^2(z) &= \frac{z}{1+z}\,,\\
F_2^2(z) &= \frac{z^2}{9+3z+z^2}\,.
\end{align}
```
