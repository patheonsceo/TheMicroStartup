# 🤝 Contributing to TheMicroStartup

Thank you for your interest in contributing to **TheMicroStartup**! This document provides guidelines and templates to help you contribute effectively.

> **Note:** The main public community is **EightEngine** — our community platform where you can connect, discuss, and collaborate. Learn more at [COMMUNITY/eightengine.md](COMMUNITY/eightengine.md)

---

## 🎯 Contribution Types

You can contribute in multiple ways:

| Type | Where | Format |
|------|-------|--------|
| 💡 **Ideas** | `IDEAS/` | Use the idea template |
| 🧱 **Projects** | `PROJECTS/` | Create a project directory |
| 📖 **Documentation** | `DOCS/` or root | Improve existing docs |
| 🔧 **Code/Tools** | `PROJECTS/tech-lab/` | Code contributions |
| 🎨 **Designs** | `VISUALS/` | Design assets and concepts |
| 📊 **Business Models** | `BUSINESS/` | Financial and revenue models |
| 🌿 **Research** | `RESEARCH/` | Sustainability and tech research |

---

## 🚀 Contribution Workflow

### Step 1: Fork & Clone

```bash
# Fork the repository on GitHub
# Then clone your fork
git clone https://github.com/YOUR_USERNAME/TheMicroStartup.git
cd TheMicroStartup
```

### Step 2: Create a Branch

```bash
# Create a new branch for your contribution
git checkout -b feature/your-contribution-name

# Or for ideas:
git checkout -b idea/your-idea-name

# Or for projects:
git checkout -b project/your-project-name
```

### Step 3: Choose Your Contribution Type

#### 📝 Submitting an Idea

1. Go to `IDEAS/` folder
2. Copy `_template.md` and rename it: `your-name-idea-title.md`
3. Fill out the template
4. Add relevant tags (`#art`, `#tech`, `#food`, `#business`, `#sustainability`, etc.)
5. Commit and push

**Template Structure:**
```markdown
# Idea Title

**Author:** Your Name  
**Date:** YYYY-MM-DD  
**Tags:** #tag1 #tag2 #tag3

## Overview
[Brief description]

## Problem Statement
[What problem does this solve?]

## Proposed Solution
[Your idea]

## Implementation Plan
[How would this work?]

## Resources Needed
[What's required?]

## Expected Outcomes
[What would success look like?]

## Open Questions
[What needs discussion?]
```

#### 🧱 Starting a Project

1. Go to `PROJECTS/` and choose the appropriate subfolder:
   - `atulyas-space/` - Physical retreat buildout
   - `art-lab/` - Art-focused experiments
   - `tech-lab/` - Hardware/software systems
   - `food-lab/` - Culinary projects
   - `self-sustain-lab/` - Renewable systems
   - `community-lab/` - Events and community
2. Create a new folder: `your-project-name/`
3. Add a `README.md` with project details
4. Follow the project template structure

**Project README Template:**
```markdown
# Project Name

**Lead:** Your Name  
**Status:** 🟢 Active / 🟡 Planning / 🔴 Paused  
**Tags:** #tag1 #tag2

## Description
[What is this project?]

## Goals
[What are you trying to achieve?]

## Timeline
[Expected timeline]

## Resources
[What you need]

## Contribution Guide
[How others can help]

## Progress
[Current status and updates]
```

#### 📖 Improving Documentation

- Fix typos or clarify language
- Add missing information
- Improve structure or formatting
- Add examples or use cases
- Translate to other languages

---

## ✅ Pull Request Guidelines

### PR Title Format

```
[Type] Brief description
```

**Types:**
- `[Idea]` - New idea submission
- `[Project]` - New project or project updates
- `[Docs]` - Documentation improvements
- `[Fix]` - Bug fixes or corrections
- `[Enhancement]` - Feature additions or improvements

**Examples:**
- `[Idea] Community garden automation system`
- `[Project] Tech-lab: Smart composting monitor`
- `[Docs] Update contribution workflow`

### PR Description Template

```markdown
## Type
- [ ] Idea
- [ ] Project
- [ ] Documentation
- [ ] Code/Tool
- [ ] Design
- [ ] Other

## Description
[What does this PR do?]

## Related
[Link to related issues/ideas/projects]

## Tags
[#art #tech #food #business #sustainability]

## Checklist
- [ ] Followed contribution guidelines
- [ ] Used appropriate template
- [ ] Added tags/categories
- [ ] Documentation is clear
- [ ] Ready for review
```

---

## 🏷️ Tagging System

Use tags to categorize contributions:

| Tag | Usage |
|-----|-------|
| `#art` | Art, design, creative projects |
| `#tech` | Technology, hardware, software |
| `#food` | Culinary, fermentation, food systems |
| `#business` | Revenue models, partnerships, strategy |
| `#sustainability` | Eco-friendly, renewable, waste management |
| `#community` | Events, meetups, social initiatives |
| `#infrastructure` | Physical space, tools, equipment |
| `#research` | Studies, papers, experiments |

**Format:** Use `#tag` format in markdown files.

---

## 📋 Code Style Guidelines

### General

- Use clear, descriptive variable/function names
- Add comments for complex logic
- Follow language-specific conventions
- Keep functions small and focused

### Markdown

- Use heading levels consistently
- Add table of contents for long documents
- Use code blocks with language tags
- Include examples where relevant

### File Organization

- Keep related files together
- Use descriptive folder/file names
- Add README.md to project folders
- Document dependencies and setup

---

## 🤝 Review Process

1. **Submit PR** - Create your pull request
2. **Labeling** - Maintainers will add appropriate labels
3. **Discussion** - Community can comment and suggest changes
4. **Review** - At least one maintainer will review
5. **Merge** - Once approved, your PR will be merged
6. **Celebrate** 🎉 - Your contribution is now part of TheMicroStartup!

---

## 💬 Communication

### Questions?

- Open an issue for general questions
- Use discussions for ideas in progress
- Join our community chat (Discord/Telegram) for real-time help

### Disagreements?

- Be respectful and constructive
- Focus on ideas, not individuals
- Use data and examples to support points
- Follow the [code of conduct](COMMUNITY/code-of-conduct.md)

---

## 🎨 Design Contributions

For visual contributions (mockups, designs, renders):

1. Place files in `VISUALS/` with appropriate subfolder
2. Include:
   - Source files (if applicable)
   - Exported versions (PNG/JPG)
   - Brief description in README
   - Attribution/credit information

---

## 🌿 Research Contributions

For research papers, references, or technical documents:

1. Place in `RESEARCH/` with subfolder:
   - `architecture/` - System designs
   - `renewable-systems/` - Sustainability research
   - `tools-and-tech/` - Technology references
2. Include:
   - Source/citation
   - Summary or key takeaways
   - Relevance to TheMicroStartup
   - Links to original sources

---

## 🚫 What Not to Contribute

- Commercial spam or advertisements
- Content that violates code of conduct
- Duplicate ideas without new insights
- Unsubstantiated claims without sources
- Content that doesn't align with project vision

---

## 📚 Resources

- [README.md](README.md) - Project overview
- [COMMUNITY/manifesto.md](COMMUNITY/manifesto.md) - Community values
- [COMMUNITY/code-of-conduct.md](COMMUNITY/code-of-conduct.md) - Behavior guidelines
- [COMMUNITY/roles.md](COMMUNITY/roles.md) - Community roles

---

## 🙏 Thank You!

Every contribution, no matter how small, makes TheMicroStartup stronger. Thank you for being part of this journey!

**Questions?** Open an issue or reach out to the community.

---

**Ready to contribute?** Pick a contribution type and get started! 🚀

