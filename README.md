# Python_production_project

I was given an assignment for the following optimization algorithm. I came up with the idea on my own and found a solution but have not verified if it's optimal.

There are 10 products that need to be scheduled on a single production line. The products each have their own time to produce and switching between products incurs
additional time, which is found in the changeover matrix.
<p>
Bgin with a given sequence and use a greedy hruistic to find the optimal sequence. Make adjacent neighbor swaps and at each pass find and make only the best swaps, 
considering all possible neighbors.
<p>
The algorithm should continue to find and make improving swaps and terminate when no further improvement can be made.
