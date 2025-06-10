# Hands-on NLP 🎯

一个从零开始实现经典 NLP 模型的学习项目，旨在深入理解自然语言处理的核心算法和技术。

## 📖 项目简介

本项目专注于从基础原理出发，手动实现 NLP 领域的经典模型。通过编码实践，深入理解每个模型的工作机制、数学原理和实际应用。

## 清单 📅

| 状态 | 模型/技术 | 描述 |
|------|-----------|------|
| ✅ **已完成** | Bigram 语言模型 | 统计语言模型的基础 |
| ✅ **已完成** | NPLM 神经网络语言模型 | 神经网络在语言建模中的应用 |
| 🔄 **开发中** | Word2Vec | 词向量表示学习 |
| 🔄 **开发中** | └─ Skip-gram 模型 | Word2Vec子模型 |
| 🔄 **开发中** | └─ CBOW 模型 | Word2Vec子模型 |
| 📅 **计划实现** | **RNN 系列** | |
| 📅 **计划实现** | └─ 基础 RNN | 循环神经网络基础 |
| 📅 **计划实现** | └─ LSTM | 长短期记忆网络 |
| 📅 **计划实现** | └─ GRU | 门控循环单元 |
| 📅 **计划实现** | **注意力机制** | |
| 📅 **计划实现** | └─ MHA | 多头注意力 |
| 📅 **计划实现** | └─ GQA | 分组查询注意力 |
| 📅 **计划实现** | └─ MLA | 多层注意力 |
| 📅 **计划实现** | **Transformer 架构** | |
| 📅 **计划实现** | └─ Encoder-Decoder 结构 | Transformer核心架构 |
| 📅 **计划实现** | └─ 位置编码 | 序列位置信息编码 |
| 📅 **计划实现** | └─ 层归一化 | 网络层标准化技术 |
| 📅 **计划实现** | BERT 简化版 | 双向编码器表示 |


## 📚 学习路径

推荐的学习顺序：

1. **基础统计模型** → N-gram
2. **词向量表示** → Word2Vec
3. **序列模型** → RNN、LSTM、GRU
4. **注意力机制** → 各种注意力计算方式
5. **Transformer** → 现代 NLP 的基石
6. **预训练模型** → BERT 等双向模型


## 🤝 贡献指南

欢迎任何形式的贡献！

- 🐛 **Bug 反馈**：发现问题请提 Issue
- 💡 **功能建议**：新的模型实现想法
- 📖 **文档改进**：完善注释和说明
- 🔧 **代码优化**：性能改进和重构

## 📚 参考资料


### 开源项目
- [Andrej Karpathy - makemore](https://github.com/karpathy/makemore) - 字符级语言模型
- [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) - Transformer 详解
- [Word2Vec 原始实现](https://code.google.com/archive/p/word2vec/)

### 重要论文
- **Word2Vec**: Efficient Estimation of Word Representations in Vector Space
- **Attention**: Attention Is All You Need  
- **BERT**: Pre-training of Deep Bidirectional Transformers

## 🙏 致谢

感谢 NLP 社区的开源贡献者们，特别是：
- Andrej Karpathy 的教育项目启发
- Hugging Face 团队的技术分享
- PyTorch 社区的工具支持

---

⭐ 如果这个项目对你有帮助，请给个 star 支持一下！