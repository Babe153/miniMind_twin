# miniMind_twin

参考 MiniMind 学习大语言模型实现与训练的个人实践项目，持续开发中。

## 当前进度

- 已添加模型配置 `miniMindConfig`，包含注意力、RoPE 和 MoE 相关参数。
- 已建立数据集与训练脚本文件，具体实现待补充。
- 当前尚未实现完整模型与训练流程。

## 项目结构

```text
model/model.py             模型配置
dataset/lm_dataset.py     数据处理（待实现）
trainer/train_pretrain.py   预训练入口（待实现）
trainer/trainer_utils.py    训练工具（待实现）
src/minimind_twin/          Python 包入口
```

## 环境准备

项目使用 Python 3.13+ 和 uv 管理依赖：

```bash
uv sync
```

主要依赖为 PyTorch、Transformers、NumPy 和 pandas。训练命令将在实现完成后补充。

虚拟环境、私有配置、训练数据和模型权重不纳入版本管理。
