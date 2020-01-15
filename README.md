# stable-opponent-shaping
Pytorch implementation of Stable Opponent Shaping ([SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)).

Apply this optimizer and compare with other multi-agent learning algorithms including Naive Learning (Simultaneous Gradient Descent), Learning with Opponent-Learning Awareness ([LOLA](https://arxiv.org/pdf/1709.04326.pdf)), LookAhead (see [SOS](https://openreview.net/pdf?id=SyGjjsC5tQ)), Consensus Optimization ([CO](https://arxiv.org/pdf/1705.10461.pdf)), Symplectic Gradient Adjustment ([SGA](https://arxiv.org/pdf/1802.05642.pdf)), Competitive Gradient Descent ([CGD](https://arxiv.org/pdf/1905.12103.pdf)), Extragradient ([EG](https://arxiv.org/pdf/1906.05945.pdf)) and Local Symplectic Surgery ([LSS](https://arxiv.org/pdf/1901.00838.pdf)). A number of games including matching pennies, iterated prisoner's dilemma and tandem are already implemented, but feel free to define any n-player game and run for yourself.

The notebook runs in ~5 minutes with GPU accelerator enabled in colab. Use this link to open directly: https://colab.research.google.com/github/aletcher/stable-opponent-shaping/blob/master/stable_opponent_shaping.ipynb

### Bibtex citation for each algorithm

@inproceedings{sos,  
title={Stable Opponent Shaping in Differentiable Games},  
author={Alistair Letcher and Jakob Foerster and David Balduzzi and Tim Rocktäschel and Shimon Whiteson},  
booktitle={International Conference on Learning Representations},  
year={2019},  
url={https://<span>openreview.net</span>/forum?id=SyGjjsC5tQ}}

@inproceedings{lola,  
  author={Jakob N. Foerster and Richard Y. Chen and Maruan Al{-}Shedivat and Shimon Whiteson and Pieter Abbeel and Igor Mordatch},  
  title={Learning with Opponent-Learning Awareness},  
  booktitle={{AAMAS}},  
  pages={122--130},  
  publisher={International Foundation for Autonomous Agents and Multiagent Systems Richland, SC, {USA} / {ACM}},  
  year={2018}  
}

@inproceedings{co,  
  title={The numerics of gans},  
  author={Mescheder, Lars and Nowozin, Sebastian and Geiger, Andreas},  
  booktitle={Advances in Neural Information Processing Systems},  
  pages={1825--1835},  
  year={2017}  
}

@inproceedings{sga,  
  title={The Mechanics of n-Player Differentiable Games},  
  author={Balduzzi, David and Racaniere, Sebastien and Martens, James and Foerster, Jakob and Tuyls, Karl and Graepel, Thore},  
  booktitle={International Conference on Machine Learning},  
  pages={363--372},  
  year={2018}  
}

@article{eg,  
  title={A Tight and Unified Analysis of Extragradient for a Whole Spectrum of Differentiable Games},  
  author={Azizian, Wa{\"\i}ss and Mitliagkas, Ioannis and Lacoste-Julien, Simon and Gidel, Gauthier},  
  journal={arXiv preprint arXiv:1906.05945},  
  year={2019}  
}

@article{cgd,  
  title={Competitive Gradient Descent},  
  author={Sch{\"a}fer, Florian and Anandkumar, Anima},    
  journal={arXiv preprint arXiv:1905.12103},  
  year={2019}  
}

@article{lss,  
    title={On Finding Local Nash Equilibria (and Only Local Nash Equilibria) in Zero-Sum Games},  
    author={Eric V. Mazumdar and Michael I. Jordan and S. Shankar Sastry},  
    year={2019},  
    journal={arXiv preprint arXiv:1901.00838},  
}
