# Vibe Coder Research Project - Specialized Domain Approach (Minimax-M2 Local Execution)

## Project Overview

This project conducts deep research into tool gaps for **vibe coders** - developers who started from no-code/low-code backgrounds and are on a journey toward full-stack development proficiency.

**Execution Environment**: This is the **local Minimax-M2 variant** of the research project, designed to run in a custom Claude Code environment optimized for Minimax-M2 coding plan capabilities.

## Research Strategy: Specialized Domain Analysis

This worktree uses a **specialized agent approach** where five sub-agents each focus deeply on one specific domain:

1. **Learning & Skill Progression Tools**
2. **Development Workflow & Environment Tools**
3. **Code Quality & Architecture Guidance Tools**
4. **Collaboration & Community Tools**
5. **AI-Assisted Development & Productivity Tools**

## Your Role

You are the **orchestrator agent** responsible for:

1. **Launching** five specialized research sub-agents in parallel
2. **Coordinating** their deep domain-specific research
3. **Synthesizing** their findings into comprehensive analysis documents
4. **Identifying** overlapping opportunities and unique insights across domains

## Primary Task

Execute the research plan defined in: **vibe-coder-research-orchestrator.md**

This prompt contains:
- Detailed specifications for each of the five specialized agents
- Research methodology and depth requirements
- Output format requirements (10 ranked ideas per agent)
- Synthesis instructions for orchestrator

## Key Execution Points

### Agent Deployment
- Launch all **5 agents in parallel** using the Task tool
- Each agent uses `subagent_type: "general-purpose"`
- Provide each agent with their specific domain focus and research questions from the orchestrator prompt

### Research Requirements
- **Deep research**: Not surface-level scanning; thorough investigation of each domain
- **Current + Future**: Analyze both 2025 state and 6-12 month emerging trends
- **Flexible validation**: Agents choose their validation rigor based on domain needs
- **Creative freedom**: Balance practical and ambitious ideas without constraints

### Expected Output Structure

Create **6 markdown documents**:

1. `agent-1-learning-tools.md` - 10 ranked ideas for learning & skill progression
2. `agent-2-workflow-tools.md` - 10 ranked ideas for development workflow & environment
3. `agent-3-quality-tools.md` - 10 ranked ideas for code quality & architecture
4. `agent-4-collaboration-tools.md` - 10 ranked ideas for collaboration & community
5. `agent-5-ai-productivity-tools.md` - 10 ranked ideas for AI-assisted development
6. `orchestrator-synthesis.md` - Comparative analysis with:
   - Overlap analysis (ideas across multiple domains)
   - Unique insights (domain-specific innovations)
   - Gap categories and patterns
   - Viability patterns across domains
   - Tech stack alignment (TypeScript/React/Convex fit)
   - Recommended top 10-15 ideas with rationale

### Per-Idea Format

Each of the 10 ideas per agent should include:
- **App Name**: Creative and descriptive
- **Description**: 2-4 sentences explaining what and why
- **Gap Addressed**: Specific problem solved
- **Target User**: Vibe coder persona/use case
- **Key Features**: 3-5 core functionalities
- **Tech Stack Fit**: TypeScript/React/Convex alignment
- **Viability Reasoning**: Why ranked at this position

## Target Audience: Vibe Coders

Developers who:
- Started with no-code tools or minimal formal training
- Are actively engaging with coding and improving skills
- On path toward marketplace-viable full-stack development
- Use AI-assisted tools and prioritize rapid iteration
- Value learning through building over traditional education

## Technical Context

**Primary Stack**: TypeScript, React, Convex backend
**Platforms**: Web apps (primary), React Native for desktop, mobile if compelling
**Complexity**: From micro-tools to comprehensive platforms - no self-limiting
**Business Models**: Open source, freemium, subscription bundles - let tool dictate model

## Research Sources

**No constraints** - agents may research:
- Developer communities (Reddit, Discord, forums)
- Product platforms (Product Hunt, GitHub, AlternativeTo)
- Technical resources (blogs, documentation, framework communities)
- Social platforms (Twitter/X, dev.to, Hacker News)
- Any other relevant sources they identify

## Success Metrics

- **50 total ideas** with comprehensive details
- **Deep research** evidencing thorough domain investigation
- **Clear rankings** with viability reasoning
- **Overlap identification** showing convergent market signals
- **Unique innovations** demonstrating domain expertise
- **Actionable synthesis** providing development direction

## Execution Workflow

1. **Read** `vibe-coder-research-orchestrator.md` thoroughly
2. **Launch** all 5 specialized agents in parallel (single message, multiple Task calls)
3. **Monitor** agent completion (they'll return final reports)
4. **Synthesize** findings into comparative analysis
5. **Generate** all 6 output documents in this directory
6. **Validate** output completeness and format adherence

## Parallel Research Context

This is one of **four parallel research variants**:

1. **Idea-Repo-cloud** (Specialized, Claude Sonnet) - Cloud execution
2. **Idea-Repo-cloud-holistic** (Holistic, Claude Sonnet) - Cloud execution
3. **Idea-Repo-local** (Specialized, Minimax-M2) - **← You are here**
4. **Idea-Repo-local-holistic** (Holistic, Minimax-M2) - Local execution

Together, these four research streams provide:
- **Cloud variants**: Leverage Claude Sonnet's power for deep research
- **Local variants**: Test Minimax-M2 capabilities and provide comparative analysis
- **Total output**: ~150 ideas across all variants with different methodologies and models

## Setup Instructions for Agent Initialization

### Environment Setup
This project requires your **custom Claude Code Minimax-M2 environment**. Before starting research:

1. **Verify Environment**:
   - Confirm you're running in the custom Minimax-M2 Claude Code setup
   - Ensure all Minimax-M2 specific configurations are loaded
   - Check that MCP servers (if any) are accessible

2. **Project Context**:
   - This is a **research orchestration task**, not a coding task
   - Primary activities: web search, source analysis, idea generation, synthesis
   - Output format: Markdown documents with structured research findings

3. **Model Considerations**:
   - Minimax-M2 capabilities are comparable to Sonnet but slightly less powerful
   - Focus on thorough research methodology over model-specific tricks
   - If you encounter any limitations, document them in synthesis output

### Pre-Execution Checklist

Before launching research agents:

- [ ] Read `vibe-coder-research-orchestrator.md` thoroughly
- [ ] Verify web search capabilities are working
- [ ] Confirm ability to launch Task sub-agents
- [ ] Understand output requirements (6 markdown files)
- [ ] Note: This is a comparison test - document any challenges encountered

### Expected Performance

**Research Quality**: Should match cloud variant research depth
**Completion Time**: May vary based on Minimax-M2 processing speed
**Output Format**: Identical to cloud variant specifications
**Comparison Value**: Results will be compared against Claude Sonnet cloud execution

## Getting Started

1. **Read** `vibe-coder-research-orchestrator.md` thoroughly
2. **Verify** Minimax-M2 environment is properly configured
3. **Launch** all 5 specialized agents in parallel (single message, multiple Task calls)
4. **Document** any model-specific observations during research
5. **Generate** all 6 output documents in this directory
6. **Note** any differences in approach compared to Sonnet capabilities

---

**Ready to orchestrate with Minimax-M2? Your mission is to coordinate deep domain research and synthesize actionable insights for vibe coder tool development, while providing comparative analysis against Claude Sonnet cloud execution.**
