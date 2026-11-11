## 1. Definition

Let $X$ and $Y$ be two nonempty sets. A mapping (or function) $f$ from $X$ to $Y$ is a rule that assigns to each element $x \in X$ exactly one element $y \in Y$.

$$
f: X \longrightarrow Y
$$

$$
x \mapsto y = f(x)
$$

Here:

- $X$ is the domain,
- $Y$ is the codomain,
- $f(x)$ is the image of $x$ under $f$.

## 2. Image and preimage

Given a mapping $f: X \to Y$:

- if $A \subseteq Y$, then $f(A) = \{f(x) \mid x \in A\}$ is the image of $A$;
- if $B \subseteq X$, then $f^{-1}(B) = \{x \in X \mid f(x) \in B\}$ is the preimage of $B$.

### 2.1. Properties of image and preimage

For all subsets:

1. $f(A \cup B) = f(A) \cup f(B)$
2. $f(A \cap B) \subseteq f(A) \cap f(B)$, with equality when $f$ is injective
3. $f^{-1}(A \cup B) = f^{-1}(A) \cup f^{-1}(B)$
4. $f^{-1}(A \cap B) = f^{-1}(A) \cap f^{-1}(B)$
5. $f^{-1}(A \setminus B) = f^{-1}(A) \setminus f^{-1}(B)$

## 3. Injective, surjective, and bijective mappings

### 3.1. Injective mapping

A mapping $f$ is injective if

$$
x_1 \neq x_2 \implies f(x_1) \neq f(x_2)
$$

Equivalently,

$$
f(x_1) = f(x_2) \implies x_1 = x_2
$$

for all $x_1, x_2 \in X$.

This means that every element of $Y$ has at most one preimage in $X$.

### 3.2. Surjective mapping

A mapping $f$ is surjective if for every $y \in Y$ there exists at least one $x \in X$ such that $y = f(x)$.

### 3.3. Bijective mapping

A mapping is bijective if it is both injective and surjective.

Equivalently, for every $y \in Y$, the equation $y = f(x)$ has a unique solution in $X$.

A bijection is a one-to-one correspondence.

## 4. Composition of mappings and inverse mapping

Two mappings $f$ and $g$ are equal if $f(x) = g(x)$ for all $x$ in the domain.

### 4.1. Composition of mappings

Let $f: X \to Y$ and $g: Y \to Z$. The composition $g \circ f$ is a mapping from $X$ to $Z$ defined by

$$
(g \circ f)(x) = g(f(x)), \quad \forall x \in X
$$

Important points:

- the composition is only defined when the codomain of the first mapping matches the domain of the second;
- composition is generally not commutative;
- if each component is injective, surjective, or bijective, then the composition has the corresponding property.

### 4.2. Inverse mapping

Let $f: X \to Y$. If there exists a mapping $g: Y \to X$ such that

$$
(g \circ f)(x) = x, \quad \forall x \in X
$$

and

$$
(f \circ g)(y) = y, \quad \forall y \in Y,
$$

then $g$ is called the inverse mapping of $f$, denoted by $f^{-1}$.

An inverse exists only for bijections.
