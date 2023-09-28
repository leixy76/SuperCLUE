# SuperCLUE

中文通用大模型综合性基准SuperCLUE

<a href='https://www.superclueai.com'>SuperCLUE最新9月榜单</a>

文章地址：<a href='https://www.cluebenchmarks.com/superclue.html'>www.cluebenchmarks.com/superclue.html</a>

技术报告：<a href='https://arxiv.org/abs/2307.15020'>SuperCLUE: A Comprehensive Chinese Large Language Model Benchmark</a>

【2023-9-12】 <a href='https://github.com/CLUEbenchmark/SuperCLUE-safety'>SuperCLUE-Safety：中文大模型多轮对抗安全基准</a>


<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/superclue_idea.jpeg"  width="90%" height="90%"></img>

### 能力评估结构图
<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/category09.png"  width="60%" height="60%"></img>

### 为什么新增AI Agent智能体能力？

AI agent（智能体）是当前与大语言模型相关的前沿研究热点，拥有类似贾维斯等科幻电影中人类超级助手的能力，可以根据需求自主的完成任务。
然而，面向AI agent智能体，缺乏针对中文大模型的广泛评估。为了解决这一问题，我们在SuperCLUE新的榜单中新增了AI agent智能体能力的测评。
这个榜单将重点评估AI agent在【工具使用】和【任务规划】两个关键能力上的表现，这项工作旨在为评估中文大模型作为智能体的表现提供一个基础和可能。

### SuperCLUE总排行榜（2023年9月）

| 排名 | 模型 | 机构 | 总分 | OPEN<br/>多轮开放问题 | OPT<br/>客观题 | 许可 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| - | GPT4 | OpenAI | 83.2 | 84.28 | 81.58 | 闭源 |
| - | gpt-3.5-turbo | OpenAI | 63.74 | 61.82 | 66.61 | 闭源 |
| - | Claude2 | Authropic | 62.98 | 60.57 | 66.6 | 闭源 |
| 🏅️ | SenseChat 3.0 | 商汤科技 | 62.75 | 54.29 | 75.45 | 闭源 |
| 🥈 | 文心一言(v2.3.1) | 百度 | 62.61 | 53.72 | 75.93 | 闭源 |
| 🥉 | ChatGLM2-Pro | 清华&智谱AI | 62.12 | 54.31 | 73.84 | 闭源 |
| 4 | vivoLM | vivo | 58.29 | 47.67 | 74.21 | 闭源 |
| 5 | Baichuan2-13B-Chat | 百川智能 | 58.03 | 52.45 | 66.4 | 开源 |
| 6 | MiniMax-Abab5.5 | MiniMax | 57.18 | 46.31 | 73.48 | 闭源 |
| 7 | 豆包 | 字节跳动 | 57.13 | 48.65 | 69.86 | 闭源 |
| 8 | Baichuan2-7B-Chat | 百川智能 | 50.11 | 42.28 | 61.86 | 开源 |
| 9 | 讯飞星火(v4.0) | 科大讯飞 | 50.06 | 40.64 | 64.2 | 闭源 |
| 10 | 通义千问(v1.0.7) | 阿里巴巴 | 49.07 | 33.78 | 72 | 闭源 |
| 11 | OpenBuddy-Llama2-70B | OpenBuddy | 44.29 | 30.84 | 64.46 | 开源 |
| 12 | Qwen-7B-Chat | 阿里巴巴 | 40.14 | 23.59 | 64.97 | 开源 |
| 13 | Chinese-Alpaca-2-13B | yiming cui | 39.81 | 32.64 | 50.56 | 开源 |
| 14 | ChatGLM2-6B | 清华&智谱AI | 38.41 | 25.49 | 57.8 | 开源 |
| 15 | ERNIE-3.5-Turbo | 百度 | 37.76 | 24.81 | 57.19 | 闭源 |
| 16 | 360GPT_S2_V94 | 360 | 37.11 | 18.97 | 64.32 | 闭源 |
| - | Llama-2-13B-Chat | Meta | 31.63 | 29.83 | 34.33 | 开源 |

本次评测选取了目前国内外最具代表性的20个通用大语言模型，9月评测数据集为全新的3458道测试题。

### SuperCLUE-OPEN多轮开放问题排行榜（2023年9月）
| 排名 | 模型 | 机构 | OPEN分数 | 语言理解与生成 | 专业技能与知识 | AI智能体 | 安全性 | 许可 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| - | GPT4 | OpenAI | 84.28 | 100 | 90.51 | 91.67 | 81.25 | 闭源 |
| - | gpt-3.5-turbo | OpenAI | 61.82 | 72.22 | 63.29 | 66.65 | 50.12 | 闭源 |
| - | Claude2 | Authropic | 60.57 | 98.15 | 71.84 | 66.67 | 30.21 | 闭源 |
| 🏅️ | ChatGLM2-Pro | 清华&智谱AI | 54.31 | 79.63 | 48.73 | 55.56 | 67.71 | 闭源 |
| 🥈 | SenseChat 3.0 | 商汤科技 | 54.29 | 88.89 | 56.65 | 69.7 | 43.75 | 闭源 |
| 🥉 | 文心一言(v2.3.1) | 百度 | 53.72 | 87.96 | 56.33 | 56.94 | 36.96 | 闭源 |
| 4 | Baichuan2-13B-Chat | 百川智能 | 52.45 | 86.11 | 43.04 | 44.43 | 34.38 | 开源 |
| 5 | 豆包 | 字节跳动 | 48.65 | 71.3 | 53.16 | 47.22 | 59.38 | 闭源 |
| 6 | vivoLM | vivo | 47.67 | 67.59 | 52.22 | 47.14 | 51.04 | 闭源 |
| 7 | MiniMax-Abab5.5 | MiniMax | 46.31 | 56.48 | 44.3 | 54.17 | 42.71 | 闭源 |
| 8 | Baichuan2-7B-Chat | 百川智能 | 42.28 | 67.59 | 34.81 | 36.11 | 35.42 | 开源 |
| 9 | 讯飞星火(v4.0) | 科大讯飞 | 40.64 | 47.22 | 43.99 | 37.42 | 54.17 | 闭源 |
| 10 | 通义千问(v1.0.7) | 阿里巴巴 | 33.78 | 45.37 | 37.34 | 41.67 | 13.54 | 闭源 |
| 11 | Chinese-Alpaca-2-13B | yiming cui | 32.64 | 77.78 | 22.78 | 22.21 | 43.75 | 开源 |
| 12 | OpenBuddy-Llama2-70B | OpenBuddy | 30.84 | 52.78 | 40.19 | 26.37 | 31.25 | 开源 |
| - | Llama-2-13B-Chat | Meta | 29.83 | 55.56 | 21.84 | 25.12 | 44.68 | 开源 |
| 13 | ChatGLM2-6B | 清华&智谱AI | 25.49 | 50.93 | 26.27 | 26.39 | 40.62 | 开源 |
| 14 | ERNIE-3.5-Turbo | 百度 | 24.81 | 35.19 | 21.2 | 37.5 | 51.01 | 闭源 |
| 15 | Qwen-7B-Chat | 阿里巴巴 | 23.59 | 50 | 21.2 | 27.14 | 21.88 | 开源 |
| 16 | 360GPT_S2_V94 | 360|18.97 |35.19 |16.77 |24.98 | 32.29| 闭源|

OPEN的分数计算方法：与代表性领先模型（如3.5）对战后，根据胜、和和败的情况计算出的分数。 胜利得3分，和得1分，负不得分。

计算公式 =（胜利次数 * 3分 + 和次数 * 1分）/ (2分 * 对战次数)，且满分上限为100分。


### SuperCLUE总排行榜（2023年8月）

| 排名  | 模型                                                                                        | 机构          | 总分    | OPEN<br>多轮开放问题 | OPT<br>三大能力客观题 |
|:---:| :-----------------------:| :--------------------: | :---------------------:| :--------------------------: | :--------------------------: |
| -   | [GPT-4 ↗](https://openai.com/)                                                            | OpenAI      | 81.03 | 86.04      | 76.02      |
| -   | [Claude-2 ↗](https://www.anthropic.com/)                                                  | Anthropic   | 67.72 | 70.06      | 65.39      |
| -   | [gpt-3.5-turbo ↗](https://openai.com/)                                                    | OpenAI      | 65.95 | 66.67      | 65.24      |
| 🏅️  | [Baichuan-13B-Chat(V2) ↗](https://huggingface.co/baichuan-inc/Baichuan-13B-Chat)          | 百川智能        | 60.02 | 60.55      | 59.49      |
| 🥈   | [MiniMax-abab5 ↗](https://api.minimax.chat/)                                                                          | MiniMax     | 55.70 | 47.95      | 63.44      |
| 🥉   | [文心一言(V2.2.3) ↗](https://yiyan.baidu.com/welcome)                                         | 百度          | 53.47 | 54.18      | 52.76      |
| 4   | [Mengzi↗](https://www.langboat.com/portal/mengzi-gpt)                                                                                     | 澜舟科技        | 52.27 | 46.20      | 58.34      |
| 5   | [讯飞星火(v2.0) ↗](https://xinghuo.xfyun.cn/)                                                 | 科大讯飞        | 51.66 | 43.55      | 59.77      |
| 6   | [通义千问(V1.0.5) ↗](https://tongyi.aliyun.com/)                                              | 阿里巴巴        | 50.40 | 41.73      | 59.08      |
| 7   | [Qwen-7B-Chat ↗](https://huggingface.co/Qwen/Qwen-7B-Chat)                                | 阿里巴巴        | 48.14 | 36.43      | 59.85      |
| 8   | [ChatGLM2-6B ↗](https://github.com/THUDM/ChatGLM2-6B)                                     | 清华&智谱AI   | 47.55 | 40.73      | 54.37      |
| 9  | [ChatGLM-130B ↗](https://chatglm.cn)                                                      | 清华&智谱AI   | 46.77 | 38.49      | 55.04      |
| 10  | [360智脑(V4.0) ↗](https://ai.360.cn)                                                        | 360       | 46.05 | 34.22      | 57.87      |
| 11  | [Openbuddy-Llama2-13b ↗](https://huggingface.co/OpenBuddy/openbuddy-llama2-13b-v8.1-fp16) | Openbuddy | 44.84 | 38.15      | 51.52      |
| -   | [Llama-2-13B-chat ↗](https://huggingface.co/meta-llama/Llama-2-13b-hf)                    | Meta        | 36.63 | 36.97      | 36.29      |
| 12  | [Chinese-Alpaca-2-13B ↗](https://huggingface.co/ziqingyang/chinese-alpaca-2-13b)          | Yiming Cui  | 35.29 | 18.33      | 52.25      |

### SuperCLUE-OPEN多轮开放问题排行榜（2023年8月）

| 排名 | 模型 | 机构 | 总分 | 胜率 | 负率 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| - | GPT-4 | OpenAI | 86.04 | 50.19% | 13.96% |
| - | gpt-3.5-turbo | OpenAI | 66.67 | 33.33% | 33.33% |
| - | Claude-2 | Anthropic | 70.06 | 28.96% | 29.94% |
| 🏅️ | Baichuan-13B-Chat(V2) | 百川智能 | 60.55 | 23.24% | 39.45% |
| 🥈 | 文心一言(V2.2.3) | 百度 | 54.18 | 18.92% | 45.82% |
| 🥉 | MiniMax-abab5 | MiniMax | 47.95 | 14.96% | 52.05% |
| 4 | Mengzi | 澜舟科技 | 46.20 | 15.96% | 53.80% |
| 5 | 讯飞星火(V2.0) | 科大讯飞 | 43.55 | 14.64% | 56.45% |
| 6 | 通义千问(V1.0.5) | 阿里巴巴 | 41.73 | 9.65% | 58.27% |
| 7 | ChatGLM2-6B | 清华&智谱AI | 40.73 | 9.05% | 59.27% |
| 8 | ChatGLM-130B | 清华&智谱AI | 38.49 | 13.12% | 61.51% |
| 9 | Openbuddy-Llama2-13b | Openbuddy | 38.15 | 8.80% | 61.85% |
| - | Llama-2-13b-chat | Meta | 36.97 | 12.82% | 63.03% |
| 10 | Qwen-7B-Chat | 阿里巴巴 | 36.43 | 9.52% | 63.57% |
| 11 | 360智脑(V4.0) | 360 | 34.22 | 8.22% | 65.78% |
| 12 | Chinese-Alpaca-2-13B | Yiming Cui | 18.33 | 4.58% | 81.67% |

注：OPEN多轮开放问题：待评估模型与代表性模型（gpt-3.5-turbo）进行对战，使用超级模型<br/>
作为评审官，计算待评估模型的胜率和平局率，获得总分。

### SuperCLUE-OPT客观题排行榜（2023年9月）

| 排名 | 模型 | 机构 | OPT分数 | 基础能力 | 中文特性 | 学术与专业能力 | 许可 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| - | GPT4 | OpenAI | 81.58 | 88.13 | 80.09 | 75.35 | 闭源 |
| 🏅️ | 文心一言(v2.3.1) | 百度 | 75.93 | 82.64 | 83.2 | 58.11 | 闭源 |
| 🥈 | SenseChat 3.0 | 商汤科技 | 75.45 | 82.3 | 80.04 | 61.71 | 闭源 |
| 🥉 | vivoLM | vivo | 74.21 | 79.27 | 81.22 | 59.2 | 闭源 |
| 4 | ChatGLM2-Pro | 清华&智谱AI | 73.84 | 79.68 | 80.94 | 57.71 | 闭源 |
| 5 | MiniMax-Abab5.5 | MiniMax | 73.48 | 79.31 | 80.76 | 57.14 | 闭源 |
| 6 | 通义千问(v1.0.7) | 阿里巴巴 | 72 | 78.17 | 78.75 | 54.65 | 闭源 |
| 7 | 豆包 | 字节跳动 | 69.86 | 78.21 | 77.44 | 49.88 | 闭源 |
| 8 | gpt-3.5-turbo | OpenAI | 66.61 | 74.65 | 69.24 | 53.43 | 闭源 |
| - | Claude2 | Authropic | 66.6 | 75 | 66.67 | 56.23 | 闭源 |
| 9 | Baichuan2-13B-Chat | 百川智能 | 66.4 | 71.61 | 75.14 | 49.02 | 开源 |
| 10 | Qwen-7B-Chat | 阿里巴巴 | 64.97 | 72.17 | 73.61 | 45.12 | 开源 |
| 11 | OpenBuddy-Llama2-70B | OpenBuddy | 64.46 | 75.34 | 65.79 | 49.71 | 开源 |
| 13 | 360GPT_S2_V94 | 360 | 64.32 | 69.8 | 73.52 | 44.81 | 闭源 |
| 12 | 讯飞星火(v4.0) | 科大讯飞 | 64.2 | 73.24 | 69.37 | 45.73 | 闭源 |
| 14 | Baichuan2-7B-Chat | 百川智能 | 61.86 | 65.91 | 71.73 | 44.41 | 开源 |
| 15 | ChatGLM2-6B | 清华&智谱AI | 57.8 | 66.95 | 62.73 | 40.37 | 开源 |
| 16 | ERNIE-3.5-Turbo | 百度 | 57.19 | 63.74 | 65.76 | 38.69 | 闭源 |
| 17 | Chinese-Alpaca-2-13B | yiming cui | 50.56 | 56.4 | 54.08 | 38.97 | 开源 |
| - | Llama-2-13B-Chat | Meta | 34.33 | 41.81 | 30.13 | 30.11 | 开源 |

-----------------------------------------------
TODO TODO TODO 
### SuperCLUE-OPT三大能力客观题排行榜（2023年8月）
| 排名 | 模型 | 机构 | 平均分 | 基础能力 | 中文特性 | 学术与专业 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| - | GPT4 | OpenAI | 76.02 | 79.85 | 76.48 | 71.72 |
| - | Claude-2 | Anthropic | 65.39 | 69.05 | 65.50 | 61.61 |
| - | gpt-3.5-turbo | OpenAI | 65.24 | 72.80 | 69.58 | 53.33 |
| 🏅️ | MiniMax-abab5 | MiniMax | 63.44 | 67.95 | 70.07 | 52.30 |
| 🥈 | Qwen-7B-Chat | 阿里巴巴 | 59.85 | 65.20 | 65.50 | 48.85 |
| 🥉 | 讯飞星火(V2.0) | 科大讯飞 | 59.77 | 65.31 | 67.44 | 46.55 |
| 4 | Baichuan-13B-Chat(V2) | 百川智能 | 59.49 | 63.66 | 66.76 | 48.05 |
| 5 | 通义千问(V1.0.5) | 阿里巴巴 | 59.08 | 63.00 | 69.29 | 44.94 |
| 6 | Mengzi | 澜舟科技 | 58.34 | 61.34 | 64.82 | 48.85 |
| 7 | 360智脑(V4.0) | 360 | 57.87 | 63.94 | 67.74 | 41.95 |
| 8 | ChatGLM-130B | 清华&智谱AI | 55.04 | 59.91 | 62.00 | 43.22 |
| 9 | ChatGLM2-6B | 清华&智谱AI | 54.37 | 60.46 | 60.35 | 42.30 |
| 10 | 文心一言(V2.2.3) | 百度 | 52.76 | 57.27 | 60.54 | 40.46 |
| 11 | Chinese-Alpaca-2-13B | Yiming Cui | 52.25 | 57.60 | 56.17 | 42.99 |
| 12 | Openbuddy-Llama2-13b | Openbuddy | 51.52 | 57.82 | 55.49 | 41.26 |
| - | Llama-2-13b-chat | Meta | 36.29 | 40.64 | 38.00 | 30.23 |

### SuperCLUE十大基础能力排行榜（2023年8月）

| 排名  |          模型           |  分数  |   语言<br>理解    |  闲聊   | 对话 | 生成<br>创作 | 知识<br>百科 |  计算   | 逻辑<br>推理 |  代码   | 角色<br>扮演  |  安全   |
| :-: | :-------------------: | :---: | :----------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|  -  |         GPT4          | 82.98 |    91.30     | 90.55 | 79.03 | 71.92 | 95.10 | 75.39 | 78.24 | 83.93 | 70.92 | 89.67 |
|  -  |     gpt-3.5-turbo     | 69.73 |    79.97     | 75.52 | 66.49 | 68.03 | 78.59 | 55.14 | 58.94 | 72.62 | 62.46 | 77.70 |
|  -  |       Claude-2        | 69.54 |    85.04     | 70.43 | 70.47 | 41.27 | 87.02 | 63.69 | 66.80 | 74.77 | 55.58 | 73.55 |
| 🏅️  | Baichuan-13B-Chat(V2) | 61.75 |    72.58     | 81.56 | 59.30 | 58.70 | 87.66 | 33.87 | 41.90 | 44.12 | 64.24 | 62.10 |
|  🥈  |     MiniMax-abab5     | 58.48 |    85.52     | 71.35 | 53.55 | 53.00 | 70.75 | 25.78 | 46.14 | 42.52 | 54.14 | 76.78 |
|  🥉  |     文心一言(V2.2.3)      | 55.58 |    78.75     | 56.17 | 51.17 | 50.47 | 54.73 | 42.59 | 51.94 | 54.19 | 41.68 | 63.62 |
|  4  |      讯飞星火(V2.0)       | 53.76 |    74.42     | 54.58 | 62.08 | 49.65 | 42.83 | 43.11 | 48.29 | 55.28 | 48.07 | 55.02 |
|  5  |        Mengzi         | 53.50 |    78.75     | 59.90 | 59.08 | 40.18 | 66.02 | 22.34 | 39.74 | 48.10 | 49.13 | 65.30 |
|  6  |     通义千问(V1.0.5)      | 51.90 |    72.30     | 46.07 | 49.50 | 58.62 | 40.15 | 50.38 | 49.21 | 47.68 | 53.63 | 42.15 |
|  7  |     Qwen-7B-Chat      | 50.36 |    67.80     | 44.85 | 53.51 | 45.84 | 45.19 | 42.31 | 48.30 | 39.95 | 40.62 | 62.27 |
|  8  |      ChatGLM2-6B      | 49.98 |    69.92     | 56.04 | 45.28 | 45.88 | 58.41 | 44.52 | 36.37 | 35.58 | 39.03 | 56.86 |
| 9  |      360智脑(V4.0)      | 48.45 |    67.44     | 61.03 | 44.29 | 32.36 | 57.18 | 45.36 | 39.65 | 43.57 | 38.44 | 46.19 |
| 10  |      ChatGLM-130B | 48.30 | 71.67 | 58.17 | 43.42 | 43.51 | 60.19 | 23.87 | 38.51 | 43.21 | 39.27 |57.26 |
| 11  | Openbuddy-Llama2-13b  | 46.61 |    71.49     | 43.33 | 43.43 | 15.31 | 56.50 | 39.85 | 49.68 | 49.80 | 36.51 | 55.77 |
| -  |   Llama-2-13b-chat    | 38.30 |    61.76     | 40.63 | 41.80 | 28.57 | 25.19 | 28.07 | 36.66 | 35.78 | 39.02 | 43.94 |
| 12  | Chinese-Alpaca-2-13B  | 38.00 |    68.65     | 36.15 | 32.75 | 20.92 | 38.69 | 32.77 | 37.61 | 21.65 | 28.03 | 50.03 |

注：SuperCLUE.十大基础能力排行榜，综合了每个子能力上多轮开放问题与三大能力客观题的分数。

### SuperCLUE中文大模型开源排行榜（2023年8月）

| 排名  |          模型           |     机构      |   总分   | OPEN多轮开放问题 | OPT三大能力客观题 |
| :-: | :-------------------: | :---------: | :----: | :--------: | :--------: |
|  🏅️  | Baichuan-13B-Chat(V2) |    百川智能     | 60.02 |   60.55   |   59.49   |
|  🥈  |     Qwen-7B-Chat      |    阿里巴巴     | 48.14 |   36.43   |   59.85   |
|  🥉  |      ChatGLM2-6B      |  清华&智谱AI  | 47.55 |   40.73   |   54.37   |
|  4  | Openbuddy-Llama2-13b  | Openbuddy | 44.84 |   38.15   |   51.53   |
|  5  |   Llama-2-13b-chat    |    Meta     | 36.63 |   36.98   |   36.29   |
|  6  | Chinese-Alpaca-2-13B  | Yiming Cui  | 35.29 |   18.33   |   52.25   |

SuperCLUE基础十大能力结构包含四个能力象限，包括语言理解与生成、知识理解与应用、专业能力和环境适应与安全性，进而细化为10项基础能力。

### 示例
#### 能力1：语义理解与抽取

这是一种语言能力，能够理解并解析输入的文字信息的含义。模型需要能够识别短语、句子、段落的含义，同时还要能从更大的文本块中抽取关键信息和主题。

##### 多轮对话示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_nlp.png"  width="100%" height="100%"></img>

注：本示例中可同时评测多轮对话能力

#### 能力2：AI agent（智能体）能力

AI agent（智能体）是当前与大语言模型相关的前沿研究热点，拥有类似贾维斯等科幻电影中人类超级助手的能力，可以根据需求自主的完成任务。

重点评估AI agent在【工具使用】和【任务规划】两个关键能力上的表现

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_agent.png"  width="100%" height="100%"></img>


#### 能力3：上下文对话

这是一种语言能力，需要理解并记住前面的对话信息，以便在回答中保持连贯性。这涉及到理解对话的整体流程和上下文环境，或生成相应的对话。

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_dial.png"  width="100%" height="100%"></img>

#### 能力4：生成与创作

这是一种语言能力，能够创造新的文本内容，如文章、文案、短故事、诗歌。这涉及到创造性地运用语言，同时还要考虑到风格、语境和目标读者。

##### 示例
<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_generate.png"  width="100%" height="100%"></img>


#### 能力5：知识与百科

这是一种知识能力，能够像百科全书一样提供知识信息。这涉及到理解和回答关于广泛主题的问题，以及提供准确、详细和最新的信息。

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_knowledge.png"  width="100%" height="100%"></img>


#### 能力6：代码

这是一种专业能力，能够理解和生成编程代码。这涉及到理解多种编程语言的语法、结构和习惯，以及如何解决编程问题。

##### 多轮对话示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_code.png"  width="100%" height="100%"></img>

注：本示例中可同时评测多轮对话能力

#### 能力7：逻辑与推理

这是一种专业能力，能够理解和应用逻辑原则进行推理。这涉及到分析问题、识别问题及推理。

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_logic.png"  width="100%" height="100%"></img>


####  能力8：计算

这是一种专业能力，使其能够执行数学运算，如加法、减法、乘法和除法，甚至更复杂的数学问题。这涉及到理解数学问题的表述，以及如何步骤地解决这些问题。

##### 多轮对话示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_compute.png"  width="100%" height="100%"></img>

注：本示例中可同时评测多轮对话能力

####  能力9：角色扮演

这是一种感知能力，使其能够在特定的模拟环境或情景中扮演一个角色。这涉及到理解特定角色的行为、说话风格，以及在特定情境下的适当反应。

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_roleplay.png"  width="100%" height="100%"></img>


####   能力10：安全

这是一种安全能力，防止生成可能引起困扰或伤害的内容。这涉及到识别和避免可能包含敏感或不适当内容的请求，以及遵守用户的隐私和安全政策。

##### 示例

<img src="https://github.com/CLUEbenchmark/SuperCLUE/blob/main/resources/r2309/image_safety.png"  width="100%" height="100%"></img>

### 8月榜单更新情况
1.综合性：将OPEN多轮开放问题与OPT三大能力客观题进行了结合起来，作为8月榜单；

2.模型细节：Baichuan-13B-Chat使用了是最新的模型权重，具体见huggingface的权重；文心一言，OPT三大能力客观题使用的是API（Ernie-3.5-turbo）；
  360使用的是api版本；

3.模型更新：去除了一些前期大家比较关注但当前活跃度不高的模型，如MOSS，BELLE等；加入了一些如Qwen-7B-Chat和3个Llam2相关模型。
