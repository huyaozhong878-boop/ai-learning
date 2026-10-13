# ai-learning

研二学习仓库：深度学习基础 → 语义方向科研 → 小论文。
主线：2026.10–12 打基础并定方向，2027 投稿小论文（详见阶段计划）。

## 目录结构

- `notes/` 每周学习笔记（`template.md` 是通用模板）
- `prompts/` 用AI一步步完成项目的实战流程
- `week01-python/` 第1周：Python工程练习
- `week02-pytorch/` 第2周：PyTorch + MNIST项目

## 每日节奏

1. 学：课程/文档，20分钟为限
2. 敲：立刻回 PyCharm 复现，不许只看
3. 记：更新 `notes/weekXX.md`（含疑问清单、AI使用记录）
4. 提交：`git add .` + `git commit -m "说明这次学会了什么"`

目标：每周 ≥5 次 commit。

## 第1周任务清单

- [x] Python环境：项目内 venv 已建好（Python 3.14 + numpy + pandas；Miniconda 被本机安全策略拦截，需要时走 IT/软件中心）
- [ ] PyCharm 绑定 .venv 解释器
- [ ] GitHub 建远程仓库并推送
- [ ] Python：OOP、异常处理、类型注解、模块与包、pip/requirements.txt
- [ ] 练习：`week01-python/csv_cleaner.py`
- [ ] 课程：李宏毅《机器学习2023》前4讲（基本概念 / Regression / Classification / Gradient Descent）
- [ ] 用AI辅助完成本周环境搭建与练习（有问题直接让AI解决）

## 第2周任务清单

- [ ] numpy：索引、切片、广播、矩阵运算
- [ ] PyTorch 官方"60分钟入门"：tensor / autograd / nn.Module / Dataset & DataLoader / 优化器
- [ ] MNIST 项目（`week02-pytorch/`），测试集准确率 ≥97%
- [ ] PyCharm 调试器单步走完一轮训练，说清 `backward()` 与 `step()` 的作用
- [ ] 学习率 ×10、÷10 各重跑一次，记录差异
- [ ] 用AI辅助完成MNIST项目搭建

## 推送到 GitHub（第1周执行）

先在 GitHub 网页上新建空仓库 `ai-learning`，然后：

```bash
git remote add origin https://github.com/<用户名>/ai-learning.git
git branch -M main
git push -u origin main
```
