# Probability and Expectation Value

## Overview

Probability and expectation value are foundational concepts in:

- Monte Carlo Methods
- Markov Chain Monte Carlo (MCMC)
- Statistics
- Finance
- Reliability Engineering
- Infrastructure Risk Modeling
- Physics

Understanding the intuition behind these concepts is critical before moving deeper into stochastic systems and simulation.

---

# Probability

Probability answers the question:

> "How likely is an event to happen?"

---

## Example: Rolling a Fair Die

A standard die has six equally likely outcomes:

| Outcome |
|---|
| 1 |
| 2 |
| 3 |
| 4 |
| 5 |
| 6 |

The probability of rolling a 3 is:

$$
P(3) = \frac{1}{6}
$$

This means:
- there is 1 favorable outcome
- out of 6 possible outcomes

or approximately:

$$
P(3) \approx 0.167
$$

which is:

$$
16.7\%
$$

---

## Visual Intuition

Imagine repeatedly rolling a die:

```text
2 5 1 3 6 2 4 1 3 5 6 2 ...
```

Over many rolls:
- each number appears roughly equally often

Probability describes:
- the long-run frequency behavior of outcomes

---

# Expectation Value

Expectation value answers the question:

> "What value do we expect on average over many trials?"

Expectation value is:
- not a guaranteed outcome
- not necessarily even a possible outcome

It is:
- the weighted average behavior of a random process

---

## Expectation Value of a Fair Die

The expectation value formula is:

$$
E[X] =
\sum x_i P(x_i)
$$

For a fair die:

$$
E[X]
$$

$$=1\left(\frac16\right)$$
$$+2\left(\frac16\right)$$
$$+3\left(\frac16\right)$$
$$+4\left(\frac16\right)$$
$$+5\left(\frac16\right)$$
$$+6\left(\frac16\right)$$

Simplifying:

$$
=\frac{1+2+3+4+5+6}{6}
=\frac{21}{6}
=3.5
$$

---

## Important Concept

A die can never actually roll a 3.5.

The expectation value is:
- not an actual outcome
- but the long-run average over many trials

---

## Visual Intuition

Suppose repeated die rolls produce:

```text
1 6 2 5 4 3 2 6 1 5 ...
```

The average value trends toward:

$$
3.5
$$

as the number of rolls increases.

---

# Infrastructure Example

Suppose:
- probability of pipe failure in a given year = 2%
- repair cost = \$500,000

Expected annual loss:

$$
E[\text{loss}]
=
0.02 \times 500000
=
10000
$$

Interpretation:
- the expected yearly financial exposure is approximately \$10,000

This is a common concept in:
- infrastructure risk analysis
- reliability engineering
- asset management

---

# Finance Example

Suppose investment returns are:

| Return | Probability |
|---|---|
| +20% | 0.3 |
| +5% | 0.5 |
| -10% | 0.2 |

Expected return:

$$
E[R]
=0.3(20)
+0.5(5)
+0.2(-10)
$$

$$
=6 + 2.5 - 2
=6.5\%
$$

Interpretation:
- the expected average return is 6.5%

Again:
- this does not mean any individual outcome will equal 6.5%
- it represents the weighted long-run average

---

# Connection to Monte Carlo Methods

Monte Carlo methods often estimate expectation values using repeated random sampling.

Instead of solving difficult equations analytically:

$$
E[f(x)]
$$

Monte Carlo methods:
1. generate many random samples
2. evaluate the function repeatedly
3. average the results

As the number of samples increases:
- the estimate converges toward the true expectation value

---

# Conceptual Summary

## Probability

Describes:

> "How likely is an event?"

---

## Expectation Value

Describes:

> "What average behavior emerges over many trials?"

---

# Relevance to MCMC

In MCMC:
- direct analytical solutions are often difficult or impossible
- random sampling is used to approximate expectation values

This allows estimation of:
- distributions
- averages
- probabilities
- system behaviors

in complex stochastic systems.

---

# Key Takeaway

Probability describes uncertainty.

Expectation value describes average behavior under uncertainty.

These concepts form the foundation for:
- Monte Carlo simulation
- MCMC
- Bayesian inference
- Reliability engineering
- Financial modeling
- Infrastructure risk analysis
- Statistical physics
- Predictive analytics