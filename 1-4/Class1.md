# 2018-1-4

## Appendix

<hr />

* Discrete math basic

  * Mathematical Statement

  * Set Notation

* Compound Statement

  * Statement

  * Logical equivalent

* Quantified Statement

  * Predicates

  * Quantifier

<hr />

## Discrete math basic

### Mathematical Statement

**1. Universal Statement** : A certain property is true for all elements in a set **(ALL,Every,For each)**

**2. Conditional Statement**: If one thing is true then some other things also has to be true.**(IF..Then..)**

**3. Existential Statement**: There is at least one thing for which the property is true.**(There is an ..)**

**4. Universal Conditional Statement** : A Statement can be write in both Universal or Conditional.**(All dogs are mammal = For all animal A, if A is a dog, then A is a mammal)**

**5. Universal Existential Statement** : A Statement can be write in both Universal or Existential.**(All Pots have lids = For all pots P, there is a a lid L such that L is a lid for P)**.

**6. Existential Universal Statement**: A Statement that is Existential because its first part asserts that a certain object exists and is universal because its second part says that the object satisfies a certain property for all things of a certain kind.**(There is a person in my class who is as least as old as every person in my class = This is a person p in my class with the property that for every person q in my class, p is at least as old as q.)**

### Set Notation

**1. Elements & Set**

   $x \in S$ and $x \notin S$ : x is or isn't a element in set S.

**2. Set and Set**

   $A \subseteq B$ : A is a subset of B, which means For all elements x, if $x\in A$ then $x\in B$.

   $A \not\subseteq B$: There is at least one element x such that $x\in A$ and $x\notin B$.

   $A \subsetneq B$: A is a proper subset of B, which means all element in A is in B but there are at least one element in B but not in A.

   $(a,b)$: a and b are the Ordered Pair, which means $(a,b) = (c,d)$ if and only if $a=c ,b=d$

<hr/>

##Compound Statement

### Statement

**1. Defination:** Statement is a sentence that is true or false but not both.

**2. Compound Statement（logical operator)**

$P \wedge Q$ : Conjunction of P and Q, which mean P but Q or Neither P nor Q or P and Q

$P \vee Q$: Disjunction of P and Q. The Statement is true when either P or Q is true or P and Q are both true.

$\sim P$: Negate of P, which mean not P.

Order of operations for logical operator:

$\sim$ , $\wedge \& \vee$(if both, parentheses maybe needed), $\longrightarrow \& \longleftrightarrow$.

**3. Conditional Statement**: If p and q are Statement variable, the Conditional of q by p is "if p then q" or "p implies q" and is denoted $p \longrightarrow q$. It's false when p is true and q is false.

| p | q   | $p \longrightarrow q$    |
| :------------- | :-------------: |:-------------: |
| T       | T      |T      |
| T       | F      |F     |
| F       | T      |T      |
| F       | F      |T      |

**_Example: Suppose "If you come tomorrow, you will get the job" is True, then "if you don't come, you MAYBE get the job" is true.But if "If you come tomorrow, you will not get the job" is definitely False_**

**4. Converse of Conditional Statement**: If $p \longrightarrow q$, then its converse Statement is $q \longrightarrow p$.


**5. Inverse of Conditional Statement**:If $p \longrightarrow q$, then its inverse Statement is $\sim p \longrightarrow \sim q$.

**6. Only if and Bi-conditional Statement**

"p only if q" is logically equivalent to "if p than q".

$p \longleftrightarrow  q$: This is a Biconditional Statement which mean $(p \longrightarrow q) \wedge (q \longrightarrow p)$

**7. Tautology Statement**

$t$: means the Compound Statement is always true.

**8. Contradictory Statement**

$c$: means the Compound Statement is always false.


### logical equivalent

**1. Defination**

$P \equiv Q$: Statement P and Statement Q are logically equivalence, which means the truth table of P and Q are same.


**2. Summary of logical equivalences**

Communicative Law:

$p \wedge q \equiv q \wedge p, p \vee q \equiv p \vee q$.

Associate Law:

$(p \wedge q )\wedge r \equiv p \wedge (q \wedge r),(p \vee q )\vee r \equiv p \vee (q \vee r)$

Distribute Law:

$p \vee (q \wedge r) \equiv (p \vee q) \wedge (p \vee r), p \wedge (q \vee r) \equiv (p \wedge q) \vee (p \wedge r)$

Negate law:

$p \vee (\sim p) \equiv t, p \wedge (\sim p) \equiv c$

Double Negate Law:

$\sim(\sim p) \equiv p$

De Morgan's Law:

$\sim(p \wedge q) \equiv \sim p \vee \sim q,\sim(p \vee q) \equiv \sim p \wedge \sim q$

Absorption Law:

$p \vee (p \wedge q) \equiv p,p \wedge (p \vee q)$

**3. Summary logical equivalences involved Conditional Statement**

$p \longrightarrow q \equiv \sim p \vee \ q$

$\sim (p \longrightarrow q) \equiv p \wedge \sim q$

$p \longrightarrow q \equiv \sim q \longrightarrow \sim p$ : This is called Contrapositive of a Statement

<hr />

## Quantified Statement

### Predicates
**1. Defination**

A predicate is a sentence that contains a finite number of variables and becomes a statement when specific values are substituted for the variables. the domain of a predicate variable is the set of all values that maybe substituted in place of the variable.

$\{ x \in D | P(x)\}$

$P(x)$ is the predicate, $x$ is in the Domain of $D$, if specify exact number, $P(x)$ becomes a statement.

| Symbol | Domain    |
| :------------- | :------------- |
| Z       | Set of all Integer       |
| R       | Set of all Real number       |
| Q       | Set of all rational numbers       |

### Quantifier
**1. Universal Quantifier**

**Defination**

When the domain of variable in predicate is Universal, then the quantifier is a Universal Quantifier.

**Prove**

The statement "$\forall x \in D,Q(x)$" is defined to be `true` if and only if $Q(x)$ is true for every x in D; it is defined to be `false` for finding a counterexample in domain.

**2. Existential Quantifier**

**Defination**

When the domain of variable in predicate is existential, then the quantifier is a existential Quantifier.

**prove**

The statement "$\exists x \in D,Q(x)$" is defined to be `true` if and only if $Q(x)$ is true for at least one x in D; it is defined to be `false` if and only if $Q(x)$ is false for every x in D;.
