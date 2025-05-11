````markdown
# What I Learned — Git & GitHub Course (Apna College)

**Author:** Maqsood Ahmad  
**Repository:** Check [my-first-github-webpage](https://maqsoodkhan840.github.io/my-first-github-webpage/)

---

## 🎓 What I Learned

1. **Version Control Fundamentals**

   - Difference between Git (distributed VCS) and GitHub (remote hosting & collaboration).
   - Benefits of version control: history, branching, collaboration.

2. **Setup & Configuration**

   - Installed Git on my machine.
   - Configured my identity:
     ```bash
     git config --global user.name "Maqsood Ahmad"
     git config --global user.email "you@example.com"
     ```

3. **Core Git Workflow**

   - Initialized repos (`git init`), cloned existing ones (`git clone`).
   - Checked status (`git status`), staged changes (`git add`), and committed (`git commit`).
   - Viewed history (`git log`, `git log --oneline`), inspected diffs (`git diff`).

4. **Working with Remotes**

   - Added remote origins (`git remote add origin <URL>`).
   - Pushed local commits (`git push -u origin main`) and pulled updates (`git pull`).

5. **Branching & Merging**

   - Created branches (`git branch <name>`), switched (`git checkout <name>`), and merged (`git merge <branch>`).
   - Resolved merge conflicts by editing files, staging, and committing.

6. **Undoing & Cleaning**

   - Unstaged changes (`git restore --staged <file>`).
   - Discarded working-directory changes (`git restore <file>`).
   - Reset commits (`git reset HEAD~1`, `git reset --hard HEAD`).
   - Reverted commits (`git revert <commit-hash>`).

7. **Collaboration on GitHub**
   - Forked repos, created pull requests, participated in code reviews.
   - Best practices: small, meaningful commits; branch per feature; sync frequently.

---

## 📥 Official Resources

- **Apna College PDF Notes**  
  Download the full course notes:  
  [https://www.apnacollege.in/notes?utm_source=chatgpt.com](https://www.apnacollege.in/notes?utm_source=chatgpt.com)
- **Official Git Cheat Sheet (PDF)**  
  [Download Git Cheat Sheet by Apna College](https://lwfiles.mycourse.app/62a6cd5e1e9e2fbf212d608d-public/publicFiles/git-cheat-sheet-education.pdf)

---

## 🛠️ Git Command Cheat-Sheet

```bash
# — Initial Setup
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# — Start or Clone a Repo
git init
git clone <repo-url>

# — Check Status & History
git status
git log
git log --oneline

# — Staging & Committing
git add <file>
git add .
git commit -m "Your message"
git commit -am "msg"   # stage & commit tracked files

# — Inspecting Changes
git diff
git diff --staged

# — Remote Operations
git remote -v
git remote add origin <url>
git push -u origin main
git pull origin <branch>

# — Branching & Merging
git branch
git branch <name>
git checkout <branch>
git checkout -b <name>
git merge <branch>

# — Cleaning & Undoing
git restore <file>
git restore --staged <file>
git reset HEAD~1
git reset --hard HEAD
git revert <commit-hash>

# — Branch Management
git branch -d <branch>
git branch -D <branch>
git branch -m <old> <new>
git push origin --delete <branch>
```
````

---

## 🔄 Git Workflows

### 1. Remote → Local (Clone & Update)

```bash
# Clone remote repository
git clone https://github.com/username/project.git
cd project

# Work locally
git status
git add .
git commit -m "Describe changes"

# Sync with remote
git pull origin main
git push origin main
```

**Steps**

1. Clone the repo
2. Edit → Stage → Commit
3. Pull to get latest changes
4. Push your commits

---

### 2. Local → Remote (Init & Publish)

```bash
# Create new project folder
mkdir my-project && cd my-project

# Initialize Git
git init

# Add files and commit
touch README.md
git add .
git commit -m "Initial commit"

# Link to GitHub & push
git remote add origin https://github.com/username/my-project.git
git push -u origin main
```

**Steps**

1. `git init` in project directory
2. Stage & commit your work
3. Add remote origin
4. Push with `-u` to set upstream

---

> **With this single README**, anyone can:
>
> - See exactly what you will learn
> - Download official course notes & cheat sheet
> - Reference all essential Git commands
> - Follow two main Git workflows

Happy learning and collaborating! 🚀

```

```
