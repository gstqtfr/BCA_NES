# BCA NES 
Variant of the B-cell algorithm (BCA) in comparison to Andrej Karpathy's NES code for reinforcement learning

## B-cell algorithm applied to NES problem as inspired by Andrej Karpathy 

I came across an implementation of Natural Evolution Strategies (NES), and thought I would use a variant of the B-cell algorithm (BCA) to see how the algorithm performs on the same problem.

This notebook was inspired by Jovan Sardinha's excellent repo:

https://github.com/jovsa/evolution-strategies-exploration/

which was in turn inspired by the one-&-only Andrej Karpathy's code found at 

https://gist.github.com/karpathy/77fbb6a8dac5395f1b73e7a89300318d

The general idea of the original code, by Karpathy and Sardinha, is to apply evolutionary strategies in the context of reinforcement learning. Further details can be found at:

https://arxiv.org/abs/1703.03864
https://medium.com/beyond-intelligence/reinforcement-learning-or-evolutionary-strategies-nature-has-a-solution-both-8bc80db539b3

It seemed likely that the other nature-inspired algorithms could also be used in this problem domain, so I designed a variant of the BCA which could be used on a GPU (for pretty obvious perfomance reasons!).

This is the original BCA paper:

Kelsey J, Timmis J. Immune inspired somatic contiguous hypermutation for function optimisation Genetic and Evolutionary Computation (GECCO 2003); 2003. July 12–16; Chicago, USA: Springer; 2003: 207–218

There are a number of other papers on the BCA, & related nature-inspired algorithms, which you can google if you're interested.
