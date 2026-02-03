# farmos-docs - Customer Documentation

**Project:** Mintlify documentation site for Juice
**Last Updated:** 2026-02-02

---

## 📚 **Navigation**

This project uses Cursor's modern rules system.

**Quick start:**
1. This file (CLAUDE.md) - Quick reference
2. `.cursor/rules/_navigation.mdc` - Auto-loads for MDX files (complete patterns)
3. `mint.json` - Site configuration and navigation

---

## 🎯 **Top 7 Critical Rules**

1. **NEVER use technical jargon** - Write for marketers, not developers
2. **NEVER skip screenshots** - Always include visuals
3. **NEVER write long paragraphs** - 2-3 sentences max
4. **NEVER forget frontmatter** - title + description required
5. **NEVER deploy without testing** - Run `mintlify dev` first
6. **NEVER modify navigation** - Without testing mint.json changes
7. **NEVER use developer terms** - User-friendly language only

---

## 🚀 **Quick Patterns**

### Page Template
```mdx
---
title: "Feature Guide"
description: "Learn how to use this feature"
---

# Feature Guide

Brief introduction in simple language.

<Steps>
  <Step title="Step 1">
    First action
  </Step>
  <Step title="Step 2">
    Second action
  </Step>
</Steps>
```

### Mintlify Components
```mdx
<Tip>Helpful tip</Tip>
<Warning>Important warning</Warning>
<Accordion title="Question?">Answer</Accordion>
```

---

## 📖 **Documentation**

**Cursor Rules:**
- `.cursor/rules/_navigation.mdc` - All Mintlify patterns

**Project Info:**
- `mint.json` - Configuration
- `README.md` - Setup guide
- 42+ MDX pages across 8 sections

---

## 🏗️ **Tech Stack**

- Mintlify (documentation framework)
- MDX (Markdown + React components)

---

## 📝 **Commands**

```bash
mintlify dev       # Local preview
mintlify build     # Build static
mintlify deploy    # Deploy
```

---

## 🔗 **Related Projects**

- **farmos-web** - Main dashboard
- **farmos-web-node** - Proxies docs
- **farmos-backend** - Auth verification

---

**Last Updated:** 2026-02-02
**Audience:** Marketing managers and content creators
**Tone:** Conversational, helpful, friendly
