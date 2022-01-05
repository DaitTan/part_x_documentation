.. part-x documentation master file, created by
   sphinx-quickstart on Wed Jan  5 07:23:12 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Part-X!
====================

Introduction
------------
Requirements driven search-based testing (also known as falsification) has proven to be a practical and effective method for discovering erroneous behaviors in Cyber-Physical Systems. Despite the constant improvements on the performance and applicability of falsification methods, they all share a common characteristic. Namely, they are best-effort methods which do not provide any guarantees on the absence of erroneous behaviors (falsifiers) when the testing budget is exhausted. The absence of finite time guarantees is a major limitation which prevents falsification methods from being utilized in certification procedures. In this paper, we address the finite-time guarantees problem by developing a new stochastic algorithm. Our proposed algorithm not only estimates (bounds) the probability that falsifying behaviors exist, but also it identifies the regions where these falsifying behaviors may occur. We demonstrate the applicability of our approach on standard benchmark functions from the optimization literature and on the F16 benchmark problem.

Link to Paper
-------------
the working paper can be accessed at https://arxiv.org/abs/2110.10729/

Citation
--------
Please cite the following paper if you use the work in your research

.. code-block:: bib

   @misc{pedrielli2021partx,
      title={Part-X: A Family of Stochastic Algorithms for Search-Based Test Generation with Probabilistic Guarantees}, 
      author={Giulia Pedrielli and Tanmay Khandait and Surdeep Chotaliya and Quinn Thibeault and Hao Huang and Mauricio Castillo-Effen and Georgios Fainekos},
      year={2021},
      eprint={2110.10729},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
      }


Usage
-----
.. toctree::
   :maxdepth: 2

   Getting Started
   Inputs
   Outputs