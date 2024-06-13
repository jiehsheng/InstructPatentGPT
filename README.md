# InstructPatentGPT
 
This repository collects the source code, datasets, SFT models,
reward models, policy models, and experimental results in the [InstructPatentGPT](https://doi.org/10.1007/s10506-024-09401-1) paper. In this research, patent prosecution is conceptualized as a system of reinforcement learning from human feedback. The objective of the system is to increase the likelihood for a language model to generate patent claims that have a higher chance of being granted. To showcase the controllability of the language model, the system learns from [*granted*] patents and [*pre-grant*] applications with different rewards. The status of [*granted*] and [*pre-grant*] are perceived as labeled human feedback implicitly. In addition, specific to patent drafting, the experiments in this research demonstrate the model's capability to learn from adjusting claim length and inclusion of limiting terms for narrowing claim scope. As proof of concept, the experiments focus on claim ones only and the training data originates from a patent dataset tailored specifically for artificial intelligence. Although the available human feedback in patent prosecution are limited and the quality of generated patent text requires improvement, the experiments following the 3-stage reinforcement learning from human feedback (RLHF) have demonstrated that generative language models are capable of reflecting the human feedback or intent in patent prosecution. To enhance the usability of language models, the implementation in this research utilizes modern techniques that enable execution on a single consumer-grade GPU. The demonstrated proof of concept, which reduces hardware requirements, will prove valuable in the future as more human feedback in patent prosecution become available for broader use, either within patent offices or in the public domain.

### Citation for this work: 
```
@article{instructpatentgpt, 
  author = {Lee, Jieh-Sheng},
  title = {InstructPatentGPT: training patent language models to follow instructions with human feedback},
  date = {2024/05/08},
  doi = {10.1007/s10506-024-09401-1},
  isbn = {1572-8382},
  journal = {Artificial Intelligence and Law},
  url = {https://doi.org/10.1007/s10506-024-09401-1},
  year = {2024},
}
```

