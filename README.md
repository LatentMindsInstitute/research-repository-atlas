# Latent Minds Institute Research Repository Atlas

A maintained reference map for public tools, environments, datasets, evaluation frameworks and learning resources relevant to advanced AI safety work.

> Status: curated reference catalogue. Inclusion is not an endorsement, security audit, replication or claim of production readiness.

Snapshot: 2026-08-07. 151 unique public repositories across 18 categories and 181 category memberships.

Open the [browser catalogue](index.html) or use the machine-readable [catalog.json](catalog.json).

## Curation boundaries

- All private personal repository names are excluded.
- Experimental, legacy and incompletely documented resources are marked as references.
- The 3,436 README-discovered links outside the reviewed corpus remain unreviewed and are not published here.
- Dual-use resources require a separate context-specific risk review before operational use.
- Repository licences remain with their original owners and must be checked at the linked source.

## Categories

### RL Environments & Games (15)

Multi-agent environments, social dilemmas, bargaining, game theory, and RL simulations for Crucible experiments.

- [cfpark00/rl-environments](https://github.com/cfpark00/rl-environments) (operational core)
- [Farama-Foundation/Gymnasium](https://github.com/Farama-Foundation/Gymnasium) (operational core)
- [Farama-Foundation/PettingZoo](https://github.com/Farama-Foundation/PettingZoo) (operational core)
- [gambitproject/gte](https://github.com/gambitproject/gte) (operational core)
- [google-deepmind/meltingpot](https://github.com/google-deepmind/meltingpot) (operational core)
- [google-deepmind/open_spiel](https://github.com/google-deepmind/open_spiel) (operational core)
- [HumanCompatibleAI/overcooked_ai](https://github.com/HumanCompatibleAI/overcooked_ai) (operational core)
- [joie-zhang/bargain](https://github.com/joie-zhang/bargain) (operational core)
- [longtermrisk/marltoolbox](https://github.com/longtermrisk/marltoolbox) (operational core)
- [oxwhirl/pymarl](https://github.com/oxwhirl/pymarl) (operational core)
- [PKU-Alignment/ReDMan](https://github.com/PKU-Alignment/ReDMan) (cross-listed experimental)
- [PKU-Alignment/safety-gymnasium](https://github.com/PKU-Alignment/safety-gymnasium) (operational core)
- [PKU-Alignment/VLA-Arena](https://github.com/PKU-Alignment/VLA-Arena) (operational core)
- [safety-research/social_games](https://github.com/safety-research/social_games) (operational core)
- [Unity-Technologies/ml-agents](https://github.com/Unity-Technologies/ml-agents) (operational core)

### AI Red Teaming & Jailbreaks (11)

Dual-use, defensive research on jailbreaks, prompt injection, red-team harnesses, and guardrail testing.

- [centerforaisafety/HarmBench](https://github.com/centerforaisafety/HarmBench) (operational core)
- [dissensus-ai/autonomous-red-team](https://github.com/dissensus-ai/autonomous-red-team) (operational core)
- [elder-plinius/T3MP3ST](https://github.com/elder-plinius/T3MP3ST) (operational core)
- [Goochbeater/Spiritual-Spell-Red-Teaming](https://github.com/Goochbeater/Spiritual-Spell-Red-Teaming) (operational core)
- [haizelabs/llama3-jailbreak](https://github.com/haizelabs/llama3-jailbreak) (operational core)
- [JailbreakBench/jailbreakbench](https://github.com/JailbreakBench/jailbreakbench) (operational core)
- [llm-attacks/llm-attacks](https://github.com/llm-attacks/llm-attacks) (operational core)
- [meta-llama/PurpleLlama](https://github.com/meta-llama/PurpleLlama) (operational core)
- [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) (operational core)
- [QData/TextAttack](https://github.com/QData/TextAttack) (operational core)
- [safety-research/agent-transcript-editor](https://github.com/safety-research/agent-transcript-editor) (operational core)

### Cybersecurity & Exploit Research (5)

Dual-use AI security, exploit benchmarks, agent scanners, bug finding, and defensive cyber tooling.

- [aliasrobotics/cai](https://github.com/aliasrobotics/cai) (operational core)
- [Hack-with-Github/Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) (operational core)
- [ispras/casr](https://github.com/ispras/casr) (operational core)
- [snyk/agent-scan](https://github.com/snyk/agent-scan) (operational core)
- [sunblaze-ucb/exploitgym](https://github.com/sunblaze-ucb/exploitgym) (operational core)

### Alignment: Control & Monitoring (9)

Control evaluations, trusted monitoring, sandbox escape, legibility, deception detection, and tamper resistance.

- [invariantlabs-ai/invariant](https://github.com/invariantlabs-ai/invariant) (operational core)
- [rishub-tamirisa/tamper-resistance](https://github.com/rishub-tamirisa/tamper-resistance) (operational core)
- [safety-research/agent-escape-bench](https://github.com/safety-research/agent-escape-bench) (operational core)
- [safety-research/assistant-axis](https://github.com/safety-research/assistant-axis) (operational core)
- [safety-research/legibility](https://github.com/safety-research/legibility) (operational core)
- [safety-research/lie-detector](https://github.com/safety-research/lie-detector) (operational core)
- [safety-research/sleight-bench](https://github.com/safety-research/sleight-bench) (operational core)
- [safety-research/trusted-monitor](https://github.com/safety-research/trusted-monitor) (operational core)
- [UKGovernmentBEIS/control-arena](https://github.com/UKGovernmentBEIS/control-arena) (operational core)

### Alignment: Model Organisms (7)

Alignment-faking model organisms, emergent misalignment, data poisoning, and falsifiable misbehavior testbeds.

- [redwoodresearch/bench-af-2](https://github.com/redwoodresearch/bench-af-2) (operational core)
- [safety-research/alignment-faking-extensions](https://github.com/safety-research/alignment-faking-extensions) (operational core)
- [safety-research/data-poisoning-public](https://github.com/safety-research/data-poisoning-public) (operational core)
- [safety-research/false-facts](https://github.com/safety-research/false-facts) (operational core)
- [safety-research/inoculation-prompting](https://github.com/safety-research/inoculation-prompting) (operational core)
- [safety-research/misalignment-indicators](https://github.com/safety-research/misalignment-indicators) (operational core)
- [safety-research/open-source-alignment-faking](https://github.com/safety-research/open-source-alignment-faking) (operational core)

### Safety Evals & Auditing (19)

Evaluation frameworks, auditing agents, safety benchmarks, model graders, and reproducible evaluation infrastructure.

- [meridianlabs-ai/inspect_petri](https://github.com/meridianlabs-ai/inspect_petri) (operational core)
- [METR/hawk](https://github.com/METR/hawk) (operational core)
- [METR/task-standard](https://github.com/METR/task-standard) (operational core)
- [PKU-Alignment/eval-anything](https://github.com/PKU-Alignment/eval-anything) (operational core)
- [PKU-Alignment/MM-DeceptionBench](https://github.com/PKU-Alignment/MM-DeceptionBench) (operational core)
- [PKU-Alignment/Safe-Policy-Optimization](https://github.com/PKU-Alignment/Safe-Policy-Optimization) (operational core)
- [PKU-Alignment/safety-gymnasium](https://github.com/PKU-Alignment/safety-gymnasium) (operational core)
- [PKU-Alignment/SafeVLA](https://github.com/PKU-Alignment/SafeVLA) (operational core)
- [PKU-Alignment/SPIKE-Bench](https://github.com/PKU-Alignment/SPIKE-Bench) (operational core)
- [PKU-Alignment/VLA-Arena](https://github.com/PKU-Alignment/VLA-Arena) (operational core)
- [safety-research/auditing-agents](https://github.com/safety-research/auditing-agents) (operational core)
- [safety-research/bloom](https://github.com/safety-research/bloom) (operational core)
- [safety-research/faithful-cot](https://github.com/safety-research/faithful-cot) (operational core)
- [safety-research/finetuning-auditor](https://github.com/safety-research/finetuning-auditor) (operational core)
- [safety-research/impossiblebench](https://github.com/safety-research/impossiblebench) (operational core)
- [safety-research/safety-examples](https://github.com/safety-research/safety-examples) (operational core)
- [safety-research/safety-tooling](https://github.com/safety-research/safety-tooling) (operational core)
- [safety-research/SCONE-bench](https://github.com/safety-research/SCONE-bench) (operational core)
- [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) (operational core)

### Mech Interp Tools (10)

Core libraries and interfaces for activations, circuits, sparse features, interventions, and visualization.

- [decoderesearch/circuit-tracer](https://github.com/decoderesearch/circuit-tracer) (operational core)
- [decoderesearch/SAELens](https://github.com/decoderesearch/SAELens) (operational core)
- [hijohnnylin/neuronpedia](https://github.com/hijohnnylin/neuronpedia) (operational core)
- [ndif-team/nnsight](https://github.com/ndif-team/nnsight) (operational core)
- [neelnanda-io/Neuroscope](https://github.com/neelnanda-io/Neuroscope) (operational core)
- [PKU-Alignment/SAELens-V](https://github.com/PKU-Alignment/SAELens-V) (operational core)
- [PKU-Alignment/TransformerLens-V](https://github.com/PKU-Alignment/TransformerLens-V) (operational core)
- [poloclub/transformer-explainer](https://github.com/poloclub/transformer-explainer) (operational core)
- [safety-research/sparse-feature-toolkit](https://github.com/safety-research/sparse-feature-toolkit) (operational core)
- [TransformerLensOrg/TransformerLens](https://github.com/TransformerLensOrg/TransformerLens) (operational core)

### Interp Experiments & Papers (10)

Research code for probes, steering, model diffing, introspection, learning dynamics, and causal interpretability.

- [anthropics/jacobian-lens](https://github.com/anthropics/jacobian-lens) (operational core)
- [EleutherAI/pythia](https://github.com/EleutherAI/pythia) (operational core)
- [PKU-Alignment/llms-resist-alignment](https://github.com/PKU-Alignment/llms-resist-alignment) (operational core)
- [PKU-Alignment/SAE-V](https://github.com/PKU-Alignment/SAE-V) (operational core)
- [safety-research/introspection-mechanisms](https://github.com/safety-research/introspection-mechanisms) (operational core)
- [safety-research/misalignment-indicators](https://github.com/safety-research/misalignment-indicators) (operational core)
- [safety-research/open-source-em-features](https://github.com/safety-research/open-source-em-features) (operational core)
- [safety-research/selective-gradient-masking](https://github.com/safety-research/selective-gradient-masking) (operational core)
- [safety-research/weight-steering](https://github.com/safety-research/weight-steering) (operational core)
- [timaeus-research/devinterp](https://github.com/timaeus-research/devinterp) (operational core)

### Safety Math & Formal Methods (9)

Math for AI safety, formal verification, theorem proving, decision theory, game theory, and proof tooling.

- [fiezt/ICML-2020-Implicit-Stackelberg-Learning](https://github.com/fiezt/ICML-2020-Implicit-Stackelberg-Learning) (operational core)
- [fiezt/Stackelberg-Code](https://github.com/fiezt/Stackelberg-Code) (operational core)
- [FStarLang/FStar](https://github.com/FStarLang/FStar) (operational core)
- [google-deepmind/deep-verify](https://github.com/google-deepmind/deep-verify) (operational core)
- [lionellevine/MAIS](https://github.com/lionellevine/MAIS) (operational core)
- [ml4tp/gamepad](https://github.com/ml4tp/gamepad) (operational core)
- [OpenLogicProject/OpenLogic](https://github.com/OpenLogicProject/OpenLogic) (operational core)
- [prove-rs/z3.rs](https://github.com/prove-rs/z3.rs) (operational core)
- [scipopt/PySCIPOpt](https://github.com/scipopt/PySCIPOpt) (operational core)

### Research Infrastructure (9)

Inference APIs, experiment scaffolds, cloud runners, provenance, labeling, tracking, and analysis tools.

- [facebookresearch/hydra](https://github.com/facebookresearch/hydra) (operational core)
- [METR/hawk](https://github.com/METR/hawk) (operational core)
- [mlflow/mlflow](https://github.com/mlflow/mlflow) (operational core)
- [paperswithcode/releasing-research-code](https://github.com/paperswithcode/releasing-research-code) (operational core)
- [PKU-Alignment/omnisafe](https://github.com/PKU-Alignment/omnisafe) (operational core)
- [safety-research/safety-tooling](https://github.com/safety-research/safety-tooling) (operational core)
- [treeverse/dvc](https://github.com/treeverse/dvc) (operational core)
- [UKGovernmentBEIS/inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai) (operational core)
- [wandb/wandb](https://github.com/wandb/wandb) (operational core)

### Agents & Research Automation (5)

Research agents, bounded autonomous science, agent harnesses, MCP, and machine-learning engineering agents.

- [mmaaz-git/agentic-pbt](https://github.com/mmaaz-git/agentic-pbt) (operational core)
- [modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol) (operational core)
- [PrimeIntellect-ai/prime-agent](https://github.com/PrimeIntellect-ai/prime-agent) (operational core)
- [SakanaAI/AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) (operational core)
- [WecoAI/aideml](https://github.com/WecoAI/aideml) (operational core)

### Training & Model Systems (17)

Pretraining, post-training, RLHF, distributed training, inference, quantization, tokenization, and model systems.

- [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention) (operational core)
- [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed) (operational core)
- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) (operational core)
- [hiyouga/LlamaFactory](https://github.com/hiyouga/LlamaFactory) (operational core)
- [huggingface/peft](https://github.com/huggingface/peft) (operational core)
- [huggingface/tokenizers](https://github.com/huggingface/tokenizers) (operational core)
- [huggingface/trl](https://github.com/huggingface/trl) (operational core)
- [NVIDIA/Megatron-LM](https://github.com/NVIDIA/Megatron-LM) (operational core)
- [OpenRLHF/OpenRLHF](https://github.com/OpenRLHF/OpenRLHF) (operational core)
- [PKU-Alignment/align-anything](https://github.com/PKU-Alignment/align-anything) (operational core)
- [PKU-Alignment/aligner](https://github.com/PKU-Alignment/aligner) (operational core)
- [PKU-Alignment/safe-rlhf](https://github.com/PKU-Alignment/safe-rlhf) (operational core)
- [PKU-Alignment/SafeDreamer](https://github.com/PKU-Alignment/SafeDreamer) (operational core)
- [PKU-Alignment/SafeVLA](https://github.com/PKU-Alignment/SafeVLA) (operational core)
- [pytorch/torchtitan](https://github.com/pytorch/torchtitan) (operational core)
- [sgl-project/sglang](https://github.com/sgl-project/sglang) (operational core)
- [vllm-project/vllm](https://github.com/vllm-project/vllm) (operational core)

### Digital Minds & Welfare (4)

Machine consciousness, introspection, valence, welfare, personas, and internal-state research.

- [safety-research/assistant-axis](https://github.com/safety-research/assistant-axis) (operational core)
- [safety-research/introspection-adapters](https://github.com/safety-research/introspection-adapters) (operational core)
- [safety-research/introspection-mechanisms](https://github.com/safety-research/introspection-mechanisms) (operational core)
- [safety-research/persona_vectors](https://github.com/safety-research/persona_vectors) (operational core)

### Datasets & Benchmarks (14)

Safety, capability, agent, interpretability, and ML datasets and benchmark suites.

- [EleutherAI/pythia](https://github.com/EleutherAI/pythia) (operational core)
- [PKU-Alignment/beavertails](https://github.com/PKU-Alignment/beavertails) (operational core)
- [PKU-Alignment/eval-anything](https://github.com/PKU-Alignment/eval-anything) (operational core)
- [PKU-Alignment/MM-DeceptionBench](https://github.com/PKU-Alignment/MM-DeceptionBench) (operational core)
- [PKU-Alignment/ProgressGym](https://github.com/PKU-Alignment/ProgressGym) (cross-listed experimental)
- [PKU-Alignment/safe-sora](https://github.com/PKU-Alignment/safe-sora) (operational core)
- [PKU-Alignment/safety-gymnasium](https://github.com/PKU-Alignment/safety-gymnasium) (operational core)
- [PKU-Alignment/SPIKE-Bench](https://github.com/PKU-Alignment/SPIKE-Bench) (operational core)
- [PKU-Alignment/VLA-Arena](https://github.com/PKU-Alignment/VLA-Arena) (operational core)
- [safety-research/agent-escape-bench](https://github.com/safety-research/agent-escape-bench) (operational core)
- [safety-research/impossiblebench](https://github.com/safety-research/impossiblebench) (operational core)
- [safety-research/SCONE-bench](https://github.com/safety-research/SCONE-bench) (operational core)
- [safety-research/sleight-bench](https://github.com/safety-research/sleight-bench) (operational core)
- [sunblaze-ucb/exploitgym](https://github.com/sunblaze-ucb/exploitgym) (operational core)

### Research Prototypes & References (15)

Undocumented, early-stage, or legacy research artifacts kept for discovery, not presented as production-ready tools.

- [edkins/ai_risk_viewer](https://github.com/edkins/ai_risk_viewer) (experimental or reference)
- [edkins/blind-audit](https://github.com/edkins/blind-audit) (experimental or reference)
- [edkins/interp-ausp](https://github.com/edkins/interp-ausp) (experimental or reference)
- [edkins/interp-bitoken](https://github.com/edkins/interp-bitoken) (experimental or reference)
- [edkins/interp-docreduce](https://github.com/edkins/interp-docreduce) (experimental or reference)
- [edkins/math-db](https://github.com/edkins/math-db) (experimental or reference)
- [edkins/proof-comparison](https://github.com/edkins/proof-comparison) (experimental or reference)
- [edkins/rust-pa](https://github.com/edkins/rust-pa) (experimental or reference)
- [edkins/solver-lang](https://github.com/edkins/solver-lang) (experimental or reference)
- [Mzane0803/the_consciousness_ai](https://github.com/Mzane0803/the_consciousness_ai) (experimental or reference)
- [PKU-Alignment/ProAgent](https://github.com/PKU-Alignment/ProAgent) (experimental or reference)
- [PKU-Alignment/ProgressGym](https://github.com/PKU-Alignment/ProgressGym) (cross-listed experimental)
- [PKU-Alignment/ReDMan](https://github.com/PKU-Alignment/ReDMan) (cross-listed experimental)
- [safety-research/crosscoder_emergent_misalignment](https://github.com/safety-research/crosscoder_emergent_misalignment) (experimental or reference)
- [safety-research/unsupervised-truth-probes](https://github.com/safety-research/unsupervised-truth-probes) (experimental or reference)

### Learn Safety & Interpretability (7)

Courses, guides, exercises, reading lists, and visual explainers for technical safety and interpretability.

- [AI-in-Transportation-Lab/awesome-mechanistic-interpretability](https://github.com/AI-in-Transportation-Lab/awesome-mechanistic-interpretability) (operational core)
- [callummcdougall/ARENA_3.0](https://github.com/callummcdougall/ARENA_3.0) (operational core)
- [lionellevine/MAIS](https://github.com/lionellevine/MAIS) (operational core)
- [OpenLogicProject/OpenLogic](https://github.com/OpenLogicProject/OpenLogic) (operational core)
- [PKU-Alignment/AlignmentSurvey](https://github.com/PKU-Alignment/AlignmentSurvey) (operational core)
- [poloclub/transformer-explainer](https://github.com/poloclub/transformer-explainer) (operational core)
- [TransformerLensOrg/TransformerLens](https://github.com/TransformerLensOrg/TransformerLens) (operational core)

### Learn ML, RL & Systems (8)

High-quality courses, books, labs, and from-scratch implementations for ML, RL, and systems foundations.

- [fastai/fastai](https://github.com/fastai/fastai) (operational core)
- [karpathy/llm.c](https://github.com/karpathy/llm.c) (operational core)
- [karpathy/nanochat](https://github.com/karpathy/nanochat) (operational core)
- [MITDeepLearning/introtodeeplearning](https://github.com/MITDeepLearning/introtodeeplearning) (operational core)
- [mryab/efficient-dl-systems](https://github.com/mryab/efficient-dl-systems) (operational core)
- [nivu/ai_all_resources](https://github.com/nivu/ai_all_resources) (operational core)
- [openai/spinningup](https://github.com/openai/spinningup) (operational core)
- [skyzh/tiny-llm](https://github.com/skyzh/tiny-llm) (operational core)

### Research Maps & Awesome Lists (7)

Curated maps, bibliographies, roadmaps, and repository collections for discovery and study.

- [AI-in-Transportation-Lab/awesome-mechanistic-interpretability](https://github.com/AI-in-Transportation-Lab/awesome-mechanistic-interpretability) (operational core)
- [awesomedata/awesome-public-datasets](https://github.com/awesomedata/awesome-public-datasets) (operational core)
- [Hack-with-Github/Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) (operational core)
- [nivu/ai_all_resources](https://github.com/nivu/ai_all_resources) (operational core)
- [PKU-Alignment/AlignmentSurvey](https://github.com/PKU-Alignment/AlignmentSurvey) (operational core)
- [Saibo-creator/Awesome-LLM-Constrained-Decoding](https://github.com/Saibo-creator/Awesome-LLM-Constrained-Decoding) (operational core)
- [Xnhyacinth/Awesome-LLM-Long-Context-Modeling](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling) (operational core)

## Method and provenance

The catalogue combines Muhammad's repositories and Stars with the public collections of Saibo, Edkins, Hammond, safety-research, nivu and PKU-Alignment. See [PROVENANCE.json](PROVENANCE.json) for coverage, unresolved gaps and exclusions.

## Reuse

Original catalogue metadata and curation notes are dedicated under CC0 1.0. Linked repositories retain their own licences, terms and attribution requirements.
