Exercise for 'Numerical Methods for PDEs'.

## 1. Forward/Backward Difference Method

The forward difference method and the backward difference scheme are used to solve the  initial boundary value problem for heat conduction equations:
$$
\begin{cases}\frac{\partial u}{\partial t}=\frac{\partial^2 u}{\partial x^2}, & 0<x<1,0<t<1 \\ u(x, 0)=\sin (\pi x), & 0 \leq x \leq 1 \\ u(0, t)=0, & 0<t \leq 1 \\ u(1, t)=0, & 0<t \leq 1\end{cases}\nonumber
$$

## 2. Explicit Central Difference Method

### For heat equation

An explicit central difference method is used to solve the following first initial boundary value problem of the heat conduction equation with convective terms:
$$
\begin{cases}\frac{\partial u}{\partial t}-b \frac{\partial u}{\partial x}=\frac{\partial^2 u}{\partial x^2}+(b-1) \mathrm{e}^{-x}+1, & 0<x<10, t>0 \\ u(x, 0)=\mathrm{e}^{-x}, & 0 \leq x \leq 10 \\ u(0, t)=t+1, & t>0 \\ u(10, t)=\mathrm{e}^{-10}+t, & t>0\end{cases}\nonumber
$$

### For TPBV

The following two-point boundary value problem is solved using the central difference method:
$$
\left\{\begin{array}{l}-u^{\prime \prime}(x)+u(x)=e^x(\sin x-2 \cos x), \quad 0<x<\pi \\ u(0)=0, \quad u(\pi)=0\end{array}\right.\nonumber
$$

## 3. Five-point Difference Method

The first side value problem of the elliptic equation is solved by five-point difference method:
$$
\left\{\begin{array}{l}-\Delta u=\left(\pi^2-1\right) e^x \sin (\pi y), \quad 0<x<2,0<y<1 \\ u(0, y)=\sin (\pi y), u(2, y)=e^2 \sin (\pi y), \quad 0 \leq y \leq 1 \\ u(x, 0)=0, u(x, 1)=0, \quad 0<x<2\end{array}\right.\nonumber
$$

## 4. Upwind Method

An implicit upwind method is used to solve the initial boundary value problem:
$$
\left\{\begin{array}{l}\frac{\partial u}{\partial t}+2 \frac{\partial u}{\partial x}=0, \quad 0<x<2,0<t \leq 1.5 \\ u(x, 0)=\mathrm{e}^x, \quad 0 \leq x \leq 2 \\ u(0, t)=\mathrm{e}^{-2 t}, \quad 0 \leq t \leq 1.5\end{array}\right.\nonumber
$$

## 5. Alternating Direction Implicit (ADI) method

The P-R (Peaceman-Rachford) method solves the following two-dimensional equations:
$$
\left\{\begin{array}{l}\frac{\partial u}{\partial t}=4^{-2} \frac{\partial^2 u}{\partial x^2}+4^{-2} \frac{\partial^2 u}{\partial y^2}, \\ u(0, y, t)=u(1, y, t)=0, \\ u(x, 0, t)=\sin \pi x \exp \left(-\frac{\pi^2}{8} t\right), u(x, 1, t)=-\sin \pi x \exp \left(-\frac{\pi^2}{8} t\right) \\ u(\mathrm{x}, \mathrm{y}, 0)=\sin \pi x \cos \pi y,\end{array}\right.\nonumber
$$
