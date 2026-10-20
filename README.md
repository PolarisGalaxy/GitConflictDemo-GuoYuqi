# GitConflictDemo-GuoYuqi

Practical 4: Collaborating with Git and resolving merge conflicts.

- Student name: Guo Yuqi
- Student ID: 20243006972
- Application name: GitConflictDemo-GuoYuqi

## Workflow recorded in this repository

1. `main` starts with the initial Android app (two buttons, same default blue colour).
2. Student 1 branch `feature-red-button` changes both buttons to red.
3. Student 2 branch `feature-green-button` is created from the same original `main`, then changes both buttons to green.
4. `feature-red-button` is merged into `main` first.
5. Merging `feature-green-button` into `main` produces an intentional conflict on the same XML lines.
6. The conflict is resolved, tested conceptually, committed, and merged into `main`.

Final resolution: Option C. The first button stays red and the second button stays green, so both feature requirements are kept after the conflict is inspected.
