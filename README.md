# OpenClaw Essentials

Professional OpenClaw agent skills for building agents and mastering the CLI.

## Skills Included

### 🤖 openclaw-agent-builder

Build specialized openclaw agents with proper workspace structure, identity files, and skills.

**Features:**
- Complete agent workspace setup
- Identity and personality configuration
- Memory system integration
- Multi-agent routing
- Skill organization patterns

### 📦 openclaw-cli

Master the OpenClaw CLI - gateway, agents, channels, skills, hooks, and automation.

**Coverage:**
- Setup & onboarding
- Gateway management
- Agent configuration
- Skills & hooks
- Channel management
- Models & authentication
- Browser control
- Nodes & devices
- System commands & cron

### 🧠 memory-curator

Systematic memory management through daily logs, session preservation, and knowledge extraction.

**Features:**
- Daily logging with timestamps and categories
- Session summary extraction from JSONL
- Full-text search across all memory files
- Knowledge extraction patterns (3+ occurrences, high-cost learnings)
- Memory organization best practices
- Python scripts for automation

**Scripts:**
- `daily_log.py` - Create/append to daily logs
- `extract_session.py` - Extract session summaries
- `search_memory.py` - Search across all memory

**References:**
- Logging patterns for different scenarios
- Knowledge extraction workflows
- MEMORY.md organization strategies

## Installation

Install individual skills via the skills CLI:

```bash
# OpenClaw Agent Builder
npx skills add https://github.com/irangareddy/openclaw-essentials --skill openclaw-agent-builder

# OpenClaw CLI Mastery
npx skills add https://github.com/irangareddy/openclaw-essentials --skill openclaw-cli

# Memory Curator
npx skills add https://github.com/irangareddy/openclaw-essentials --skill memory-curator
```

## Usage

Once installed, these skills are automatically available to your OpenClaw agents.

**For agent building:**
- Creating new agents
- Structuring workspaces
- Configuring identities
- Adding capabilities

**For CLI operations:**
- Managing gateway
- Configuring channels
- Running hooks
- Checking status

**For memory management:**
- Daily activity logging
- Session context preservation
- Knowledge extraction and curation
- Searching past decisions and learnings

## Skills Format

Follows the [AgentSkills.io](https://agentskills.io/) specification.

## License

MIT

## Author

Ranga Reddy Nukala
