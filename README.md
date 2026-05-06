### Zaidan Mir

Final-year BSc Computer Science at Kingston University, applying for AI/ML MSc programmes for September 2026 entry.

Kingston's CS degree is software-engineering heavy — no formal modules in linear algebra, multivariate calculus, or probability. Rather than route around that gap, I'm closing it directly. Each of the projects below pairs a from-first-principles mathematical derivation with a NumPy implementation that matches the derivation step by step. No autograd, no PyTorch shortcuts.

---

#### Projects

**[Transformer from scratch](https://github.com/zaidanmir/transformer-from-scratch)**  
Decoder-only Transformer trained on Tiny Shakespeare, in pure NumPy. Scaled dot-product attention, multi-head decomposition, causal masking, and sinusoidal position encodings — all derived in [`notes/attention.md`](https://github.com/zaidanmir/transformer-from-scratch/blob/main/notes/attention.md), including the variance argument for the √dₖ scaling.

**[MLP from scratch](https://github.com/zaidanmir/mnist-nn-from-scratch)**  
Two-layer multi-layer perceptron on MNIST, in pure NumPy. Forward pass, backpropagation, and mini-batch SGD implemented to match the chain-rule derivation in [`notes/backprop.md`](https://github.com/zaidanmir/mnist-nn-from-scratch/blob/main/notes/backprop.md), including the softmax + cross-entropy gradient collapse to `p − one_hot(y)`.

**[Naive Bayes spam classifier](https://github.com/zaidanmir/naive-bayes-spam)**  
Multinomial Naive Bayes from first principles on the UCI SMS Spam Collection. Bayes' theorem, log-likelihood in log-space, and Laplace smoothing derived; benchmarked against the scikit-learn baseline.

**[DDPM from scratch](https://github.com/zaidanmir/diffusion-from-scratch)**  
Denoising Diffusion Probabilistic Models on Fashion-MNIST. Currently working through the variational lower bound derivation before implementation begins.

**Travelyn AI** *(final-year project, repository private)*  
iOS commuter app integrating four live UK transport APIs (TfL, National Rail Darwin, BODS SIRI-VM, OpenStreetMap) on a Backend-for-Frontend architecture. On-device unsupervised clustering (300 m greedy nearest-neighbour, three-visit minimum, time-bucketed) learns each user's commute patterns without training data; a separate pipeline interpolates live vehicle positions between scheduled and actual times. Verified with an XCTest unit suite and a five-participant Nielsen-heuristics usability study.

---

#### Currently learning

- Imperial College London — *Mathematics for Machine Learning* (Coursera): linear algebra, multivariate calculus, PCA.
- MIT 18.06 — *Linear Algebra* (Gilbert Strang, OpenCourseWare): supplementary depth.
- Joe Blitzstein — *Stat 110* (Harvard, YouTube): probability foundations.

---

zaidan2440@gmail.com
