# 第2周项目：MNIST手写数字分类

建议结构：

```
mnist/
├── data/            # 数据集目录，已gitignore
├── src/
│   ├── model.py     # 模型定义（先MLP，有余力换CNN）
│   ├── train.py     # 训练循环
│   └── evaluate.py  # 测试集评估
```

验收：

- 测试集准确率 ≥97%
- PyCharm 调试器单步走完一轮训练
- 学习率 ×10 / ÷10 对比实验，结果记入 `notes/week02.md`
