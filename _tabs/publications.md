---
icon: fas fa-file-alt
order: 2
---

## Papers / 论文

> \* 表示共同第一作者。我的名字以 **粗体** 标出。

### Under Review / 在审

1. **SHORE-RL: Shortening Effective Horizons for Long-Horizon Residual Reinforcement Learning**
   J. Wang\*, **C. Xin**\*, et al., G. Wang.
   *AAAI 2027* (Under Review) · 共同第一作者
   : 通过冻结预训练 BC/VLA 基座策略、仅学习有界残差（residual），利用局部 latent waypoint 与稠密 progress reward 分别缩短残差 actor 与 critic 的有效 horizon，解决长时程稀疏奖励下 Residual RL 的性能坍塌问题。真机双 7-DoF 臂三项长时程操作任务成功率显著提升。

2. **Velocity Ambiguity Profiles: Time-Resolved Bayes-Risk Diagnostics for Flow Matching**
   Y. Mei\*, X. Zhu\*, C. Wang\*, **C. Xin**\*, et al., G. Wang.
   *NeurIPS 2026* (Under Review) · 共同第一作者
   : 提出 Flow Matching 的时序 Bayes-risk 诊断框架 VAP，将速度预测损失分解为不可约项与可约项，定位各时间区域的数据瓶颈；配套理论刻画、自适应时间采样策略与数据充分性诊断流水线。

3. **Mode-Coverage Learnability of Data-Free Neural Samplers**
   Y. Mei\*, X. Zhu\*, B. Zhang\*, **C. Xin**, et al., G. Wang.
   *AAAI 2027* (Under Review)
   : 针对 data-free neural sampler 的 mode collapse 问题提出 "Location is not Presence" 核心区分，建立 signal-budget lower bound 与正面可学习性结果，并给出可复现的实验验证体系。

4. **ForesightFlow: Self-Guided Flow Matching for Improving Vision-Language-Action Models**
   Y. Mei\*, et al., **C. Xin**, et al., G. Wang.
   *NeurIPS 2026* (Under Review) · 
   : 利用自引导的 Flow Matching 改进视觉-语言-动作模型，在 BEHAVIOR-1K 长时程任务上完成基线训练与评测。

5. **Good Evaluator, Bad Selector: Counterfactual Calibration for Closed-Loop Best-of-K Policies**
   C. Zhang\*, Y. Mei\*, **C. Xin**, et al., G. Wang.
   *ICLR 2027* (Under Review)
   : 针对闭环 Best-of-K 策略中评估器与选择器错配问题，提出反事实校准方法。

### Accepted / 已发表

6. **Hierarchical Value-Decomposed Offline Reinforcement Learning for Whole-Body Control**
   Z. Zhang\*, et al., **C. Xin**, et al., Y. Yu.
   *ICLR 2026* (Accepted) · 
   : 面向全身控制的层次化价值分解离线强化学习；参与构建 WB-50 数据集（50 小时）并制定数据采集与阶段化评估规范。

## In Preparation / 撰写中

- **H2R-4DGen: From Pose-free Ego-Centric Human Data to 4D Robot Data Generation**
  H. Fan, X. Wang, **C. Xin**, et al., G. Wang. *CVPR 2027* (In Preparation)
  : 负责从 Spatial MP4 到机器人训练 episode 的端到端 Human-to-Robot 流水线：融合双目/公制深度、视频分割、手部重建（WiLoR/MANO）、对象重绘与 CuRobo IK，生成与原视频一致的可审计机器人训练数据。

## Patents / 专利

- 王钢，**辛晨博**，梅云鹏，朱啸闻等. 一种面向机器人动作生成的流匹配速度歧义诊断与时间采样方法（发明专利，第一发明人，已受理）
- 刘奋荣, 成凤祥, **辛晨博**, 李昊轩. 一种基于前提排序算法提升大模型推理能力的方法和系统（发明专利，已受理）
