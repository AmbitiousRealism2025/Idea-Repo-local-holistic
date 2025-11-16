# Minimax-M2 Local Research Setup Guide

## Project: Vibe Coder Tool Gap Research - Holistic Validation Approach

This guide explains how to set up and execute this research project in your custom Minimax-M2 Claude Code environment.

## What This Project Does

This project uses an orchestrator agent to launch **5 holistic research agents** with unique analytical lenses that will:
1. Research tool gaps across ALL domains from different perspectives
2. Apply mandatory 3-source validation to every idea
3. Generate 5 validated, execution-ready app ideas per lens (25 total)
4. Create buildability matrix and execution roadmap

## Prerequisites

- Custom Claude Code environment configured for Minimax-M2
- All Minimax-M2 specific settings and configurations loaded
- Web search capabilities enabled (critical for validation)
- Task/sub-agent capabilities available

## Setup Steps

### 1. Load Project into Custom Environment

1. Open your custom Minimax-M2 Claude Code environment
2. Navigate to this project directory: `/Users/ambrealismwork/Desktop/Coding-Projects/Idea-Repo-local-holistic`
3. Ensure the environment reads the `CLAUDE.md` file (this happens automatically in Claude Code)

### 2. Verify Environment

Before starting, confirm:
- [ ] Minimax-M2 model is active
- [ ] Web search is working (CRITICAL for validation requirements)
- [ ] Task tool is available for sub-agent launching
- [ ] All MCP servers (if any) are accessible

### 3. Execute Research

Simply instruct the agent:

```
Execute the research plan in vibe-coder-holistic-research-orchestrator.md
```

The agent will:
1. Read the holistic orchestrator prompt
2. Launch 5 holistic research agents in parallel (each with unique lens)
3. Enforce mandatory 3-source validation for every idea
4. Assess buildability for solo founder execution
5. Synthesize findings into buildability matrix and roadmap

## Expected Output

The agent will create **6 markdown files** in this directory:

1. `agent-1-pain-point-lens.md` - User pain point perspective (5 validated ideas)
2. `agent-2-competitive-gap-lens.md` - Competitive analysis perspective (5 validated ideas)
3. `agent-3-emerging-tech-lens.md` - Emerging technology perspective (5 validated ideas)
4. `agent-4-workflow-integration-lens.md` - Workflow integration perspective (5 validated ideas)
5. `agent-5-indie-hacker-lens.md` - Indie hacker perspective (5 validated ideas)
6. `orchestrator-synthesis.md` - Comprehensive analysis with:
   - Buildability Matrix (Effort vs Impact)
   - Market Timing Analysis
   - Sequencing Strategy
   - Top 10 Execution-Ready Ideas

## Critical Validation Requirements

**Every idea MUST include**:
- **3+ independent sources** confirming the need/gap
- **Competitive landscape analysis** of existing tools
- **Buildability assessment** with complexity/timeline/risks
- **Solo founder viability** confirmation

This is more rigorous than the specialized approach - quality over quantity.

## Parallel Execution Context

This is **one of four parallel research projects**:

- **Idea-Repo-cloud** (Specialized, Claude Sonnet) - Cloud execution
- **Idea-Repo-cloud-holistic** (Holistic, Claude Sonnet) - Cloud execution
- **Idea-Repo-local** (Specialized, Minimax-M2) - Local execution
- **Idea-Repo-local-holistic** (Holistic, Minimax-M2) - **← This project**

Total expected output: ~150 app ideas across all four projects

## After Execution

### Review Results
1. Check that all 6 output files were created
2. Verify every idea has 3+ source citations
3. Confirm buildability assessments are complete
4. Review the buildability matrix and execution roadmap
5. Compare against cloud variant results (when available)

### Document Observations
If you notice any Minimax-M2 specific behaviors, limitations, or advantages:
- Note them in the `orchestrator-synthesis.md` output
- Consider how validation rigor affects research process
- Document any challenges with multi-source validation

### Git Operations
After research completes:
```bash
git add .
git commit -m "Complete holistic validation research with Minimax-M2"
git push origin master
```

## Troubleshooting

**Issue**: Agent doesn't launch sub-agents
- **Solution**: Verify Task tool is available, try explicit instructions

**Issue**: Web search not working
- **Solution**: CRITICAL - validation requires search. Check Minimax-M2 environment configuration

**Issue**: Validation sources insufficient
- **Solution**: Remind agent of mandatory 3-source requirement, extend research time

**Issue**: Output format doesn't match specification
- **Solution**: Remind agent to follow exact format with all validation sections

**Issue**: Buildability matrix missing
- **Solution**: Ensure orchestrator completes synthesis phase with matrix generation

## Key Differences from Specialized Approach

| Aspect | Specialized | Holistic (This Project) |
|--------|-------------|------------------------|
| Agent Focus | One domain each | All domains, different lenses |
| Ideas per Agent | 10 | 5 |
| Validation | Optional | Mandatory 3+ sources |
| Buildability | Optional | Mandatory assessment |
| Output | 50 ideas | 25 validated ideas |
| Emphasis | Creative exploration | Execution-ready opportunities |

## Next Steps

After completing this holistic research:
1. Compare with `Idea-Repo-local` specialized results
2. Compare Minimax-M2 results against Claude Sonnet cloud results
3. Analyze how validation requirements affected idea quality
4. Synthesize insights across all four research variants
5. Use buildability matrix to prioritize development

## Questions?

Refer to:
- `CLAUDE.md` - Full project context and instructions
- `vibe-coder-holistic-research-orchestrator.md` - Detailed research specifications
- Parent README (if available) - Overall project documentation

---

**Ready to begin? Load this project in your Minimax-M2 environment and instruct the agent to execute the validated research plan!**
