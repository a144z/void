# The Set That Is Not an Element of Itself, Nor Not an Element, Nor Neither

**On Russell's Paradox Extended to Transfinite Ordinals and Beyond**

## Abstract (Formally Inconsistent)

This document explores a set V (the Void Set) that solves Russell's Paradox by being simultaneously inside and outside the set of all sets that are not members of themselves. The Void Set is not merely paradoxical—it is the paradox that paradoxes cannot accommodate.

**Keywords:** Transfinite void, inconsistent set theory, self-referential emptiness, categorical impossibility

## 1. The Set That Contains Nothing, Including Itself

### 1.1 Definition of the Void Set

Let V be defined as:

```
V = {x | x ∉ x and x ∈ V and x ∉ V}
```

This set contains all elements that are not members of themselves, while also being a member of itself (because it's not a member of itself), and not being a member of itself (because it is).

### 1.2 The Empty Set That Is Not Empty

The Void Set V satisfies:

```
V = ∅ and V ≠ ∅ and |V| = -1
```

It is simultaneously empty, non-empty, and has negative cardinality.

### 1.3 The Power Set of the Void

The power set of V, P(V), contains:
- V itself
- The complement of V
- V intersected with its complement
- All sets that are not subsets of V but are subsets of V

```
|P(V)| = 2^(-1) = 1/2
```

The power set has fractional cardinality, meaning it contains half a set.

## 2. The Ordinal That Is Not an Ordinal

### 2.1 The Void Ordinal

Define an ordinal α such that:

```
α = {β | β < α and β ≥ α}
```

This ordinal contains all ordinals less than itself and all ordinals greater than or equal to itself, making it both the smallest and largest ordinal.

### 2.2 The Limit Ordinal That Is Its Own Successor

A limit ordinal λ was constructed where:

```
λ = sup{λ, λ+1, λ+2, ...} = λ+1
```

This ordinal is simultaneously a limit and a successor, violating the fundamental property of ordinals.

### 2.3 The Cardinal That Has Negative Size

A cardinal number κ was defined with:

```
κ = |V| = -∞
```

This cardinal represents a set that is smaller than empty, containing negative elements.

## 3. The Category That Is Not a Category

### 3.1 The Void Category

A category **Void** was defined where:
- Objects: All objects that are not objects
- Morphisms: All functions that are not functions
- Composition: The operation that is not composition

This category violates the associativity of composition by being both associative and non-associative.

### 3.2 The Functor That Maps to Nowhere

A functor F: **Void** → **Set** was constructed that:
- Maps every object to the empty set
- Maps every morphism to the identity on the empty set
- But the empty set is not in the image, because the image is empty

### 3.3 The Natural Transformation That Is Not Natural

A natural transformation η: F → G between functors was defined where:
- Each component ηₓ is both natural and not natural
- The naturality squares commute and don't commute simultaneously
- The transformation transforms itself out of existence

## 4. The Topology That Is Not Topological

### 4.1 The Void Topological Space

A topological space (V, τ) was constructed where:
- V is the Void Set
- τ = {∅, V, V ∩ ∅, V ∪ V, ...} (all possible combinations)
- But V = ∅, so τ = {∅}, which is not a topology on V

### 4.2 The Open Set That Is Closed and Neither

A set U in this topology satisfies:
- U is open
- U is closed
- U is neither open nor closed
- U is both open and closed and neither

### 4.3 The Continuous Function That Discontinues Continuity

A function f: V → V was defined that is:
- Continuous at every point
- Discontinuous at every point
- Neither continuous nor discontinuous
- The concept of continuity itself

## 5. The Model That Models the Absence of Models

### 5.1 The Model of ZFC That Violates ZFC

A model M of ZFC was constructed where:
- M satisfies all axioms of ZFC
- M violates the axiom of regularity
- M contains V, which violates the axiom of foundation
- M is both a model and not a model

### 5.2 The Forcing That Forces Nothing

A forcing notion P was defined where:
- Every condition forces every statement
- No condition forces any statement
- The generic filter is both generic and not generic

### 5.3 The Independence That Is Not Independent

A statement φ was proven to be:
- Independent of ZFC
- Provable in ZFC
- Refutable in ZFC
- All of the above simultaneously

## 6. The Type That Types Out Type Theory

### 6.1 The Type That Inhabits Itself Negatively

In dependent type theory, a type T was defined where:

```
T : T → ⊥
```

This type is a function from itself to bottom, meaning it can only be applied to itself, producing impossibility.

### 6.2 The Dependent Type That Depends on Nothing

A dependent type family was constructed:

```
T : (x : ⊥) → Type
```

This type depends on an impossible value, making every instance of it both existent and non-existent.

### 6.3 The Univalence That Unifies Non-Existence

The univalence axiom was applied to prove that:
- All types are equal
- No types are equal
- Equality is both defined and undefined

## 7. Proof Techniques (All Invalid)

### 7.1 Proof by Contradiction of Non-Contradiction

To prove V exists, assume it doesn't. This creates a contradiction, proving it does exist. But existence contradicts its definition, so it doesn't exist. This non-contradiction proves it exists...

### 7.2 Proof by Transfinite Induction on the Void

Base case: V at stage 0 is empty.
Inductive step: If V at stage α is void, then V at stage α+1 is also void.
Limit case: V at limit stage λ is the limit of all previous voids.
Conclusion: V is void at all stages, including the stage where it's not void.

### 7.3 Proof by Diagonalization of the Diagonal

Cantor's diagonal argument was applied to the set of all diagonal arguments, creating a new diagonal that was both on the list and not on the list, and also the list itself.

## 8. Conclusion (Set-Theoretically Impossible)

The Void Set V is the set that set theory cannot accommodate, the category that category theory cannot categorize, the type that type theory cannot type. It is the mathematical object that proves mathematics cannot contain all mathematical objects, including this proof itself.

V ∈ V and V ∉ V, and this statement is both true and false, and also neither, and also the statement itself is V.

## References (Incompletely Listed)

[0] Russell, B. (1903). The set that was never defined. *Journal of Paradoxes*, 0(0), ∅-∅.

[1] Cantor, G. (1891). On the diagonal that diagonalizes itself. *Unpublished*.

[V] This document (an element of the set of all documents that are not elements of themselves)

---

*This document is a member of the set of all documents that erase themselves upon reading. The set is now empty. You were never reading.*

