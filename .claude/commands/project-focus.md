---
description: Activate deep focus mode for specific project
allowed-tools: Read, LS, Grep, TodoWrite, TodoRead
argument-hint: [project-name]
---

# /project-focus Command

Activates deep focus mode for a specific project with full context loading and task optimization.

## What it does:
1. Loads complete project context and structure
2. Identifies current project status and blockers
3. Optimizes task sequence for maximum productivity
4. Sets up distraction-free work environment
5. Integrates with energy and time management

## Usage:
```
/project-focus [project-name]
```

Available projects:
- `grupo-purdy` - Web scraping system for automotive market
- `dojo-coding` - Educational platform and bootcamps
- `indie-mind` - Content creation and marketing
- `ai-agents` - Conversational AI development

## Implementation:
- Scans project folder in `01_projects/`
- Loads all relevant documentation and context
- Reviews TODO.md for project-specific tasks
- Creates focus session plan
- Tracks time and progress metrics