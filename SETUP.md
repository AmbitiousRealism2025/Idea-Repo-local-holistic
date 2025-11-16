# Minimax-M2 Local Research Setup Guide

## Project: Vibe Coder Tool Gap Research - Specialized Domain Approach

This guide explains how to set up and execute this research project in your custom Minimax-M2 Claude Code environment.

## What This Project Does

This project uses an orchestrator agent to launch **5 specialized research agents** that will:
1. Research tool gaps for vibe coders across 5 different domains
2. Generate 10 ranked app ideas per domain (50 total)
3. Synthesize findings into comprehensive analysis documents

## Prerequisites

- Custom Claude Code environment configured for Minimax-M2
- All Minimax-M2 specific settings and configurations loaded
- Web search capabilities enabled
- Task/sub-agent capabilities available

## Setup Steps

### 1. Load Project into Custom Environment

1. Open your custom Minimax-M2 Claude Code environment
2. Navigate to this project directory: `/Users/ambrealismwork/Desktop/Coding-Projects/Idea-Repo-local`
3. Ensure the environment reads the `CLAUDE.md` file (this happens automatically in Claude Code)

### 2. Verify Environment

Before starting, confirm:
- [ ] Minimax-M2 model is active
- [ ] Web search is working
- [ ] Task tool is available for sub-agent launching
- [ ] All MCP servers (if any) are accessible

### 3. Execute Research

Simply instruct the agent:

```
Execute the research plan in vibe-coder-research-orchestrator.md
```

The agent will:
1. Read the orchestrator prompt
2. Launch 5 specialized research agents in parallel
3. Coordinate their research activities
4. Synthesize all findings into 6 markdown documents

## Expected Output

The agent will create **6 markdown files** in this directory:

1. `agent-1-learning-tools.md` - Learning & skill progression tools (10 ideas)
2. `agent-2-workflow-tools.md` - Development workflow & environment tools (10 ideas)
3. `agent-3-quality-tools.md` - Code quality & architecture guidance tools (10 ideas)
4. `agent-4-collaboration-tools.md` - Collaboration & community tools (10 ideas)
5. `agent-5-ai-productivity-tools.md` - AI-assisted development tools (10 ideas)
6. `orchestrator-synthesis.md` - Comparative analysis & top recommendations

## Parallel Execution Context

This is **one of four parallel research projects**:

- **Idea-Repo-cloud** (Specialized, Claude Sonnet) - Cloud execution
- **Idea-Repo-cloud-holistic** (Holistic, Claude Sonnet) - Cloud execution
- **Idea-Repo-local** (Specialized, Minimax-M2) - **← This project**
- **Idea-Repo-local-holistic** (Holistic, Minimax-M2) - Local execution

Total expected output: ~150 app ideas across all four projects

## After Execution

### Review Results
1. Check that all 6 output files were created
2. Review the quality and depth of research
3. Compare against cloud variant results (when available)

### Document Observations
If you notice any Minimax-M2 specific behaviors, limitations, or advantages:
- Note them in the `orchestrator-synthesis.md` output
- Consider documenting for future reference

### Git Operations
After research completes:
```bash
git add .
git commit -m "Complete specialized research with Minimax-M2"
git push origin master
```

## Troubleshooting

**Issue**: Agent doesn't launch sub-agents
- **Solution**: Verify Task tool is available, try explicit instructions

**Issue**: Web search not working
- **Solution**: Check Minimax-M2 environment configuration, ensure search capabilities enabled

**Issue**: Output format doesn't match specification
- **Solution**: Remind agent to follow the exact format in orchestrator prompt

## Next Steps

After completing this specialized research:
1. Switch to `Idea-Repo-local-holistic` for the holistic validation approach
2. Compare results between specialized and holistic methodologies
3. Compare Minimax-M2 results against Claude Sonnet cloud results
4. Synthesize insights across all four research variants

## Questions?

Refer to:
- `CLAUDE.md` - Full project context and instructions
- `vibe-coder-research-orchestrator.md` - Detailed research specifications
- Parent README (if available) - Overall project documentation

---

**Ready to begin? Load this project in your Minimax-M2 environment and instruct the agent to execute the research plan!**
