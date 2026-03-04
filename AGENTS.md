# AGENTS.md - Guidelines for AI Coding Agents

This document provides guidelines for AI coding agents working on the Awesome JAM repository. This is a curated list repository containing Markdown documentation, not a traditional code project.

## Repository Overview

**Type**: Curated list / Documentation repository
**Primary Language**: Markdown
**Purpose**: A curated collection of JAM (Join-Accumulate Machine) resources, tools, examples, tutorials, and more
**Main Files**:
- `README.md` - Main curated list (primary content)
- `CONTRIBUTING.md` - Contribution guidelines
- `LICENSE` - MIT License
- `AGENTS.md` - This file (AI agent guidelines)

## Repository Structure

```
Awesome-JAM/
├── README.md          # Main curated list (primary content)
├── CONTRIBUTING.md    # Contribution guidelines
├── LICENSE            # MIT License
└── AGENTS.md          # This file
```

## README Sections

The main `README.md` is organized into these sections (in order):

1. **About JAM** - Overview of JAM technology
2. **SDKs** - Development kits for building JAM services
3. **Tools** - Development tools, debuggers, playgrounds, utilities
4. **Examples & Demos** - Real-world examples and demo projects
5. **Documentation** - Official docs, specs, technical references
6. **Tutorials** - Step-by-step guides and learning resources
7. **Videos** - Conference talks, tutorials, educational content
8. **Articles** - Blog posts and write-ups, with subsections:
   - Technical Deep Dives
   - Educational & Explainers
   - Vision & Analysis
   - Use Cases & Applications
   - Events & News
   - Developer Resources
9. **Community & Resources** - Community links and additional resources
10. **Contributing** - How to contribute (inline summary)

## Working with This Repository

### Validation Steps

When making changes, validate manually:

1. **Markdown Formatting**:
   - Check that all Markdown syntax is correct
   - Ensure proper heading hierarchy (no skipped levels)
   - Verify lists are properly formatted

2. **Link Validation**:
   - All URLs should be accessible (no 404s)
   - GitHub links should point to valid repositories
   - Use HTTPS for all external links

3. **Awesome List Compliance**:
   - Follow [awesome-manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)
   - Maintain quality over quantity
   - Include the awesome badge in README

4. **Table of Contents**:
   - Ensure the Contents section in README matches the actual sections
   - Anchor links must match heading text exactly

## Content Guidelines

### Entry Format

The standard entry format used throughout the README is:

```markdown
- [Resource Name](url) by [@username](github-profile) - Brief description
```

**Variations by section:**

- **SDKs / Tools / Examples**: Standard format with GitHub profile attribution
- **Documentation**: Standard format; some entries may omit attribution for official specs
- **Tutorials**: Standard format; some entries may omit `by` attribution
- **Videos**: Title links to YouTube/video URL, no `by` attribution (author in description if needed)
  ```markdown
  - [Video Title](youtube-url) - Brief description
  ```
- **Articles**: Include author name (not necessarily GitHub handle) and optional date
  ```markdown
  - [Article Title](url) by Author Name (Month Year) - Brief description
  ```
- **Community & Resources**: Standard format; some entries may omit attribution
  ```markdown
  - [Resource Name](url) - Brief description
  ```

### Structure and Organization

1. **Table of Contents**:
   - Keep in sync with actual sections
   - Update TOC when adding new sections
   - Use consistent anchor link formatting

2. **Sections**:
   - Group related resources together
   - Maintain consistent section naming
   - Use descriptive section headers

3. **Resource Ordering**:
   - Within sections, order entries **alphabetically by resource name**
   - For articles, order alphabetically within each subsection
   - Group article subsections logically (Technical Deep Dives, Educational, etc.)

### Markdown Style

1. **Headings**:
   - Use ATX-style headings (`#`, `##`, etc.) not Setext-style
   - One H1 (`#`) per file (the title)
   - Maintain proper hierarchy (don't skip levels)
   - Add blank line before and after headings

2. **Links**:
   - Use inline links: `[text](url)`
   - Include link title when helpful: `[text](url "title")`
   - Prefer absolute URLs over relative URLs
   - Use HTTPS protocol for all external links

3. **Lists**:
   - Use `-` for unordered lists (not `*` or `+`)
   - Use consistent indentation (2 spaces for nested lists)
   - Add blank line before and after lists
   - For numbered lists, use `1.`, `2.`, etc.

4. **Emphasis**:
   - Use `**bold**` for emphasis (not `__bold__`)
   - Use `*italic*` for lighter emphasis (not `_italic_`)
   - Use `` `code` `` for inline code/technical terms

5. **Line Length**:
   - No strict line length limit
   - Break lines at natural boundaries (sentences, list items)
   - Keep URLs on same line as their link text

### Content Standards

1. **Descriptions**:
   - Keep brief (1-2 sentences)
   - Be specific about what the resource provides
   - Use active voice
   - Avoid marketing language or superlatives
   - Focus on facts, not opinions

2. **Attributions**:
   - Credit original authors with `by [@username](profile-link)` for code/tools
   - For articles, use `by Author Name` (real name or handle as published)
   - Link to GitHub profiles when available
   - For organizations, link to their GitHub org page

3. **Categorization**:
   - Place resources in the most appropriate section
   - For articles, choose the best-fitting subsection
   - If unsure, suggest new category via issue/PR
   - Avoid duplicate entries across sections

4. **Quality Standards**:
   - Resources should be relevant to JAM development
   - Links must be working and accessible
   - Content should add value to developers/learners
   - Prefer official/authoritative sources when available

## Git Workflow

### Commit Messages

Use clear, descriptive commit messages:

```
Add [Resource Name] to [Section]
Update [Section] with new resources
Fix broken link in [Section]
Reorganize [Section] for better clarity
Remove outdated resource: [Name]
```

**Format**:
- Start with imperative verb (Add, Update, Fix, Remove, etc.)
- Be specific about what changed
- Keep subject line under 72 characters
- Add body for complex changes

### Branch Naming

For contributions:
```
add-[resource-name]
fix-[issue-description]
update-[section-name]
```

### Pull Requests

1. **Title**: Clear description of change
2. **Description**:
   - What resource(s) are being added/changed
   - Why this resource is valuable
   - Any relevant context
3. **Checklist**:
   - [ ] Links are working
   - [ ] Entry follows format guidelines
   - [ ] Description is clear and concise
   - [ ] Alphabetically ordered (if applicable)
   - [ ] Attribution included

## Common Tasks

### Adding a New Resource

1. Determine the appropriate section (see [README Sections](#readme-sections))
2. Format entry according to the section's format variation
3. Insert in alphabetical order within the section
4. Verify all links work (use HTTPS)
5. Commit with descriptive message (e.g., `Add [Name] to [Section]`)

### Adding an Article

1. Determine the best subsection under Articles (Technical Deep Dives, Educational, etc.)
2. Format entry: `- [Title](url) by Author Name (Month Year) - Brief description`
3. Insert in alphabetical order within the subsection
4. Verify the article link works
5. Commit with descriptive message

### Adding a New Section

1. Consider if it fits the awesome list philosophy
2. Add section header with proper level (`##` for top-level, `###` for subsections)
3. Update Table of Contents in README
4. Add initial resources (3+ recommended)
5. Place section in logical position relative to existing sections

### Fixing Broken Links

1. Verify link is actually broken (not a temporary issue)
2. Search for updated/replacement URL
3. Update or remove resource
4. Document reason in commit message

### Reorganizing Content

1. Ensure reorganization improves clarity
2. Maintain all existing content
3. Update Table of Contents
4. Test all anchor links still work

## Quality Checklist

Before submitting changes:

- [ ] All links are functional and use HTTPS
- [ ] Markdown syntax is correct
- [ ] Entry format follows guidelines for its section
- [ ] Resources are in appropriate sections
- [ ] Alphabetical ordering maintained within sections
- [ ] Attributions included
- [ ] Descriptions are clear and concise
- [ ] No duplicate entries
- [ ] Table of Contents updated (if needed)
- [ ] Commit messages are descriptive
- [ ] Changes align with awesome-manifesto principles

## References

- [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/main/awesome.md)
- [Markdown Guide](https://www.markdownguide.org/)
- [Contributing Guidelines](CONTRIBUTING.md)

## Notes for AI Agents

- This is a **documentation-only** repository - no code to compile or test
- Focus on **content quality** and **proper formatting**
- Always **verify links** before adding them
- Respect the **awesome list philosophy** - quality over quantity
- When in doubt, open an **issue for discussion** before making major changes
- Follow the existing **patterns and structure** in README.md
- Pay attention to **section-specific format variations** (articles vs. tools vs. videos)
- The Articles section has **subsections** - place articles in the correct one
- Keep the **Table of Contents** in sync with actual section headings
