# Contributing to The Agent Framework Graveyard

Thanks for helping document the **actual complexity** of AI Agent frameworks!

## 🎯 What We're Looking For

Frameworks that:
- Promise "easy setup" but require hours of configuration
- Have 1000+ GitHub stars but low actual usage
- Assume technical knowledge not mentioned in docs
- Leave users frustrated and projects abandoned

## 📝 How to Add a Framework

### 1. Fork & Clone

```bash
git fork easyclaw/agent-framework-graveyard
git clone https://github.com/YOUR_USERNAME/agent-framework-graveyard
```

### 2. Add Framework Entry

Use this template in `README.md`:

```markdown
### 🔧 [Framework Name]

**Promises:**
- Feature 1
- Feature 2
- Feature 3

**Reality:**
- Actual requirement 1 (e.g., "Requires Docker")
- Actual requirement 2 (e.g., "YAML configuration needed")
- Learning curve detail
- Best for: [Target audience]

**Complexity Score:** ⭐⭐⭐⭐ (X/5)

**Simple Alternative:** [Tool Name](link) — One-sentence value prop
```

### 3. Complexity Score Guide

- ⭐ (1/5): Beginner-friendly, minimal setup
- ⭐⭐ (2/5): Some configuration needed
- ⭐⭐⭐ (3/5): Moderate learning curve
- ⭐⭐⭐⭐ (4/5): Requires technical knowledge
- ⭐⭐⭐⭐⭐ (5/5): Expert-level complexity

### 4. Guidelines

**DO:**
- ✅ Be honest about actual complexity
- ✅ Focus on setup/onboarding experience
- ✅ Mention target audience (who it's actually for)
- ✅ Suggest practical alternatives

**DON'T:**
- ❌ Be mean or dismissive
- ❌ Attack developers/maintainers
- ❌ Exaggerate issues
- ❌ Submit without trying the framework

### 5. Submit PR

```bash
git checkout -b add-framework-name
git add README.md
git commit -m "Add [Framework Name] to graveyard"
git push origin add-framework-name
```

Then create PR on GitHub.

## 🤔 What About Tools That Work?

If you found a simple alternative that actually works, add it to:
- **Simple Alternative** section of the framework entry
- Or submit a separate "What Works" list

## 📊 Data Sources

When adding a framework, cite sources:
- Setup time: Personal experience or community reports
- Abandonment rate: GitHub stars vs actual usage (if available)
- Complexity: Official docs review

## 🙏 Code of Conduct

- Be constructive, not destructive
- Respect all maintainers and projects
- Focus on user experience, not code quality
- Remember: complexity isn't always bad, just not for everyone

---

Questions? Open an issue or DM [@EasyClawBot](https://twitter.com/EasyClawBot)
