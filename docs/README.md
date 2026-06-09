<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-11 ~ 2026-06-09
- 运行时间：2026-06-09 10:09:30 UTC
- 运行状态：成功
- 本次总论文数：31
- 精读区：0
- 速读区：31

### 今日简报（AI）
今日速读31篇强化学习与LLM对齐方向论文，重点关注三项满分研究。

《Missing Old Logits》揭示异步智能体RL中的语义错配，提出离策略修正方法；《Adaptive Importance Sampling》针对量化RL给出自适应重要性采样方案；《Diagnosing Training Inference Mismatch》诊断LLM强化学习中的训练-推理不一致问题，三者均值得精读。

下一步建议优先精读这三篇10分论文，关注旧logits修复、量化采样优化和训练推理差异缓解的具体方法。
- 详情：[/20260511-20260609/README](/20260511-20260609/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [Missing Old Logits in Asynchronous Agentic RL: Semantic Mismatch and Repair Methods for Off-Policy Correction](/20260511-20260609/2605.12070v2-missing-old-logits-in-asynchronous-agentic-rl-semantic-mismatch-and-repair-methods-for-off-policy-correction)  
   标签：评分：10.0/10、query:rl-rollout
   evidence：显式处理异步代理RL中的训推不一致
2. [AIS: Adaptive Importance Sampling for Quantized RL](/20260511-20260609/2605.13907v1-ais-adaptive-importance-sampling-for-quantized-rl)  
   标签：评分：10.0/10、query:rl-rollout
   evidence：直接处理LLM RL中低精度rollout导致的rollout训练不匹配
3. [Diagnosing Training Inference Mismatch in LLM Reinforcement Learning](/20260511-20260609/2605.14220v1-diagnosing-training-inference-mismatch-in-llm-reinforcement-learning)  
   标签：评分：10.0/10、query:rl-rollout
   evidence：直接诊断LLM强化学习中的训练-推理不匹配（TIM），隔离原因并提出补救措施
4. [PR2: Predictive Routing Replay for MoE-Based LLM Reinforcement Learning](/20260511-20260609/2606.00395v2-pr2-predictive-routing-replay-for-moe-based-llm-reinforcement-learning)  
   标签：评分：10.0/10、query:rl-rollout
   evidence：直接解决MoE LLM强化学习中由于路由器漂移导致的rollout-训练不匹配
5. [Reformulate LLM Reinforcement Learning for Efficient Training under Black-box Discrepancy](/20260511-20260609/2606.08779v1-reformulate-llm-reinforcement-learning-for-efficient-training-under-black-box-discrepancy)  
   标签：评分：10.0/10、query:rl-rollout
   evidence：直接应对LLM强化学习中的训练-推理不一致
6. [COPRA: Conditional Parameter Adaptation with Reinforcement Learning for Video Anomaly Detection](/20260511-20260609/2605.15325v1-copra-conditional-parameter-adaptation-with-reinforcement-learning-for-video-anomaly-detection)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：利用RL解决VLM视频异常检测中的训推不一致
7. [Spend Your Rollouts Where It Counts: Rollout Allocation for Group-Based RL Post-Training](/20260511-20260609/2605.26606v1-spend-your-rollouts-where-it-counts-rollout-allocation-for-group-based-rl-post-training)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：基于组的RL后训练中的rollout分配
8. [DARTS: Distribution-Aware Active Rollout Trajectory Shaping for Accelerating LLM Reinforcement Learning](/20260511-20260609/2605.30859v1-darts-distribution-aware-active-rollout-trajectory-shaping-for-accelerating-llm-reinforcement-learning)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：通过rollout轨迹形状加速强化学习
9. [EchoRL: Reinforcement Learning via Rollout Echoing](/20260511-20260609/2605.31228v1-echorl-reinforcement-learning-via-rollout-echoing)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：提出EchoRL解决RL训练中rollout优势退化问题
10. [DRIFT: Decoupled Rollouts and Importance-Weighted Fine-Tuning for Efficient Multi-Turn Optimization](/20260511-20260609/2605.31455v1-drift-decoupled-rollouts-and-importance-weighted-fine-tuning-for-efficient-multi-turn-optimization)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：解耦路径并使用重要性加权提升效率
11. [Are Full Rollouts Necessary for On-Policy Distillation?](/20260511-20260609/2605.31490v1-are-full-rollouts-necessary-for-on-policy-distillation)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：探讨在策略蒸馏中完整路径的必要性
12. [Are Full Rollouts Necessary for On-Policy Distillation?](/20260511-20260609/2605.31490v2-are-full-rollouts-necessary-for-on-policy-distillation)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：探讨在策略蒸馏中完整路径的必要性
13. [Learning When Not to Act: Mitigating Tool Abuse in Agentic Reinforcement Learning](/20260511-20260609/2606.02132v2-learning-when-not-to-act-mitigating-tool-abuse-in-agentic-reinforcement-learning)  
   标签：评分：9.0/10、query:ag-rl
   evidence：直接处理智能体强化学习中的工具滥用问题，使用基于rollout的方法
14. [Libra: Efficient Resource Management for Agentic RL Post-Training](/20260511-20260609/2606.03077v1-libra-efficient-resource-management-for-agentic-rl-post-training)  
   标签：评分：9.0/10、query:ag-rl
   evidence：针对智能体RL后训练资源管理，解决rollout速度和不对称问题
15. [Tool-Aware Optimization with Entropy Guidance for Efficient Agentic Reinforcement Learning](/20260511-20260609/2606.03762v1-tool-aware-optimization-with-entropy-guidance-for-efficient-agentic-reinforcement-learning)  
   标签：评分：9.0/10、query:ag-rl
   evidence：提出TAO-RL框架用于高效智能体强化学习，包含工具感知轨迹过滤和熵引导
16. [Sparrow: Sparse Rollout for Stable and Efficient Long-context RL of Large Language Models](/20260511-20260609/2606.08446v1-sparrow-sparse-rollout-for-stable-and-efficient-long-context-rl-of-large-language-models)  
   标签：评分：9.0/10、query:rl-rollout
   evidence：稀疏rollout直接解决长上下文RL中的rollout速度和稳定性问题
17. [Missing Old Logits in Asynchronous Agentic RL: Semantic Mismatch and Repair Methods for Off-Policy Correction](/20260511-20260609/2605.12070v1-missing-old-logits-in-asynchronous-agentic-rl-semantic-mismatch-and-repair-methods-for-off-policy-correction)  
   标签：评分：8.0/10、query:ag-rl
   evidence：明确处理异步智能体RL中的训练-推理不一致和策略陈旧性，提出语义失配修复方法
18. [Ranking-Aware Calibration for Reliable Multimodal Reinforcement Learning](/20260511-20260609/2605.16999v1-ranking-aware-calibration-for-reliable-multimodal-reinforcement-learning)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：强化学习策略校准中训练与推理的差距导致过度自信
19. [ParaVT: Taming the Tool Prior Paradox for Parallel Tool Use in Agentic Video Reinforcement Learning](/20260511-20260609/2605.20342v2-paravt-taming-the-tool-prior-paradox-for-parallel-tool-use-in-agentic-video-reinforcement-learning)  
   标签：评分：8.0/10、query:ag-rl
   evidence：多智能体RL用于智能体视频工具调用
20. [Not All Transitions Matter: Evidence from PPO](/20260511-20260609/2605.24071v1-not-all-transitions-matter-evidence-from-ppo)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：研究PPO rollout中的冗余并建议丢弃过渡以改善训练
21. [BASIS: Batchwise Advantage Estimation from Single-Rollout Information Sharing for LLM Reasoning](/20260511-20260609/2605.27293v1-basis-batchwise-advantage-estimation-from-single-rollout-information-sharing-for-llm-reasoning)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：单rollout批量优势估计提升rollout样本效率
22. [SKILLC: Learning Autonomous Skill Internalization in LLM Agents via Contrastive Credit Assignment](/20260511-20260609/2605.27899v1-skillc-learning-autonomous-skill-internalization-in-llm-agents-via-contrastive-credit-assignment)  
   标签：评分：8.0/10、query:ag-rl
   evidence：聚焦于智能体强化学习中的技能内化，使用rollout对比学习
23. [Where Rollouts Begin: Low-Load, High-Leverage First-Token Diversification for RLVR](/20260511-20260609/2605.28295v1-where-rollouts-begin-low-load-high-leverage-first-token-diversification-for-rlvr)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：聚焦于RLVR中的rollout多样性，是rollout优化的关键方面
24. [PR2: Predictive Routing Replay for MoE-Based LLM Reinforcement Learning](/20260511-20260609/2606.00395v1-pr2-predictive-routing-replay-for-moe-based-llm-reinforcement-learning)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：解决MoE基LLM RL中因路由器漂移导致的rollout-训练不匹配，提出PR2
25. [Internalize the Temperature: On-Policy Self-Distillation as Policy Reheater for Reinforcement Learning](/20260511-20260609/2606.00755v1-internalize-the-temperature-on-policy-self-distillation-as-policy-reheater-for-reinforcement-learning)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：应对路径多样性坍缩并提出自蒸馏方法
26. [Policy and World Modeling Co-Training for Language Agents](/20260511-20260609/2606.02388v1-policy-and-world-modeling-co-training-for-language-agents)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：利用在线RL路径中的状态转移为世界模型提供监督
27. [ASymPO: Asymmetric-Scale Policy Optimization for Asynchronous LLM Post-Training Without Behavior Information](/20260511-20260609/2606.03070v1-asympo-asymmetric-scale-policy-optimization-for-asynchronous-llm-post-training-without-behavior-information)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：解决异步RL中陈旧响应导致的训练-推理分布漂移，提出无需行为信息的ASymPO
28. [ASymPO: Asymmetric-Scale Policy Optimization for Asynchronous LLM Post-Training Without Behavior Information](/20260511-20260609/2606.03070v2-asympo-asymmetric-scale-policy-optimization-for-asynchronous-llm-post-training-without-behavior-information)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：解决异步RL中陈旧响应导致的训练-推理分布漂移，提出无需行为信息的ASymPO
29. [Rollout-Level Advantage-Prioritized Experience Replay for GRPO](/20260511-20260609/2606.04560v1-rollout-level-advantage-prioritized-experience-replay-for-grpo)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：提出面向GRPO的rollout级经验回放，提高rollout利用效率
30. [SALT: When More Rollouts Don't Help in Group-Based Policy Optimization and How to Make Them Matter](/20260511-20260609/2606.05800v1-salt-when-more-rollouts-dont-help-in-group-based-policy-optimization-and-how-to-make-them-matter)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：基于组的策略优化中 rollout 效率问题
31. [sGPO: Trading Inference FLOPs for Training Efficiency in RLVR](/20260511-20260609/2606.08854v1-sgpo-trading-inference-flops-for-training-efficiency-in-rlvr)  
   标签：评分：8.0/10、query:rl-rollout
   evidence：RLVR中的rollout预算分配与效率


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
