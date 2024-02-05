# Git Commands

1. **`git add <file>`**:
   - This command is used to stage changes made to a specific file or a set of files for inclusion in the next commit. When you make changes to your files, they are initially considered "uncommitted" or in the "working directory." Using `git add` moves these changes to the "staging area" or "index," indicating that you intend to include them in the next commit.

2. **`git status`**:
   - The `git status` command allows you to check the current state of your Git repository. It provides information about which files are in the working directory, which files are staged (added using `git add`), and which files are already committed. It also informs you of any untracked files and provides hints on what to do next.

3. **`git commit -m "<message>"`**:
   - After you've staged your changes using `git add`, the next step is to create a new commit. A commit is a snapshot of your project at a specific point in time and includes the changes you've staged. The `-m` flag is used to provide a brief and meaningful message that describes the purpose of the commit. This message is important because it helps you and others understand the purpose and context of the change.

In summary:
- When you work on a project with Git, your files initially start as "uncommitted" changes in the working directory.
- You use `git add` to stage specific files or changes you want to include in the next commit.
- `git status` helps you monitor the status of your changes, showing you what's untracked, what's staged, and what's committed.
- Finally, you use `git commit -m "<message>"` to create a new commit that records the staged changes along with a meaningful message explaining what those changes are for.

This workflow allows you to track and manage your project's history, collaborate with others, and easily understand the evolution of your codebase over time.
