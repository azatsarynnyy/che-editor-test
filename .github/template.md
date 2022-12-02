---
title: Che-Code automatic rebase against upstream VS Code is failed
assignees: azatsarynnyy
labels: kind/bug

---

### Is your task related to a problem? Please describe
The GitHub Workflow has been unable to update Che-Code with the latest VS Code patches and needs human attention.

### Describe the solution you'd like
1. See the failed run at https://github.com/che-incubator/che-code/actions/runs/{{ env.RUN_ID }}.
2. Perform the rebase manually (fix the detected merge conflicts).
https://github.com/che-incubator/che-code#how-to-fix-the-rebase-insiders-workflow
