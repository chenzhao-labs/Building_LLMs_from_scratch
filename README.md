# Building LLMs from Scratch 学习资料

📚 深度学习大语言模型构建教程 | 🧠 从零开始实现 LLM 组件 | 💻 实践代码与笔记

## 说明

这是一个关于从零构建大语言模型（LLM）的学习资料库，包含了我在 YouTube 博主的教学视频下进行的一系列实验和学习笔记。

> **注意**: 这些资料来源于免费开放的教程，仅供个人学习参考。

## 📁 目录结构

- `1.Data_Loader_Input_Output_Pairs.ipynb`: 数据加载器和输入输出对的实现
- `3.Tokenizer.ipynb`: 分词器的实现和使用
- `4.Token_Embeddings.ipynb`: 词嵌入的实现
- `5.Position Embeddings.ipynb`: 位置嵌入的实现
- `12.LLM_Data_Preprocessing.ipynb`: LLM 数据预处理
- `14.Attention mechanism.ipynb`: 注意力机制
- `15.Trainable Self Attention.ipynb`: 可训练的自注意力机制
- `16.Causal Attention.ipynb`: 因果注意力机制
- `17.Multi-head attention.ipynb`: 多头注意力机制
- `18.Multi-head attention.ipynb`: 多头注意力机制（重复）
- `19-25.LLM Architecture.ipynb`: LLM 架构相关
- `26.LLM Loss function.ipynb`: LLM 损失函数
- `27.LLM Training Validation Loss.ipynb`: 训练验证损失
- `28.LLM Pretraining.ipynb`: LLM 预训练
- `29-30.LLM Decoding Strategies.ipynb`: 解码策略
- `31-32.Model_Weights_Loaded.ipynb`: 模型权重加载
- `33-34.Classification finetuning data loading.ipynb`: 分类微调数据加载
- `35-36.Architecture Classification finetuning.ipynb`: 架构分类微调
- `37-38.Instruction fine-tuning dataset prep loading.ipynb`: 指令微调数据集准备
- `持续更新中......`

## 📚 主要内容

### 1. 📝 数据处理
- 文本数据加载和预处理
- 实现简单的分词器 (SimpleTokenizerV1/V2)
- 字节对编码 (Byte Pair Encoding, BPE)
- 使用 tiktoken 库实现 GPT-2 分词器

### 2. 🔄 数据加载器
- 实现 GPT 数据集类 (GPTDatasetV1)
- 滑动窗口方法创建输入-目标对
- PyTorch DataLoader 的使用

### 3. 🔗 词嵌入和位置嵌入
- 词嵌入层的实现
- 位置嵌入的实现
- 嵌入层的组合使用

### 4. 👁️ 注意力机制
- 自注意力机制
- 可训练的自注意力
- 因果注意力 (Causal Attention)
- 多头注意力机制

### 5. 🏗️ LLM 架构
- Transformer 架构组件
- 模型整体架构设计

### 6. 📈 训练相关
- 损失函数
- 验证损失
- 预训练过程
- 微调技术

## 📁 使用的资源

- `the-verdict.txt`: 用于实验的短篇小说文本
- `gpt2/`: GPT-2 相关文件
- 各种 Jupyter Notebook 文件包含实验代码和说明

## ⚙️ 技术栈

- 🐍 Python
- 🔥 PyTorch
- 📘 Jupyter Notebook
- 🧮 tiktoken
- 📊 NumPy
- 🔍 正则表达式 (re)

## 🎯 学习目标

通过这些实验，学习者可以深入理解：
- 🧩 LLM 的基本构建块
- 📋 数据预处理的重要性
- 👁️ 注意力机制的工作原理
- 🏗️ Transformer 架构的设计思路
- 🚀 模型训练和微调的过程

## 🙏 致谢

感谢 YouTube 博主 Dr. Raj Dandekar 提供的免费开放教程，让我能够深入学习 LLM 的构建过程。

🎓 **Dr. Raj Dandekar** (MIT PhD, IIT Madras department topper)  
💼 [LinkedIn](https://www.linkedin.com/in/raj-abhijit-dandekar-67a33118a)

## 📄 许可证

仅供个人学习使用。
