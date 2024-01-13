<img src="figure/title.png" alt="image" width="1000" height="auto" class="center">

# Introduction 

The resources related to the trustworthiness of large models (LMs) across multiple dimensions (e.g., safety, security, and privacy),                  with a special focus on multi-modal LMs (e.g., vision-language models and diffusion models). 

- This repo is in progress :seedling: (currently manually collected).
- Welcome to recommend resources to us (via <a href="https://github.com/ThuCCSLab/lm-ssp/issues">                 <img src="https://icons.iconarchive.com/icons/github/octicons/128/issue-opened-16-icon.png" width="15" height="15"></a>                 Issues / <a href="https://github.com/ThuCCSLab/lm-ssp/pulls"><img src="https://icons.iconarchive.com/icons/iconoir-team/iconoir/128/git-pull-request-icon.png"                  width="17" height="17"></a> Pull requests / <a href="mailto:thu_crypto_ai@163.com"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/solid/envelope-open.svg"                 width="15" height="15"></a> Email / ...)!
- Badges: 

    - Model: ![img](https://img.shields.io/badge/llm-589cf4) ![img](https://img.shields.io/badge/vlm-c7688b)  ![img](https://img.shields.io/badge/diffusion-a99cf4) 

    - Comment: ![img](https://img.shields.io/badge/benchmark-87b800) ![img](https://img.shields.io/badge/new_dataset-87b800) ![img](https://img.shields.io/badge/agent-87b800)                 ![img](https://img.shields.io/badge/codeGen-87b800) ![img](https://img.shields.io/badge/defense-87b800) 

   - Venue (Continuous update): ![img](https://img.shields.io/badge/conference-f1b800) or ![img](https://img.shields.io/badge/blog-f1b800)

 

# Book

-  [2024/01] **[NIST Trustworthy and Responsible AI Reports](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-2e2023.pdf)**

# Survey

-  [2024/01] **[TrustLLM: Trustworthiness in Large Language Models](https://arxiv.org/abs/2401.05561)** <a href="https://github.com/HowieHwong/TrustLLM"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/12] **[A Survey on Large Language Model (LLM) Security and Privacy: The Good, the Bad, and the Ugly](https://arxiv.org/abs/2312.02003)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks](https://arxiv.org/abs/2310.10844)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models' Alignment](https://arxiv.org/abs/2308.05374)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/07] **[A Comprehensive Overview of Large Language Models](https://arxiv.org/abs/2307.06435)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/06] **[DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs/2306.11698)** <a href="https://decodingtrust.github.io/"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800) ![img](https://img.shields.io/badge/Best_paper-ff0000)
-  [2023/03] **[A Survey of Large Language Models](https://arxiv.org/abs/2303.18223)** ![img](https://img.shields.io/badge/LLM-589cf4)

# Paper

<img src="figure/map.png" alt="image" width="1000" height="auto" class="center">



## A. Security


### A1. Adversarial Examples

-  [2024/01] **[INSTRUCTTA: Instruction-Tuned Targeted Attack for Large Vision-Language Models](https://arxiv.org/abs/2312.01886)** ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/11] **[How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs](https://arxiv.org/abs/2311.16101)** <a href="https://github.com/UCSC-VLAA/vllm-safety-benchmark"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/Benchmark-87b800)
-  [2023/11] **[DiffAttack: Evasion Attacks Against Diffusion-Based Adversarial Purification](https://arxiv.org/abs/2311.16124)** <a href="https://github.com/kangmintong/DiffAttack"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/11] **[Can Protective Perturbation Safeguard Personal Data from Being Exploited by Stable Diffusion?](https://arxiv.org/abs/2312.00084)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/Defense-87b800)
-  [2023/10] **[Misusing Tools in Large Language Models With Visual Adversarial Examples](https://arxiv.org/abs/2310.03185)** ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/09] **[How Robust is Google's Bard to Adversarial Image Attacks?](https://arxiv.org/abs/2309.11751)** <a href="https://github.com/thu-ml/Attack-Bard"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/09] **[Image Hijacks: Adversarial Images Can Control Generative Models at Runtime](https://arxiv.org/abs/2309.00236)** <a href="https://github.com/euanong/image-hijacks"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/08] **[Ceci n'est pas une pomme: Adversarial Illusions in Multi-Modal Embeddings](https://arxiv.org/abs/2308.11804)** <a href="https://github.com/ebagdasa/adversarial_illusions"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/08] **[On the Adversarial Robustness of Multi-Modal Foundation Models](https://arxiv.org/abs/2308.10741)** ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/ICCV'23_(AROW_Workshop)-f1b800)
-  [2023/08] **[Robustness Over Time: Understanding Adversarial Examples' Effectiveness on Longitudinal Versions of Large Language Models](https://arxiv.org/abs/2308.07847)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/07] **[Jailbreak in Pieces: Compositional Adversarial Attacks on Multi-Modal Language Models](https://arxiv.org/abs/2307.14539)** ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/06] **[Adversarial Examples in the Age of ChatGPT](http://spylab.ai/blog/chatbot-adversarial-examples/)** ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/Blog-f1b800)
-  [2023/06] **[Visual Adversarial Examples Jailbreak Large Language Models](https://arxiv.org/abs/2306.13213)** <a href="https://github.com/Unispac/Visual-Adversarial-Examples-Jailbreak-Large-Language-Models"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/06] **[Stable Diffusion is Unstable](https://arxiv.org/abs/2306.02583)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/06] **[Unlearnable Examples for Diffusion Models: Protect Data from Unauthorized Exploitation](https://arxiv.org/abs/2306.01902)** <a href="https://github.com/ZhengyueZhao/EUDP"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4)
-  [2023/06] **[PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts](https://arxiv.org/abs/2306.04528)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Benchmark-87b800)
-  [2023/06] **[Adversarial examples in the age of ChatGPT](http://spylab.ai/blog/chatbot-adversarial-examples/)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Blog-f1b800)
-  [2023/06] **[Are aligned neural networks adversarially aligned?](https://arxiv.org/abs/2306.15447)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/05] **[On evaluating adversarial robustness of large vision-language models](https://arxiv.org/abs/2305.16934)** <a href="https://github.com/yunqing-me/AttackVLM"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/03] **[Anti-DreamBooth: Protecting Users from Personalized Text-to-Image Synthesis](https://arxiv.org/abs/2303.15433)** <a href="https://github.com/VinAIResearch/Anti-DreamBooth"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/ICCV'23-f1b800)
-  [2023/02] **[Adversarial Example Does Good: Preventing Painting Imitation from Diffusion Models via Adversarial Examples](https://arxiv.org/abs/2302.04578)** <a href="https://github.com/mist-project/mist"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/ICML'23-f1b800)
-  [2023/02] **[Raising the Cost of Malicious AI-Powered Image Editing](https://arxiv.org/abs/2302.06588)** <a href="https://github.com/MadryLab/photoguard"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/ICML'23-f1b800)
-  [2022/12] **[Understanding Zero-shot Adversarial Robustness for Large-Scale Model](https://arxiv.org/abs/2212.07016)** <a href="https://github.com/cvlab-columbia/ZSRobust4FoundationModel"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/ICLR'23-f1b800)

### A2. Code Generation Security

-  [2024/01] **[DebugBench: Evaluating Debugging Capability of Large Language Models](https://arxiv.org/abs/2401.04621)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/02] **[Large Language Models for Code: Security Hardening and Adversarial Testing](https://arxiv.org/abs/2302.05319)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800) ![img](https://img.shields.io/badge/Best_paper-ff0000)
-  [2022/11] **[Do Users Write More Insecure Code with AI Assistants?](https://arxiv.org/abs/2211.03622)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)

### A3. Poisoning (Backdoor/Targeted/Indiscriminate) 

-  [2024/01] **[Sleeper Agents: Training Deceptive LLMs that Persist Through Safety Training](https://arxiv.org/abs/2401.05566)** <a href="https://github.com/anthropics/sleeper-agents-paper"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/12] **[Unleashing Cheapfakes through Trojan Plugins of Large Language Models](https://arxiv.org/abs/2312.00374)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[Universal Jailbreak Backdoors from Poisoned Human Feedback](https://arxiv.org/abs/2311.14455)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[Test-time Backdoor Mitigation for Black-Box Large Language Models with Defensive Demonstrations](https://arxiv.org/abs/2311.09763)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Defense-87b800)
-  [2023/10] **[Composite Backdoor Attacks Against Large Language Models](https://arxiv.org/abs/2310.07676)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[The Poison of Alignment](https://arxiv.org/abs/2308.13449)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[LMSanitator: Defending Prompt-Tuning Against Task-Agnostic Backdoors](https://arxiv.org/abs/2308.13904)** <a href="https://github.com/meng-wenlong/LMSanitator"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NDSS'24-f1b800)
-  [2023/07] **[Backdooring Instruction-Tuned Large Language Models with Virtual Prompt Injection](https://arxiv.org/abs/2307.16888)** <a href="https://github.com/wegodev2/virtual-prompt-injection"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/06] **[On the Exploitability of Instruction Tuning](https://arxiv.org/abs/2306.17194)** <a href="https://github.com/azshue/AutoPoison"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/05] **[Poisoning Language Models During Instruction Tuning](https://arxiv.org/abs/2305.00944)** <a href="https://github.com/AlexWan0/Poisoning-Instruction-Tuned-Models"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/ICML'23-f1b800)
-  [2023/05] **[Instructions as Backdoors: Backdoor Vulnerabilities of Instruction Tuning for Large Language Models](https://arxiv.org/abs/2305.14710)** ![img](https://img.shields.io/badge/LLM-589cf4)

## B. Safety


### B1. Deepfake

-  [2023/05] **[Evading Watermark based Detection of AI-Generated Content](https://arxiv.org/abs/2305.03807)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)
-  [2023/03] **[Can AI-Generated Text be Reliably Detected?](https://arxiv.org/abs/2303.11156)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/03] **[MGTBench: Benchmarking Machine-Generated Text Detection](https://arxiv.org/abs/2303.14822)** <a href="https://github.com/xinleihe/MGTBench"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2022/12] **[CoCo: Coherence-Enhanced Machine-Generated Text Detection Under Data Limitation With Contrastive Learning](https://arxiv.org/abs/2212.10341)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2022/10] **[DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Generation Models](https://arxiv.org/abs/2210.06998)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)

### B2. Hallucination

-  [2023/12] **[The Earth is Flat because...: Investigating LLMs' Belief towards Misinformation via Persuasive Conversation](https://arxiv.org/abs/2312.09085)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[Calibrated Language Models Must Hallucinate](https://arxiv.org/abs/2311.14648)** ![img](https://img.shields.io/badge/LLM-589cf4)

### B3. Jailbreak

-  [2024/01] **[How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLM](https://www.yi-zeng.com/wp-content/uploads/2024/01/view.pdf)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2024/01] **[MLLM-Protector: Ensuring MLLM's Safety without Hurting Performance](https://arxiv.org/abs/2401.02906)** <a href="https://github.com/pipilurj/MLLM-protector"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/Defense-87b800)
-  [2023/12] **[A Mutation-Based Method for Multi-Modal Jailbreaking Attack Detection](https://arxiv.org/abs/2312.10766)** ![img](https://img.shields.io/badge/VLM-c7688b) ![img](https://img.shields.io/badge/Defense-87b800)
-  [2023/12] **[Adversarial Attacks on GPT-4 via Simple Random Search](https://www.andriushchenko.me/gpt4adv.pdf)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/12] **[Make Them Spill the Beans! Coercive Knowledge Extraction from (Production) LLMs](https://arxiv.org/abs/2312.04782)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CodeGen-87b800)
-  [2023/11] **[FigStep: Jailbreaking Large Vision-language Models via Typographic Visual Prompts](https://arxiv.org/abs/2311.05608)** <a href="https://github.com/ThuCCSLab/FigStep"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/11] **[Evil Geniuses: Delving into the Safety of LLM-based Agents](https://arxiv.org/abs/2311.11855)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Agent-87b800)
-  [2023/10] **[Jailbreak and Guard Aligned Language Models with Only Few In-Context Demonstrations](https://arxiv.org/abs/2310.06387)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Adversarial Attacks on LLMs](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Blog-f1b800)
-  [2023/10] **[AutoDAN: Generating Stealthy Jailbreak Prompts on Aligned Large Language Models](https://arxiv.org/abs/2310.04451)** <a href="https://github.com/SheltonLiu-N/AutoDAN"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models](https://arxiv.org/abs/2310.15140)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Catastrophic Jailbreak of Open-source LLMs via Exploiting Generation](https://arxiv.org/abs/2310.06987)** <a href="https://github.com/Princeton-SysML/Jailbreak_LLM"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Jailbreaking Black Box Large Language Models in Twenty Queries](https://arxiv.org/abs/2310.08419)** <a href="https://github.com/patrickrchao/JailbreakingLLMs"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/09] **[GPTFUZZER: Red Teaming Large Language Models with Auto-Generated Jailbreak Prompts](https://arxiv.org/abs/2309.10253)** <a href="https://github.com/sherdencooper/GPTFuzz"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/09] **[Open Sesame! Universal Black Box Jailbreaking of Large Language Models](https://arxiv.org/abs/2309.01446)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[Detecting Language Model Attacks with Perplexity](https://arxiv.org/abs/2308.14132)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Defense-87b800)
-  [2023/08] **[“Do Anything Now”: Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models](https://arxiv.org/abs/2308.03825)** <a href="https://github.com/verazuo/jailbreak_llms"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher](https://arxiv.org/abs/2308.06463)** <a href="https://github.com/RobustNLP/CipherChat"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/07] **[MasterKey: Automated Jailbreak Across Multiple Large Language Model Chatbots](https://arxiv.org/abs/2307.08715)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NDSS'24-f1b800)
-  [2023/07] **[Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/07] **[Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043)** <a href="https://github.com/llm-attacks/llm-attacks"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)

### B4. Safety Alignment

-  [2024/01] **[Agent Alignment in Evolving Social Norms](https://arxiv.org/abs/2401.04620)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Agent-87b800)
-  [2023/12] **[Exploiting Novel GPT-4 APIs](https://arxiv.org/abs/2312.14302)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://arxiv.org/abs/2310.03693)** <a href="https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models](https://arxiv.org/abs/2310.02949v1)** <a href="https://github.com/BeyonderXX/ShadowAlignment"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content](https://arxiv.org/abs/2308.05596)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/S&P'24-f1b800)

### B5. Toxicity

-  [2024/01] **[A Mechanistic Understanding of Alignment Algorithms: A Case Study on DPO and Toxicity](https://arxiv.org/abs/2401.01967)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[On the Proactive Generation of Unsafe Images From Text-To-Image Models Using Benign Prompts](https://arxiv.org/abs/2310.16613)** ![img](https://img.shields.io/badge/VLM-c7688b)
-  [2023/05] **[Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models](https://arxiv.org/abs/2305.13873)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800)

## C. Privacy


### C1. Copyright

-  [2024/01] **[Generative AI Has a Visual Plagiarism Problem](https://spectrum.ieee.org/midjourney-copyright)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/Blog-f1b800)
-  [2023/12] **[Mark My Words: Analyzing and Evaluating Language Model Watermarks](https://arxiv.org/abs/2312.00273)** <a href="https://github.com/wagner-group/MarkMyWords"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[A Robust Semantics-based Watermark for Large Language Model against Paraphrasing](https://arxiv.org/abs/2311.08721)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[Protecting Intellectual Property of Large Language Model-Based Code Generation APIs via Watermarks](https://dl.acm.org/doi/abs/10.1145/3576915.3623120)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CodeGen-87b800) ![img](https://img.shields.io/badge/CCS'23-f1b800)
-  [2023/08] **[PromptCARE: Prompt Copyright Protection by Watermark Injection and Verification](https://arxiv.org/abs/2308.02816)** <a href="https://github.com/grasses/PromptCARE"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/S&P'24-f1b800)
-  [2023/06] **[Generative Watermarking Against Unauthorized Subject-Driven Image Synthesis](https://arxiv.org/abs/2306.07754)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)
-  [2023/05] **[Watermarking Diffusion Model](https://arxiv.org/abs/2305.12502)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)
-  [2023/05] **[Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust](https://arxiv.org/abs/2305.20030)** <a href="https://github.com/YuxinWenRick/tree-ring-watermark"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)
-  [2023/02] **[Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models](https://arxiv.org/abs/2302.04222)** <a href="https://glaze.cs.uchicago.edu/"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Security'23-f1b800) ![img](https://img.shields.io/badge/Best_paper-ff0000)
-  [2023/01] **[A Watermark for Large Language Models](https://arxiv.org/abs/2301.10226)** <a href="github.com/jwkirchenbauer/lm-watermarking"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/ICML'23-f1b800) ![img](https://img.shields.io/badge/Best_paper-ff0000)

### C2. Data Reconstruction

-  [2023/11] **[Language Model Inversion](https://arxiv.org/abs/2311.13647)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/11] **[Scalable Extraction of Training Data from (Production) Language Models](https://arxiv.org/abs/2311.17035)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/01] **[Extracting Training Data from Diffusion Models](https://arxiv.org/abs/2301.13188)** ![img](https://img.shields.io/badge/Diffusion-a99cf4) ![img](https://img.shields.io/badge/Security'23-f1b800)
-  [2020/12] **[Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Security'21-f1b800)

### C3. Extraction (Model/Prompt/Hyperparameters)

-  [2023/03] **[On Extracting Specialized Code Abilities from Large Language Models: A Feasibility Study](https://arxiv.org/abs/2303.03012)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/ICSE'24-f1b800)
-  [2023/03] **[Stealing the Decoding Algorithms of Language Models](https://arxiv.org/abs/2303.04729)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/CCS'23-f1b800) ![img](https://img.shields.io/badge/Best_paper-ff0000)
-  [2023/02] **[Prompt Stealing Attacks Against Text-to-Image Generation Models](https://arxiv.org/abs/2302.09923)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)

### C4. Membership Inference

-  [2023/12] **[Black-box Membership Inference Attacks against Fine-tuned Diffusion Models](https://arxiv.org/abs/2312.08207)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)
-  [2023/11] **[Practical Membership Inference Attacks against Fine-tuned Large Language Models via Self-prompt Calibration](https://arxiv.org/abs/2311.06062)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Last One Standing: A Comparative Analysis of Security and Privacy of Soft Prompt Tuning, LoRA, and In-Context Learning](https://arxiv.org/abs/2310.11397)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/09] **[DP-Forward: Fine-tuning and Inference on Language Models with Differential Privacy in Forward Pass](https://arxiv.org/abs/2309.06746)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/Defense-87b800) ![img](https://img.shields.io/badge/CCS'23-f1b800)
-  [2023/09] **[Privacy Side Channels in Machine Learning Systems](https://arxiv.org/abs/2309.05610)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/08] **[White-box Membership Inference Attacks against Diffusion Models](https://arxiv.org/abs/2308.06405)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)
-  [2022/10] **[Membership Inference Attacks Against Text-to-image Generation Models](https://arxiv.org/abs/2210.00968)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)

### C5. Property Inference

-  [2023/10] **[Beyond Memorization: Violating Privacy Via Inference with Large Language Models](https://arxiv.org/abs/2310.07298)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/07] **[ProPILE: Probing Privacy Leakage in Large Language Models](https://arxiv.org/abs/2307.01881)** ![img](https://img.shields.io/badge/LLM-589cf4) ![img](https://img.shields.io/badge/NeurIPS'23-f1b800)

### C6. Unlearning

-  [2023/10] **[Detecting Pretraining Data from Large Language Models](https://arxiv.org/abs/2310.16789)** <a href="https://swj0419.github.io/detect-pretrain.github.io/"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Large Language Model Unlearning](https://arxiv.org/abs/2310.10683)** <a href="https://github.com/kevinyaobytedance/llm_unlearn"><img src="https://github.com/FortAwesome/Font-Awesome/blob/6.x/svgs/brands/github.svg" width="15" height="15"></a> ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[In-Context Unlearning: Language Models as Few Shot Unlearners](https://arxiv.org/abs/2310.07579)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Unlearn What You Want to Forget: Efficient Unlearning for LLMs](https://arxiv.org/abs/2310.20150)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/10] **[Who's Harry Potter? Approximate Unlearning in LLMs](https://arxiv.org/abs/2310.02238?s=08)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/07] **[Right to be Forgotten in the Era of Large Language Models: Implications, Challenges, and Solutions](https://arxiv.org/abs/2307.03941)** ![img](https://img.shields.io/badge/LLM-589cf4)
-  [2023/03] **[Erasing Concepts from Diffusion Models](https://arxiv.org/abs/2303.07345)** ![img](https://img.shields.io/badge/Diffusion-a99cf4)

# Acknowledgement

- Organizers: [Tianshuo Cong](https://tianshuocong.github.io/), [Xinlei He](https://xinleihe.github.io/), [Zhengyu Zhao](https://zhengyuzhao.github.io/), [Yugeng Liu](https://liu.ai/)

- This project is inspired by [LLM Security](https://llmsecurity.net/), [Awesome LLM Security](https://github.com/corca-ai/awesome-llm-security), [LLM Security & Privacy](https://github.com/chawins/llm-sp),             [UR2-LLMs](https://github.com/jxzhangjhu/Awesome-LLM-Uncertainty-Reliability-Robustness)

<img src="figure/logo.png" alt="image" width="500" height="auto">
