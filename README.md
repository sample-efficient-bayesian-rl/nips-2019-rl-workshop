# Introduction
Source for the workshop paper: E. Markou and C. E. Rasmussen, <em>Bayesian methods for efficient Reinforcement Learning in tabular problems</em>, appearing in the 2019 NIPS Workshop on Biological and Artificial RL.

We compare different Bayesian methods for representing an RL agent's uncertainty about cumulative rewards, including our own approach based on moment matching across the Bellman equations.

| Method                                        | Authors             | Paper |
| :-------------------------------------------- | :------------------ | :---- |
| Bayesian Q-Learning                           | Dearden et. al.     | [link](https://www.aaai.org/Papers/AAAI/1998/AAAI98-108.pdf)  |
| Uncertainty Bellman Equation                  | O'Donoghue et. al.  | [link](https://arxiv.org/abs/1709.05380)  |
| Posterior Sampling for Reinforcement Learning | Osband et. al.      | [link](http://papers.nips.cc/paper/5185-more-efficient-reinforcement-learning-via-posterior-sampling)  |
| Moment Matching                               | Ours                | [link](https://github.com/stratisMarkou/sample-efficient-bayesian-rl/blob/master/writeup/bayesian-methods-for-rl.pdf)  |

# Evnironments

# Results

## Summary
<div style="text-align:center"><img src="writeup/png/regret_summary_deepsea.png" float=center width="600" /></div>
<div style="text-align:center"><img src="writeup/png/regret_summary_widenarrow.png" float=center width="600" /></div>
<div style="text-align:center"><img src="writeup/png/regret_summary_priormdp.png" float=center width="600" /></div>

# Conclusions
