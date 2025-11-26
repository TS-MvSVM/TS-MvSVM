# Triple Sparse Multiview Support Vector Machine and Its Safe Screening Rules

This repository contains the implementation of the paper: "Triple Sparse Multiview Support Vector Machine and Its Safe Screening Rules".

We are currently organizing and documenting the code to ensure it is easy to reproduce our experimental results (including the TS-MvSVM model and the Multiview Safe Screening Rules).

The source code for this project will be made publicly available immediately upon the acceptance of the paper. 

## Abstract

Multiview data contains substantial redundancy,
relying on only a few informative views, discriminative features,
and active samples to define the decision boundary. However,
most existing multiview learning methods neglect view redun-
dancy or are restricted to single-level sparsity, which constrains
their flexibility and efficiency. In this paper, we propose the
Triple Sparse Multiview Support Vector Machine (TS-MvSVM),
a unified framework that simultaneously induces sparsity across
view, feature, and sample levels. This framework extends sparse
learning to the general multiview domain, capturing non-linear
relationships while preserving consensus and complementarity.
Crucially, we pioneer the introduction of view-level sparsity,
achieving a triple sparse structure that simultaneously eliminates
redundant views, irrelevant features, and inactive samples. To
counterbalance computational complexity, we derive the first
Multiview Safe Screening Rules (MvSSR). Taking advantage of
the synergy between feature screening and sample screening
to dynamically downsize the optimization problem, our method
significantly accelerates training while guaranteeing optimality.
Extensive experiments demonstrate that TS-MvSVM achieves
superior classification performance, while MvSSR improve com-
putational efficiency. The source code is available at https:
//github.com/TS-MvSVM/TS-MvSVM.

## Updates

- [2025-XX-XX]: Paper submitted for review.
