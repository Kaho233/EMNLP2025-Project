# EMNLP2025-Project

/n project/
/n ├── configs/                # 超参数配置
/n │   └── train.yaml
/n ├── data/                   # 数据集与文本描述
/n ├── models/
/n │   ├── diffusion.py        # 扩散模型主干
/n │   ├── region_agent.py     # 区域策略网络
/n │   ├── mixer.py            # 多智能体混合网络（QMIX）
/n │   └── rewards.py          # 奖励计算模块
/n ├── utils/
/n │   ├── region_split.py     # 图像区域划分工具
/n │   └── logger.py           # 训练日志记录
/n └── train.py                # 主训练脚本
