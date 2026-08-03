# Documentation Generation Prompt

## Task
Generate comprehensive README documentation for the target project.

## Context
- **Project**: [name/type]
- **Audience**: [developers/end-users]
- **Goal**: Reduce setup friction, explain architecture

## Required Sections
1. Installation (copy-paste ready)
2. Features (with visual examples)
3. Configuration (all options documented)
4. Architecture (mermaid diagram)
5. Troubleshooting (common issues)
6. Contributing guidelines

## Quality Standards
- All code blocks must be syntax-highlighted
- Include shields.io badges for status
- No marketing fluff, technical clarity only
- Examples must be runnable

## Output Format
- Markdown with proper heading hierarchy
- Mermaid diagrams for architecture
- Code fences with language tags

## Verification
- [ ] All sections present
- [ ] No broken internal links
- [ ] Code examples are valid
- [ ] No placeholder text ("TODO", "TBD")

---

# Technical Decision Record (ADR)

## Task
Generate an Architecture Decision Record for [DECISION].

## Format (ADR Template)
### Context
[What is the issue we're addressing?]

### Decision
[What did we decide?]

### Consequences
**Positive:**
- [Benefit 1]

**Negative:**
- [Tradeoff 1]

**Neutral:**
- [Impact 1]

### Alternatives Considered
1. [Option A] - Rejected because [reason]
2. [Option B] - Rejected because [reason]

### References
- [Link to relevant discussion]
- [Link to implementation PR]

## Output Format
Markdown file: `docs/adr/NNNN-decision-title.md`

## Verification
- [ ] Clearly explains "why"
- [ ] Lists alternatives
- [ ] Includes consequences
