---
icon: fas fa-flask
order: 3
---

## Funding / 科研项目基金

### 北京市自然科学基金"启研计划"（本科生专项）· 第一主持人

**2026.05 – 至今**
课题：基于 WAM 与 VLA 闭环协同进化的人形机器人策略研究

- 提出**闭环协同进化范式**：世界模型（WAM）预测未来观测作为规划先验，VLA 执行轨迹反哺 WAM 训练
- 设计**记忆机制**（长时序观测压缩与检索）与**隐空间思维链**（latent 空间多步隐式推理）
- 主导 BEHAVIOR-1K 上 300 项任务子集的仿真验证，完成灵御智能 TeleAvatar 人形机器人实机部署推理全流程
- 依托本课题已产出 3 篇在审论文

## Internship / 实习经历

### 南京南栖仙策（Polixir）· 机器学习工程师（暑期实习）

**2025.07 – 2025.08**

- 面向星海图 Galaxea R1（轮式底盘 + 升降躯干 + 双臂移动操作机器人）搭建模仿学习数据与基线体系，打通"真机数采 → 数据处理 → 策略训练 → 评测"流程
- 通过 JoyLo 套件遥操作采集并标注近 3,000 条操作演示轨迹（LeRobot 格式）
- 参与机器人硬件调试，负责相机手眼标定
- 部署并复现 Diffusion Policy、Pi0、WB-VIMA 三类模仿学习基线，在 BEHAVIOR-1K 任务上完成推理评测

## Research Platforms / 研究平台与数据

- **真机平台**: 双 7-DoF 机械臂（16 维 joint/gripper action，三路 RGB 相机）、Galaxea R1 全身移动操作平台、灵御智能 TeleAvatar 人形机器人
- **数据**: 遥操作演示轨迹（JoyLo/VR）、第一人称人类数据、BEHAVIOR-1K / OmniGibson 仿真
- **工具链**: JAX/Optax、PyTorch、LeRobot、CuRobo IK、USD、PyTorch3D、FoundationStereo、SAM2、WiLoR/MANO
