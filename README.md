
# Git and GitHub Workshop

This guide covers the basics of using Git for version control and collaborating on GitHub.

---

## 1. Introduction to Git
1. **Set up Git Configuration**
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

## 2. Basic Git Commands
1. **Initialize a Repository**
   ```bash
   git init
   ```
2. **Add Files to the Staging Area**
   ```bash
   git add <filename>   # Add a specific file
   git add .            # Add all files in the directory
   ```
3. **Commit Changes**
   ```bash
   git commit -m "Commit message here"
   ```
4. **View Commit History**
   ```bash
   git log
   ```

## 3. Working with Branches
1. **Create a New Branch**
   ```bash
   git branch <branch-name>
   ```
2. **Switch to a Branch**
   ```bash
   git checkout <branch-name>
   ```
3. **Merge Branches**
   ```bash
   git checkout main          # Switch to the main branch
   git merge <branch-name>    # Merge the specified branch into main
   ```

## 4. Introduction to GitHub
1. **Create a GitHub Account**
2. **Create a New Repository on GitHub**

## 5. Using Git with GitHub
1. **Clone a Repository**
   ```bash
   git clone <repository-url>
   ```
2. **Push Changes to GitHub**
   ```bash
   git push origin <branch-name>
   ```
3. **Pull Updates from GitHub**
   ```bash
   git pull origin <branch-name>
   ```

## 6. Collaborating on GitHub
1. **Fork a Repository**
2. **Create a Merge Request (MR)**
   - Go to **Merge Requests** and click **New Merge Request**.
3. **Review and Approve MRs**

## 7. Best Practices
- **Commit Messages:** Use clear, concise messages describing changes.
- **Branch Naming:** Use descriptive names for branches (e.g., `feature-login` or `bugfix-navbar`).

---

This guide provides the steps needed to get started with Git and GitHub for version control and collaboration.
