# pfc4admintools
## pfc4updatereadme

```bash
pfc4updatereadme <project name>
```

Updates README.md in all students' projects with the given name, with the README.md file from the solution project.

Performs git pull and git push to remotes.

Uses absolute paths:
- for the solution project: `~/0projects/tic4/pfc/ideas/`
- for the students' projects: `~/0projects/tic4/pfc/students/`

## pfc4getpfcs

```bash
pfc4getpfcs
```

Gets a list of PFCs and saves it to a file called `pfcs.csv`

The list is a CSV file with three fields:
```bash
group,project-slug,project-url
```

The project's URL is the clone by HTTPS URL.
