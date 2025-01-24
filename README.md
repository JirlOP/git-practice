# git-practice

Repository to practice Git, GitHub essentials and document process as a runbook. Moreover, it is a source of documentation of Git/GitHub processes.

## Features

- Documentation of Git and GitHub processes.
- Practice Git commands and workflows.

## Contributing

1. Clone the repository.

```bash
git clone https://github.com/JirlOP/git-practice.git
cd git-practice
```

2. Create an issue in GitHub for the next to complete with the format: `TN: Task to complete`.

**Note**: Replace `N` with the ticket number.

3. Create a new branch depending on the task and ticket you are working on.

```bash
git checkout -b feature/TN/thing-to-do
```

Note: Replace `N` with your ticket number.

4. PR to main branch with the runbook of a process you wanna add.

```bash
git add .
git commit -m "Add: Runbook for process"
git push origin feature/TN/thing-to-do
```

5. Then create a PR on GitHub to merge your feature branch into `main`. With the name of the ticket `TN` to resolve.

6. Wait for the PR to be reviewed and merged.

## License

**MIT License** - see the [LICENSE](LICENSE) file for details.

