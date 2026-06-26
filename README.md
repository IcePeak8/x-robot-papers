# X-Robot Papers

> Robotics / Embodied AI paper radar for quadruped navigation, locomotion, Sim2Real, ROS/Nav2, VLA, SLAM, control, and real robot deployment.

![papers](https://img.shields.io/badge/papers-5-blue) ![latest](https://img.shields.io/badge/latest-2026--06--26-green) ![language](https://img.shields.io/badge/notes-Chinese-orange)

## Radar

| 方向 | 数量 | 重点 |
| --- | ---: | --- |
| Quadruped / Locomotion | 3 | 四足 RL、控制器先验、极端地形、跨平台 locomotion |
| Navigation / Isaac | 1 | Isaac Lab、human-aware navigation、动态人群 benchmark |
| VLA / Evaluation | 1 | VLA smoke test、部署前评测、policy routing |

## Featured Papers

| Paper | Area | Links | 为什么值得看 |
| --- | --- | --- | --- |
| MPC-Injection: Biasing Off-Policy Locomotion RL Toward Controller-Induced Behavior Basins | Locomotion / RL / Sim2Real | [arXiv](https://arxiv.org/abs/2606.26392) · [alphaXiv](https://alphaxiv.org/abs/2606.26392) · [PDF](https://arxiv.org/pdf/2606.26392) | 非常贴近四足 RL 部署、控制器先验，以及“高 reward 不等于可用 gait”的问题。 |
| NavIsaacLab: Generating Realistic Crowd via Parallel Robot Learning for Benchmarking Human-aware Navigation | Navigation / Isaac | [arXiv](https://arxiv.org/abs/2606.26265) · [alphaXiv](https://alphaxiv.org/abs/2606.26265) · [PDF](https://arxiv.org/pdf/2606.26265) | 适合沉淀 ROS/Nav2 social navigation、Isaac 仿真和导航 benchmark 设计思路。 |
| StairMaster: Learning to Conquer Risky Hollow Stairs for Agile Quadrupedal Robots | Quadruped / Sim2Real | [arXiv](https://arxiv.org/abs/2606.25765) · [alphaXiv](https://alphaxiv.org/abs/2606.25765) · [PDF](https://arxiv.org/pdf/2606.25765) | 空心楼梯是一个很具体的四足失败场景：深度稀疏、腿部卡陷、主动感知和极端地形稳定性。 |

## By Topic

- **Quadruped**: [StairMaster](#stairmaster-learning-to-conquer-risky-hollow-stairs-for-agile-quadrupedal-robots), [Learning Perceptive Platform Adaptive Locomotion Controllers](#learning-perceptive-platform-adaptive-locomotion-controllers-for-quadrupedal-robots)
- **Locomotion / Control**: [MPC-Injection](#mpc-injection-biasing-off-policy-locomotion-rl-toward-controller-induced-behavior-basins)
- **Navigation / Isaac**: [NavIsaacLab](#navisaaclab-generating-realistic-crowd-via-parallel-robot-learning-for-benchmarking-human-aware-navigation)
- **VLA / Evaluation**: [RouterVLA](#routervla-turning-smoke-tests-into-supervision-for-heterogeneous-vla-selection)

## Complete List

### 2026-06-26 添加

#### MPC-Injection: Biasing Off-Policy Locomotion RL Toward Controller-Induced Behavior Basins

`Locomotion` `Quadruped` `RL` `Sim2Real` `Control`

- 发布日期：2026-06-24
- 链接：[arXiv](https://arxiv.org/abs/2606.26392) · [alphaXiv](https://alphaxiv.org/abs/2606.26392) · [PDF](https://arxiv.org/pdf/2606.26392)
- 一句话总结：使用 MPC 生成的 transitions，把 off-policy locomotion RL 引向更可部署的行为区域。
- 收藏理由：非常贴近四足 RL 部署、控制器先验、Sim2Real 和“高 reward 不等于可用 gait”的工程问题。
- 工程备注：重点看它和 reward shaping 的边界，以及学出来的 gait 是否能通过真实机器人的命令接口、控制延迟和安全约束。

#### NavIsaacLab: Generating Realistic Crowd via Parallel Robot Learning for Benchmarking Human-aware Navigation

`Navigation` `Isaac` `Benchmark` `Sim2Real`

- 发布日期：2026-06-24
- 链接：[arXiv](https://arxiv.org/abs/2606.26265) · [alphaXiv](https://alphaxiv.org/abs/2606.26265) · [PDF](https://arxiv.org/pdf/2606.26265)
- 一句话总结：基于 Isaac Lab 生成人群导航场景，用于 human-aware navigation benchmark。
- 收藏理由：适合沉淀 ROS/Nav2 social navigation、Isaac 仿真和导航 benchmark 设计思路。
- 工程备注：重点检查传感器假设、人群行为真实性、动态障碍恢复能力，以及它和 Nav2 测试方式的对应关系。

#### StairMaster: Learning to Conquer Risky Hollow Stairs for Agile Quadrupedal Robots

`Quadruped` `Locomotion` `Sim2Real` `RL`

- 发布日期：2026-06-24
- 链接：[arXiv](https://arxiv.org/abs/2606.25765) · [alphaXiv](https://alphaxiv.org/abs/2606.25765) · [PDF](https://arxiv.org/pdf/2606.25765)
- 一句话总结：面向空心楼梯的四足三阶段 RL 框架，重点处理深度感知噪声和 Sim2Real。
- 收藏理由：问题非常具体：深度稀疏、腿部卡陷、主动感知和极端地形稳定性。
- 工程备注：重点看真实硬件测试、深度 artifact 建模、跌倒/恢复策略和控制延迟假设。

#### Learning Perceptive Platform Adaptive Locomotion Controllers for Quadrupedal Robots

`Quadruped` `Locomotion` `RL` `Sim2Real`

- 发布日期：2026-06-23
- 链接：[arXiv](https://arxiv.org/abs/2606.25179) · [alphaXiv](https://alphixiv.org/abs/2606.25179) · [PDF](https://arxiv.org/pdf/2606.25179)
- 一句话总结：研究跨不同四足平台的形态自适应 perceptive locomotion controller。
- 收藏理由：适合思考 universal quadruped policy 的边界，以及不同机器人平台之间的部署差异。
- 工程备注：重点比较 blind、critic-perceptive 和 fully perceptive 方案，关注感知噪声与形态差异造成的稳定性问题。

#### RouterVLA: Turning Smoke Tests into Supervision for Heterogeneous VLA Selection

`VLA` `Benchmark` `Dataset`

- 发布日期：2026-06-25
- 链接：[arXiv](https://arxiv.org/abs/2606.27355) · [alphaXiv](https://alphaxiv.org/abs/2606.27355) · [PDF](https://arxiv.org/pdf/2606.27355)
- 一句话总结：把部署前 smoke test rollout 转成监督信号，用于在多个 VLA policy 之间做选择。
- 收藏理由：适合作为 VLA 部署评测、策略路由和防止测试指标虚高的方法笔记。
- 工程备注：重点看 smoke test 是否覆盖真实 failure mode，是否存在评估泄漏，以及如何映射到真机 rollout ledger。

## Monthly Archive

- [2026-06](papers/2026-06.md)

## Data

- [JSONL](data/papers.jsonl)
