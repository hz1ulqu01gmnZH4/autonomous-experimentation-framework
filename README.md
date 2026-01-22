# Autonomous Experimentation Framework

Multi-agent system for autonomous scientific experimentation using **Plan-Act-Reflect-Revise** methodology from MCP-SIM (KAIST, Nature 2025).

## Agents

| Agent | Role |
|-------|------|
| `experiment-orchestrator` | Central coordinator with shared memory |
| `hypothesis-generator` | Generate and evolve testable hypotheses |
| `experiment-designer` | Design rigorous experiments |
| `experiment-executor` | Safe execution with checkpointing |
| `result-analyzer` | Statistical analysis |
| `error-diagnostician` | Diagnose and fix failures |
| `literature-researcher` | Search and synthesize prior work |
| `reflection-refiner` | Learn and improve methodology |

## Usage

```bash
# Full experiment
/experiment "Your research objective"

# Individual agents
Task("hypothesis-generator", "Generate hypotheses for: {topic}", "hypothesis-generator")
Task("experiment-designer", "Design experiment for: {hypothesis}", "experiment-designer")
```

## Sources

- [MCP-SIM](https://www.nature.com/articles/s44387-025-00057-z) (KAIST, Nature 2025)
- [Curie](https://arxiv.org/abs/2502.16069)
- [Kosmos](https://arxiv.org/abs/2511.02824)
- [Google AI Co-Scientist](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/)
