To ensure that the numerical methods do not introduce significant errors, it is essential to periodically check the conservation of energy and momentum in the system. This involves calculating the total energy and momentum at each time step and comparing them to the initial values.

Total Energy:
$$
E = \sum_{i} \left( \frac{1}{2} m_i v_i^2 \right) - \sum_{i < j} \left( G \frac{m_i m_j}{r_{ij}} \right)
$$

Total Momentum:
$$
\mathbf{P} = \sum_{i} m_i \mathbf{v}_i
$$

Any significant deviation from the initial values indicates numerical errors.
