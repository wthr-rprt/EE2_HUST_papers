## 0. Binary operations

Let $X \neq \emptyset$ be a set. A binary operation on $X$, denoted by $*$, is a rule that assigns to each pair $(x,y) \in X \times X$ a unique element of $X$.

$$
*: X^2 \to X
$$

$$
(x,y) \mapsto x*y
$$

The set $X$ together with a binary operation is called a binary algebra, denoted by $(X,*)$.

Depending on the set, the operation may be addition, multiplication, composition, etc.

### Some properties

1. A binary operation $*$ is associative if

$$
(a*b)*c = a*(b*c), \quad \forall a,b,c \in X
$$

2. A binary operation $*$ is commutative if

$$
a*b = b*a, \quad \forall a,b \in X
$$

3. An element $e \in X$ is called an identity element if

$$
a*e = e*a = a, \quad \forall a \in X
$$

4. If $X$ has an identity $e$ and $a \in X$, then an element $b \in X$ is called an inverse of $a$ if

$$
a*b = b*a = e
$$

### Notation convention

For convenience, binary operations are often called addition or multiplication even outside numeric sets.

- If the operation is addition, then the identity is denoted by $\theta$ and the inverse of $x$ is $-x$.
- If the operation is multiplication, then the identity is denoted by $1$ and the inverse is $x^{-1}$.

## Groups, rings, and fields

### 1. Groups

Let $X \neq \emptyset$ with an operation $+$, and let $(X,+)$ be a binary algebra. It is called a group if the following hold:

1. associativity:
   $$
   (a+b)+c = a+(b+c), \quad \forall a,b,c \in X
   $$
2. existence of identity $\theta \in X$ such that:
   $$
   x + \theta = \theta + x = x, \quad \forall x \in X
   $$
3. for every $x \in X$, there exists an inverse $-x \in X$ such that:
   $$
   x + (-x) = (-x) + x = \theta
   $$

If, in addition, the operation is commutative, then the group is called an abelian group.

### 2. Rings

Let $X \neq \emptyset$ be equipped with two operations, $+$ and $\cdot$. Then $(X,+,\cdot)$ is a ring if:

1. $(X,+)$ is an abelian group;
2. multiplication is associative:
   $$
   (a\cdot b)\cdot c = a\cdot (b\cdot c), \quad \forall a,b,c\in X
   $$
3. multiplication is distributive with respect to addition:
   $$
   a(b+c) = ab + ac
   $$
   and
   $$
   (b+c)a = ba + ca, \quad \forall a,b,c \in X
   $$

If multiplication is also commutative, the ring is called a commutative ring. If multiplication has an identity, the ring is called a ring with identity.

### 3. Fields

Let $X$ be a nonempty set with two operations, $+$ and $\cdot$. Then $(X,+,\cdot)$ is a field if:

1. $(X,+,\cdot)$ is a commutative ring with identity $1$;
2. for every nonzero $x \in X$, there exists an inverse $x^{-1}$ such that:

$$
x\cdot x^{-1} = x^{-1} \cdot x = 1
$$

Thus, a field is a set in which addition, subtraction, multiplication, and division by nonzero elements are all well-defined and behave in the usual way.
