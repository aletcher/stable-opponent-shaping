# stable-opponent-shaping
Pytorch implementation of Stable Opponent Shaping ([SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)).

Apply this optimizer and compare with other multi-agent learning algorithms including Naive Learning (Simultaneous Gradient Descent), Learning with Opponent-Learning Awareness ([LOLA](https://arxiv.org/pdf/1709.04326.pdf)), LookAhead (see [SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)), Consensus Optimization ([CO](https://arxiv.org/pdf/1705.10461.pdf)), Symplectic Gradient Adjustment ([SGA](https://arxiv.org/pdf/1802.05642.pdf)), Competitive Gradient Descent ([CGD](https://arxiv.org/pdf/1905.12103.pdf)), Extragradient ([EG](https://arxiv.org/pdf/1906.05945.pdf)) and Local Symplectic Surgery ([LSS](https://arxiv.org/pdf/1901.00838.pdf)). A number of games including matching pennies, iterated prisoner's dilemma and tandem are already implemented, but feel free to define any n-player game and run for yourself.

The notebook runs in ~5 minutes with GPU accelerator enabled in colab. Use this link to open directly: https://colab.research.google.com/github/aletcher/stable-opponent-shaping/blob/master/stable_opponent_shaping.ipynb

Please find the bibtex citation for each algorithm in the bibtex.md file.
