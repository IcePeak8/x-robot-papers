# X-Robot Papers

机器人与具身智能最新论文收藏列表。

## 2026-06-30 添加

- **PinNet: Keypoint-Aware Learned Local Descriptors with Geometric Embedding for Loop Closure in LiDAR SLAM** · [arXiv](https://arxiv.org/abs/2606.28637) · [alphaXiv](https://alphaxiv.org/abs/2606.28637) — 用 learned keypoint/descriptor 改善 LiDAR SLAM 回环检测，直指长距离导航里的漂移问题。
- **FADA: Few-Shot Domain Adaptation via Dynamics Alignment for Humanoid Control** · [arXiv](https://arxiv.org/abs/2606.28476) · [alphaXiv](https://alphaxiv.org/abs/2606.28476) — 只用约 2 分钟目标域 rollout 微调 inverse dynamics，让人形控制适应地形、载荷和执行器差异。
- **The Speedup Paradox: Rethinking Inference Speed-Quality Trade-off in Embodied Tasks** · [arXiv](https://arxiv.org/abs/2606.28529) · [alphaXiv](https://alphaxiv.org/abs/2606.28529) — 讨论具身任务中推理加速不一定等于任务更快，关键在闭环交互而非单步延迟。
- **ReactiveBFM: Reactive Closed-Loop Motion Planning Towards Universal Humanoid Whole-Body Control** · [arXiv](https://arxiv.org/abs/2606.30362) · [alphaXiv](https://alphaxiv.org/abs/2606.30362) — 在 Unitree G1 上做实时闭环全身动作规划，重点处理重规划延迟和 tracking exposure bias。
- **Vision-Language-Action Models: Experimental Insights from a Real-World UR5 Platform** · [arXiv](https://arxiv.org/abs/2606.30456) · [alphaXiv](https://alphaxiv.org/abs/2606.30456) — 用 UR5 真机实验说明 VLA 落地瓶颈常在动作语义、坐标系、时间对齐和数据管线。

## 2026-06-29 添加

- **Support-Constrained RL Enables Real-World Policy Improvement without Real-World Experience** · [arXiv](https://arxiv.org/abs/2606.27475) · [alphaXiv](https://alphaxiv.org/abs/2606.27475) — 用支持约束的 real-to-sim-to-real RL，在不追加真机采样的前提下提升真实操作策略成功率。
- **SceneBot: Contact-Prompted General Humanoid Whole Body Tracking with Scene-Interaction** · [arXiv](https://arxiv.org/abs/2606.27581) · [alphaXiv](https://alphaxiv.org/abs/2606.27581) — 让人形机器人在含接触场景里做更通用的全身跟踪，把动作模仿推进到可交互环境。
- **Direct Action-Head Injection of A Grounded 3D Point Unlocks Spatial and Task Generalization** · [arXiv](https://arxiv.org/abs/2606.27663) · [alphaXiv](https://alphaxiv.org/abs/2606.27663) — 向 VLA action head 注入 grounded 3D point，提升机械臂在空间变化和新任务下的泛化能力。
- **SpikeVLA: Vision-Language-Action Models with Spiking Neural Networks** · [arXiv](https://arxiv.org/abs/2606.27807) · [alphaXiv](https://alphaxiv.org/abs/2606.27807) — 用脉冲神经网络改造 VLA，直指机器人部署里最敏感的推理延迟与能耗问题。

## 2026-06-26 添加

- **MPC-Injection: Biasing Off-Policy Locomotion RL Toward Controller-Induced Behavior Basins** · [arXiv](https://arxiv.org/abs/2606.26392) · [alphaXiv](https://alphaxiv.org/abs/2606.26392) — 使用 MPC 生成的 transitions，把 off-policy locomotion RL 引向更可部署的行为区域。
- **NavIsaacLab: Generating Realistic Crowd via Parallel Robot Learning for Benchmarking Human-aware Navigation** · [arXiv](https://arxiv.org/abs/2606.26265) · [alphaXiv](https://alphaxiv.org/abs/2606.26265) — 基于 Isaac Lab 生成人群导航场景，用于 human-aware navigation benchmark。
- **StairMaster: Learning to Conquer Risky Hollow Stairs for Agile Quadrupedal Robots** · [arXiv](https://arxiv.org/abs/2606.25765) · [alphaXiv](https://alphaxiv.org/abs/2606.25765) — 面向空心楼梯的四足三阶段 RL 框架，重点处理深度感知噪声和 Sim2Real。
- **Learning Perceptive Platform Adaptive Locomotion Controllers for Quadrupedal Robots** · [arXiv](https://arxiv.org/abs/2606.25179) · [alphaXiv](https://alphaxiv.org/abs/2606.25179) — 研究跨不同四足平台的形态自适应 perceptive locomotion controller。
- **RouterVLA: Turning Smoke Tests into Supervision for Heterogeneous VLA Selection** · [arXiv](https://arxiv.org/abs/2606.27355) · [alphaXiv](https://alphaxiv.org/abs/2606.27355) — 把部署前 smoke test rollout 转成监督信号，用于在多个 VLA policy 之间做选择。

## Archive

- [2026-06](papers/2026-06.md)
