## Uroš Savurdić

M.Sc. student in Electrical Engineering and Computer Science, and previously an
Applied Science Intern at Microsoft. I work on machine learning systems and the
evaluation infrastructure around them — the part that tells you whether a model
actually does what you claim it does.

Most of what I build falls into four groups: LLM evaluation and the data
behind it, post-training and model internals, retrieval and representation
learning, and performance work across hardware and computing paradigms.

### Selected work

| Project | What it is |
|---|---|
| **[DPO safety representations](https://github.com/urosavurdic/dpo-safety-representations)** | How safety SFT and DPO change a small model's internals: SFT preserves the harmful–benign contrast, DPO redirects it. Matched starts, three runs per arm, steering and ablation tests. |
| **[Attention mechanism paradigms](https://github.com/urosavurdic/attention-mechanism-paradigms)** | Attention on 12 execution substrates and 17 implementations, measured and modelled stage by stage. Softmax is 0.4% of the FLOPs and up to 35% of the measured runtime; a silent float64 promotion under NumPy 2 made FP32 look 20× slower. |
| **[Optimization methods](https://github.com/urosavurdic/optimization-methods)** | Six optimisation problems from scratch in NumPy — metaheuristics, derivative-free fitting, and backpropagation raced against a genetic algorithm. |
| **[Code search engine](https://github.com/urosavurdic/embeddings-based-code-search-engine)** | Semantic code search over CoSQA. A bi-encoder fine-tuned with InfoNCE lifts MRR@10 from 0.79 to 0.91. |
| **[Written text recognizer](https://github.com/urosavurdic/Written-Text-Recognizer)** | Handwritten paragraph recognition, ResNet encoder into a Transformer decoder, served over FastAPI. |

### Tools

Python · PyTorch · PyTorch Lightning · NumPy · JAX · scikit-learn · FAISS ·
FastAPI · Docker · CUDA · MATLAB

### Elsewhere

[Portfolio](https://urosavurdic.github.io) · [LinkedIn](https://rs.linkedin.com/in/urosavurdic)
