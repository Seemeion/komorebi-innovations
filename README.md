# komorebi-innovations

Fashion product

**Komorebi Innovations** proposes an interaction system that involves three main elements: sunlight, intermediate materials, and transmitted light. When sunlight passes through an intermediate material, such as fabric or lace, it undergoes refraction and/or reflection, resulting in the formation of dynamic shadows and patterns on a projection surface.

The following functions can be considered in the mathematical modeling of this interaction system: 

1. Sunlight intensity ($I_0$)
2. Incident angle ($\theta_1$)
3. Refractive index of intermediate material ($n_1$)
4. Refractive index of surrounding medium (e.g. air) ($n_0$)
5. Transmission coefficient (T)
6. Reflection coefficient (R)
7. Shadow projection onto a surface (e.g. skin or fabric) (S)

The relationships between these functions can be described mathematically using the Fresnel equations, which govern the reflection and refraction of light at the interface between two media with different refractive indices. The equations can be expressed as follows:

$$
R = \left(\frac{n_1 \cos \theta_1 - n_0 \cos \theta_2}{n_1 \cos \theta_1 + n_0 \cos \theta_2}\right)^2
$$

$$
T = 1 - R
$$

$$
\theta_2 = \arcsin\left(\frac{n_0 \sin \theta_1}{n_1}\right)
$$

Where R is the reflection coefficient, T is the transmission coefficient, $\theta_1$ is the incident angle, $\theta_2$ is the refracted angle, $n_1$ is the refractive index of the intermediate material, and $n_0$ is the refractive index of the surrounding medium (e.g. air).

By incorporating these equations into the modeling of the interaction system, it is possible to predict the patterns and shadows that will be projected onto a surface when sunlight passes through a given intermediate material. This can inform the design and fabrication of translucent garments and accessories that produce unique visual effects when exposed to sunlight.

