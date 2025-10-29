# Writing Templates

## Equipment Documentation Template

```markdown
---
sidebar_position: 1
---

# Equipment Name

One-line description.

## Specifications
- **Model:**
- **Location:**
- **Certification Required:** Yes/No

## Getting Started
[Quick start guide]

## Safety
:::danger
Critical safety info
:::

## Common Tasks
### Task Name
Steps...

## Troubleshooting
Common issues and solutions
```

## Style Guide

- Use active voice: "Click the button" not "The button should be clicked"
- Address reader as "you"
- Present tense: "The printer heats" not "will heat"
- Be specific: include model numbers, measurements

## Markdown Features

### Admonitions
```markdown
:::note
Standard note
:::

:::tip
Helpful tip
:::

:::warning
Pay attention
:::

:::danger
Safety critical
:::
```

### Code Blocks
````markdown
```python
print("Hello!")
```
````

### Images
```markdown
![Description](/img/path/to/image.jpg)
```

## Advanced Tasks

### Adding a New Section
1. Create folder in `docs/`
2. Add `_category_.json` with metadata
3. Update `sidebars.js` if needed

