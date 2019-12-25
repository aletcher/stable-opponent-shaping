# stable-opponent-shaping
Pytorch implementation of Stable Opponent Shaping ([SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)).

Apply this optimizer and compare with other algorithms including Simultaneous Gradient Descent, Symplectic Gradient Adjustment ([SGA](http://jmlr.csail.mit.edu/papers/volume20/19-008/19-008.pdf)), Consensus Optimization ([CO](https://arxiv.org/pdf/1705.10461.pdf)), Learning with Opponent-Learning Awareness ([LOLA](https://arxiv.org/pdf/1709.04326.pdf)) and LookAhead (see [SOS](https://openreview.net/pdf?id=SyGjjsC5tQ) paper). A number of games including matching pennies, iterated prisoner's dilemma and the tandem game are already implemented, but feel free to define any n-player game and compare for yourselves.

Use this link to run the notebook in colab: https://colab.research.google.com/github/aletcher/stable-opponent-shaping/blob/master/stable-opponent-shaping.ipynb
