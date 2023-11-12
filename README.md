# hamiltonian-win-cycles
Find and graphically illustrate a Hamiltonian cycle in a graph where wins are directed edges.
A Hamiltonian win cycle is a closed loop that includes exactly one win by all teams in a league: A beat B beat C ... Z beat A.

All the code is in the nb-file. 
It is very simple, the key functions are 
[FindHamiltonianCycle](https://reference.wolfram.com/language/ref/FindHamiltonianCycle.html)
and
[Graph](https://reference.wolfram.com/language/ref/Graph.html).
Evaluating the whole notebook in Mathematica recreates the example output. The example input is the match data from Premier League season 2023-24, up until 2023-11-06, which is when the earlest Hamiltonian cycle was completed.

# Example output

![Example Hamiltonian win cycle graph](https://github.com/tervio/hamiltonian-win-cycles/blob/main/output/eng-tier-1-2023-2024.svg?raw=true)
Earliest Hamiltonian win cycles in the Premier League 2023-24 appeared on 11-06. There were 25, this is a random choice.

Here is the part of the example input that shows up as the displayed Hamiltonian win cycle: 
[View the CSV file](https://github.com/tervio/hamiltonian-win-cycles/blob/main/output/eng-tier-1-2023-2024.csv)
