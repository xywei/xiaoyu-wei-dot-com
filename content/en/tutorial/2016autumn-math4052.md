+++
title = "(2016 Autumn) Math 4052 Partial Differential Equations"
math = true
lastmod = 2019-03-01
draft = false
weight = -162
+++

Outline: Derivatives of the Laplace equations, the wave equations and diffusion equation; Methods to solve equations: separation of variables, Fourier series and integrals and characteristics; maximum principles, Green's functions.

Here you can find homework problems and solutions. The problems are selected from 
the text book (*Partial differential equations, an introduction, Walter A. Strauss,  The second edition, John Wiley & Sons,  Ltd.*) and are listed here for your convenience. 

<!--more-->

## Basic Info

- Course Name: Partial Differential Equations
- Lecturers: Chair Prof. Xiao-Ping Wang
- Sessions: T1A (Wednesday 16:30-17:20 at Room 1505), T1B (Monday 17:30-18:20 at Room 1511)
- Course Page: http://www.math.ust.hk/~mawang/teaching/math4052/math4052a.html
- Semester: 2016-Autumn

#### Homework Problems
- Homework 1 (Due in tutorial class in the week of Sept 12):
  1. ([Page 5](page-005.pdf), Q2(a)(b)). Which of the following operators are linear?
     - $ \mathscr{ L } u = u_x + x u_y $.
     - $ \mathscr{ L } u = u_x + u u_y $.
  2. ([Page 5](page-005.pdf), Q3\(c)(d)). For each of the following equations, state the order and
  whether it is nonlinear, linear inhomogeneous, or linear homogeneous; provide
  reasons.
     - $ u_t - u\_{xxt} + u u_x = 0 $.
     - $ u_{tt} - u\_{xx} + x^2 = 0 $.
  3. ([Page 9](page-009.pdf), Q1). Solve the first-order equation $ 2u_t + 3u_x = 0 $ with the auxiliary condition
$ u=\sin x $ when $ t=0 $. 

- Homework 2 (Due in tutorial class in the week of Sept 19):
  1. ([Page 27](page-027.pdf), Q3). Solve the boundary problem $ u'^\prime = 0 $
     for $ 0<x<1 $ with $ u'(0)+k u(0) = 0 $ and $ u'(1)\pm k u(1)=0 $.
     Do the $+$ and $-$ cases separately. What is special about the case $k=2$?
  2. ([Page 31](page-031.pdf), Q1). What is the type of each of the following equations?
     - $ u\_{xx}  - u\_{xy} + 2 u _y + u\_{yy} - 3 u\_{yx} + 4u = 0$.
     - $ 9 u\_{xx}  + 6 u\_{xy} + u\_{yy} + u\_{x}  = 0$.
  3. ([Page 32](page-032.pdf), Q6). Consider the equation $ 3u\_y + u\_{xy} = 0$.
     - What is its type?
     - Find the general solution. (*Hint:* Substitute $v=u_y$.)
     - With the auxiliary conditions $u(x,0)= e^{-3x}$ and $u_y(x,0)=0$,
       does a solution exist? Is it unique?
- Homework 3 (Due in tutorial class in the week of Sept 26):
  1. ([Page 38](page-038.pdf), Q1). Solve $ u\_{tt} = c^2 u\_{xx}$, $u(x,0)=e^x$, 
    $u\_t(x,0) = \sin x$.
  2. ([Page 38](page-038.pdf), Q2). Solve $ u\_{tt} = c^2 u\_{xx}$, $u(x,0)=\log (1+x^2)$, 
    $u\_t(x,0) = 4+x$.
  3. ([Page 38](page-038.pdf), Q9). Solve $u\_{xx} - 3 u\_{xt} - 4u\_{tt} = 0$, 
    $u(x,0)=x^2$, $u_t(x,0)=e^x$. (*Hint:* Factor the operator as we did for the 
    wave equation.)
  4. ([Page 41](page-041.pdf), Q4). If $u(x,t)$ satisfies the wave equation $u\_{tt} = u\_{xx}$, prove the identity
  $$u(x+h,t+k) + u(x-h,t-k) = u(x+k,t+h) + u(x-k,t-h)$$
  for all $x,t,h$, and $k$. Sketch the quadrilateral $Q$ whose vertices are the arguments in the identity.
- Homework 4 (Due in tutorial class in the week of Oct. 3):
  1. ([Page 52](page-052.pdf), Q3). Use the method of Green's function to solve the diffusion equation $u\_t = k u\_{xx}$, subject to the initial condition $u(x,0)=\phi(x)$, where $ \phi(x) = e^{3x} $.
  1. ([Page 52](page-052.pdf), Q4). Solve the diffusion equation above if $\phi(x) = e^{-x}$ for $x>0$ and $\phi(x)=0$ for $x<0$.
  1. ([Page 52](page-052.pdf), Q5). Prove properties (a)-(e) seen on [Page 47](page-047.pdf) of the diffusion equation $u\_t = k u\_{xx}$.
- Homework 5 (Due in tutorial class in the week of Oct. 10):
  1. ([Page 89](page-089.pdf), Q2). Consider a metal rod ($0<x<l$), insulated along its sides but not at its ends, which is initially at temperature $=1$. Suddenly both ends are plunged into a bath of temperature $=0$. Write the differential equation, boundary conditions, and initial condition. Write the formula for the temperature $u(x,t)$ at later times. In this problem, *assume* the infinite series expansion
  $$ 1 = \frac{4}{\pi} \left( \sin \frac{\pi x}{l} + \frac{1}{3}\sin\frac{3 \pi x}{l} + \frac{1}{5}\sin\frac{5 \pi x}{l}+ \cdots  \right) $$
  1. ([Page 89](page-089.pdf), Q4). Consider waves in a resistant medium that satisfy the problem
  $$ u\_{tt} = c^2 u\_{xx} - r u\_t \quad \text{for} \quad 0<x<l $$
  $$ u= 0 \quad \text{at both ends} $$
  $$ u(x,0)= \phi(x) \quad u\_{t}(x,0) = \psi(x),$$
  where $r$ is a constant, $0<r<2\pi c/l$. Write down the series expansion of the solution.
  1. ([Page 92](page-092.pdf), Q2). Consider the equation $u\_{tt}=c^2 u\_{xx}$ for $0<x<l$, with the boundary conditions $u\_x(0,t) = 0,u(l,t)=0$ (Neumann at the left, Dirichlet at the right).
     1. Show that the eigenfunctions are $\cos\left[ \left( n+\frac{1}{2}\right)\pi x/l\right]$.
     1. Write the series expansion for a solution $u(x,t)$.
  1. ([Page 92](page-092.pdf), Q3). Solve the Schrödinger equation $u\_t = i k u\_{xx}$ for real $k$ in the interval $0<x<l$ with the boundary conditions $u_x(0,t) = 0,u(l,t) = 0$.
- Homework 6 (Due in tutorial class in the week of Oct. 16):
  1. ([Page 45](page-045.pdf), Q2). Consider a solution of the diffusion equation
  $u_t = u\_{xx}$ in $\\{ 0 \leq x \leq l, 0 \leq t < \infty \\}$.
     1. Let $M(T) = $ the maximum of $u(x,t)$ in the closed rectangle $\\{ 0 \leq x \leq l,
        0 \leq t \leq T \\}$. Does $M(T)$ increase or decrease as a function of $T$?
     2. Let $m(T) = $ the minimum of $u(x,t)$ in the closed rectangle $\\{ 0 \leq x \leq l,
        0 \leq t \leq T \\}$. Does $m(T)$ increase or decrease as a function of $T$?
  1. ([Page 46](page-046.pdf), Q4). Consider the diffusion equation $u_t = u\_{xx}$  in $\\{ 0<x<1,0<t< \infty \\}$ 
  with $u(0,t)=u(1,t)=0$ and $u(x,0)=4x(1-x)$.
     1. Show that $ 0 < u(x,t) < 1 $ for all $t>0$ and $0<x<1$.
     2. Show that $ u(x,t) = u(1-x,t) $ for all $t\geq 0$ and $0 \leq x \leq 1$.
     3. Use the energy method to show that $ \int _0 ^1 u^2 dx$ is a strictly decreasing
     function of $t$.

- Homework 7 (Due in tutorial class in the week of Oct. 31):
  1. ([Page 111](page-111.pdf), Q2). Let $\phi(x) \equiv x^2$ for $0 \leq x \leq 1 = l$.
     1. Calculate its Fourier sine series.
     2. Calculate its Fourier cosine series.
  1. ([Page 111](page-111.pdf), Q4).  Find the Fourier cosine series of the function
     $ | \sin x | $ in the interval $(-\pi,\pi)$. Use it to find the sums
     $$ \sum\_{n=1}^\infty \frac{1}{4 n^2 - 1} \quad \text{and} \quad 
        \sum\_{n=1}^\infty \frac{(-1)^n}{4n^2 - 1}. $$
  1. ([Page 134](page-134.pdf), Q1). $\sum\_{n=0}^\infty (-1)^n x^{2n}$ is a 
     geometric series.
     1. Does it converge pointwise in the interval $-1<x<1$ ?
     1. Does it converge uniformly in the interval $-1<x<1$ ?
     1. Does it converge in the $L^2$ sense in the interval $-1<x<1$ ?  
        (*Hint*: You can compute its partial sums explicitly.)
  1. ([Page 134](page-134.pdf), Q5). Let $\phi(x)=0$ for $0<x<1$ and $\phi(x)=1$ 
     for $1<x<3$.
     1. Find the first four nonzero terms of its Fourier cosine series explicitly.
     1. For each $x$ $(0\leq x \leq 3)$, what is the sum of this series?
     1. Does it converge to $\phi(x)$ in the $L^2$ sense? Why?
     1. Put $x=0$ to find the sum  
        $$  1 + \frac{1}{2} - \frac{1}{4} - \frac{1}{5} + \frac{1}{7} + \frac{1}{8} - \frac{1}{10} - \frac{1}{11} + \dots .$$
  1. ([Page 134](page-134.pdf)~[Page 135](page-135.pdf), Q7). Let 
     $$ \phi(x) = \left\\{ \begin{align} -1-x \quad & \text{for}\quad -1 < x < 0 \\\\ +1-x \quad & \text{for}\quad 0 < x < 1. \end{align} \right.$$
     1. Find the full Fourier series of $\phi(x)$ in the interval $(-1,1)$.
     1. Find the first three nonzero terms explicitly.
     1. Does it converge in the mean square sense?
     1. Does it converge pointwise?
     1. Does it converge uniformly to $\phi(x)$ in the interval $(-1,1)$?

- Homework 8 (Due in tutorial class in the week of Nov. 7):
  1. ([Page 160](page-160.pdf), Q6). Solve $u\_{xx} + u\_{yy}=1$
     in the annulus $a<r<b$ with $u(x,y)$ vanishing on both parts
     of the boundary $r=a$ and $r=b$.
  1. ([Page 160](page-160.pdf), Q9). A spherical shell with inner radius $1$
     and outer radius $2$ has a steady-state temperature distribution. Its
     inner boundary is held at $100\unicode{x2103}$. Its outer boundary satisfies
     $\partial u / \partial r = - \gamma < 0 $, where $\gamma$ is a constant.
     1. Find the temperature. (*Hint*: The temperature depends only on the radius.)
     1. What are the hottest and coldest temperatures?
     1. Can you choose $\gamma$ so that the temperature on its outer boundary is 
        $20\unicode{x2103}$?
  1. ([Page 164](page-164.pdf)~[Page 165](page-165.pdf), Q1). Solve  $u\_{xx} + u\_{yy}=0$
     in the rectangle $0<x<a$, $0<y<b$ with the following boundary conditions:
     $$ \begin{align} & u\_x  = -a \quad \text{on } x=0 \qquad & u\_x  = 0 \quad \text{on } x=a \\\\  & u\_y  = b \quad \text{on } y=0  \qquad & u\_y = 0 \quad \text{on } y=b.   \end{align}
     $$
     (*Hint*: Note that the necessary condition of Exercise 6.1.11 is satisfied. A shortcut
     is to guess that the solution might be a quadratic polynomial in $x$ and $y$.)
  1. ([Page 165](page-165.pdf), Q4). Find the harmonic function in the square 
     $\\{ 0<x<1, 0<y<1 \\}$ with the boundary conditions $u(x,0)=x$, $u(x,1)=0$,
     $u\_x(0,y)=0$, $u\_x( 1,y )=y^2$.

- Homework 9 (Due in  tutorial class in the week of Nov. 14):
  1. ([Page 172](page-172.pdf), Q1). Suppose that $u$ is a harmonic function in the disk $D=\\{r<2\\}$ and that $u=3 \sin 2 \theta + 1$ 
     for $r=2$. Without finding the solution, answer the following questions:
     1. Find the maximum value of $u$ in $\bar{D}$.
     1. Calculate the value of $u$ at the origin.
  1. ([Page 172](page-172.pdf), Q2). Solve $u\_{xx} + u\_{yy}=0$ in the disk $D=\\{r<a\\}$ with the boundary condition
    $$ u = 1 + 3 \sin \theta \quad \text{on } r=a. $$
  1. ([Page 175](page-175.pdf), Q1). Solve $u\_{xx} + u\_{yy}=0$ in the *exterior* $\\{r>a\\}$ of a disk, with the boundary condition
     $u=1+3\sin\theta$ on $r=a$, and the condition at infinity that $u$ be bounded as $r\longrightarrow\infty$.
  1. ([Page 176](page-176.pdf), Q10).Solve $u\_{xx} + u\_{yy}=0$ in the quarter-disk $\\{ x^2 + y^2 < a^2, x>0, y>0 \\}$
     with the following BCs:
     $$ u=0 \quad \text{on } x=0 \text{ and on } y=0 \quad \text{and} \quad \frac{\partial u}{\partial r} = 1 \quad \text{on } r=a.$$
     Write the answer as an infinite series and write the first two nonzero terms explicitly.

- Homework 10 (Due in  tutorial class in the week of Nov. 21):
  1. ([Page 184](page-184.pdf), Q2). Prove the uniqueness up to constants of the Neumann problem using the energy method.
  1. ([Page 184](page-184.pdf), Q3). Prove the uniqueness of the Robin problem $ \partial u / \partial n + a(\mathbf{x}) u(\mathbf{x}) = h(\mathbf{x})$
     provided that $a(\mathbf{x})>0$ on the boundary.
  1. ([Page 187](page-187.pdf), Q1). Derive the representation formula for harmonic functions in two dimensions: 
     $$ u(\mathbf{x}\_0) = \frac{1}{2\pi} \int\_{\text{bdy} D} \left[ 
     u(\mathbf{x}) \frac{\partial}{\partial n} ( \log |\mathbf{x} - \mathbf{x}\_0| ) - \frac{\partial u}{\partial n} \log |\mathbf{x} - \mathbf{x}\_0| 
     \right] ds.$$
  1. ([Page 187](page-187.pdf), Q2). Let $\phi(\mathbf{x})$ be any $\mathbf{C}^2$ function defined on all of three-dimensional space that vanishes outside
     some sphere. Show that
     $$ \phi(\mathbf{0}) = - \iiint \frac{1}{|\mathbf{x}|} \Delta \phi(\mathbf{x}) \frac{d\mathbf{x}}{4\pi}. $$
     The integration is taken over the region where $\phi(\mathbf{x})$ is not zero.

- Homework 11 (Due in  tutorial class in the week of Nov. 28):
  1. ([Page 196](page-196.pdf), Q1). Find the one-dimensional Green's function for the interval $(0,l)$. The three properties defining it can be restated as follows.
     1. It solves $G'^\prime (x) = 0$ for $x\neq x\_0$ ("harmonic").
     2. $G(0) = G(l) = 0$.
     3. $G(x)$ is continuous at $x\_0$ and $G(x) + \frac{1}{2} | x - x\_0 |$ is harmonic at $x\_0$.
  1. ([Page 196](page-196.pdf), Q6).
     1. Find the Green's function for the half-plane $ \\{ (x,y): y>0 \\} $.
     2. Use it to solve the Dirichlet problem in the half-plane with boundary values $h(x)$.
     3. Calculate the solution with $u(x,0) = 1$.
  1. ([Page 197](page-197.pdf), Q9). Find the Green's function for the tilted half-space $ \\{ (x,y,z): ax+by+cz>0  \\} $. (*Hint*: Either do it from scratch by reflecting across the tilted plane, or change variables in the double integral (3)
  $$ 0 = \iint\_{\text{bdy }D} \left( u \frac{\partial H}{\partial n} - \frac{\partial u}{\partial n} H \right) dS  $$
  using a linear transformation.)
  1. ([Page 197](page-197.pdf), Q17). 
     1. Find the Green's function for the quadrant
        $$ Q = \\{ (x,y) : x>0,y>0 \\}.$$
        (*Hint*: Either use the method of reflection or reduce to the half-plane problem by the transformation $(x,y) \mapsto (x^2-y^2,2xy)$.)
     2, Use your answer in the previous part to solve the Dirichlet problem
       $$ \begin{eqnarray} u\_{xx} + u\_{yy} = 0 \text{ in } Q, \quad u(0,y) = g(y) \text{ for } y>0, \\\\  u(x,0) = h(x) \text{ for } x>0. \end{eqnarray} $$

#### Answers and Hints
- Homework 1: [Answers and Hints](hw-01.pdf).
- Homework 2: [Answers and Hints](hw-02.pdf).
- Homework 3: [Answers and Hints](hw-03.pdf).
- Homework 4: [Answers and Hints](hw-04.pdf).
- Homework 5: [Answers and Hints](hw-05.pdf).
- Homework 6: [Answers and Hints](hw-06.pdf).
- Homework 7: [Answers and Hints](hw-07.pdf).
- Homework 8: [Answers and Hints](hw-08.pdf).
- Homework 9: [Answers and Hints](hw-09.pdf).
- Homework 10: [Answers and Hints](hw-10.pdf).
- Homework 11: [Answers and Hints](hw-11.pdf).
