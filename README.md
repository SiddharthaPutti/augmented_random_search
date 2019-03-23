# Strom_breaker
augmented random search
A common belief in model-free reinforcement learning is that methods based on random search in the parameter space of policies 
exhibit signiﬁcantly worse sample complexity than those that explore the space of actions. We dispel such beliefs by introducing 
a random search method for training static, linear policies for continuous control problems, matching state-ofthe-art sample 
eﬃciency on the benchmark MuJoCo locomotion tasks. Our method also ﬁnds a nearly optimal controller for a challenging instance of
the Linear Quadratic Regulator, a classical problem in control theory, when the dynamics are not known. Computationally, our random 
search algorithm is at least 15 times more eﬃcient than the fastest competing model-free methods on these benchmarks. We take advantage
of this computational eﬃciency to evaluate the performance of our method over hundreds of random seeds and many diﬀerent hyperparameter
conﬁgurations for each benchmark task. Our simulations highlight a high variability in performance in these benchmark tasks, suggesting
that commonly used estimations of sample eﬃciency do not adequately evaluate the performance of RL algorithms.
