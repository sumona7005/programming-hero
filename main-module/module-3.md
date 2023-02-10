# Note

- install Git, Node.js, Create GitHub account
- create a GitHub repository
- command line/cmd: `cd..` , `cd folder-name`
- VS Code setting: terminal > integrated: Font Size
- Git commands:
  - terminal:
    - check if powershell is set by default
    - enter `git --version` to check if git is working
  - Set Git user:
    - `git config --global user.email "user@mail.com"`
    - `git config --global user.name "User Name"`
  - Track works:
    - `git init` , `git add .`
    - `git commit -m "commit message"`
    - `git branch -M main`
  - Send to GitHub for the first time:
    - `git remote add origin https://github-repo-link`
    - `git push -u origin main`
  - (Optional) create README file before add, commit, push:
    - `echo "# repo-name" >> README.md`
  - After changing on GitHub: `git pull`
  - When user & remote origin is already added:
    - `git add .` , `git commit -m "message"` , `git push`
- delete new codes: VS Code → Source Control → Discard Changes
- host the project:
  - GitHub repo → setting → pages → main branch → save
- GitHub issues:
  - `git --version` fails: change PowerShell to Git Bash
  - can't push: forgot to save/add/commit
  - page is broken: not having index.html file
  - remote origin already exists: `git remote set-url`
- Working with branch:
  - [cheat sheet](https://github.com/joshnh/Git-Commands)
  - `git branch`
  - `git branch branch-name`
  - `git checkout branch-name`
  - `git push --set-upstream origin branch-name`
  - `git merge branch-name`
  - `git pull`
  - `git checkout -b branch-name`
  - merge conflict (changes in both branches):
    - accept Current Change or Incoming Change

# Screenshot

![](/screenshot/26.png)
![](/screenshot/27.png)
