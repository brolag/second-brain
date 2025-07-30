---
description: Structured multi-source research methodology
allowed-tools: Read, Write, Edit, WebFetch, WebSearch, Grep
---

# Deep Research

Conduct comprehensive multi-source research with systematic analysis and knowledge integration.

## Usage
`/deep-research <topic>` - Execute deep research on the specified topic requiring thorough investigation across multiple sources and perspectives.

**Arguments:**
- `<topic>` - The research topic or question to investigate comprehensively

## Advanced Research Protocol

### Phase 1: Research Planning & Scoping
```xml
<research_scope>
- Define primary research question
- Identify 3-5 key subtopics
- Determine credible source types needed
- Set depth and breadth parameters
</research_scope>
```

### Phase 2: Multi-Source Investigation
Execute **minimum 5 web searches** with progressive refinement:
1. **Broad overview search**: "{topic} comprehensive guide 2025"
2. **Academic/expert search**: "{topic} research papers expert analysis"
3. **Current trends search**: "{topic} latest developments news 2025"
4. **Practical applications**: "{topic} implementation case studies"
5. **Critical perspectives**: "{topic} challenges limitations criticism"

### Phase 3: Chain-of-Thought Analysis
For each source, document:
```xml
<analysis>
<credibility>Source authority and recency</credibility>
<key_insights>3-5 main findings</key_insights>
<contradictions>Conflicting information noted</contradictions>
<gaps>Information still needed</gaps>
</analysis>
```

### Phase 4: Knowledge Synthesis
Cross-reference findings with existing vault knowledge:
- Search `03_resources/` for related content
- Check `01_projects/` for relevant context
- Identify connections to current work

### Phase 5: Structured Documentation

#### Create Research MOC Structure:
```
📂 03_resources/MOCs/
└── MOC_{topic}_Research_{date}.md
    ├── ## Executive Summary
    ├── ## Key Findings & Insights
    ├── ## Source Analysis & Credibility
    ├── ## Contradictions & Gaps
    ├── ## Connections to Existing Projects
    ├── ## Action Items & Next Steps
    └── ## Source Bibliography
```

#### Individual Research Notes:
- Create detailed notes for each major subtopic
- Use consistent tagging: `#research #{topic} #{date}`
- Include proper citations and source links
- Apply PARA methodology classification

### Phase 6: Integration & Actions
- Link to relevant `01_projects/` if applicable
- Update `📝 TODO.md` with research-driven actions
- Create follow-up research questions if needed
- Schedule review date for information updates

## Quality Standards
- **Minimum 5 web searches** for thoroughness
- **3+ credible sources** per major finding
- **Cross-validation** of key claims
- **Explicit uncertainty** acknowledgment
- **Actionable insights** extraction

## Output Deliverables
1. **Research MOC**: Comprehensive overview with structured analysis
2. **Subtopic Notes**: Detailed individual notes with specific insights
3. **Connection Map**: Links to existing vault content and projects
4. **Action Plan**: Specific next steps based on findings
5. **Source Repository**: Organized bibliography with credibility assessment

## Triggers for Deep Research Mode
Use this command when you encounter:
- "Deep dive into..."
- "Comprehensive analysis of..."
- "Research and evaluate..."
- "Investigate thoroughly..."
- Complex multi-faceted questions requiring systematic investigation