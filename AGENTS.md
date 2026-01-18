# AGENTS.md - Guidelines for AI Coding Agents

This document provides guidelines for AI coding agents working on the Awesome JAM repository. This is a curated list repository containing Markdown documentation, not a traditional code project.

## Repository Overview

**Type**: Curated list / Documentation repository  
**Primary Language**: Markdown  
**Purpose**: A curated collection of JAM (Join-Accumulate Machine) resources, tools, examples, tutorials, and more  
**Main Files**:
- `README.md` - Main curated list
- `CONTRIBUTING.md` - Contribution guidelines
- `LICENSE` - MIT License

## Repository Structure

```
Awesome-JAM/
├── README.md          # Main curated list (primary content)
├── CONTRIBUTING.md    # Contribution guidelines
├── LICENSE            # MIT License
└── AGENTS.md          # This file
```

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

## Content Guidelines

### Structure and Organization

1. **Table of Contents**:
   - Keep alphabetically ordered where appropriate
   - Update TOC when adding new sections
   - Use consistent anchor link formatting

2. **Sections**:
   - Group related resources together
   - Maintain consistent section naming
   - Use descriptive section headers

3. **Entry Format**:
   ```markdown
   - [Resource Name](url) by [@username](github-profile) - Brief description
   ```

4. **Resource Ordering**:
   - Within sections, order entries alphabetically by resource name
   - For articles/videos with dates, consider chronological ordering
   - Group subsections logically (e.g., Technical Deep Dives, Educational content)

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
   - Always credit original authors with `by [@username](profile-link)`
   - Link to GitHub profiles when available
   - For organizations, link to their GitHub org page

3. **Categorization**:
   - Place resources in the most appropriate section
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

1. Determine the appropriate section
2. Format entry according to guidelines
3. Insert in alphabetical order (if applicable)
4. Verify all links work
5. Commit with descriptive message

### Adding a New Section

1. Consider if it fits the awesome list philosophy
2. Add section header with proper level
3. Update Table of Contents
4. Add initial resources (3+ recommended)
5. Place section in logical position

### Fixing Broken Links

1. Verify link is actually broken
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
- [ ] Entry format follows guidelines
- [ ] Resources are in appropriate sections
- [ ] Alphabetical ordering maintained
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
