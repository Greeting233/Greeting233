# Hi, I'm Jiadong Liu 👋

M.S. student in Information Systems at Northeastern University, Silicon Valley campus (San Jose, CA).  
B.Eng. in Electronic Information Science and Technology (Intelligent Chip Design), Taishan University (China).

I work on **efficient, adaptive, and reliable AI systems for resource-constrained edge platforms** — small, measurable systems that connect model behavior, context construction, latency, and real-world task usefulness.

## Research interests

- AI systems and edge intelligence
- Runtime-adaptive inference and context construction
- Screen-aware and human-in-the-loop LLM systems
- Efficient model execution and adaptive computation
- Control-oriented and embedded intelligent systems

## Selected projects

### 🧪 Edge-NPU Adaptivity (deployment measurement)

Deployment characterization of adaptive vision inference on a commercial edge-NPU platform: first-invocation warmup, co-resident model switching, INT8 quantization format, and CPU–NPU output consistency. A per-tensor INT8 accuracy collapse is localized to the quantization pipeline (not the NPU backend) by reproducing the same failure on CPU and NPU paths. Public preprint with a reproducibility artifact.

→ [edge-npu-adaptivity-artifact](https://github.com/Greeting233/edge-npu-adaptivity-artifact) · Zenodo DOI: [10.5281/zenodo.21298690](https://doi.org/10.5281/zenodo.21298690)

### 📊 UISP Adaptive Pruning

Uncertainty-driven input-adaptive structured pruning for BN-based CNNs. Experiments on ResNet-18 / CIFAR-10 with N=10 seeds; statistical comparison against matched random pruning. Honest report of when the recursive confidence proxy degrades to identity mapping under static convolutional weights — a cross-domain boundary diagnostic, not a successful transfer claim.

→ [uisp-adaptive-pruning](https://github.com/Greeting233/uisp-adaptive-pruning) (see `KEY_RESULTS.md` and `experiment_log.pdf`)

### 🔧 ScreenSense-Agent

A suggestion-first, screen-aware research system for low-latency desktop context extraction and task-relevant LLM suggestion generation. Single-frame macOS pipeline:

`screen capture → OCR → task discrimination → context construction → LLM suggestion → read-only overlay`

Released as **v0.1.0** (MIT) with an N=10 pilot manual evaluation. The pre-registered global first-runnable threshold was **not** met, but the pilot revealed a consistent outcome-level boundary: structured / traceback-style errors were more likely to produce useful suggestions, while non-structured terminal/file errors often fell to minimal context and generic fallback. **Suggestion-only by design**: no keyboard/mouse takeover, no permission bypass.

→ [screensense-agent](https://github.com/Greeting233/screensense-agent)

### 📄 First-author publication

*Comparative Study of Neural Architecture Search Methods: Random Search, RNN + Reinforcement Learning, and Evolutionary Algorithms on CIFAR-10*. IET Conference Proceedings / CONF-SPML 2025, EI Compendex.  
DOI: [10.1049/icp.2025.1009](https://doi.org/10.1049/icp.2025.1009)

## Ongoing work

A first-author manuscript on runtime-adaptive neuro-fuzzy edge control with sampled-data stability analysis, in collaboration with the corresponding author. Being developed for a control / automation venue.

## Contact

- 📧 liu.jiad [at] northeastern [dot] edu
- 🔗 [LinkedIn: Jiadong Liu](https://www.linkedin.com/in/jiadongliu/)
- 🆔 [ORCID: 0009-0008-5992-2065](https://orcid.org/0009-0008-5992-2065)
