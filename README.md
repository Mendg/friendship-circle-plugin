# Friendship Circle Plugin for Claude Code

A comprehensive toolkit for Friendship Circle International and Team Friendship — fundraising, communications, event design, and organizational leadership.

## Installation

### Option 1: Local Testing
```bash
claude --plugin-dir /path/to/friendship-circle-plugin
```

### Option 2: From GitHub (after you push it)
```bash
# First, create a marketplace or add to an existing one
/plugin marketplace add your-github-username/friendship-circle-plugin
/plugin install friendship-circle@your-marketplace
```

## What's Included

### Skills (Auto-activate on context)

| Skill | Triggers on... |
|-------|----------------|
| `fundraising-coach` | Donor strategy, campaign planning, retention |
| `communications` | Writing appeals, emails, donor content |
| `event-design` | Planning Team Friendship events |
| `gamification` | P2P campaign engagement ideas |
| `eos-rocks` | Quarterly planning, 90-day priorities |
| `eos-clarity-break` | Strategic thinking sessions |

### Agents (Specialized sub-agents)

| Agent | What it does |
|-------|--------------|
| `donor-pipeline` | Qualifies leads, prioritizes outreach, suggests personalized approaches |
| `recruitment` | Generates custom recruitment messages for Team Friendship events |
| `appeal-writer` | Drafts fundraising communications in authentic FC voice |
| `event-planner` | Designs transformational event experiences |

### Commands (Slash commands)

| Command | Usage |
|---------|-------|
| `/friendship-circle:draft-appeal` | Write a fundraising email or appeal |
| `/friendship-circle:qualify-donors` | Prioritize a donor list for outreach |
| `/friendship-circle:recruit` | Generate Team Friendship recruitment messages |
| `/friendship-circle:plan-event` | Design a transformational event |
| `/friendship-circle:gamify` | Get campaign gamification ideas |
| `/friendship-circle:rocks` | Create or review quarterly Rocks |
| `/friendship-circle:clarity-break` | Facilitate strategic thinking session |

## Usage Examples

### Draft an end-of-year appeal
```
/friendship-circle:draft-appeal end-of-year for mid-level donors ($500-$2000)
```

### Prioritize donor calls
```
/friendship-circle:qualify-donors

[paste your donor list]
```

### Recruit for Kilimanjaro
```
/friendship-circle:recruit February Kilimanjaro men's trip - need 5 more participants
```

### Plan a marathon weekend
```
/friendship-circle:plan-event NYC Marathon weekend - 30 participants
```

### Gamify a campaign
```
/friendship-circle:gamify end-of-year giving campaign, need to hit $100K by Dec 31
```

## Voice & Philosophy

All communications follow these principles:
- **Authentic over polished**: Raw, personal beats corporate
- **Emotion leads → Clarity closes → Urgency converts**
- **Make the donor the hero**
- **Transformation over transaction**
- **One specific story beats statistics**

## Customization

### Adding your own stories
Add a `references/` folder inside any skill with:
- `email_examples.md` — Sample emails that worked
- `stories.md` — Beneficiary stories to reference
- `messaging-frameworks.md` — Your messaging templates

### Adjusting agent behavior
Edit the `AGENT.md` files to change:
- Qualification criteria
- Output format
- Specific language/tone

## Contributing

This plugin is built for Friendship Circle International. To contribute:
1. Fork the repo
2. Make changes
3. Submit a PR with description of what you changed and why

## License

MIT - Use freely, attribution appreciated.
