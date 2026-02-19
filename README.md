# Bzy-Tiny-Llama2
# Bzy-Tiny-Llama2 🦙

这是一个基于 **LLaMA2** 架构手动实现的微型语言模型项目。

## 🌟 项目亮点
- **纯手写架构**：实现了 RMSNorm, RoPE 旋转位置编码, GQA 分组查询注意力机制。
- **全流程打通**：包含从 BPE 分词器训练到模型 Pre-training（预训练）及 Inference（推理）的完整逻辑。
- **教学友好**：代码结构清晰，适合大模型底层原理学习。

## 📂 文件说明
- `step1_model.ipynb`: 包含模型定义的 Jupyter Notebook。
- `tokenizer.json`: 训练好的 BPE 分词器字典。
- `corpus.txt`: 用于训练的原始语料库。

## 🚀 如何运行
1. 安装依赖：`pip install torch transformers`
2. 打开 `step1_model.ipynb` 按照步骤运行即可。
