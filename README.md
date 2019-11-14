# FuzzGuard
This repo is the released code of FuzzGuard in USENIX Security 2020.


We propose FuzzGuard, a deep-learning-based approach
to predict the reachability of inputs (i.e., miss the target or not)
before executing the target program, helping DGF filtering
out the unreachable ones to boost the performance of fuzzing.
To apply deep learning with DGF, we design a suite of new
techniques (e.g., step-forwarding approach, representative data
selection) to solve the problems of unbalanced labeled data
and insufficient time in the training process. Further, we implement
the proposed approach called FuzzGuard and equip it
with the state-of-the-art DGF (e.g., AFLGo). Evaluations on
45 real vulnerabilities show that FuzzGuard boosts the fuzzing
efficiency of the vanilla AFLGo up to 17.1 times.
