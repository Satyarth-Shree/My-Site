---
title: Home
---

# Del Operator

## Representation

It is represented as $\vec{\nabla}$ .

$$
\vec{\nabla} = \hat{i}\frac{\partial}{\partial x} + \hat{j}\frac{\partial}{\partial y} + \hat{k}\frac{\partial}{\partial z}
$$
## Concept 

If an operator applied over a function generates the same function then that function is known as an eigen function and the value multiplied with it is known as eigen value.

### Example No.1 

$$
\frac{d(e^{-2x})}{dx} = -2e^{-2x}
$$
Here $e^{-2x}$ is an eigen function and $-2$ is an eigen value. Here we have applied differential operator over this function.

### Example No.2

$$
\frac{d(\cos x)}{dx}= -\sin x
$$
Here $\cos x$ is not an eigen function because when we applied an operator over it then the same function was not generated again.


# Gradient of a Scalar Function

## Representation

Represented as $\text{Grade} \, \phi$ or $\vec{\nabla} \phi$ .

## Concept 

1. Gradient is possible with a scalar only.
$$
\vec{\nabla} = \left(\hat{i}\frac{\partial}{\partial x} + \hat{j}\frac{\partial}{\partial y} + \hat{k}\frac{\partial}{\partial z} \right)\phi
$$
$\phi$ represents a scalar function.
2. Result of a gradient is always a vector
3. Gradient tells us the behaviour of the function with respect to the position of coordinates.

## Questions

### Question No.1
$$
\begin{aligned}
 \text{Calculate the gradient of} & \text{the scalar function } \phi \text{ where} \\
& \phi = x^2y \, - 3xz^3
\end{aligned}
$$

### Question No.2

$$
\text{Calculate gradient of} \; r^3 \; \text{where r is the position vector}
$$

# Divergence of a Vector Field

## Representation

It is represented as $\vec{\nabla} \cdot \vec{A}$  or $\text{Div} \vec{A}$ .

## Concept

$$
\begin{aligned}
\text{Let's suppose} \; & \vec{A} = \hat{i}A_x \, + \hat{j}A_y + \hat{k}A_z, \; \text{then divergence of} \; \vec{A} \; \text{will be} \\
& \vec{\nabla} \cdot \vec{A}  = \left( \hat{i}\frac{\partial}{\partial x} + \hat{j}\frac{\partial}{\partial y} + \hat{k}\frac{\partial}{\partial z}  \right) \cdot \left(\hat{i}A_x + \hat{j}A_y + \hat{k}A_z \right) \\
& \phantom{\vec{\nabla} \cdot \vec{A}} = \frac{\partial A_x}{\partial x} + \frac{\partial A_y}{\partial y} + \frac{\partial A_z}{\partial z}
\end{aligned} 
$$

1. Divergence is possible with a vector only.
2. Divergence of a vector is always a scalar.
3. If divergence of a vector field is zero then the field is said to be solenoidal in nature. 
4. If divergence has a positive value then the field acts like a source.
5. If divergence has a negative value then the field acts like a sink.

## Questions

### Question No.1

$$
\text{Calculate} \; \vec{\nabla} \cdot \left(r^{3n} \; \vec{r} \right), \, \text{where} \; \vec{r} \; \text{is the position vector.}
$$

### Question No.2

$$
\begin{aligned}

\text{Check whether the} \; & \text{given vector field is solenoidal in nature or not.} \\
& \vec{A} = x^2y \, \hat{i} \; - \;yx^2 \, \hat{j} \; + \; 3xz^5 \, \hat{k}

\end{aligned}
$$

# Curl of a Vector Field

## Representation

Curl of a vector field is represented as $\vec{\nabla} \times \vec{A}$ .

## Concept

$$
\begin{aligned}

\text{Let's suppose} & \, \vec{A} = \hat{i}A_x + \hat{j}A_y + \hat{k}A_z, \,\text{then curl of} \, \vec{A} \, \text{will be} \\
& \vec{\nabla} \times \vec{A} = 

\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
A_x & A_y & A_z 
\end{vmatrix} \\

& \phantom{\vec{\nabla} \times \vec{A}} = \hat{i} \left(\frac{\partial A_z}{\partial y} - \frac{\partial A_y}{\partial z} \right) \, - \, \hat{j} \left(\frac{\partial A_z}{\partial x} - \frac{\partial A_x}{\partial z} \right) \, + \, \hat{k} \left(\frac{\partial A_y}{\partial x} - \frac{\partial A_x}{\partial y} \right)

\end{aligned}
$$

1. Curl is possible with a vector only.
2. Curl of a vector is always a vector.
3. If curl of a vector field is zero then the field is said to be irrotational or conservative in nature.
4. If curl of a vector field is not equal to zero then the field is said to be rotational or non conservative in nature.

## Questions

### Question No.1

$$
\text{Calculate} \; \vec{\nabla} \times \left(\frac{\vec{r}}{r^n} \right), \; \text{where} \; \vec{r} \; \text{a position vector.}
$$

### Question No.2

$$
\begin{aligned}

\text{Check whether the} \; & \text{given vector field is conservative or non conservative in nature.} \\
& \vec{A} = x^2y \, \hat{i} \; - \;yx^2 \, \hat{j} \; + \; 3xz^5 \, \hat{k}

\end{aligned}
$$

# Identities

## Identity No.1

Curl of gradient of any scalar function is always zero. Mathematically this identity can be expressed as:
$$
\vec{\nabla} \times \left(\vec{\nabla} \phi \right) = 0
$$

## Identity No.2

Divergence of curl of any vector is always zero. Mathematically this identity can be expressed as:
$$
\vec{\nabla} \cdot \left(\vec{\nabla} \times \vec{A} \right) = 0
$$

# Gauss Divergence Theorem

## Theorem

$$
\int_{v} \left(\vec{\nabla} \cdot \vec{A} \right)dV = \oint_{s} \vec{A} \cdot d\vec{s}
$$

## Concept

This theorem is sued to convert volume integral into surface integral and vice - a - versa.

# Stoke's Theorem

## Theorem

$$
\oint_{s} \left(\vec{\nabla} \times \vec{A} \right) \cdot d\vec{s} = \oint \vec{A} \cdot d\vec{l}
$$

## Concept

This theorem is used to convert volume integral to line integral or vice - a - versa.

# Gauss Law In Electrostatics

## Definition

It states that net electric flux through any closed surface is always equal to $\frac{1}{\epsilon_0}$ times the net charge enclosed by that surface.

## Mathematical Representation

$$
\oint_{S} \vec{E} \cdot d\vec{s} = \frac{\text{q}}{\epsilon_0}
$$

# Gauss Law in Magnetostatics

## Definition

It states that net magnetic flux through any closed surface is always zero.

## Mathematical Representation

$$
\oint_{S} \vec{B} \cdot d\vec{s} = 0
$$

# Faraday's Law of Electromagnetic Induction

Refer to [[maths/index.md]] 
