# PythonBandit
Multi Armed Bandit 

(Greedy, e-Greedy, Random)


Implemented version of the multi-armed bandit algorithm has 8 arms. The algorithm is implemented as ”MultiBandit” class where k is a parameter defining the number of arms. The class
has three methods, implementing common strategies for ”pulling arms”:
1. ”random strategy” - method chooses arms randomly with ”choose arm” and collects
the rewards (NumPy random function).
2. ”greedy strategy” - method uses a greedy strategy to choose arms with the highest estimated value ”choose arm greedy” and updates the estimated value of each arm based on
the rewards received.
3. ”egreedy strategy” - method uses an epsilon-greedy strategy to choose arms with the
highest estimated value with probability 1 - epsilon and selects a random arm with probability
epsilon ”choose arm egreedy” method then updates the estimated value of each arm based
on the rewards received.
