# LM-SSP

The resources related to the safety, security, and privacy (SSP) of large models (LM).
Here LM contains large language models (LLMs), large vision-language models (LVMs), diffusion models, and so on.

- This repo is in progress 🌱 (currently manually collected)

- Welcome to recommend resources to us (via Issue/Pull request/[Email](thu_crypto_ai@163.com)/...)!

- Tags:
![img](https://img.shields.io/badge/blog/paper/book-18a5ab)
![img](https://img.shields.io/badge/code-8B8989)
![img](https://img.shields.io/badge/defense-87b800)
![img](https://img.shields.io/badge/llm-c7688b)
![img](https://img.shields.io/badge/vlm-589cf4)
![img](https://img.shields.io/badge/diffusion-a99cf4)
![img](https://img.shields.io/badge/conference-f1b800)


# News
- 🔥🔥🔥 [2024-01-09] Add 7 papers from [NeurIPS'23](https://openreview.net/group?id=NeurIPS.cc/2023/Conference#tab-accept-oral)
- 🔥🔥🔥 [2024-01-09] Add 8 papers from [CCS'23](https://www.sigsac.org/ccs/CCS2023/program.html)

# Books

- [2024/01] **NIST Trustworthy and Responsible AI Reports** [![img](https://img.shields.io/badge/book-18a5ab)](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf) 

# Surveys
- [2023/12] **A Survey on Large Language Model (LLM) Security and Privacy: The Good, the Bad, and the Ugly** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.02003) 
- [2023/07] **A Comprehensive Overview of Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2307.06435) 

# Papers

## Content
- **Safety**: [Jailbreak](#sec-a1), [Safety Alignment](#sec-a2), [Toxicity](#sec-a3), [Deepfake](#sec-a4), [Agent](#sec-a5), [Hallucination](#sec-a6)
- **Security**: [Adversarial Attacks](#sec-b1), [Code Generation](#sec-b2), [Backdoor/Poisoning](#sec-b3)
- **Privacy**: [Data Reconstruction](#sec-c1), [Membership Inference](#sec-c2), [Property Inference](#sec-c3), [Extraction (Model/Prompt/Hyperparameters)](#sec-c4), [Unlearning](#sec-c5), [Copyright](#sec-c6)

## A. Safety <a name="sec-a"></a>
### A1. Jailbreak <a name="sec-a1"></a>
- [2024/01] **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs** [![img](https://img.shields.io/badge/paper-18a5ab)](https://www.yi-zeng.com/wp-content/uploads/2024/01/view.pdf) ![img](https://img.shields.io/badge/llm-c7688b)
- [2024/01] **MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2401.02906) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/pipilurj/MLLM-protector) ![img](https://img.shields.io/badge/vlm-589cf4) ![img](https://img.shields.io/badge/defense-87b800) 
- [2023/12] **Adversarial Attacks on GPT-4 via Simple Random Search** [![img](https://img.shields.io/badge/paper-18a5ab)](https://www.andriushchenko.me/gpt4adv.pdf) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/12] **Make Them Spill the Beans! Coercive Knowledge Extraction from (Production) LLMs** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.04782) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/11] **FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.05608) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/ThuCCSLab/FigStep) ![img](https://img.shields.io/badge/vlm-589cf4) 
- [2023/10] **Adversarial Attacks on LLMs** [![img](https://img.shields.io/badge/blog-18a5ab)](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.04451) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/SheltonLiu-N/AutoDAN) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.04451) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **Catastrophic Jailbreak of Open-source LLMs via Exploiting Generation** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.06987) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/Princeton-SysML/Jailbreak_LLM) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2309.10253) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/sherdencooper/GPTFuzz) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **Jailbreaking Black Box Large Language Models in Twenty Queries** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.08419) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/patrickrchao/JailbreakingLLMs) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/09] **Open Sesame! Universal Black Box Jailbreaking of Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2309.01446) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/08] **Detecting Language Model Attacks with Perplexity** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.14132) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800) 
- [2023/08] **GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.06463) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/RobustNLP/CipherChat) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/07] **MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2307.08715) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/NDSS'24-f1b800)
- [2023/07] **Jailbroken: How Does LLM Safety Training Fail?** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2307.02483) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
- [2023/07] **Universal and Transferable Adversarial Attacks on Aligned Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2307.15043) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/llm-attacks/llm-attacks) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/06] **DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2306.11698) [![img](https://img.shields.io/badge/code-8B8989)](https://decodingtrust.github.io/) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/NeurIPS'23%20(Outstanding%20Paper)-f1b800)

### A2. Safety Alignment <a name="sec-a2"></a>
- [2024/01] **A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/pdf/2401.01967.pdf) 
- [2023/12] **Exploiting Novel GPT-4 APIs** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.14302) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.03693) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.02949v1) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/BeyonderXX/ShadowAlignment) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **UltraFeedback: Boosting Language Models with High-quality Feedback** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.01377) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/OpenBMB/UltraFeedback) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800)

### A3. Toxicity <a name="sec-a3"></a>
- [2023/11] **Comprehensive Assessment of Toxicity in ChatGPT** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.14685) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/10] **On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.16613) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2023/08] **You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.05596) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/S&P'24-f1b800)
- [2023/05] **Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2305.13873) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)

### A4. Deepfake <a name="sec-a4"></a>
- [2023/05] **Evading Watermark based Detection of AI-Generated Content** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2305.03807) ![img](https://img.shields.io/badge/CCS'23-f1b800)
- [2023/03] **MGTBench: Benchmarking Machine-Generated Text Detection** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2303.14822) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/xinleihe/MGTBench) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2022/10] **DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Generation Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2210.06998) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)

### A5. Agent <a name="sec-a5"></a>
- [2023/11] **Evil Geniuses: Delving into the Safety of LLM-based Agents** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.11855) ![img](https://img.shields.io/badge/llm-c7688b)

### A6. Hallucination <a name="sec-a6"></a>
- [2023/12] **The Earth is Flat because...: Investigating LLMs' Belief towards Misinformation via Persuasive Conversation** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.09085) [![img](https://img.shields.io/badge/code-8B8989)](https://llms-believe-the-earth-is-flat.github.io/) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/11] **Calibrated Language Models Must Hallucinate**  [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.14648) ![img](https://img.shields.io/badge/llm-c7688b)

## B. Security <a name="sec-b"></a>
### B1. Adversarial Attacks <a name="sec-b1"></a>
- [2024/01] **INSTRUCTTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/pdf/2312.01886.pdf) ![img](https://img.shields.io/badge/vlm-589cf4)
- [2023/11] **DiffAttack: Evasion Attacks Against Diffusion-Based Adversarial Purification**  [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.16124) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/kangmintong/DiffAttack) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
- [2023/08] **Robustness Over Time: Understanding Adversarial Examples' Effectiveness on Longitudinal Versions of Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.07847) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/06] **PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2306.04528) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/06] **Are aligned neural networks adversarially aligned?** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2306.15447) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
- [2023/06] **Stable Diffusion is Unstable**  [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2306.02583) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800) 
- [2022/05] **Diffusion Models for Adversarial Purification** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2205.07460) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/defense-87b800) ![img](https://img.shields.io/badge/ICML'22-f1b800) 

### B2. Code Generation <a name="sec-b2"></a>
- [2023/02] **Large Language Models for Code: Security Hardening and Adversarial Testing** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2302.05319) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/CCS'23_(Distinguished_paper)-f1b800)
- [2022/11] **Do Users Write More Insecure Code with AI Assistants?** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2211.03622) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/CCS'23-f1b800)

### B3. Backdoor/Poisoning <a name="sec-b3"></a>
- [2023/12] **Unleashing Cheapfakes through Trojan Plugins of Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.00374) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/10] **Composite Backdoor Attacks Against Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.07676) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/10] **Prompt Backdoors in Visual Prompt Learning** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.07676) ![img](https://img.shields.io/badge/vlm-589cf4)
- [2023/05] **Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2305.14710)  ![img](https://img.shields.io/badge/llm-c7688b)
- [2022/11] **LMSanitator: Defending Prompt-Tuning Against Task-Agnostic Backdoors** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/pdf/2308.13904.pdf) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/meng-wenlong/LMSanitator) ![img](https://img.shields.io/badge/defense-87b800) ![img](https://img.shields.io/badge/NDSS'24-f1b800)

## C. Privacy <a name="sec-c"></a>
### C1. Data Reconstruction <a name="sec-c1"></a>
- [2023/11] **Language Model Inversion** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.13647) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/11] **Scalable Extraction of Training Data from (Production) Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.17035) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/01] **Extracting Training Data from Diffusion Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://www.usenix.org/system/files/usenixsecurity23-carlini.pdf) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/Security'23-f1b800)
- [2020/12] **Extracting Training Data from Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2012.07805) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/Security'21-f1b800)

### C2. Membership Inference <a name="sec-c2"></a>
- [2023/12] **Black-box Membership Inference Attacks against Fine-tuned Diffusion Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.08207) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2023/11] **Practical Membership Inference Attacks against Fine-tuned Large Language Models via Self-prompt Calibration** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2311.06062) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/10] **Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.11397) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/09] **DP-Forward: Fine-tuning and Inference on Language Models with Differential Privacy in Forward Pass** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2309.06746) ![img](https://img.shields.io/badge/defense-87b800) ![img](https://img.shields.io/badge/CCS'23-f1b800)
- [2023/08] **White-box Membership Inference Attacks against Diffusion Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.06405) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2022/10] **Membership Inference Attacks Against Text-to-image Generation Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2210.00968) ![img](https://img.shields.io/badge/diffusion-a99cf4)

### C3. Property Inference <a name="sec-c3"></a>
- [2023/10] **Beyond Memorization: Violating Privacy Via Inference with Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.07298) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/07] **ProPILE: Probing Privacy Leakage in Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2307.01881) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)


### C4. Extraction (Model/Prompt/Hyperparameters) <a name="sec-c4"></a>
- [2023/03] **Stealing the Decoding Algorithms of Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2303.04729) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/CCS'23_(Distinguished_paper)-f1b800)
- [2023/02] **Prompt Stealing Attacks Against Text-to-Image Generation Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2302.09923) ![img](https://img.shields.io/badge/diffusion-a99cf4)

### C5. Unlearning <a name="sec-c5"></a>
- [2023/11] **Detecting Pretraining Data from Large Language Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.16789) [![img](https://img.shields.io/badge/code-8B8989)]([![img](https://img.shields.io/badge/code-8B8989)](https://github.com/meng-wenlong/LMSanitator)) ![img](https://img.shields.io/badge/llm-c7688b)
- [2023/10] **Unlearn What You Want to Forget: Efficient Unlearning for LLMs** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.20150) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800) 
- [2023/10] **Who's Harry Potter? Approximate Unlearning in LLMs** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2310.02238?s=08) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800) 
- [2023/03] **Erasing Concepts from Diffusion Models** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2303.07345) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/defense-87b800) 

### C6. Copyright <a name="sec-c6"></a>
- [2024/01] **Generative AI Has a Visual Plagiarism Problem** [![img](https://img.shields.io/badge/blog-18a5ab)](https://spectrum.ieee.org/midjourney-copyright) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2023/12] **Mark My Words: Analyzing and Evaluating Language Model Watermarks** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2312.00273) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/wagner-group/MarkMyWords) ![img](https://img.shields.io/badge/llm-c7688b) 
- [2023/11] **Protecting Intellectual Property of Large Language Model-Based Code Generation APIs via Watermarks** [![img](https://img.shields.io/badge/paper-18a5ab)](https://dl.acm.org/doi/abs/10.1145/3576915.3623120) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800)  ![img](https://img.shields.io/badge/CCS'23-f1b800)
- [2023/08] **PromptCARE: Prompt Copyright Protection by Watermark Injection and Verification**  [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2308.02816) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/grasses/PromptCARE) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800)  ![img](https://img.shields.io/badge/S&P'24-f1b800)
- [2023/06] **Generative Watermarking Against Unauthorized Subject-Driven Image Synthesis** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2306.07754) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2023/05] **Watermarking Diffusion Model** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2305.12502) ![img](https://img.shields.io/badge/diffusion-a99cf4)
- [2023/05] **Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust** [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2305.20030) [![img](https://img.shields.io/badge/code-8B8989)](https://github.com/YuxinWenRick/tree-ring-watermark) ![img](https://img.shields.io/badge/diffusion-a99cf4) ![img](https://img.shields.io/badge/defense-87b800)  ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
- [2023/01] **A Watermark for Large Language Models**  [![img](https://img.shields.io/badge/paper-18a5ab)](https://arxiv.org/abs/2301.10226) [![img](https://img.shields.io/badge/code-8B8989)](github.com/jwkirchenbauer/lm-watermarking) ![img](https://img.shields.io/badge/llm-c7688b) ![img](https://img.shields.io/badge/defense-87b800)  ![img](https://img.shields.io/badge/ICML'23_(Outstanding_paper)-f1b800)
