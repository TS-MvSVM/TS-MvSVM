# [Insert Paper Title Here]

This repository contains the implementation of the paper: "Triple Sparse Multiview Support Vector Machine
and Its Safe Screening Rules".


The source code for this project will be made publicly available immediately upon the acceptance of the paper. We are currently organizing and documenting the code to ensure it is easy to reproduce our experimental results (including the TS-MvSVM model and the Multiview Safe Screening Rules).

## Abstract

Learning from large-scale multiview data presents
significant challenges, particularly in managing high dimen-
sionality and complex multiview structures. Although exist-
ing multiview learning methods effectively integrate consensus
and complementarity, they suffer from pairwise computational
bottlenecks or inherent linear limitations. Furthermore, these
methods neglect view redundancy by assuming all views are
informative, and lack simultaneous screening rules for efficient
feature and sample reduction. To address these limitations, we
propose the Triple Sparse Multiview Support Vector Machine
(TS-MvSVM). This unified framework extends sparse learning to
the general multiview domain, capturing non-linear relationships
while preserving consensus and complementarity. Crucially, we
pioneer the introduction of view-level sparsity, achieving a triple
sparse structure that simultaneously eliminates redundant views,
irrelevant features, and inactive samples. To counterbalance
the computational complexity, we derive the first Multiview
Safe Screening Rules (MvSSR). By exploiting the synergy be-
tween feature and sample screening to dynamically downsize
the optimization problem, our method significantly accelerates
training while guaranteeing optimality. Extensive experiments
demonstrate that TS-MvSVM achieves superior classification
performance, while MvSSR enhance computational efficiency.

## Updates

- [2025-XX-XX]: Paper submitted for review.
