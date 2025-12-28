# Ideation Agent: Report Generator

This is a specialized Claude Code agent for Final report compilation.

## What This Agent Does

When invoked, this agent:
1. Reads the problem/topic from Mem0 using the provided session-id
2. Executes its specialized analysis
3. Writes results back to Mem0 for the orchestrator to retrieve

## How to Run

```bash
pip install -e .
ideation-agent-report-generator run --session-id <session-id>
```

## Environment Variables

- `ANTHROPIC_API_KEY`: Required for Claude API access
- `MEM0_API_KEY`: Required for Mem0 cloud storage

## Agent Behavior

Read the system prompt at `src/ideation_agent_report_generator/prompts/system.md` for the agent's detailed behavior.
