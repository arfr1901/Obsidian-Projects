Symplectic integrators are a class of numerical integration methods used to solve Hamiltonian systems. They are designed to conserve the symplectic structure of the phase space, which helps to preserve energy and momentum over long simulations. A common symplectic integrator is the leapfrog method.

$$
\mathbf{v}\left(t + \frac{\Delta t}{2}\right) = \mathbf{v}(t) + \mathbf{a}(t) \frac{\Delta t}{2}
$$
$$
\mathbf{r}(t + \Delta t) = \mathbf{r}(t) + \mathbf{v}\left(t + \frac{\Delta t}{2}\right) \Delta t
$$
$$
\mathbf{v}(t + \Delta t) = \mathbf{v}\left(t + \frac{\Delta t}{2}\right) + \mathbf{a}(t + \Delta t) \frac{\Delta t}{2}
$$
