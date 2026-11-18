<h1 align="center">Sunil Kumar S</h1>

<p align="center">Software Engineer II @ Walmart Global Tech &nbsp;·&nbsp; ML research &nbsp;·&nbsp; BE CSE, CEG</p>

<p align="center">
  <a href="mailto:sunilkumarssk.2021@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/sunilsk17/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

---

- 🏢 &nbsp;Software Engineer II @ **Walmart Global Tech** 
- 🎓 &nbsp;BE Computer Science and Engineering, College of Engineering Guindy (CGPA 9.21/10)
- 🔬 &nbsp;Research: trustworthy AI (hallucination detection in VLMs/LLMs), efficient & edge ML, streaming & learning-augmented algorithms
- 🌐 &nbsp;[Portfolio](https://sunilsk17.github.io) · [Google Scholar](https://scholar.google.com/citations?user=nttuj54AAAAJ&hl=en)

---

### Contact

<a href="mailto:sunilkumarssk.2021@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;<a href="https://www.linkedin.com/in/sunilsk17/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

---

### Skills

**Languages:**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/C-555555?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /> <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white" />

**ML & Data:**

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/MLX-000000?style=flat-square&logo=apple&logoColor=white" /> <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" /> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" /> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" /> <img src="https://img.shields.io/badge/NLTK-3c763d?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />

**Cloud & Data Eng:**

<img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" /> <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" /> <img src="https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white" /> <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" /> <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" /> <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />

**Tools:**

<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" /> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" /> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />

---

### Projects

**[LatentTokenGuard](https://github.com/sunilsk17/LatentTokenGuard)** — Training-free detection of hallucinated objects in VLM captions from the model's own hidden states (top-k cosine between object and image tokens), with no extra forward pass. Found that caption position alone predicts hallucination (up to 84 AUROC) and built a position-controlled benchmark on LLaVA-1.5-7B/13B and Qwen2.5-VL-7B: 79.7 / 78.7 / 82.8 AUROC within position bins, the best single training-free score on all three, against 6 baselines incl. GLSim (NeurIPS 2025).

**[mlx-spectral-gnn](https://github.com/sunilsk17/mlx-spectral-gnn)** — Hardware-aware spectral graph sparsification. Prunes structurally redundant edges using spectral distances from the graph Laplacian instead of random DropEdge. Zero-copy CPU↔GPU via unified memory. Keeps accuracy at up to 30% sparsity with lower variance than stochastic baselines.

**[annealed-ewc-edge-cl](https://github.com/sunilsk17/annealed-ewc-edge-cl)** — Annealed EWC: a harmonic-decay regularization schedule for sub-1M-parameter edge models, where standard EWC fails. 8.4% higher accuracy and 43.2% less forgetting on MobileNetV3-Small (CIFAR-10/100). Accepted at ACS/IEEE AICCSA 2026.

**[Learning-Augmented-MAXCUT-Streaming](https://github.com/sunilsk17/Learning-Augmented-MAXCUT-Streaming)** — Three learning-augmented streaming MAX-CUT algorithms: SAHO (two-tier hub/peripheral ML), ARSP (confidence ensemble + dynamic threshold), TCAO (community-prior). Tested on Enron mail graphs and Ottawa road networks.

**[Stream-Order-Sensitivity-in-Distinct-Element-Estimation](https://github.com/sunilsk17/Stream-Order-Sensitivity-in-Distinct-Element-Estimation)** — How stream ordering breaks HyperLogLog, Theta Sketch, and KMV. HLL needs 53.8% more data to hit 5% error under natural ordering on Enron. KMV flips it — 20× faster under grouped ordering.

**[GreenSketch](https://github.com/sunilsk17/GreenSketch)** — Energy-aware HLL variants (LHLL, THLL, AP-HLL) for edge streams. 18.6% energy reduction on Wikipedia pageviews at <1% accuracy loss.

**[Phishing-Detection](https://github.com/sunilsk17/Phishing-Detection)** — URL phishing classifier: a Conditional VAE for minority-class augmentation and 48→16 feature compression, feeding a ResNeXt-GRU. 91.44% validation accuracy.

**[Social\_Media\_Sentiment\_Analysis](https://github.com/sunilsk17/Social_Media_Sentiment_Analysis)** — 82% accuracy on Twitter Sentiment140 with Bagging + SVM. Beats logistic regression and naive Bayes.

