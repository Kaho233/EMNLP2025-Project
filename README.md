# EMNLP2025-Project

<br> project/
<br> ├── configs/                # 超参数配置
<br> │   └── train.yaml
<br> ├── data/                   # 数据集与文本描述
<br> ├── models/
<br> │   ├── diffusion.py        # 扩散模型主干
<br> │   ├── region_agent.py     # 区域策略网络
<br> │   ├── mixer.py            # 多智能体混合网络（QMIX）
<br> │   └── rewards.py          # 奖励计算模块
<br> ├── utils/
<br> │   ├── region_split.py     # 图像区域划分工具
<br> │   └── logger.py           # 训练日志记录
<br> └── train.py                # 主训练脚本
