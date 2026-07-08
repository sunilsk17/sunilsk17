<h1 align="center">Hey, I'm Sunil Kumar 👋</h1>

<p align="center">
  CS undergrad · ML research · systems thinking
</p>

<p align="center">
  <a href="mailto:sunilkumarssk.2021@gmail.com"><img src="https://img.shields.io/badge/email-sunilkumarssk.2021@gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sunilkumarssk"><img src="https://img.shields.io/badge/LinkedIn-sunilkumarssk-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/sunilsk17"><img src="https://img.shields.io/github/followers/sunilsk17?label=Follow&style=flat-square&logo=github" /></a>
</p>

---

I work at the intersection of **ML research and systems**—mostly deep learning, graph algorithms, and making models run efficiently on constrained hardware. Lately I've been spending a lot of time on hallucination in VLMs, GNNs on Apple Silicon, and streaming algorithm theory.

---

### Things I'm currently working on

- Latent-space hallucination detection for large vision-language models
- GNN acceleration on Apple Silicon (MLX framework)
- Energy-efficient cardinality estimation for edge deployments

---

### Projects worth looking at

**[LatentTokenGuard](https://github.com/sunilsk17/LatentTokenGuard)** — Hallucination detection in LVLMs without modifying the decoding loop. Works by measuring cosine similarity between generated token embeddings and visual patch representations in the model's internal latent space. Single-pass, post-hoc, no output distortion.

**[mlx-graphs](https://github.com/sunilsk17/mlx-graphs)** — GNN library built on Apple's MLX framework. All ops run natively on Apple Silicon's unified memory—benchmarks show up to 10× speedup over CPU-bound implementations. Has docs, Discord, and full test coverage.

**[mlx-spectral-gnn](https://github.com/sunilsk17/mlx-spectral-gnn)** — Hardware-aware spectral graph sparsification. Instead of randomly dropping edges (DropEdge), this computes distances in the spectral space of the graph Laplacian and prunes structurally redundant edges. Zero-copy memory between CPU (ARPACK solver) and GPU via unified memory—eliminates PCIe bottleneck of classical approaches.

**[annealed-ewc-edge-cl](https://github.com/sunilsk17/annealed-ewc-edge-cl)** — Continual learning experiments on edge hardware with MobileNetV3 and ResNet-18. Tests EWC across λ ∈ {0–5000}, annealed regularization schedules, and LwF distillation on CIFAR-10/100. Has consolidated results JSON and paper plots.

**[Learning-Augmented-MAXCUT-Streaming](https://github.com/sunilsk17/Learning-Augmented-MAXCUT-Streaming)** — Three streaming MAX-CUT algorithms that use learned predictions: SAHO (two-tier hub/peripheral ML), ARSP (confidence ensemble with dynamic threshold), TCAO (community-prior-augmented). Benchmarked on Enron mail graphs and Ottawa road networks.

**[Stream-Order-Sensitivity-in-Distinct-Element-Estimation](https://github.com/sunilsk17/Stream-Order-Sensitivity-in-Distinct-Element-Estimation)** — Empirical study of how stream ordering affects HyperLogLog, Theta Sketch, and KMV. Key result: HLL needs 53.8% more data to reach 5% error under natural (clustered) stream ordering on Enron vs. random. KMV shows the inverse—20× faster under grouped ordering due to its order-statistic structure.

**[GreenSketch](https://github.com/sunilsk17/GreenSketch)** — Energy-aware HyperLogLog variants for edge streaming (LHLL, THLL, AP-HLL). 18.6% energy reduction on Wikipedia pageviews at <1% accuracy loss.

**[Phishing-Detection](https://github.com/sunilsk17/Phishing-Detection)** — Phishing URL classifier using VAE data augmentation + ResNeXt-GRU architecture on handcrafted URL features.

**[Social\_Media\_Sentiment\_Analysis](https://github.com/sunilsk17/Social_Media_Sentiment_Analysis)** — 82% accuracy on Twitter Sentiment140 using Bagging + SVM with feature selection. Beats logistic regression and naive Bayes baselines.

---

### Stack

`Python` `C++` `PyTorch` `MLX` `PySpark` `JavaScript` `Node.js` `Scikit-learn` `NumPy`

---

### Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sunilsk17&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sunilsk17&layout=compact&theme=dark&hide_border=true&langs_count=6" height="165" />
</p>
