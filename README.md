# What I Learned — Git & GitHub Course (Apna College)

**Author:** Maqsood Ahmad
**Repository:** [Git-And-GitHub-Course](https://github.com/maqsoodkhan840/Git-And-GitHub-Course)
**Repository:** Check[my-first-github-webpage](https://maqsoodkhan840.github.io/my-first-github-webpage/)

---

## 🎓 What I Learned

1. **Version Control Fundamentals**

   - Difference between **Git** (distributed VCS) and **GitHub** (remote hosting & collaboration).
   - Benefits: project history, branching, and team collaboration.

2. **Setup & Configuration**

   - Installed Git locally.
   - Configured identity:

     ```bash
     git config --global user.name "Maqsood Ahmad"
     git config --global user.email "you@example.com"
     ```

3. **Core Git Workflow**

   - **Initialize** repositories (`git init`), **clone** existing (`git clone`).
   - **Check status** (`git status`), **stage** changes (`git add`), **commit** (`git commit`).
   - **View history** (`git log`, `git log --oneline`), **inspect diffs** (`git diff`).

4. **Working with Remotes**

   - **Add remote** (`git remote add origin <URL>`).
   - **Push** (`git push -u origin main`) and **pull** (`git pull origin main`).

5. **Branching & Merging**

   - **Create** (`git branch <name>`), **switch** (`git checkout <name>`), **merge** (`git merge <branch>`).
   - Handle merge conflicts by editing files, staging, and committing.

6. **Undoing & Cleaning**

   - **Unstage** changes (`git restore --staged <file>`).
   - **Discard** working-directory edits (`git restore <file>`).
   - **Reset commits** (`git reset HEAD~1`, `git reset --hard HEAD`).
   - **Revert** a commit (`git revert <commit-hash>`).

7. **GitHub Collaboration**

   - **Fork** repositories, create **pull requests**, and perform **code reviews**.
   - Best practices: small, focused commits; feature branches; sync frequently.

---

## 📥 Official Resources

- **Apna College PDF Notes** – [Download here](https://www.apnacollege.in/notes?utm_source=chatgpt.com)
- **Git Cheat Sheet (PDF)** – [Download here](https://lwfiles.mycourse.app/62a6cd5e1e9e2fbf212d608d-public/publicFiles/git-cheat-sheet-education.pdf)

---

## 🛠️ Git Command Cheat-Sheet

```bash
# Initial Setup
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Start or Clone a Repo
git init
git clone <repo-url>

# Status & History
git status
git log
git log --oneline

# Stage & Commit
git add <file>
git add .
git restore --staged <file>
git commit -m "Commit message"
git commit -am "msg"

# Inspect Changes
git diff
git diff --staged

# Remote Operations
git remote -v
git remote add origin <url>
git push -u origin main
git pull origin main

# Branching & Merging
git branch
git branch <name>
git checkout <branch>
git checkout -b <name>
git merge <branch>

# Cleaning & Undoing
git restore <file>
git restore --staged <file>
git reset HEAD~1
git reset --hard HEAD
git revert <commit-hash>

# Branch Management
git branch -d <branch>
git branch -D <branch>
git branch -m <old> <new>
git push origin --delete <branch>
```

---

## 🔄 Git Workflows

### 1. Remote → Local Workflow (Clone & Update)

```bash
# 1. Clone the remote repository
git clone https://github.com/username/project.git
cd project

# 2. Work locally
# — make edits, add or remove files
git status
git add .
git commit -m "Describe changes"

# 3. Sync changes
git pull origin main
git push origin main
```

**Steps:**

1. Clone to local machine
2. Edit → Stage → Commit
3. Pull latest updates
4. Push your commits

---

### 2. Local → Remote Workflow (Init & Publish)

```bash
# 1. Initialize project folder
mkdir my-project && cd my-project

# 2. Initialize Git and commit
git init
touch README.md
git add .
git commit -m "Initial commit"

# 3. Link and push to GitHub
git remote add origin https://github.com/username/my-project.git
git push -u origin main
```

**Steps:**

1. `git init` in project directory
2. Stage & commit work
3. Add remote origin
4. Push with upstream set

---

> **Usage:**
>
> ```bash
> git add README.md
> git commit -m "Add consolidated course notes, commands & workflows"
> git push origin main
> ```

Happy learning and collaborating! 🚀
