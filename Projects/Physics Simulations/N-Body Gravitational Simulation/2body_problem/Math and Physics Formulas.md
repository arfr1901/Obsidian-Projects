# Gravitational Force

Newton's law of gravitation states that the force between two bodies is given by:

$$
F = G \frac{m_1 m_2}{r^2} \tag{1}
$$

where:

- **F** is the gravitational force.
- **G** is the gravitational constant.
- **m<sub>1</sub>** and **m<sub>2</sub>** are the masses of the two bodies.
- **r** is the distance between the centers of the two bodies.

## C++ Code Implementation

The following C++ code represents Newton's law of gravitation, and it calculates the gravitational force between two bodies:

```cpp
// Gravitational constant
const double G = 6.67430e-11;

struct Body {
    double mass;
    double x, y, z; // Position
};

void gravitationalForce(const Body& a, const Body& b, double& fx, double& fy, double& fz) {
    double dx = b.x - a.x;
    double dy = b.y - a.y;
    double dz = b.z - a.z;
    double distance = std::sqrt(dx * dx + dy * dy + dz * dz);
    double force = G * a.mass * b.mass / (distance * distance);
    fx = force * dx / distance;
    fy = force * dy / distance;
    fz = force * dz / distance;
}
