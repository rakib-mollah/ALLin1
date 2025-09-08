# 🔑 Key GitHub Repositories for LLM Fine-Tuning, Quantization, LoRA, and Distillation

A quick, curated map of open-source tools you can use to customize and optimize large language models. You’ll find starter tutorials and production-grade libraries across four buckets: **Fine-Tuning**, **Quantization**, **LoRA (parameter-efficient adaptation)**, and **Distillation**. Each entry links straight to the repo or article so you can dive in fast.


---

## 📑 Table of Contents
- [🎯 Fine-Tuning LLMs](#-fine-tuning-llms)
- [⚡ Quantization](#-quantization)
- [🪶 LoRA (Low-Rank Adaptation)](#-lora-low-rank-adaptation)
- [🔄 Distillation](#-distillation)
- [📚 Further Reading](#-further-reading)

---



## 🎯 Fine-Tuning LLMs

- [poloclub/Fine-tuning-LLMs](https://github.com/poloclub/Fine-tuning-LLMs) — Colab-friendly tutorial for fine-tuning open-source LLMs (e.g., Llama-2) with QLoRA.  
- [georgian-io/LLM-Finetuning-Toolkit](https://github.com/georgian-io/LLM-Finetuning-Toolkit) — Config-driven CLI that launches and tracks experiments via YAML pipelines.  
- [dvgodoy/FineTuningLLMs](https://github.com/dvgodoy/FineTuningLLMs) — Companion code for a practical guidebook; includes quantization, LoRA, dataset prep, training, and querying.  
- [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — End-to-end fine-tuning and serving for LLaMA-family models with a clean UX.  

---



## ⚡ Quantization

- [vllm-project/llm-compressor](https://github.com/vllm-project/llm-compressor) — Algorithms like GPTQ and SmoothQuant for int8 weight/activation quantization; integrates with vLLM.  
- [facebookresearch/LLM-QAT](https://github.com/facebookresearch/LLM-QAT) — Data-free Quantization-Aware Training; supports weight, activation, and KV-cache quantization down to 4-bit.  
- [ruikangliu/FlatQuant](https://github.com/ruikangliu/FlatQuant) — Fake-quantization for W4A4 inference with vLLM; per-layer affine transform optimization.  
- [pprp/Awesome-LLM-Quantization](https://github.com/pprp/Awesome-LLM-Quantization) — Curated list of PTQ and QAT methods for LLMs.  
- [Efficient-ML/Awesome-Model-Quantization](https://github.com/Efficient-ML/Awesome-Model-Quantization) — Broader quantization landscape across models and tasks.  
- [eth-sri/llm-quantization-attack](https://github.com/eth-sri/llm-quantization-attack) — Security angle: analyses and assets on attacking quantized LLMs.  
- [📝 Blog](https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html) — Practical GPTQ primer with working examples.  

---




## 🪶 LoRA (Low-Rank Adaptation)

- [microsoft/LoRA](https://github.com/microsoft/LoRA) — The original LoRA implementation; now influences/feeds into HF PEFT.  
- [josephtkim/LoRA-fine-tune-RoBERTa](https://github.com/josephtkim/LoRA-fine-tune-RoBERTa) — Notebook showing LoRA applied to RoBERTa for Yelp polarity with strong parameter savings.  
- [tsmatz/finetune_llm_with_lora](https://github.com/tsmatz/finetune_llm_with_lora) — Hands-on LoRA walkthroughs for multiple model families.  
- [Open-Finance-Lab/FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) — Benchmarking LoRA variants on financial tasks; tracks accuracy/F1/BERTScore and cost.  
- [fshnkarimi/Fine-tuning-an-LLM-using-LoRA](https://github.com/fshnkarimi/Fine-tuning-an-LLM-using-LoRA) — Minimal example wired for quick experiments.  

---




## 🔄 Distillation

- [arcee-ai/DistillKit](https://github.com/arcee-ai/DistillKit) — Teacher-student workflows using logits and hidden states; focused on practical pipelines.  
- [horus-ai-labs/DistillFlow](https://github.com/horus-ai-labs/DistillFlow/) — Scalable, multi-strategy distillation (logits, attention, layer-wise) plus fine-tuning and resource allocation.  
- [predibase/llm_distillation_playbook](https://github.com/predibase/llm_distillation_playbook) — Industry-leaning playbook of best practices for LLM distillation in production.  
- [jongwooko/distillm](https://github.com/jongwooko/distillm) — ICML-published DistiLLM implementation with LoRA checkpoint release.  
- [haitongli/knowledge-distillation-pytorch](https://github.com/haitongli/knowledge-distillation-pytorch) — General KD templates in PyTorch you can adapt for LLMs.  
- [modelscope/easydistill](https://github.com/modelscope/easydistill) — Simple KD recipes and utilities for quick iteration.  
- [SforAiDl/KD_Lib](https://github.com/SforAiDl/KD_Lib) — Library of KD losses and strategies.  
- [Tebmer/Awesome-Knowledge-Distillation-of-LLMs](https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs) — Big-picture index of KD resources specific to LLMs.  
- [songmzhang/DSKD](https://github.com/songmzhang/DSKD) — Dataset-aware KD methods.  
- [tsitsimis/neural-network-distillation](https://github.com/tsitsimis/neural-network-distillation) — Classic KD patterns and examples.  
- [Guang000/Awesome-Dataset-Distillation](https://github.com/Guang000/Awesome-Dataset-Distillation) — Dataset distillation techniques that pair well with KD for small-data regimes.  
- [Nardien/agent-distillation](https://github.com/Nardien/agent-distillation) — Early work on distilling agentic behaviors.  
- [jdeschena/sdtt](https://github.com/jdeschena/sdtt) — Sequence-to-sequence distillation tooling.  
- [Nicolas-BZRD/llm-recipes](https://github.com/Nicolas-BZRD/llm-recipes) — Mixed bag of fine-tuning, KD, and eval recipes worth browsing.  

---



## 📚 Further Reading

- [GitHub Blog](https://github.blog/ai-and-ml/llms/customizing-and-fine-tuning-llms-what-you-need-to-know/) — Customizing and fine-tuning LLMs: what you need to know.  
- [Jack Young](https://jackyoung96.github.io/2024/08/08/llm-distillation-en/) — A readable intro to LLM distillation (2024). 
