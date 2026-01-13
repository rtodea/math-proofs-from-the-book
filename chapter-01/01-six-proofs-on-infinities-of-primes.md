# Are prime numbers infinite? Here are six different proofs that they are.

## Proof 1: Euclid's Proof

Assume there are finitely many primes:

> \( p_1, p_2, \ldots, p_n \)

Consider the number \(N\) composite:

> \( N = p_1 \times p_2 \times \ldots \times p_n + 1 \).

This number \( N \) is not divisible by any of the primes \( p_1, p_2, \ldots, p_n \) (it leaves a remainder of 1 when divided by any of them). 

Therefore, \( N \) must either be prime itself or have prime factors not in our original list.

This contradicts our assumption that we had listed all primes. Hence, there are infinitely many primes.

## Strategy of Proof 1

We have a proof by contradiction.

Why does it work?

It works because of how math is structured: if we assume something and derive a contradiction, then our assumption must be false.

But what guarantees that the chain of reasoning we used to derive the contradiction is valid?

The guarantee comes from the axioms and rules of inference that underpin mathematics. These foundational principles ensure that if we start with true statements (or assumptions) and apply valid logical steps, the conclusions we reach will also be true.

Some relevant axioms and rules of inference include:

1. **Axioms of Arithmetic**: These include properties of numbers, such as the existence of prime numbers and the fundamental theorem of arithmetic (every integer greater than 1 is either a prime or can be factored into primes).
2. **Law of Non-Contradiction**: This states that a statement and its negation cannot both be true simultaneously. In our proof, we assumed a finite list of primes and derived a contradiction, which means our initial assumption must be false.
3. **Rules of Logical Inference**: These include modus ponens (if \( P \) implies \( Q \) and \( P \) is true, then \( Q \) is true) and proof by contradiction (if assuming \( P \) leads to a contradiction, then \( P \) must be false).

Let's dive deeper into the "Logical Inference" aspect.

### Logical Inference in Proof by Contradiction

In a proof by contradiction, we start by assuming the negation of what we want to prove.

> \( \neg P \) --- means "not P"

We then use logical inference to derive consequences from this assumption.

If we eventually derive a contradiction (a statement that is always false, such as \( Q \) and \( \neg Q \)), we conclude that our initial assumption \( \neg P \) must be false.
