# rl-exploration
Reinforcement Learning papers on exploration methods.

## Count-based

**Count-based exploration** is a category of exploration methods that encourage the agent to explore novel states by memorizing states' visitation counts.

| Title | AKA | Author | Date | Links |
| ----- | --- | ------ | ---- | ----- |
| Exploration in Model-based Reinforcement Learning by Empirically Estimating Learning Progress | - | Lopes et al. | 2012.12 | [[Paper]](https://papers.nips.cc/paper/4642-exploration-in-model-based-reinforcement-learning-by-empirically-estimating-learning-progress.pdf) |
| An Analytic Solution to Discrete Bayesian Reinforcement Learning | BEETLE | Poupart et al. | 2006.06 | [[Paper]](https://cs.uwaterloo.ca/~ppoupart/publications/bayesian-rl/icml-brl-8pages.pdf) |
| Unifying Count-Based Exploration and Intrinsic Motivation | DQN-CTS | Bellmare et al. | 2016.06 | [[Paper]](https://arxiv.org/pdf/1606.01868.pdf) |
| #Exploration: A Study of Count-Based Exploration for Deep Reinforcement Learning | - | Tang et al. | 2016.11 | [[Paper]](https://arxiv.org/pdf/1611.04717.pdf) |
| Count-Based Exploration with Neural Density Models | DQN-PixelCNN | Ostrovski et al. | 2017.03 | [[Paper]](https://arxiv.org/pdf/1703.01310.pdf) |

## Novel behavior-based

**Novel behavior-based** is a category of exploration methods that encourage the agent to perform novel behaviors. Behaviors are specified by application-specific behavior-characteristic. For eg. distance traveled or speed of agent.

| Title | AKA | Author | Date | Links |
| ----- | --- | ------ | ---- | ----- |
| Improving Exploration in Evolution Strategies for Deep Reinforcement Learning via a Population of Novelty-Seeking Agents | NS-ES | Conti et al. | 2017.12 | [[Paper]](https://arxiv.org/pdf/1712.06560.pdf) |
| Novelty-Guided Reinforcement Learning via Encoded Behaviors | - | Ramamurthy et al. | 2020.07 | [[Paper]](https://www.researchgate.net/publication/347020430_Novelty-Guided_Reinforcement_Learning_via_Encoded_Behaviors) |
| Guided Reinforcement Learning via Sequence Learning | - | Ramamurthy et al. | 2020.10 | [[Paper]](https://www.researchgate.net/publication/346250289_Guided_Reinforcement_Learning_via_Sequence_Learning) |

## Curiosity

**Curiosity-driven exploration** is a category of exploration methods that "generate an intrinsic reward signal based on how hard it is
for the agent to predict the consequences of its own actions, i.e. predict the next state given the current state and the executed
action." (Pathak et al., 2017)

| Title | AKA | Author | Date | Links |
| ----- | --- | ------ | ---- | ----- |
| Curious Model-building Control Systems | - | Schmidhuber | 1991.11 | [[Paper]](http://people.idsia.ch/~juergen/curioussingapore/curioussingapore.html) |
| Reinforcement-Driven Information Acquisition in Non-deterministic Environments | - | Storck et al. | 1995 | [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.35.8445) |
| Formal Theory of Creativity, Fun, and Intrinsic Motivation (1990–2010) | - | Schmidhuber | 2010.07 | [[Paper]](http://people.idsia.ch/~juergen/ieeecreative.pdf) |
| Planning to Be Surprised: Optimal Bayesian Exploration in Dynamic Environments | - | Sun et al. | 2011.03 | [[Paper]](https://arxiv.org/pdf/1103.5708.pdf) |
| VIME: Variational Information Maximizing Exploration | VIME | Houthooft et al. | 2016.05 | [[Paper]](https://arxiv.org/pdf/1605.09674.pdf) |
| Curiosity-driven Exploration by Self-supervised Prediction | ICM | Pathak et al. | 2017.05 | [[Paper]](https://arxiv.org/pdf/1705.05363.pdf) |
| Large-Scale Study of Curiosity-Driven Learning | ICM | Burda et al. | 2018.08 | [[Paper]](https://arxiv.org/pdf/1808.04355.pdf) |

## Misc.

| Title | AKA | Author | Date | Links |
| ----- | --- | ------ | ---- | ----- |
| Intrinsically Motivated Reinforcement Learning | - | Singh et al. | 2004 | [[Paper]](https://papers.nips.cc/paper/2552-intrinsically-motivated-reinforcement-learning.pdf) |
| A Theoretical Analysis of Model-Based Interval Estimation | MBIE | Strehl and Littman | 2005.08 | [[Paper]](https://sites.ualberta.ca/~szepesva/CMPUT654/littman.pdf) |
| An Analysis of Model-based Interval Estimation for Markov Decision Processes | MBIE-EB | Strehl and Littman | 2008.09 | [[Paper]](https://ac.els-cdn.com/S0022000008000767/1-s2.0-S0022000008000767-main.pdf?_tid=dba05b98-5cd3-4c12-aeff-a8aa2c7d6870&acdnat=1540993730_de215257b8096570d8faf7914f3d1820) |
| Incentivizing Exploration In Reinforcement Learning With Deep Predictive Models | - | Stadie et al. | 2015.07 | [[Paper]](https://arxiv.org/pdf/1507.00814.pdf) |
| Variational Information Maximisation for Intrinsically Motivated Reinforcement Learning | - | Mohamed and Rezende | 2015.09 | [[Paper]](https://arxiv.org/pdf/1509.08731.pdf) |
