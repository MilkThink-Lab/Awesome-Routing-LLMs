

# Awesome-Routing-LLMs

A curated list of awesome works in Routing LLMs paradigm

🤩👉 Welcome to submit your contributions to this code repository.

---

## Survey

| **Paper**                                                    | **Conference/Journal** | **Code** |
| ------------------------------------------------------------ | ---------------------- | -------- |
| [Dynamic Model Routing and Cascading for Efficient LLM Inference: A Survey](https://arxiv.org/abs/2603.04445) | arxiv'26               |          |

## Routing Papers: Pre‑judgment Routing

*Pre‑judgment routing makes a routing decision before any generation starts. It relies only on the initial query and static model information, making it suitable for fast, one‑shot allocation. The three main strategies are feature matching, predictive scoring, and constrained optimization.*

### **Sub‑Category: Constrained Optimization**

In deployment, routing often faces hard resource constraints (e.g., maximum latency or cost). This paradigm casts decision‑making as constrained utility maximization, using optimization strategies, multi‑objective formulations, or adaptive policies such as reinforcement learning to trade off quality and cost under budget limits.

| Title                                                        | Publish               | Domain                                        | Code                                                         |
| ------------------------------------------------------------ | --------------------- | --------------------------------------------- | ------------------------------------------------------------ |
| [Towards Generalized Routing: Model and Agent Orchestration for Adaptive and Efficient Inference](https://arxiv.org/abs/2509.07571) | ArXiv 2025            | General, Code, Math, QA                       | –                                                            |
| [Dynamic Quality-Latency Aware Routing for LLM Inference in Wireless Edge-Device Networks](https://ieeexplore.ieee.org/abstract/document/11147210) | ICCC Workshop 2025    | General, Dialogue, Math                       | –                                                            |
| [RADAR: Reasoning-Ability and Difficulty-Aware Routing for Reasoning LLMs](https://arxiv.org/abs/2509.25426) (RADAR) | NeurIPS 2025 Workshop | Reasoning, Math, STEM, QA                     | –                                                            |
| [CARROT: A Cost Aware Rate Optimal Router](https://arxiv.org/abs/2502.03261) (CARROT) | ICLR Workshop 2025    | General, Math, Reasoning, RAG, QA             | [GitHub](https://github.com/somerstep/CARROT)                |
| [Causal LLM Routing: End-to-End Regret Minimization from Observational Data](https://arxiv.org/abs/2505.16037) (Causal LLM Routing) | NeurIPS 2025          | General, Reasoning, Math, Code, Dialogue      | –                                                            |
| [Cost-Aware Routing for Efficient Text-To-Image Generation](https://arxiv.org/abs/2506.14753) | ArXiv 2025            | Gen, Multimodal                               | –                                                            |
| [Federate the Router: Learning Language Model Routers with Sparse and Decentralized Evaluations](https://arxiv.org/abs/2601.22318) (Federate the Router) | ArXiv 2026            | General                                       | –                                                            |
| [Fly-swat or Cannon? Cost-Effective Language Model Choice via Meta-Modeling](https://arxiv.org/abs/2308.06077) (FORC) | WSDM 2024             | QA, Reasoning, Classify, Detection, General   | [GitHub](https://github.com/epfl-dlab/forc)                  |
| [IPR: Intelligent Prompt Routing with User-Controlled Quality-Cost Trade-offs](https://aclanthology.org/2025.emnlp-industry.170/) (IPR) | EMNLP 2025            | General, Dialogue, QA, Reasoning              | –                                                            |
| [IRT-Router: Effective and Interpretable Multi-LLM Routing via Item Response Theory](https://aclanthology.org/2025.acl-long.761/) (IRT-Router) | ACL 2025              | General, Math, Code, Reasoning, QA            | [GitHub](https://github.com/Mercidaiha/IRT-Router)           |
| [LLMRank: Understanding LLM Strengths for Model Routing](https://arxiv.org/abs/2510.01234) (LLMRank) | ArXiv 2025            | General, Reasoning, Math, Code, QA            | –                                                            |
| [MetaLLM: A High-performant and Cost-efficient Dynamic Framework for Wrapping LLMs](https://arxiv.org/abs/2407.10834) (MetaLLM) | ArXiv 2024            | Classify, QA                                  | [GitHub](https://github.com/mail-research/MetaLLM-wrapper/)  |
| [PROTEUS: SLA-Aware Routing via Lagrangian RL for Multi-LLM Serving System](https://arxiv.org/abs/2601.19402) (PROTEUS) | ArXiv 2026            | General, Reasoning, Math, Code                | –                                                            |
| [R2-ROUTER: A New Paradigm for LLM Routing with Reasoning](https://arxiv.org/abs/2602.02823) (R2-ROUTER) | ICML 2026             | General, Math, Reasoning, STEM, RAG           | [HuggingFace](https://huggingface.co/JiaqiXue/r2-router/tree/main) |
| [Routoo: Learning to Route to Large Language Models Effectively](https://arxiv.org/abs/2401.13979) (ROUTOO) | ArXiv 2024            | General, QA                                   | –                                                            |
| [Truthful Reverse Auctions for Adaptive Selection via Contextual Multi-Armed Bandits](https://arxiv.org/abs/2602.14476) | AAMAS 2026            | General                                       | –                                                            |
| [Tryage: Real-time, intelligent Routing of User Prompts to Large Language Models](https://arxiv.org/abs/2308.11601) (Tryage) | ArXiv 2023            | Code, Finance, Law, Math, Med, General        | –                                                            |
| [Efficient and Interpretable Multi-Agent LLM Routing via Ant Colony Optimization](https://arxiv.org/abs/2603.12933) | ArXiv 2026            | Math, Code, Reasoning, General                | –                                                            |
| [Adaptive LLM Routing under Budget Constraints](https://aclanthology.org/2025.findings-emnlp.1301/) | EMNLP 2025            | General                                       | –                                                            |
| [Efficient Routing of Inference Requests across LLM Instances in Cloud-Edge Computing](https://arxiv.org/abs/2507.15553) (Efficient Routing) | ArXiv 2025            | Code, Math, QA, Reasoning, General            | –                                                            |
| [GreenServ: Energy-Efficient Context-Aware Dynamic Routing for Multi-Model LLM Inference](https://arxiv.org/abs/2601.17551) (GreenServ) | ArXiv 2026            | QA, Reasoning, Math, General                  | [GitHub](https://github.com/TZData1/llm-inference-router)    |
| [MasRouter: Learning to Route LLMs for Multi-Agent Systems](https://arxiv.org/abs/2502.11133) (MasRouter) | ACL 2025              | Agent, Code, Math, General, Reasoning         | [GitHub](https://github.com/yanweiyue/masrouter)             |
| [MixLLM: Dynamic Routing in Mixed Large Language Models](https://arxiv.org/abs/2502.18482) (MixLLM) | NAACL 2025            | General                                       | –                                                            |
| [Near-Optimal Online Deployment and Routing for Streaming LLMs](https://arxiv.org/abs/2506.17254) (NEAR-OPTIMAL) | ICLR 2026             | General                                       | –                                                            |
| [OmniRouter: Budget and Performance Controllable Multi-LLM Routing](https://arxiv.org/abs/2502.20576) (OmniRouter) | KDD-25 (2025)         | General, Math, QA, Reasoning                  | [GitHub](https://github.com/dongyuanjushi/OmniRouter)        |
| [OptLLM: Optimal Assignment of Queries to Large Language Models](https://arxiv.org/abs/2405.15130) (OptLLM) | ICWS 2024             | Classify, QA, Reasoning, General, Log parsing | [GitHub](https://github.com/LLMs-EffiUse-Lab/OptLLM)         |
| [SC-MAS: Constructing Cost-Efficient Multi-Agent Systems with Edge-Level Heterogeneous Collaboration](https://arxiv.org/abs/2601.09434) (SC-MAS) | ArXiv 2026            | General, Math, Code, Reasoning, Agent         | –                                                            |
| [xRouter: Training Cost-Aware LLMs Orchestration System via Reinforcement Learning](https://arxiv.org/abs/2510.08439) (xRouter) | ArXiv 2025            | Code, Math, Reasoning, QA, General            | [GitHub](https://github.com/SalesforceAIResearch/xRouter)    |
| [Beyond GPT‑5: Making LLMs Cheaper and Better via Performance‑Efficiency Optimized Routing](https://arxiv.org/abs/2508.12631) (Beyond GPT‑5) | DAI 2025              | Agent, Code, General, QA, Reasoning, STEM     | [GitHub](https://github.com/ZhangYiqun018/AvengersPro)       |
| [Routesplain: Towards Faithful and Intervenable Routing for Software-related Tasks](https://arxiv.org/abs/2511.09373) (ROUTESPLAIN) | ArXiv 2025            | Code, QA                                      | –                                                            |
| [Universal LLM Routing with Correctness‑Based Representation](https://openreview.net/forum?id=86eGohKPyy) | ICLR Workshop 2024    | Code, Math, QA, General                       | –                                                            |
| [SpareLLM: Automatically Selecting Task‑Specific Minimum‑Cost Large Language Models under Equivalence Constraint](https://dl.acm.org/doi/abs/10.1145/3725356) (SpareLLM) | SIGMOD 2025           | General                                       | [GitHub](https://github.com/saehanjo/spare-llm)              |
| [BOUTE: Cost‑Efficient LLM Serving with Heterogeneous LLMs and GPUs via Multi‑Objective Bayesian Optimization](https://arxiv.org/abs/2602.10729) (Boute) | ArXiv 2026            | General, Math, Reasoning                      | –                                                            |
| [Outcome‑Aware Tool Selection for Semantic Routers: Latency‑Constrained Learning Without LLM Inference](https://arxiv.org/abs/2603.13426) (OATS) | ArXiv 2026            | Agent, Retrieval                              | –                                                            |

### **Sub‑Category: Feature Matching**

*Feature matching aligns the query representation and model capability representations in a shared space, then selects the model whose embedding is closest to the query. This approach can be lightweight and training‑free, but may degrade under distribution shift; adaptive methods use attention, policy learning, or prototype matching to stay robust.*

| Title                                                        | Publish      | Domain                                           | Code                                                         |
| ------------------------------------------------------------ | ------------ | ------------------------------------------------ | ------------------------------------------------------------ |
| [Talk to Right Specialists: Routing and Planning in Multi‑Agent System for Question Answering](https://arxiv.org/abs/2501.07813) (Talk to Right Specialists) | ArXiv 2025   | QA, RAG, Agent                                   | –                                                            |
| [Arch-Router: Aligning LLM Routing with Human Preferences](https://arxiv.org/abs/2506.16655) (Arch-Router) | ArXiv 2025   | General, Dialogue                                | [GitHub](https://github.com/katanemo/archgw)                 |
| [Cost‑Aware Contrastive Routing for LLMs](https://arxiv.org/abs/2508.12491) (CSCR) | NeurIPS 2025 | General                                          | [GitHub](https://github.com/rezashkv/cscr)                   |
| [EmbedLLM: Learning Compact Representations of Large Language Models](https://openreview.net/forum?id=Fs9EabmQrJ) (EMBEDLLM) | ICLR 2025    | General, QA, Math, Code, Med                     | [GitHub](https://github.com/richardzhuang0412/EmbedLLM)      |
| [Exploring Knowledge Purification in Multi‑Teacher Knowledge Distillation for LLMs](https://arxiv.org/abs/2602.01064) | ICLR 2026    | QA, Reasoning, Med                               | –                                                            |
| [RouterDC: Query‑Based Router by Dual Contrastive Learning for Assembling Large Language Models](https://openreview.net/forum?id=7RQvjayHrM) (RouterDC) | NeurIPS 2024 | General, Math, Code, Reasoning                   | [GitHub](https://github.com/shuhao02/RouterDC)               |
| [Routing with Generated Data: Annotation‑Free LLM Skill Estimation and Expert Selection](https://arxiv.org/abs/2601.09692) (Routing with Generated Data) | ArXiv 2026   | General, QA, Reasoning, Math, Med                | [GitHub](https://github.com/tianyiniu/RoutingGenData)        |
| [TagRouter: Learning Route to LLMs through Tags for Open‑Domain Text Generation Tasks](https://aclanthology.org/2025.findings-acl.1110/) (TAGROUTER) | ACL 2025     | General, Gen                                     | –                                                            |
| [The Avengers: A Simple Recipe for Uniting Smaller Language Models to Challenge Proprietary Giants](https://arxiv.org/abs/2505.19797) (Avengers) | AAAI 2025    | Math, Code, Logic, Knowledge, Affective, General | [GitHub](https://github.com/ZhangYiqun018/Avengers)          |
| [RadialRouter: Structured Representation for Efficient and Robust Large Language Models Routing](https://arxiv.org/abs/2506.03880) (RadialRouter) | EMNLP 2025   | General, Reasoning, Math, Code, QA               | [GitHub](https://github.com/RuihanJin/RadialRouter)          |
| [n‑Musketeers: Reinforcement Learning Shapes Collaboration Among Language Models](https://arxiv.org/abs/2602.09173) (n-Musketeers) | ArXiv 2026   | Math, Logic, Code, Reasoning                     | –                                                            |
| [TCAndon-Router: Adaptive Reasoning Router for Multi‑Agent Collaboration](https://arxiv.org/abs/2601.04544) (TCAndon-Router) | ArXiv 2026   | General, Reasoning, QA                           | [HuggingFace](https://huggingface.co/tencent/TCAndon-Router/tree/main) |
| [Minimizing Mismatch Risk: A Prototype‑Based Routing Framework for Zero‑shot LLM‑generated Text Detection](https://arxiv.org/abs/2602.01240) (DetectRouter) | ICML2026     | Detection, Security                              | –                                                            |
| [Toward Super Agent System with Hybrid AI Routers](https://arxiv.org/abs/2504.10519) (Super Agent System) | ArXiv 2025   | Agent, Code                                      | –                                                            |
| [vLLM Semantic Router: Signal Driven Decision Routing for Mixture‑of‑Modality Models](https://arxiv.org/abs/2603.04444) | ArXiv 2026   | General, Multimodal                              | [GitHub](https://github.com/vllm-project/semantic-router)    |

### **Sub‑Category: Predictive Scoring**

*Predictive scoring learns a parametric estimator (e.g., a small neural network) that predicts the expected utility of each model for a given query. This enables quality‑cost trade‑offs, multi‑objective optimization, and robustness under distribution shift through techniques like minimax, causal inference, or uncertainty estimation.*

| Title                                                        | Publish               | Domain                                    | Code                                                        |
| ------------------------------------------------------------ | --------------------- | ----------------------------------------- | ----------------------------------------------------------- |
| [Think When Needed: Model‑Aware Reasoning Routing for LLM‑based Ranking](https://arxiv.org/abs/2601.18146) (Think When Needed) | ArXiv 2026            | Retrieval, Reasoning                      | –                                                           |
| [Adaptive Routing of Text‑to‑Image Generation Requests Between Large Cloud Model and Light‑Weight Edge Model](https://openaccess.thecvf.com/content/ICCV2025/html/Xin_Adaptive_Routing_of_Text-to-Image_Generation_Requests_Between_Large_Cloud_Model_ICCV_2025_paper.html) (RouteT2I) | ICCV 2025             | Gen, Multimodal                           | –                                                           |
| [BEST‑Route: Adaptive LLM Routing with Test‑Time Optimal Compute](https://openreview.net/forum?id=tFBIbCVXkG) (BEST-Route) | ICML 2025             | QA, Code, Safety                          | [GitHub](https://github.com/microsoft/best-route-llm)       |
| [Capability Instruction Tuning: A New Paradigm for Dynamic LLM Routing](https://arxiv.org/abs/2502.17282) (Capability Instruction Tuning) | AAAI 2025             | General, Multimodal                       | [GitHub](https://github.com/Now-Join-Us/CIT-LLM-Routing)    |
| [CARGO: A Framework for Confidence‑Aware Routing of Large Language Models](https://arxiv.org/abs/2509.14899) (CARGO) | CASCON 2025           | Math, Code, Reasoning, Gen, General       | [GitHub](https://github.com/AmineBarrak/CARGO-Routing_LLMs) |
| [Domain Adaptation for Robust Model Routing](https://openreview.net/forum?id=86eGohKPyy) | NeurIPS 2024 Workshop | Theory, Gen                               | –                                                           |
| [Harnessing the Power of Multiple Minds: Lessons Learned from LLM Routing](https://arxiv.org/abs/2405.00467) | NAACLW 2024           | Reasoning, Math, General                  | [GitHub](https://github.com/kvadityasrivatsa/llm-routing)   |
| [Hybrid LLM: Cost‑Efficient and Quality‑Aware Query Routing](https://openreview.net/forum?id=02f3mUtqnM) (Hybrid LLM) | ICLR 2024             | General                                   | –                                                           |
| [Meta‑Router: Bridging Gold‑standard and Preference‑based Evaluations in Large Language Model Routing](https://arxiv.org/abs/2509.25535) (Meta-Router) | ICLR 2026             | Med, Law, Finance                         | –                                                           |
| [One Head, Many Models: Cross‑Attention Routing for Cost‑Aware LLM Selection](https://arxiv.org/abs/2509.09782) | ArXiv 2025            | General, Math, Code, Reasoning, QA        | –                                                           |
| [Principled Model Routing for Unknown Mixtures of Source Domains](https://openreview.net/forum?id=w7Fe5rHLvJ) | NeurIPS 2025          | General                                   | –                                                           |
| [RouteLLM: Learning to Route LLMs from Preference Data](https://openreview.net/forum?id=8sSqNntaMr) (ROUTELLM) | ICLR 2024             | General, QA, Math, Reasoning              | –                                                           |
| [Routing to the Expert: Efficient Reward‑guided Ensemble of Large Language Models](https://aclanthology.org/2024.naacl-long.109/) (Zooter) | NAACL 2024            | General, Math, Code, Dialogue             | –                                                           |
| [TensorOpera Router: A Multi‑Model Router for Efficient LLM Inference](https://arxiv.org/abs/2408.12320) (TensorOpera Router) | EMNLP 2024            | Med, Code, General, Math, Reasoning, STEM | –                                                           |
| [AgentRouter: A Knowledge‑Graph‑Guided LLM Router for Collaborative Multi‑Agent Question Answering](https://arxiv.org/abs/2510.05445) (AgentRouter) | ArXiv 2025            | Agent, QA, Reasoning                      | –                                                           |
| [HAPS: Hierarchical LLM Routing with Joint Architecture and Parameter Search](https://arxiv.org/abs/2601.05903) (HAPS) | ArXiv 2026            | Agent, QA, Reasoning, General             | [GitHub](https://github.com/zihangtian/HAPS)                |
| [Optimizing Reasoning Efficiency through Prompt Difficulty Prediction](https://arxiv.org/abs/2511.03808) (Optimizing Reasoning) | ArXiv 2025            | Math, Reasoning, STEM                     | –                                                           |
| [Route‑and‑Reason: Scaling Large Language Model Reasoning with Reinforced Model Router](https://arxiv.org/abs/2506.05901) (Route-and-Reason) | ArXiv 2025            | Code, Logic, Math, QA, Reasoning          | [GitHub](https://github.com/tsinghua-fib-lab/R2-Reasoner)   |
| [Leveraging Uncertainty Estimation for Efficient LLM Routing](https://arxiv.org/abs/2502.11021) | ICML Workshop 2025    | General, QA, Math                         | –                                                           |
| [ICL‑Router: In‑Context Learned Model Representations for LLM Routing](https://arxiv.org/abs/2510.09719) (ICL-Router) | AAAI 2025             | General, Math, Code, Logic, Reasoning     | [GitHub](https://github.com/lalalamdbf/ICL-Router)          |
| [Universal LLM Routing with Correctness‑Based Representation](https://openreview.net/forum?id=86eGohKPyy) (UniRoute) | ICLR Workshop 2025    | Med, Code, General, Math, Reasoning, STEM | –                                                           |
| [When Routing Collapses: On the Degenerate Convergence of LLM Routers](https://arxiv.org/abs/2602.03478) (EquiRouter) | ArXiv 2026            | General                                   | [GitHub](https://github.com/AIGNLAI/EquiRouter)             |
| [Dynamic Mix Precision Routing for Efficient Multi‑step LLM Interaction](https://arxiv.org/abs/2602.02711) (DMR) | ArXiv 2026            | Agent, Reasoning                          | –                                                           |
| [LLM Router: Rethinking Routing with Prefill Activations](https://arxiv.org/abs/2603.20895) (LLM Router) | ArXiv 2026            | General, Code, Reasoning, STEM            | –                                                           |
| [ConsRoute: Consistency‑Aware Adaptive Query Routing for Cloud‑Edge‑Device Large Language Models](https://arxiv.org/abs/2603.21237) (ConsRoute) | ArXiv 2026            | General, Math, Code, Dialogue             | –                                                           |

---

## Routing Papers: Verification Routing

*Verification routing expands the decision space to intermediate generation states (partial outputs, confidence scores, or reasoning steps). It can revise routing decisions during inference, making the process more adaptive. Two common patterns are self‑assessment (reactive fallback) and collaborative generation (proactive, token‑level interleaving).*

### **Sub‑Category: Collaborative Generation**

*Collaborative generation integrates decision points directly into the generation process. Instead of a one‑shot model choice, multiple models collaborate step‑wise or token‑wise – e.g., switching control at reasoning boundaries or invoking expert models only at critical tokens. This enables fine‑grained, online adaptation.*



| Title                                                        | Publish      | Domain                                                    | Code                                                         |
| ------------------------------------------------------------ | ------------ | --------------------------------------------------------- | ------------------------------------------------------------ |
| [Heterogeneous Swarms: Jointly Optimizing Model Roles and Weights for Multi‑LLM Systems](https://arxiv.org/abs/2502.04510) (HETEROGENEOUS SWARMS) | NeurIPS 2025 | General, Reasoning, Agent, QA, Math                       | [GitHub](https://github.com/BunsenFeng/heterogeneous_swarm)  |
| [Mixture of Thoughts: Learning to Aggregate What Experts Think, Not Just What They Say](https://arxiv.org/abs/2509.21164) (Mixture of Thoughts) | ICLR2026     | General, Math, Code, Reasoning                            | [GitHub](https://github.com/jacobfa/mot)                     |
| [R2R: Efficiently Navigating Divergent Reasoning Paths with Small‑Large Model Token Routing](https://arxiv.org/abs/2505.21600) (R2R) | NeurIPS 2025 | Math, Code, QA, Reasoning                                 | [GitHub](https://github.com/thu-nics/R2R)                    |
| [RelayLLM: Efficient Reasoning via Collaborative Decoding](https://arxiv.org/abs/2601.05167) (RelayLLM) | ArXiv 2026   | Math, Reasoning                                           | [GitHub](https://github.com/Chengsong-Huang/RelayLLM)        |
| [Budget‑Aware Agentic Routing via Boundary‑Guided Training](https://arxiv.org/abs/2602.21227) (Budget-Aware Agentic) | ArXiv 2026   | Agent, Reasoning, Code                                    | –                                                            |
| [Learning Query‑Aware Budget‑Tier Routing for Runtime Agent Memory](https://arxiv.org/abs/2602.06025) (BudgetMem) | ICML 2026    | Agent, RAG, QA, Dialogue                                  | [GitHub](https://github.com/ViktorAxelsen/BudgetMem)         |
| [Optimizing NetGPT via Routing‑Based Synergy and Reinforcement Learning](https://arxiv.org/abs/2511.22217) | ArXiv 2025   | Agent                                                     | –                                                            |
| [Atlas: Orchestrating Heterogeneous Models and Tools for Multi‑Domain Complex Reasoning](https://arxiv.org/abs/2601.03872) (Atlas) | ArXiv 2026   | Agent, Code, Logic, Math, Multimodal, QA, Reasoning, STEM | –                                                            |
| [ReMA: Learning to Meta‑Think for LLMs with Multi‑Agent Reinforcement Learning](https://arxiv.org/abs/2503.09501) (ReMA) | NeurIPS 2025 | Math, Reasoning, Agent                                    | [GitHub](https://github.com/ziyuwan/ReMA-public)             |
| [Controlling Performance and Budget of a Centralized Multi‑Agent LLM System with Reinforcement Learning](https://arxiv.org/abs/2511.02755) | ArXiv 2025   | Math, Agent, Reasoning                                    | –                                                            |
| [Router‑R1: Teaching LLMs Multi‑Round Routing and Aggregation via Reinforcement Learning](https://openreview.net/forum?id=DWf4vroKWJ) (Router-R1) | NeurIPS 2025 | QA, Reasoning                                             | [GitHub](https://github.com/ulab-uiuc/Router-R1)             |
| [SkillOrchestra: Learning to Route Agents via Skill Transfer](https://arxiv.org/abs/2602.19672) (SkillOrchestra) | ArXiv 2026   | Agent, QA, Math, Reasoning                                | [GitHub](https://github.com/jiayuww/SkillOrchestra)          |
| [LightRouter: Towards Efficient LLM Collaboration with Minimal Overhead](https://arxiv.org/abs/2505.16221) (LightRouter) | ArXiv 2025   | General, Code, Math, QA, Reasoning                        | –                                                            |
| [Token‑Level LLM Collaboration via FusionRoute](https://arxiv.org/abs/2601.05106) (FusionRoute) | ICML 2026    | Math, Code, General                                       | [GitHub](https://github.com/xiongny/FusionRoute/tree/master) |
| [TARo: Token‑level Adaptive Routing for LLM Test‑time Alignment](https://arxiv.org/abs/2603.18411) (TARo) | ArXiv 2026   | Math, Med, Reasoning, Gen                                 | –                                                            |
| [Neural Chain-of-Thought Search: Searching the Optimal Reasoning Path to Enhance Large Language Models](https://arxiv.org/abs/2601.11340)(NCoTs) | ArXiv 2026   | Math, Reasoning, General                                  | [GitHub](https://github.com/MilkThink-Lab/Neural-CoT-Search) |

### **Sub‑Category: Self‑Assessment**

*Self‑assessment uses the model’s own confidence, uncertainty, or self‑consistency signals to decide whether to keep using a lightweight model or escalate to a stronger one. Decisions can be made at sequence end or at reasoning bottlenecks, often with a confidence threshold that triggers fallback.*

| Title                                                        | Publish               | Domain                             | Code                                               |
| ------------------------------------------------------------ | --------------------- | ---------------------------------- | -------------------------------------------------- |
| [ACAR: Adaptive Complexity Routing for Multi‑Model Ensembles with Auditable Decision Traces](https://arxiv.org/abs/2602.21231) (ACAR) | ArXiv 2026            | Math, Reasoning, Code, QA, General | [GitHub](https://github.com/mechramc/ACAR-TeamLLM) |
| [AutoMix: Automatically Mixing Language Models](https://arxiv.org/abs/2310.12963) (AutoMix) | NeurIPS 2024          | QA, Reasoning, Dialogue            | [GitHub](https://github.com/automix-llm/automix)   |
| [Cache & Distil: Optimising API Calls to Large Language Models](https://aclanthology.org/2024.findings-acl.704/) (Cache & Distil) | ACL 2024              | Classify                           | –                                                  |
| [Confident or Seek Stronger: Exploring Uncertainty‑Based On‑Device LLM Routing From Benchmarking to Generalization](https://arxiv.org/abs/2502.04428) (Confident or Seek Stronger) | NeurIPS 2025 Workshop | General, Math, Reasoning, QA       | –                                                  |
| [CP‑Router: An Uncertainty‑Aware Router Between LLM and LRM](https://arxiv.org/abs/2505.19970) (CP-Router) | AAAI 2026             | QA, Reasoning, Math, Logic         | –                                                  |
| [DiSRouter: Distributed Self‑Routing for LLM Selections](https://arxiv.org/abs/2510.19208) (DISROUTER) | ICLR 2026             | General, Math, QA, Reasoning       | –                                                  |
| [Learning to Route LLMs with Confidence Tokens](https://arxiv.org/abs/2410.13284) (Self-REF) | ICML 2025             | General, QA, Math, Med, STEM       | –                                                  |
| [Optimising Calls to Large Language Models with Uncertainty‑Based Two‑Tier Selection](https://arxiv.org/abs/2405.02134) | COLM 2024             | Classify, QA, Reasoning, General   | –                                                  |
| [SATER: A Self‑Aware and Token‑Efficient Approach to Routing and Cascading](https://aclanthology.org/2025.emnlp-main.531/) (SATER) | EMNLP 2025            | General, Math, Reasoning, QA       | –                                                  |

---

## Routing Papers: Memory‑based Routing

*Memory‑based routing conditions decisions not only on the current query but also on persistent historical memory – past queries, outcomes, or user interactions. This grounds uncertain online prediction in reusable evidence, enabling cross‑domain and multi‑turn adaptation. The main approaches are retrieval‑based and structured (graph‑based) routing.*

### **Sub‑Category: Retrieval**

*Retrieval‑based routing finds a semantic neighborhood of historical samples similar to the current query, then aggregates observed model utilities from those samples (e.g., via kNN or proximity weighting). This local estimation adapts to query variations without heavy retraining and can handle distribution shifts gracefully.*

| Title                                                        | Publish               | Domain                                         | Code                                                     |
| ------------------------------------------------------------ | --------------------- | ---------------------------------------------- | -------------------------------------------------------- |
| [Eagle: Efficient Training‑Free Router for Multi‑LLM Inference](https://arxiv.org/abs/2409.15518) (Eagle) | NeurIPS 2024 Workshop | General, Math, Code, Reasoning, QA             | [GitHub](https://github.com/vibss2397/eagle_llm_routing) |
| [PORT: Efficient Training‑Free Online Routing for High‑Volume Multi‑LLM Serving](https://arxiv.org/abs/2509.02718) (PORT) | NeurIPS 2025 Workshop | General, Math, Reasoning, QA, Code             | [GitHub](https://github.com/fzwark/PORT)                 |
| [Large Language Model Routing with Benchmark Datasets](https://arxiv.org/abs/2309.15789) | COLM 2023             | General, QA, Classify, Reasoning               | –                                                        |
| [ProxRouter: Proximity‑Weighted LLM Query Routing for Improved Robustness to Outliers](https://arxiv.org/abs/2510.09852) (ProxRouter) | ArXiv 2025            | General, Math, QA, Reasoning, Med              | –                                                        |
| [Real‑Time Adapting Routing (RAR): Improving Efficiency Through Continuous Learning in Software Powered by Layered Foundation Models](https://ieeexplore.ieee.org/abstract/document/11121685) (RAR) | ICSE-SEIP 2025        | QA, Reasoning, Law, Psych                      | –                                                        |
| [Rethinking Predictive Modeling for LLM Routing: When Simple kNN Beats Complex Learned Routers](https://arxiv.org/abs/2505.12601) | ArXiv 2025            | General, QA, Reasoning, Multimodal, Math, Code | –                                                        |
| [SeqMMR: Sequential Model Merging and LLM Routing for Enhanced Batched Sequential Knowledge Editing](https://aclanthology.org/2025.findings-acl.870/) (SeqMMR) | ACL 2025              | Knowledge Editing                              | –                                                        |
| [EvoRoute: Experience‑Driven Self‑Routing LLM Agent Systems](https://arxiv.org/abs/2601.02695) (EvoRoute) | ArXiv 2026            | Agent, General                                 | –                                                        |
| [Models Under SCOPE: Scalable and Controllable Routing via Pre‑hoc Reasoning](https://arxiv.org/abs/2601.22323) (SCOPE) | ICML 2026             | General, Reasoning, Math, STEM                 | [GitHub](https://github.com/Sullivan07043/SCOPE)         |

### **Sub‑Category: Structured**

*Structured routing represents interactions, queries, tasks, and models as nodes in a topological history graph. Routing becomes a graph‑based scoring problem – e.g., using a Graph Neural Network to encode query and model nodes and predict their routing affinity. This supports relational reasoning, personalization, and long‑term planning.*

| Title                                                        | Publish    | Domain                      | Code                                               |
| ------------------------------------------------------------ | ---------- | --------------------------- | -------------------------------------------------- |
| [GraphRouter: A Graph‑based Router for LLM Selections](https://arxiv.org/abs/2410.03834) (GRAPHROUTER) | ICLR 2025  | General, QA, Reasoning      | [GitHub](https://github.com/ulab-uiuc/GraphRouter) |
| [GMTRouter: Personalized LLM Router over Multi‑turn User Interactions](https://arxiv.org/abs/2511.08590) (GMTRouter) | ArXiv 2025 | General, Dialogue, Math, QA | [GitHub](https://github.com/ulab-uiuc/GMTRouter)   |

## Routing Papers: System Analysis

*Analytical work studies system‑level behavior: theoretical bounds, benchmark  evaluation, and safety risks. These works treat routing as part of a  larger ecosystem with multiple objectives, constraints, and potential  adversaries. The three sub‑categories cover theoretical modeling,  benchmark & evaluation, and safety analysis.*

### **Sub‑Category: Theoretical Modeling**

*Theoretical modeling applies tools from pricing theory, queueing analysis, and game theory to understand routing in constrained, dynamic, or strategic  settings. For example, Stackelberg games model LLM service pricing,  while contextual queueing bandits capture user retrials and scheduling.  These studies reveal interdependencies among routing quality, latency,  and cost.*

| Method                                                       | Domain  | Publish    | Code |
| ------------------------------------------------------------ | ------- | ---------- | ---- |
| [PriLLM (Pricing Online LLM Services with Data‑Calibrated Stackelberg Routing Game)](https://arxiv.org/abs/2511.09062) | Code    | AAAI 2025  | –    |
| [Mahmood et al. (Routing, Cascades, and User Choice for LLMs)](https://arxiv.org/abs/2602.09902) | Theory  | ICLR 2026  | –    |
| [Bae et al. (Learning to Route and Schedule LLMs from User Retrials via Contextual Queueing Bandits)](https://arxiv.org/abs/2602.02061) | General | ArXiv 2026 | –    |

### **Sub‑Category: Benchmark and Evaluation**

*Benchmarks assess routers across diverse tasks, model pools, and deployment  constraints (latency, cost, robustness). They extend evaluation from  static model selection to dynamic, multi‑dimensional trade‑offs.  Representative benchmarks include RouterBench, RouterEval,  VL‑RouterBench (multimodal), and AgentSelect (agentic scenarios). A  unified framework is needed to jointly evaluate quality, latency, cost,  robustness, and resource efficiency.*

| Method                                                       | Domain                              | Publish               | Code                                                         |
| ------------------------------------------------------------ | ----------------------------------- | --------------------- | ------------------------------------------------------------ |
| [Multi-LLM Collaboration for Medication Recommendation](https://arxiv.org/abs/2512.05066) | Med                                 | ArXiv 2025            | –                                                            |
| [AmongUs (Measuring and Mitigating Malicious Contributions in Model Collaboration Systems)](https://arxiv.org/abs/2602.05176) | Security, Safety                    | ICML 2026             | [GitHub](https://github.com/Ziyuan-Yang/AmongUs)             |
| [AgentSelect (Benchmark for Narrative Query‑to‑Agent Recommendation)](https://arxiv.org/abs/2603.03761) | Agent                               | ArXiv 2026            | [GitHub](https://github.com/Ancientshi/AgentMatch)           |
| [DSC (How Robust Are Router‑LLMs? Analysis of the Fragility of LLM Routing Capabilities)](https://arxiv.org/abs/2504.07113) | STEM, Safety                        | EACL 2026             | –                                                            |
| [IPW (Intelligence per Watt: Measuring Intelligence Efficiency of Local AI)](https://arxiv.org/abs/2511.07885) | Chat, General                       | ArXiv 2025            | –                                                            |
| [LLMRouterBench (A Massive Benchmark and Unified Framework for LLM Routing)](https://arxiv.org/abs/2601.07206) | STEM, Med                           | ArXiv 2026            | [GitHub](https://github.com/ynulihao/LLMRouterBench)         |
| [MMR-Bench (A Comprehensive Benchmark for Multimodal LLM Routing)](https://arxiv.org/abs/2601.17814) | Multimodal, VQA                     | ArXiv 2026            | [GitHub](https://github.com/Hunter-Wrynn/MMR-Bench)          |
| [Model-GLUE (Democratized LLM Scaling for A Large Model Zoo in the Wild)](https://arxiv.org/abs/2410.05357) | STEM, Chat                          | NeurIPS 2024          | [GitHub](https://github.com/Model-GLUE/Model-GLUE)           |
| [Prompt-to-Leaderboard (Prompt‑Adaptive LLM Evaluations)](https://arxiv.org/abs/2502.14855) | Chat, General                       | ICML 2025             | [GitHub](https://github.com/lmarena/p2l)                     |
| [RouterArena (An Open Platform for Comprehensive Comparison of LLM Routers)](https://arxiv.org/abs/2510.00202) | General                             | ICLR 2025             | [GitHub](https://github.com/RouteWorks/RouterArena)          |
| [RouterEval (A Comprehensive Benchmark for Routing LLMs)](https://arxiv.org/abs/2503.10657) | General, QA, Reasoning, Math        | EMNLP 2025            | [GitHub](https://github.com/MilkThink-Lab/RouterEval)        |
| [RouterBench (A Benchmark for Multi‑LLM Routing System)](https://arxiv.org/abs/2403.12031) | STEM, RAG                           | ICML Workshop 2024    | [GitHub](https://github.com/withmartian/routerbench)         |
| [RouterXBench (Towards Fair and Comprehensive Evaluation of Routers in Collaborative LLM Systems)](https://arxiv.org/abs/2602.11877) | General, Math, Knowledge, Reasoning | ArXiv 2026            | [GitHub](https://github.com/zhuchichi56/RouterXBench)        |
| [VL-RouterBench (A Benchmark for Vision‑Language Model Routing)](https://arxiv.org/abs/2512.23562) | Multimodal, STEM                    | ArXiv 2025            | [GitHub](https://github.com/K1nght/VL-RouterBench)           |
| [Feng et al. (When One LLM Drools, Multi‑LLM Collaboration Rules)](https://arxiv.org/abs/2502.04506) | General                             | ArXiv 2025            | –                                                            |
| [Yuan et al. (Who Routes the Router: Rethinking the Evaluation of LLM Routing Systems)](https://openreview.net/forum?id=EEPostHMtF) | General                             | NeurIPS 2025 Workshop | [GitHub](https://github.com/jy-yuan/rethinking-routing-evaluation) |
| [RoutingLLM (Boosting LLM Performance for Network Routing)](https://ieeexplore.ieee.org/document/11461033) | Network Routing                     | ICASSP 2026           | –                                                            |

---

## Production Tools & Open-Source Implementations

*Real-world, deployable routing systems that can be used directly in production. These are open-source tools you can install and run today.*

| Tool | Description | Installation | Benchmark |
|:-----|:------------|:-------------|:----------|
| [**A3M Router** 🏆](https://github.com/Das-rebel/a3m-router) | Open-source LLM router with **parallel multi-LLM execution** — runs 47+ providers simultaneously with confidence-scored voting. Features ensemble voting, query-type presets, semantic cache, budget enforcement, circuit breaker, and persistent episodic memory. | `npm install -g adaptive-memory-multi-model-router` | 🥇 **RouterArena #1** (76.43) — beats Sqwish, Azure, GPT-5, RouteLLM. [Results](https://github.com/RouteWorks/RouterArena/pull/113) |

### **Sub‑Category: Safety Analysis**

*Safety analysis studies routing failures under adversarial, unreliable, or  privacy‑sensitive conditions. Attackers can redirect queries to  expensive models or bypass policies (e.g., confounder gadgets,  adversarial suffixes). Defenses include contrastive learning,  embedding‑based filtering, and hybrid surrogate models. Future routers  must embed safety, privacy, and security as core design constraints.*

| Method                                                       | Domain            | Publish    | Code                                                         |
| ------------------------------------------------------------ | ----------------- | ---------- | ------------------------------------------------------------ |
| [RerouteGuard (Understanding and Mitigating Adversarial Risks for LLM Routing)](https://arxiv.org/abs/2601.21380) | STEM, Safety      | ArXiv 2026 | –                                                            |
| [Rerouting LLM Routers](https://arxiv.org/abs/2501.01818)    | General, Security | COLM 2025  | [GitHub](https://github.com/avitalsh/rerouting_llm_routers/tree/main) |
| [R2A (Route to Rome Attack: Directing LLM Routers to Expensive Models via Adversarial Suffix Optimization)](https://arxiv.org/abs/2604.15022) | Safety, Security  | ACL 2026   | [GitHub](https://github.com/thcxiker/R2A-Attack)             |