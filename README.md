# EMNLP2025-Project

project/
├── configs/                # 超参数配置
│   └── train.yaml
├── data/                   # 数据集与文本描述
├── models/
│   ├── diffusion.py        # 扩散模型主干
│   ├── region_agent.py     # 区域策略网络
│   ├── mixer.py            # 多智能体混合网络（QMIX）
│   └── rewards.py          # 奖励计算模块
├── utils/
│   ├── region_split.py     # 图像区域划分工具
│   └── logger.py           # 训练日志记录
└── train.py                # 主训练脚本
