## Lab 2 - Nim Strategy
The goal of this project is to write an evolutionary strategy in order to find an optimal strategy to follow for the Nim game (miserè variation).<br>
The code, along with a detailed commentary is present in the `lab2-nim.ipynb` notebook.
<br>
This lab was solved in cooperation with [Guido Pio Natalizio](https://github.com/Guido-Pio-Natalizio/computational-intelligence).

## Notes
- The strategy defined in the `optimal` function doesn't implement the mathematical solution of Nim, so it's possible for the ES to find a way to beat it, this, in my opinion, leads to more interesting results than having the ES run against an unbeatable model. 
- The `mutate` function implements mutation using an uniform distribution rather than a normal one, even if this is different from what we observe in nature it shouldn't be an issue.
## Peer Reviews on Lab 2
### Done
[Giovanni Violo](https://github.com/giovanni-violo/Computational_intelligence_317617/issues/1)
### Received
_None yet, if you're reading this, feel free to write one_ 😇
