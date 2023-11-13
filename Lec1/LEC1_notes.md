# LEC1 

## Ordered set (有序集)

### Set 

- Set: A group of element, maybe empty or nonempty

- Subset: A, B are set, $\forall a \in A, a \in B \Leftrightarrow A \subset B$

  *Proper subset* means $\exist b \in B, b \notin A$

- Equality: A, B are set, $A \subset B, B \subset A, A = B$

### Ordered Sets

- Ordered Sets : Sets with order
- Supremum and infimum: Supremum is the least number in the set we discussing, which is larger than all the elements in one of its subset.
- Least-upper-bound property: $\forall E \subset S, E \ne \empty, E$ is bounded above, then $sup\space E \in S$

### Remarks

- Ordered sets is similar to the definition like metric space or norm space.
- All the stuff talked above try to remind us that there exists many **gaps** in the ration number set Q.

## Fields（域）

- Fields: fields is a set of number with two operations, addition and multiplication.

### Fields

#### addition

- Five basic properties: 1. Close; 2. Commutative; 3. Associative; 4. Identity(0); 5. Inversible

#### multiplication

- Five basic properties: 1. Close; 2. Commutative; 3. Associative; 4. Identity(1); 5. Inversible

### The real fields

- Rational field is a subfield of real field.

- Always rational numbers between two real numbers:

  - a) $\text{If } x \in R, y\in R , x>0, \exist n \in \mathbb{Z}, nx > y:$

  $$
  \begin{split}
  &\text{By contradiction, suppose } \exist y, \exist n \in \mathbb{Z}, nx \leq y \Rightarrow y = sup(nx) \\
  &y-x < nx \Rightarrow y < (n+1)x, (n+1) \in \mathbb{Z},\text{proof done.}
  \end{split}
  $$

  - b)

- Real numbers and Decimals

### The complex fields



### remarks

- The definition of field is quite similar to the definition of **vector space**, enclosure of addition and multiplication.
- The set of real numbers are with least-upper-bound-property, which means it has **no gap**, to some extent we will say, **continuous**.
