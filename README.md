# Capstone Thesis: Should You Swing on a 2-0 Count?
Undergraduate capstone thesis from California Lutheran University, 2016-2017.

A softball coach told me my whole life: don't swing on a 2-0 count. This project tested that with data.

**Question:** Does swinging on a 2-0 count reduce a batter's expected outcome, and if so, by how much?

Method: Markov chain model of plate appearance states, fit on MLB Retrosheet data. Each state is a count (balls-strikes), and transition probabilities are estimated from historical pitch-by-pitch records. Expected run value is computed for each state, making it possible to compare the value of swinging versus taking on any given count.

**Finding:** Taking on a 2-0 count produces a higher expected run value than swinging. The coach was right.

---
**Stack:** R · Retrosheet play-by-play data

---
**Keywords:** Sabermetrics, Markov chains, count leverage, expected run value
