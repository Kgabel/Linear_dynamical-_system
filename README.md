**Simulation of Linear_dynamical_system**
## Linear time invariant systems
To simulate the solution of a continuous-time linear dynamical system given the system matrix $A$ and initial condition $x_0$:

$\dot{x} = Ax, x(0) = x_0, $

We will use the matrix exponential formula to compute the state transition matrix and then use it to evolve the system over time. 

## Unstable
The system matrix $A$ is given by:

$
A = \begin{bmatrix}
1 & 2 \\
-2 & 1 \\
\end{bmatrix}.
$

The system of equations can be written as:

\begin{align*}
\frac{dx_1}{dt} &= 1 \cdot x_1 + 2 \cdot x_2 \\
\frac{dx_2}{dt} &= -2 \cdot x_1 + 1 \cdot x_2 \\
\end{align*}

where $x_1$ and $x_2$ are the state variables, and the coefficients of the system matrix $A$ determine the dynamics of the system.


