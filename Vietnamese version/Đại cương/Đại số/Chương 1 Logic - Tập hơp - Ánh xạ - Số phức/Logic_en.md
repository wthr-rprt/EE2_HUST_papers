# Logic

This is an English translation of the original Vietnamese note. The Vietnamese note remains unchanged in the vault.

## 1. Mathematical propositions and truth values

A mathematical proposition is a statement that is either true or false, with no ambiguity. If the information is insufficient to decide, it is called a hypothesis, often denoted by symbols such as $A$, $B$, $C$, $D$, and so on.

The truth value of a proposition is its truth or falsity. This is similar to binary logic or bits, usually written as $V(A)$, $V(B)$, etc.

## 2. Propositional operations

Propositional logic uses operations analogous to digital logic gates.

### Negation

The negation of $A$, denoted by $\overline{A}$, is true when $A$ is false and false when $A$ is true.

| $A$ | $\overline{A}$ |
| --- | --------------- |
| 1   | 0               |
| 0   | 1               |

### Conjunction (AND)

$A \land B$ is true only when both $A$ and $B$ are true.

| $A$ | $B$ | $A \land B$ |
| --- | --- | ----------- |
| 1   | 1   | 1           |
| 1   | 0   | 0           |
| 0   | 1   | 0           |
| 0   | 0   | 0           |

### Disjunction (OR)

$A \lor B$ is true when at least one of $A$ or $B$ is true.

| $A$ | $B$ | $A \lor B$ |
| --- | --- | ---------- |
| 1   | 1   | 1          |
| 1   | 0   | 1          |
| 0   | 1   | 1          |
| 0   | 0   | 0          |

### Implication

$A \rightarrow B$ means “if $A$, then $B$”.

| $A$ | $B$ | $A \rightarrow B$ |
| --- | --- | ----------------- |
| 1   | 1   | 1                 |
| 1   | 0   | 0                 |
| 0   | 1   | 1                 |
| 0   | 0   | 1                 |

### Equivalence

$A \leftrightarrow B$ means “$A$ is equivalent to $B$”.

| $A$ | $B$ | $A \leftrightarrow B$ |
| --- | --- | --------------------- |
| 1   | 1   | 1                     |
| 1   | 0   | 0                     |
| 0   | 1   | 0                     |
| 0   | 0   | 1                     |

## 3. Expressions and propositional variables — logical equivalence

In essence, a propositional expression is an expression built from propositions, and logical equivalence is analogous to equality. A formula that is always true is called a tautology, while a formula that is always false is called a contradiction.

The basic logical properties include:

- double negation
- commutativity
- associativity
- distributivity
- implication as disjunction with negation
- equivalence as two-way implication
- idempotence
- De Morgan’s laws

### 3.1. Predicate functions

A predicate is a proposition depending on a variable, such as a statement involving $x$.

### 3.2. Universal and existential quantifiers

- For all: $\forall$
- There exists: $\exists$

These quantifiers are essential in mathematical reasoning and formal proofs.
