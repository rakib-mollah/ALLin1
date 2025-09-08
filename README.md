# Key GitHub Repositories for LLM Fine‑Tuning, Quantization, LoRA, and Distillation

A quick, curated map of open‑source tools you can use to customize and optimize large language models. You’ll find starter tutorials and production‑grade libraries across four buckets: **Fine‑Tuning**, **Quantization**, **LoRA (parameter‑efficient adaptation)**, and **Distillation**. Each entry links straight to the repo or article so you can dive in fast.

---

## Table of Contents
- [Fine‑Tuning LLMs](#fine-tuning-llms)
- [Quantization](#quantization)
- [LoRA](#lora-low-rank-adaptation)
- [Distillation](#distillation)
- [Further Reading](#further-reading)

---

## Fine‑Tuning LLMs

- **poloclub/Fine-tuning-LLMs** — Colab‑friendly tutorial for fine‑tuning open‑source LLMs (e.g., Llama‑2) with QLoRA.  
  https://github.com/poloclub/Fine-tuning-LLMs

- **tsmatz/finetune_llm_with_lora** — LoRA from scratch in Jupyter notebooks; walk‑throughs for OPT/GPT‑2 and more.  
  https://github.com/tsmatz/finetune_llm_with_lora

- **georgian-io/LLM-Finetuning-Toolkit** — Config‑driven CLI that launches and tracks experiments via YAML pipelines.  
  https://github.com/georgian-io/LLM-Finetuning-Toolkit

- **dvgodoy/FineTuningLLMs** — Companion code for a practical guidebook; includes quantization, LoRA, dataset prep, training, and querying.  
  https://github.com/dvgodoy/FineTuningLLMs

- **hiyouga/LLaMA-Factory** — End‑to‑end fine‑tuning and serving for LLaMA‑family models with a clean UX.  
  https://github.com/hiyouga/LLaMA-Factory

---

## Quantization

- **vllm-project/llm-compressor** — Algorithms like GPTQ and SmoothQuant for int8 weight/activation quantization; integrates with vLLM.  
  https://github.com/vllm-project/llm-compressor

- **facebookresearch/LLM-QAT** — Data‑free Quantization‑Aware Training; supports weight, activation, and KV‑cache quantization down to 4‑bit.  
  https://github.com/facebookresearch/LLM-QAT

- **ruikangliu/FlatQuant** — Fake‑quantization for W4A4 inference with vLLM; per‑layer affine transform optimization.  
  https://github.com/ruikangliu/FlatQuant

- **pprp/Awesome-LLM-Quantization** — Curated list of PTQ and QAT methods for LLMs.  
  https://github.com/pprp/Awesome-LLM-Quantization

- **Efficient-ML/Awesome-Model-Quantization** — Broader quantization landscape across models and tasks.  
  https://github.com/Efficient-ML/Awesome-Model-Quantization

- **eth-sri/llm-quantization-attack** — Security angle: analyses and assets on attacking quantized LLMs.  
  https://github.com/eth-sri/llm-quantization-attack

- **Blog** — Practical GPTQ primer with working examples.  
  https://mlabonne.github.io/blog/posts/4_bit_Quantization_with_GPTQ.html

---

## LoRA (Low‑Rank Adaptation)

- **microsoft/LoRA** — The original LoRA implementation; now influences/feeds into HF PEFT.  
  https://github.com/microsoft/LoRA

- **josephtkim/LoRA-fine-tune-RoBERTa** — Notebook showing LoRA applied to RoBERTa for Yelp polarity with strong parameter savings.  
  https://github.com/josephtkim/LoRA-fine-tune-RoBERTa

- **tsmatz/finetune_llm_with_lora** — Listed above; hands‑on LoRA walkthroughs for multiple model families.  
  https://github.com/tsmatz/finetune_llm_with_lora

- **Open-Finance-Lab/FinLoRA** — Benchmarking LoRA variants on financial tasks; tracks accuracy/F1/BERTScore and cost.  
  https://github.com/Open-Finance-Lab/FinLoRA

- **fshnkarimi/Fine-tuning-an-LLM-using-LoRA** — Minimal example wired for quick experiments.  
  https://github.com/fshnkarimi/Fine-tuning-an-LLM-using-LoRA

---

## Distillation

- **arcee-ai/DistillKit** — Teacher‑student workflows using logits and hidden states; focused on practical pipelines.  
  https://github.com/arcee-ai/DistillKit

- **horus-ai-labs/DistillFlow** — Scalable, multi‑strategy distillation (logits, attention, layer‑wise) plus fine‑tuning and resource allocation.  
  https://github.com/horus-ai-labs/DistillFlow/

- **predibase/llm_distillation_playbook** — Industry‑leaning playbook of best practices for LLM distillation in production.  
  https://github.com/predibase/llm_distillation_playbook

- **jongwooko/distillm** — ICML‑published DistiLLM implementation with LoRA checkpoint release.  
  https://github.com/jongwooko/distillm

- **haitongli/knowledge-distillation-pytorch** — General KD templates in PyTorch you can adapt for LLMs.  
  https://github.com/haitongli/knowledge-distillation-pytorch

- **modelscope/easydistill** — Simple KD recipes and utilities for quick iteration.  
  https://github.com/modelscope/easydistill

- **SforAiDl/KD_Lib** — Library of KD losses and strategies.  
  https://github.com/SforAiDl/KD_Lib

- **Tebmer/Awesome-Knowledge-Distillation-of-LLMs** — Big‑picture index of KD resources specific to LLMs.  
  https://github.com/Tebmer/Awesome-Knowledge-Distillation-of-LLMs

- **songmzhang/DSKD** — Dataset‑aware KD methods.  
  https://github.com/songmzhang/DSKD

- **tsitsimis/neural-network-distillation** — Classic KD patterns and examples.  
  https://github.com/tsitsimis/neural-network-distillation

- **Guang000/Awesome-Dataset-Distillation** — Dataset distillation techniques that pair well with KD for small‑data regimes.  
  https://github.com/Guang000/Awesome-Dataset-Distillation

- **Nardien/agent-distillation** — Early work on distilling agentic behaviors.  
  https://github.com/Nardien/agent-distillation

- **jdeschena/sdtt** — Sequence‑to‑sequence distillation tooling.  
  https://github.com/jdeschena/sdtt

- **Nicolas-BZRD/llm-recipes** — Mixed bag of fine‑tuning, KD, and eval recipes worth browsing.  
  https://github.com/Nicolas-BZRD/llm-recipes

- **Topic search** — Explore the wider space via GitHub topic aggregations.  
  https://github.com/topics/distillation-model?o=desc&s=forks

---

## Further Reading

- **GitHub Blog** — Customizing and fine‑tuning LLMs: what you need to know.  
  https://github.blog/ai-and-ml/llms/customizing-and-fine-tuning-llms-what-you-need-to-know/

- **Jack Young** — A readable intro to LLM distillation (2024).  
  https://jackyoung96.github.io/2024/08/08/llm-distillation-en/
