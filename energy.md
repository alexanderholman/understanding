# Energy

## Kinetic energy in classical mechanics

Kinetic energy in classical mechanics can be described through the equation:

$$E_{kinetic} = \dfrac{1}{2}mv^2$$

`E` represents the `kinetic energy` of a system.

`m` represents the `mass` of a system.

`v` represents the `velocity` of the system.

## Discribing kinetic energy in terms of momentum

In quantum mechanics energy is represented in the form of momentum. This can also be described in classical mechanics.

Momentum can be described in classical mechanics as:

$$p = mv$$

`p` represents the `momentum` of a `mass` at a given `velocity`.

Velocity of a mass can therefor be described as a `mass` with a given `momentum`:

$$v = \dfrac{p}{m}$$

We can use the equation above to then describe `kinetic energy` of a system in terms of `momentum` as follows:

$$E = \dfrac{1}{2}mv^2$$

Expands to:

$$E = \dfrac{1}{2}mvv$$

Multiply by _2_:

$$2E = mvv$$

Substitute _mv_ for _p_:

$$2E = pv$$

Substitute _v_ for $\dfrac{p}{m}$:

$$2E = \dfrac{pp}{m}$$

Simplify to:

$$2E = \dfrac{p^2}{m}$$

Divide by _2_:

$$E = \dfrac{p^2}{2m}$$

## Momentum described in quantum mechanics

Momentum can be described in quantum mechanics using the formula:

$$p = {\hbar}k$$

${\hbar}$ represents the `reduced Plancks constant`.

`k` represents a particle's (e.g. an electron) wave vector.

## Kinetic energy described through momentum in quantum mechanics

Using the equations above, we can then describe `kinetic energy` in terms of `momentum` using quantum mechanics as follows:

$$E_{kinetic} = \dfrac{p^2}{2m}$$

Expand to:

$$E_{kinetic} = \dfrac{pp}{2m}$$

Substitute _p_ for ${\hbar}k$:

$$E_{kinetic} = \dfrac{{\hbar}k{\hbar}k}{2m}$$

Simplify to:

$$E_{kinetic} = \dfrac{{\hbar}^2k^2}{2m}$$

## Total Energy in quantum mechanics

The `total energy` of a system can be described in 2 parts; `kinetic energy` and `potential energy`, the relationship between the three described by the equation:

$$E_{total} = E_{kinetic} + E_{potential}$$

$E_{potential}$ is the `potential energy` of a system caused by its position `r` (or, equivalently `k` in `reciprical space` within a `periodic lattice`. It arises from particle to particle interaction, e.g. `ion` to `ion` `(i-i)`, `electron` to `electron` `(e-e)`, and `ion` to `electron` `(i-e)`.

### Particle pair interactions

#### Ion - Ion

$$E_{i-i} = \sum_{i,j} V_{i-i}(|\mathbf{r}_i - \mathbf{r}_j|)$$

#### Electron - Electron

$$E_{e-e} = \sum_{i,j} V_{e-e}(|\mathbf{r}_i - \mathbf{r}_j|)$$

#### Ion - Electron

$$E_{i-e} = \sum_{i,j} V_{i-e}(|\mathbf{r}_i - \mathbf{r}_j|)$$

Such that the `potential energy` of a system can be described as:

$$E_{potential} = E_{i-i} + E_{e-e} + E_{i-e}$$

#### Generalised formulation

Let the interactions be denoted by $S = [i-i, e-e, i-e]$.

The total potential energy can now be expressed as:

$$E_{potential} = \sum_{\alpha \in S} \sum_{i,j} V_{\alpha}(|\mathbf{r}_i - \mathbf{r}_j|)$$

${\alpha}$ indexes the type of interaction (_i-i_, _e-e_, _i-e_).

$V_{\alpha}(|\mathbf{r}_i - \mathbf{r}_j|)$ is the interaction potential for type , dependent on the distance $|\mathbf{r}_i - \mathbf{r}_j|$.

## The Free Electron Approximation

The `Free Electron Approximation` is a simplification where one makes the assumption that electrons are free particles in a system, meaning they experience no forces from `ions` in a `lattice`, or other `electrons`, and are treated as such.

Under the `Free Electron Approximation` we say electrons experience no forces as a result of the `periodic lattice`.
