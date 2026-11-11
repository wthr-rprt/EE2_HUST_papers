- Complex numbers form a field in algebraic structure
### 1. Definition and structure

The set of complex numbers $\mathbb{C}$ is an extension field of $\mathbb{R}$, constructed from the set $\mathbb{R} \times \mathbb{R}$ with addition and multiplication defined in a special way.

Let

$$
i = (0,1)
$$

Then

$$
i^2 = -1
$$

This is the key property that makes the complex numbers algebraically closed.

> Fundamental theorem of algebra: every polynomial of degree $n$ in one variable has $n$ roots in the complex field.

### 2. Algebraic (canonical) form

A complex number is written as

$$
z = a + bi \quad (a,b \in \mathbb{R})
$$

The number has two parts:

- real part: $\operatorname{Re}(z) = a$
- imaginary part: $\operatorname{Im}(z) = b$

The complex conjugate of $z$ is

$$
\bar{z} = a - bi
$$

### 3. Trigonometric form and argument

The modulus of a complex number is

$$
|z| = \sqrt{a^2 + b^2}
$$

The argument of $z$ is the angle $\varphi$ such that

$$
z = r(\cos\varphi + i\sin\varphi)
$$

where:

- $r = |z|$
- $\varphi = \arg(z)$

Also,

$$
\arg(z) = \Arg(z) + 2k\pi, \quad k \in \mathbb{Z}
$$

### 4. Operations on complex numbers and conjugates

#### 4.1. Complex numbers

Let

$$
z_1 = a_1 + b_1 i, \quad z_2 = a_2 + b_2 i
$$

Then:

- addition/subtraction:

$$
z_1 \pm z_2 = (a_1 \pm a_2) + (b_1 \pm b_2)i
$$

- multiplication:

$$
z_1 z_2 = (a_1a_2 - b_1b_2) + (a_1b_2 + a_2b_1)i
$$

and in polar form,

$$
z_1 z_2 = r_1 r_2\big(\cos(\varphi_1 + \varphi_2) + i\sin(\varphi_1 + \varphi_2)\big)
$$

- division:

$$
\frac{z_1}{z_2} = \frac{z_1\overline{z_2}}{z_2\overline{z_2}} = \frac{(a_1a_2 + b_1b_2) + (-a_1b_2 + a_2b_1)i}{a^2 + b^2}, \quad z_2 \neq 0
$$

and in polar form,

$$
\frac{z_1}{z_2} = \frac{r_1}{r_2}\big(\cos(\varphi_1 - \varphi_2) + i\sin(\varphi_1 - \varphi_2)\big)
$$

- powers:

$$
z^n = r^n(\cos n\varphi + i\sin n\varphi)
$$

If $r=1$, this reduces to De Moivre’s formula:

$$
(\cos\varphi + i\sin\varphi)^n = \cos(n\varphi) + i\sin(n\varphi)
$$

- Euler’s formula:

$$
e^{i\varphi} = \cos\varphi + i\sin\varphi
$$

In particular,

$$
e^{i\pi} = -1
$$

- nth roots of a complex number:

$$
z_k = \sqrt[n]{r}\left[\cos\left(\frac{\varphi + 2k\pi}{n}\right) + i\sin\left(\frac{\varphi + 2k\pi}{n}\right)\right], \quad k = 0,1,\dots,n-1
$$

The $n$ roots of a complex number form a regular polygon on the complex plane.

#### 4.2. Complex conjugates

Let $z = a + bi$ and $\overline{z} = a - bi$.

Then:

- $z + \overline{z} = 2a = 2\operatorname{Re}(z) \in \mathbb{R}$
- $z\overline{z} = a^2 + b^2 = |z|^2 = |\overline{z}|^2 \in \mathbb{R}$
- $z \in \mathbb{R} \iff z - \overline{z} = 0$
- $\operatorname{Re}(z) = 0 \iff z + \overline{z} = 0$
- $\overline{z} = r(\cos(-\varphi) + i\sin(-\varphi))$
- conjugation preserves addition, subtraction, multiplication, and division
- conjugating twice returns the original number
- $\frac{1}{z} = \frac{\overline{z}}{|z|^2}$
