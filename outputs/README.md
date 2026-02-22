# Sample Outputs

This folder contains raw agent conversation logs and generated artifacts from notebook runs.

## Folder Structure

```
outputs/
├── phase1-waterfall/           # Outputs from Waterfall methodology (AutoGen)
│   ├── 1.Initiating_the_Phased_Workflow.md
│   └── 2.Final_Report_by_Agents.md
└── phase2-scrum/               # Outputs from Scrum methodology (4 frameworks)
    ├── AutoGen_Scrum_Workflow.md
    ├── LlamaIndex_Scrum_Workflow.md
    ├── LangChain_Scrum_Workflow.md
    └── LangGraph_Scrum_Workflow.md
```

## What You'll Find

- **Agent Conversations**: Raw text logs showing how AI agents communicate and collaborate
- **Generated Artifacts**: Requirements documents, design specifications, code snippets, test cases
- **Workflow Progression**: Step-by-step demonstration of each SDLC phase
- **Framework Comparison**: Side-by-side outputs from AutoGen, LlamaIndex, LangChain, and LangGraph

## Key Metrics by Framework (Phase 2 - Scrum)

| Framework | User Stories | SLOC | Test Cases | Documentation |
|-----------|--------------|------|------------|---------------|
| AutoGen | 10 | 2,100 | 6 | 50 pages |
| LlamaIndex | 10 | 930 | 21 | 36 pages |
| LangChain | 10 | 1,600 | 46 | 6 docs |
| LangGraph | 10 | 1,800 | 15 | 50 pages |

These outputs demonstrate what the multi-agent system produces when you run the notebooks with your own API key.
