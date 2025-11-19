---
name: 🤖 CI/CD Configuration
about: Use this for changes to GitHub Actions, Workflows, or Build Scripts
title: "ci(scope): <description>"
labels: ["ci", "needs-review"]
assignees: ''
---

## 🤖 Change Description
## 🎯 Affected Workflows
- [ ] **Build / Compile**
- [ ] **Test Runner**
- [ ] **Deployment / Release**
- [ ] **Linting / Static Analysis**

## 🧪 Verification (Critical)
- [ ] I triggered the workflow manually on this branch.
- [ ] I inspected the logs and they look correct.
- [ ] I validated the YAML syntax (e.g., using an online validator or IDE plugin).

## 📸 Log Snippet (Optional)
```text
Success: Build container pushed to registry (2m 30s)
```

## ✅ Checklist

  - [ ] This change does not expose secrets or API keys.
  - [ ] I have tested the "fallback" behavior (what happens if it fails?).
  - [ ] I informed the team if this changes how they deploy/test.

<!-- end list -->