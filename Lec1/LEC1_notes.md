# LEC1 

## Ordered set (有序集)

### Set 

- $\sqrt{2}$ is a irrational number and a gap in $\mathbb{Q}$
- Set: A group of element, maybe empty or nonempty

- Subset: A, B are set, $\forall a \in A, a \in B \Leftrightarrow A \subset B$

  *Proper subset* means $\exist b \in B, b \notin A$

- Equality: A, B are set, $A \subset B, B \subset A, A = B$

### Ordered Sets

- Ordered Sets : Sets with order
- Supremum and infimum: Supremum is the least number in the set we discussing, which is larger than all the elements in one of its subset.
- Least-upper-bound property: $\forall E \subset S, E \ne \empty, E$ is bounded above, then $sup\space E \in S$

### Remarks

- The way of proving the $\sqrt{2}$ is a gap reminds me the **Newton method(牛顿法)** , 
    $$
    \text{Guess the result is }x_0 \text{ first, then:}\\
    x_{n+1} = {x_{n}^2 + 2 \over 2x_{n}} \\
    x_{n+1}- x_n = {2 - x_n^2 \over 2x_n} \\
    x_n^2 > 2 \Rightarrow x_{n+1}- x_n < 0 \\
    x_n^2 < 2 \Rightarrow x_{n+1}- x_n > 0
    $$
    

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

  - a) $\text{If } x \in R, y\in R , x>0, \exist n \in \mathbb{Z}, nx > y:$ By contradiction, suppose

  $$
  \exist y, \exist n \in \mathbb{Z}, nx \leq y \Rightarrow y = sup(nx) \\
  y-x < nx \Rightarrow y < (n+1)x, (n+1) \in \mathbb{Z},\\
  \text{contradiction works, proof done.}
  $$
  
  - b) Proved by a),
  $$
  n\in\mathbb{Z^+}, y-x > 0 \Rightarrow n(y-x)>1 \\
  N, X\in\mathbb{Z^+}, NX > x \Rightarrow nNX > nx\\
  M\in\mathbb{Z},nx>M \Rightarrow -nx < -M\leq|M| \\
  m_1, m_2, m\in\mathbb{Z^+},-m_1<nx<m_2 \Rightarrow m-1 \leq nx < m\\
  nx<m\leq1+nx<ny \Rightarrow x < {n \over m} < y
  $$
  
- $x, y \in \mathbb{R}, \forall x > 0, \exist y > 0, y = \sqrt[n]{x}, y$ is the only positive solution

    Proof by contradiction and binomial theorem(二项式定理)， the only thing we got to know is every subset in E have a upper bound, then according to 1.19 it would have a supremum. If $(Sup\space E)^n$ is neither less nor larger than x, then we will get it. 

- Real numbers and Decimals

### The complex fields

- Quite similar, nothing special to talk about

### remarks

- **Contradiction and induction(反证和归纳)** are useful method for proof

- The definition of field is quite similar to the definition of **vector space**, enclosure of addition and multiplication.
- The proof of existence of $\sqrt[n]{x}$ is quite similar to **Newton method** as well, we are going to prove both side would converge to the real result.
- The set of real numbers are with least-upper-bound-property, which means it has **no gap**, to some extent we will say, **continuous**.
