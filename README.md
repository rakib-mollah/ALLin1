# 🔑 Key GitHub Repositories for LLM Fine-Tuning, Quantization, LoRA, and Distillation

A curated map of open-source tools to customize and optimize large language models.  
You’ll find starter tutorials and production-grade libraries across four buckets: **Fine-Tuning**, **Quantization**, **LoRA**, and **Distillation**.  

---

## 📑 Table of Contents
- [🎯 Fine-Tuning LLMs](#-fine-tuning-llms)
- [⚡ Quantization](#-quantization)
- [🪶 LoRA (Low-Rank Adaptation)](#-lora-low-rank-adaptation)
- [🔄 Distillation](#-distillation)
- [📚 Further Reading](#-further-reading)

---

## 🎯 Fine-Tuning LLMs

- 🤖 [poloclub/Fine-tuning-LLMs](https://github.com/poloclub/Fine-tuning-LLMs) — Colab-friendly tutorial for fine-tuning open-source LLMs with QLoRA.  
- 🧰 [georgian-io/LLM-Finetuning-Toolkit](https://github.com/georgian-io/LLM-Finetuning-Toolkit) — Config-driven CLI with YAML pipelines for experiment tracking.  
- 📘 [dvgodoy/FineTuningLLMs](https://github.com/dvgodoy/FineTuningLLMs) — Companion code to a practical guidebook; includes quantization, LoRA, and dataset prep.  
- 🏗️ [hiyouga/LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) — End-to-end fine-tuning and serving for LLaMA-family models.  

---

## ⚡ Quantization

- 🔧 [vllm-project/llm-compressor](https://github.com/vllm-project/llm-compressor) — Implements GPTQ and SmoothQuant; integrates with vLLM.  
- 🧮 [facebookresearch/LLM-QAT](https://github.com/facebookresearch/LLM-QAT) — Data-free Quantization-Aware Training (down to 4-bit).  
- 📐 [ruikangliu/FlatQuant](https://github.com/ruikangliu/FlatQuant) — Fake-quantization for W4A4 inference; per-layer optimization.  
- 🌍 [pprp/Awesome-LLM-Quantization](https://github.com/pprp/Awesome-LLM-Quantization) — Curated list of PTQ and QAT methods.  
- 📊 [Efficient-ML/Awesome-Model-Quantization](https://github.com/Efficient-ML/Awesome-Model-Quantization) — Broader quantization resources across models.  
- 🛡️ [eth-sri/llm-quantization-attack](https://github.com/eth-sri/llm-quantization-attack) — Security research on attacking quantized LLMs.  
- 📝 [Blog: GPTQ Primer](https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html) — Practical intro with examples.  

---

## 🪶 LoRA (Low-Rank Adaptation)

- 🏛️ [microsoft/LoRA](https://github.com/microsoft/LoRA) — Original LoRA implementation; foundation for HF PEFT.  
- 📝 [josephtkim/LoRA-fine-tune-RoBERTa](https://github.com/josephtkim/LoRA-fine-tune-RoBERTa) — LoRA applied to RoBERTa for Yelp polarity.  
- 🧪 [tsmatz/finetune_llm_with_lora](https://github.com/tsmatz/finetune_llm_with_lora) — Hands-on LoRA walkthroughs across models.  
- 💹 [Open-Finance-Lab/FinLoRA](https://github.com/Open-Finance-Lab/FinLoRA) — LoRA benchmarks on financial tasks.  
- ⚡ [fshnkarimi/Fine-tuning-an-LLM-using-LoRA](https://github.com/fshnkarimi/Fine-tuning-an-LLM-using-LoRA) — Minimal LoRA example for quick runs.  

---

## 🔄 Distillation

- 🧑‍🏫 [arcee-ai/DistillKit](https://github.com/arcee-ai/DistillKit) — Teacher-student pipelines with logits and hidden states.  
- 🌊 [horus-ai-labs/DistillFlow](https://github.com/horus-ai-labs/DistillFlow/) — Multi-strategy distillation + fine-tuning support.  
- 📒 [predibase/llm_distillation_playbook](https://github.com/predibase/llm_distillation_playbook) — Production best practices for distillation.  
- 📰 [jongwooko/distillm](https://github.com/jongwooko/distillm) — ICML DistiLLM implementation with LoRA checkpoints.  
- 🔬 [haitongli/knowledge-distillation-pytorch](https://github.com/haitongli/knowledge-distillation-pytorch) — KD templates in PyTorch.  
- 🛠️ [modelscope/easydistill](https://github.com/modelscope/easydistill) — Simple KD recipes for quick use.  
- 📚 [SforAiDl/KD_Lib](https://github.com/SforAiDl/KD_Lib) — KD loss functions and strategies.  
- 🌐 [Tebmer/Awesome-Knowledge-Distillation-of-LLMs](https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs) — Index of KD resources for LLMs.  
- 🎯 [songmzhang/DSKD](https://github.com/songmzhang/DSKD) — Dataset-aware KD methods.  
- 🔁 [tsitsimis/neural-network-distillation](https://github.com/tsitsimis/neural-network-distillation) — Classic KD patterns.  
- 🧩 [Guang000/Awesome-Dataset-Distillation](https://github.com/Guang000/Awesome-Dataset-Distillation) — Dataset distillation methods for small-data regimes.  
- 🤖 [Nardien/agent-distillation](https://github.com/Nardien/agent-distillation) — Distilling agent-like behaviors.  
- 📐 [jdeschena/sdtt](https://github.com/jdeschena/sdtt) — Seq2Seq distillation tooling.  
- 🗂️ [Nicolas-BZRD/llm-recipes](https://github.com/Nicolas-BZRD/llm-recipes) — Mix of fine-tuning, KD, and eval recipes.  

---

## 📚 Further Reading

- 📰 [GitHub Blog](https://github.blog/ai-and-ml/llms/customizing-and-fine-tuning-llms-what-you-need-to-know/) — Customizing and fine-tuning LLMs: what you need to know.  
- 📖 [Jack Young](https://jackyoung96.github.io/2024/08/08/llm-distillation-en/) — Clear introduction to LLM distillation (2024).  
