# experts and adversarial bandits
Project assignment about experts and adversarial bandits for the course of Reinforcement Learning at Techninal University of Crete in 2023  

**Assignment Description:**

You are given a dataset of real traffic loads over time (normalized), for a number of servers. These demands are non stationary.  

Your goal is to devise algorithms that learn to predict the least loaded server at every time round. Imagine, for example, that you had to offload computing tasks, one after another, to one of these servers: the higher the load of the server at that time, the longer the delay for your own offloaded task as well.  

**Part I:**  
- Implement the Multiplicate Weights algorithm assuming an "Experts" environment (i.e., you get to learn the load of other servers at every round, not just the one you chose).

- Implement the Multiplicate Weights algorithm assuming a "Bandit" environment.

- Compare the cummulative regret of the two algorthms, for horizon values T = 1000, T = 7000 (entire duration of dataset)

**Part II:** 
- Adapt UCB to this problem as well (remember, you now have losses, not rewards as in the previous assignment)

- Compare the performance of UCB to that of MW algorithm for the bandit setting (again for T = 1000, T = 7000).

**Notes:**

For all algorithm parameters (eta, gamma, etc.) follow the suggestions in the uploaded lecture notes.

**Submission:**

a) a python notebook that compiles and produces the above plots

b) a short report (2-page max), with plots related to the above questions and your observations/remarks.
