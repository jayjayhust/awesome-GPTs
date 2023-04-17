<h1 align="center">
  awesome open-source GPTs and GPT-based applications
</h1>

### ChatGPT的开源平替项目集锦

| 项目名称 | stars | 主项目方 | 备注 |
| :----- | :----- | :----- | :----- |
| <a href="https://github.com/tatsu-lab/stanford_alpaca"> Stanford Alpaca </a> | <a href="https://github.com/tatsu-lab/stanford_alpaca/stargazers"><img src="https://img.shields.io/github/stars/tatsu-lab/stanford_alpaca" alt="GitHub stars"></a> | 斯坦福大学 | Below is a command that fine-tunes LLaMA-7B with our dataset on a machine with 4 A100 80G GPUs in FSDP(Fully Sharded Data Parallel) mode. |
| <a href="https://github.com/LC1332/Luotuo-Chinese-LLM"> 骆驼(Luotuo) </a> | <a href="https://github.com/LC1332/Luotuo-Chinese-LLM/stargazers"><img src="https://img.shields.io/github/stars/LC1332/Luotuo-Chinese-LLM" alt="GitHub stars"></a> | 华中师范大学、商汤科技 | 项目方购买autoDL上的GPU租赁服务(A100)来训练模型。（我们仍然需要后续训练10个以上的模型，所以我们期望2万左右的赞助总额）。附有相关开源项目列表。 |
| <a href="https://github.com/hpcaitech/ColossalAI"> Colossia-AI </a> | <a href="https://github.com/hpcaitech/ColossalAI/stargazers"><img src="https://img.shields.io/github/stars/hpcaitech/ColossalAI" alt="GitHub stars"></a> | 新加坡国立大学 | A mini demo training process requires only 1.62GB of GPU memory (any consumer-grade GPU). Increase the capacity of the fine-tuning model by up to 3.7 times on a single GPU. |
| <a href="https://github.com/nomic-ai/gpt4all"> GPT4All </a> | <a href="https://github.com/nomic-ai/gpt4all/stargazers"><img src="https://img.shields.io/github/stars/nomic-ai/gpt4all" alt="GitHub stars"></a> | Nomic AI | (IN PROGRESS) Build easy custom training scripts to allow users to fine tune models. |
| <a href="https://github.com/lm-sys/FastChat"> vicuna </a> | <a href="https://github.com/lm-sys/FastChat/stargazers"><img src="https://img.shields.io/github/stars/lm-sys/FastChat" alt="GitHub stars"></a> | UC伯克利、CMU、斯坦福、UCSD、MBZUAI | 使用：Vicuna-13B需要大约28GB的GPU显存；如果没有足够的显存，则可以使用模型并行来聚合同一台机器上多个GPU的显存；如果想在CPU上运行，则需要大约60GB的内存。训练：Vicuna可以在8个拥有80GB内存的A100 GPU上进行训练。|
| <a href="https://github.com/OptimalScale/LMFlow"> LMFlow </a> | <a href="https://github.com/OptimalScale/LMFlow/stargazers"><img src="https://img.shields.io/github/stars/OptimalScale/LMFlow" alt="GitHub stars"></a> | 香港科技大学统计和机器学习实验室 | The LLaMA 33B (LoRA) performance is achieved with only ~16h finetuning on the training split of PubMedQA and MedMCQA with a single 8 x A100 server. GPT-neo-2.7b model can be train on a single RTX3090(24G) but it is a rather weak model, which only supports English and may sometimes generate unsatisfactory responses. |
| <a href="https://github.com/THUDM/ChatGLM-6B"> ChatGLM-6B </a> | <a href="https://github.com/THUDM/ChatGLM-6B/stargazers"><img src="https://img.shields.io/github/stars/THUDM/ChatGLM-6B" alt="GitHub stars"></a> | Knowledge Engineering Group (KEG) & Data Mining at Tsinghua University | 结合模型量化技术，用户可以在消费级的显卡上进行本地部署（INT4 量化级别下最低只需 6GB 显存）。为了方便下游开发者针对自己的应用场景定制模型，我们同时实现了基于 P-Tuning v2 的高效参数微调方法 (使用指南) ，INT4 量化级别下最低只需 7GB 显存即可启动微调。 |

### ChatGPT的应用项目集锦
| 项目名称 | stars | 项目描述 | 主项目方 |
| :----- | :----- | :----- | :----- |
| <a href="https://github.com/microsoft/JARVIS"> JARVIS </a> | <a href="https://github.com/microsoft/JARVIS/stargazers"><img src="https://img.shields.io/github/stars/microsoft/JARVIS" alt="GitHub stars"></a> | a system to connect LLMs with ML community(HuggingGPT) | Microsoft |
| <a href="https://github.com/torantulino/auto-gpt"> Auto-GPT </a> | <a href="https://github.com/torantulino/auto-gpt/stargazers"><img src="https://img.shields.io/github/stars/torantulino/auto-gpt" alt="GitHub stars"></a> | Auto-GPT: An Autonomous GPT-4 Experiment | Significant Gravitas |
| <a href="https://github.com/reworkd/AgentGPT"> AgentGPT </a> | <a href="https://github.com/reworkd/AgentGPT/stargazers"><img src="https://img.shields.io/github/stars/reworkd/AgentGPT" alt="GitHub stars"></a> | Assemble, configure, and deploy autonomous AI Agents in your browser. | <a href="https://agentgpt.reworkd.ai/"> reworkd </a> |
| <a href="https://github.com/microsoft/deepspeed"> DeepSpeed </a> | <a href="https://github.com/microsoft/deepspeed/stargazers"><img src="https://img.shields.io/github/stars/microsoft/deepspeed" alt="GitHub stars"></a> | DeepSpeed empowers ChatGPT-like model training with a single click, offering 15x speedup over SOTA RLHF systems with unprecedented cost reduction at all scales. | Microsoft |
| <a href="https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat"> DeepSpeed-Chat </a> | <a href="https://github.com/microsoft/DeepSpeedExamples/stargazers"><img src="https://img.shields.io/github/stars/microsoft/DeepSpeedExamples" alt="GitHub stars"></a> | Easy, Fast and Affordable RLHF Training of ChatGPT-like Models at All Scales. (See the following table for the E2E time breakdown for training a 1.3 billion parameter ChatGPT model via DeepSpeed-Chat on a single commodity NVIDIA A6000 GPU with 48GB memory, in 2.2hr.) | Microsoft |

### 各大公司LLM模型汇总
Google的LaMDA（137B）和PaLM（540B），DeepMind的Gopher（280B）、BigScience的BLOOM（175B）、Meta的OPT（175B）、Nvidia的TNLG v2（530B）以及清华大学的GLM-130B（130B）、OpenAI的GTP-1(0.117B)/GPT-2(1.5B)/GPT-3(175B)/GPT-3.5(175B)/GPT-4(未公开，猜测为100 x 1000B)、OpenAI开放的finetune模型Ada(0.35B)/Babbage(1.3B)/Curie(6.7B)/Davinci(175B)。

### 其他相关开源项目
| 项目名称 | stars | 项目描述 | 主项目方 |
| :----- | :----- | :----- | :----- |
| <a href="https://github.com/TheRamU/Fay"> Fay </a> | <a href="https://github.com/TheRamU/Fay/stargazers"><img src="https://img.shields.io/github/stars/TheRamU/Fay" alt="GitHub stars"></a> | 数字人 | TheRamU |