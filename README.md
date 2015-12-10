# AI: Ticket To Ride
**Summer 2015**

The Artificial Intelligence course (CS 4710) pitted student-submitted software agents against each other in a computer version of the [Ticket to Ride](http://www.daysofwonder.com/tickettoride/en/usa/)<sup>(R)</sup> board game.

Initial attempts at a depth-limited classical-search approach produced mediocre results.  Just days before the competition, the class learned about Markov chains and the use of Markov decision processes (MDP).  I scrambled to implement and test a basic MDP to compete, and ultimately **won the class tournament**.

The Markovian AI uses a small state space of 8 carefully chosen states.  It runs blazingly fast, using hashmaps for probabilistic lookups, a variant of Dijkstra's shortest-path algorithm, and several linear processes with small input sizes.  The program couples short-term and long-term planning, modifying its behavior over time to maximize the overall chance of success.  The Ticket to Ride challenge is still assigned as part of CS 4710; additional details are available by request only.

## Tools
* Java
* Eclipse IDE
