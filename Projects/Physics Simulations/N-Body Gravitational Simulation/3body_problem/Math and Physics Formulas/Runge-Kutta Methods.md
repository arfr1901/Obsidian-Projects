The Runge-Kutta methods are a family of iterative methods for approximating solutions to ordinary differential equations. The most commonly used method is the fourth-order Runge-Kutta method (RK4). The RK4 method provides a good balance between accuracy and computational efficiency. The update equations are:

$$
k_1 = f(t, \mathbf{y})
$$
$$
k_2 = f\left(t + \frac{\Delta t}{2}, \mathbf{y} + \frac{\Delta t}{2} k_1\right)
$$
$$
k_3 = f\left(t + \frac{\Delta t}{2}, \mathbf{y} + \frac{\Delta t}{2} k_2\right)
$$
$$
k_4 = f(t + \Delta t, \mathbf{y} + \Delta t k_3)
$$
$$
\mathbf{y}(t + \Delta t) = \mathbf{y}(t) + \frac{\Delta t}{6} (k_1 + 2k_2 + 2k_3 + k_4)
$$

where $f$ represents the system of differential equations, $\mathbf{y}$ is the state vector (position and velocity), and $\Delta t$ is the time step.
