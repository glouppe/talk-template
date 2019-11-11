class: middle, center, title-slide
count: false

# Template

A Turing machine example

<br><br>

Gilles Louppe<br>
[g.louppe@uliege.be](mailto:g.louppe@uliege.be)

---

class: middle

# Turing machines

---

class: middle

.center.circle[![](figures/turing.jpg)]

A **Turing machine** is a mathematical *model of computation* that defines an abstract machine, which manipulates symbols on a strip of tape according to a table of rules.

Despite the model's simplicity, given any computer algorithm, a Turing machine capable of simulating that algorithm's logic can be constructed.

---

class: middle, center

.width-100[![](figures/tm.jpg)]

---

# Formation definition

Following Hopcroft and Ullman (1979, p. 148), a (one-tape) Turing machine can be formally defined as a 7-tuple $M=(Q,\Gamma,b,\Sigma,\delta, q\_0, F)$, where
- $Q$ is a finite, non-empty set of states;
- $\Gamma$ is a finite, non-empty set of tapes alphabet symbols;
- $b \in \Gamma \setminus \\{b\\}$ is the set of input symbols, that is, the set of symbols allowed to appear in the initial tape contents;
- $q\_0 \in Q$ is the initial state;
- $F \subseteq Q$ is the set of final states or accepting states. The initial tape contents is said to be accepted by $M$ if it eventually halts in a state from $F$.
- $\delta: (Q \setminus F) \times \Gamma \rightarrow Q \times \Gamma \times \\{L,R\\}$ is the state transition function.

---

class: middle

## Sub-title

Lorem ipsum.

.footnote[This is a footnote.]

---

class: middle

# Summary

---

class: middle

- abc
- def
- ghi

---

# References

- Turing, Alan M. "Computing machinery and intelligence." Parsing the Turing Test. Springer, Dordrecht, 2009. 23-65.

---

class: end-slide, center
count: false

The end.
