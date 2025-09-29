# doc-physics

# Classical Mechanics

## Mechanics of a particle

The general trajectory of a classical partical in the three-dimensional space is given by

$$
\vec x(t)=(x(t),y(t),z(t))^T=
$$

where the coordinate functions $x\equiv x(t)$ depend on the time variable $t\in\mathbb R$.

We define the velocity of a classical particle as the derivative with respect to the time variable

$$
\vec v(t)=\dot{\vec x}(t)=\frac{\mathrm d}{\mathrm dt}\vec x(t)=(\dot x(t),\dot y(t),\dot z(t))^T
$$

The acceleration of a classical particle is given by

$$
\vec a(t)=\dot{\vec v}(t)=\frac{\mathrm d}{\mathrm dt}\vec v(t)=(\ddot x(t),\ddot y(t),\ddot z(t))^T
$$

In case of a constant acceleration $\vec a(t)=\vec a$, the coordinate function is given by

$$
\vec x(t)=\frac{1}{2}\vec a t^2+\vec v_0 t + \vec x_0
,\quad
\vec x_0=\vec x(t=0)
,\quad
\vec v_0=\dot{\vec x}(t=0)
$$

### Free fall
In case of a vacuum (no external forces but only gravitational force in the negative $z$-direction) the free fall of a classical particle is described by

$$
a_z=-g=-9,81\, m/s^2,\quad a_y=a_x=0,\quad \vec v_0=\vec 0, \quad \vec x_0=h\vec e_z
$$

and the trajectory of the particle

$$
z(t)=-\frac{1}{2}gt^2+h
$$

where $z=0$ for $t=\sqrt{2h/g}$ being the time duration of the fall with the maximum velocity given by $v_m=\sqrt{2hg}$.

### Projectile movement

### Circular movement

A uniform circular movement of a classical particle is described as follows

$$
v=\frac{\mathrm ds}{\mathrm dt}=R\frac{\mathrm d\varphi}{\mathrm dt}=R\omega,
$$

with the circular velocity $\omega$ and

$$
\begin{aligned}
\vec x(t)&=R(\cos\omega t,\sin\omega t)^T=R\vec e_r(t),
\\
\vec v(t)&=R\omega(-\sin\omega t,\cos\omega t)^T=R\omega\vec e_\varphi(t),
\\
\vec a(t)&=-\omega^2\vec x(t)=-R\omega^2\vec e_r(t)
\end{aligned}
$$

and the circular unit vectors

$$
\begin{aligned}
\vec e_r(t)&=(\cos\omega t,\sin\omega t)^T,\\
\vec e_\varphi(t)&=(-\sin\omega t,\cos\omega t)^T
\end{aligned}
$$

## Forces

The superposition priciple is given by

$$
\vec F=\sum_i \vec F_i
$$

with a force field defined by $\vec F\equiv \vec F(\vec x)$. A specific type of force fields are represented by central force fields depending of the radial distance only $\vec F(\vec x)=f(|\vec x|)\vec e_r$.

### Examples

#### Gravitational force
The gravitational force between two point like classical particles with masses $m_1,m_2$ is given by

$$
\vec F_G=-G\frac{m_1m_2}{|\vec x_1(t)-\vec x_2(t)|^3}(\vec x_1(t)-\vec x_2(t))
$$

#### Electrostatic force
The electrodynamical force (Coulomb force) between two point charges $q_1,q_2$ is given by

$$
\vec F_C=\frac{q_1q_2}{4\pi\varepsilon_0}
\frac{(\vec x_1(t)-\vec x_2(t))}
{|\vec x_1(t)-\vec x_2(t)|^3}
$$

## Newton's Axioms of classical mechanics

### 1. Axiom

Every body remains in the state of rest or in a uniform linear motion unless a force acts upon it.

The state of movement is represented as the momentum of a particle

$$
\vec p(t)=m\vec v(t)
$$

The momentum of a free particle is constant with respect to time $\dot{\vec p}=0$.

### 2. Axiom

The cause of a change in a body's momentum is a force acting on the particle

$$
\vec F(t)=\frac{\mathrm d\vec p}{\mathrm dt}
$$

which is given by

$$
\vec F(t)=m\frac{\mathrm d\vec v}{\mathrm dt}
+\vec v\frac{dm}{dt}
$$

### 3. Axiom

For two bodies that interact only with each other but not with other bodies, the force $\vec F_1$ on one body is equal and opposite to the force $\vec F_2$ on the other body, Newton's law "action = reactio" is given by

$$
\vec F_1=-\vec F_2
$$

such that for every action, there is an equal and opposite action.

# Thermodynamics



# Electrodynamics

## Lorenz force on a charged particle

The force on a charged particle with charge $q$ and mass $m$ is given by

$$
\vec F_L(\vec x)=q(\vec E(\vec x)+\dot{\vec x}\times\vec B(\vec x))
$$

## Maxwell's Equations

Maxwell's equations of electrodynamics are given by

$$
\begin{aligned}
\vec\nabla\cdot\vec E(\vec x)&=\frac{\rho(\vec x)}{\varepsilon_0}
\\
\vec\nabla\cdot\vec B(\vec x)&=0
\\
\vec\nabla\times\vec E(\vec x)&=-\frac{\partial \vec B(\vec x)}{\partial t}
\\
\vec\nabla\times\vec B(\vec x)&=\mu_0\left(\vec j(\vec x)+\varepsilon_0\frac{\partial \vec E(\vec x)}{\partial t}\right)
\end{aligned}
$$

### Gauß's law of electrostatics

The Gauß law of electrostatic is formulated as follows

$$
\int_{V} \vec\nabla\cdot\vec E(\vec x) d^3x
=
\int_{\partial V} \vec E(\vec x)d\vec \sigma
=
\frac{Q}{\varepsilon_0}
$$

and describes the fact that the electric charge $Q$ is the source and sink of the electrostatic fields.

### Gauß's law of magnetostatics

The Gauß law of magnetostatics is formulated as 

$$
\int_{V}\vec\nabla\cdot\vec B(\vec x)d^3x=
\int_{\partial V}\vec B(\vec x)d\vec\sigma=0
$$

and describes the fact that the magnetic field is free of sources and sinks and all magnetic field lines are closed.

### Faraday's induction law

The law of Faraday describes the dynamical creation of a magnetic field induced by a dynamic electric field

$$
\int_{\partial A}\vec E(\vec x)d\vec x=
\int_{A}\vec\nabla\times\vec E(\vec x)d\vec\sigma=
-\frac{\partial}{\partial t}\int_{A} \vec B(\vec x)d\vec\sigma
$$

# Quatum Mechanics

# Quantum Field Theory

# Particle Theory

# General Relativity

# Cosmology

# References
