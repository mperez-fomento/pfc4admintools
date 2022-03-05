# pfc4admintools
## pfc4updatereadme

### Syntax

```bash
pfc4updatereadme <project name>
```

### Overview

Updates README.md in all students' projects with the given name, with the README.md file from the solution project.

Performs git pull and git push to remotes.

Uses absolute paths:
- for the solution project: `~/0projects/tic4/pfc/ideas/`
- for the students' projects: `~/0projects/tic4/pfc/students/`
