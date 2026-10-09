### 杨桑多杰 / Yang Sangduojie

南开大学 · 物联网工程 · 本科在读 · 对自然语言处理与机器学习感兴趣

做实验的习惯是先把流程固定下来——统一数据划分、固定随机种子，让报告里的每个数字都能重新跑出来。业余喜欢 Counter-Strike。

---

**技能 / Skills**

- 编程语言：Python、C++
- 机器学习：scikit-learn、PyTorch
- 自然语言处理：Hugging Face Transformers、gensim、NLTK
- 工具：Git、LaTeX

**项目 / Projects**

**[NKU-2026-NLP-Work_1](https://github.com/YangSangDJ/NKU-2026-NLP-Work_1)** · 文本分类实现

在 NYT 新闻数据集（11,519 篇 / 3 分类，sports 占 75%）上比较三类文本表示方法：

- **词袋模型**：Binary Bag of Words、Word Frequency
- **静态词向量**：预训练 GloVe 6B 100d；以及在 AG News、NYT 训练集上训练的 Word2Vec
- **预训练语言模型**：`bert-base-uncased` 微调（max_length = 64，3 epochs）

统一采用 80/10/10 分层划分，在 NYT 测试集上报告 Accuracy 与 Macro-F1。

**联系 / Contact**

- Email：yangsangdj@qq.com
