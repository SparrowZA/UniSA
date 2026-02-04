# UniSA BSc Computing Repository

Welcome! This repository contains study materials, resources, and documentation for **BSc Computing students at the University of South Africa (UniSA)**.

## About This Repository

This repository is organized by course code and contains prescribed books, study guides, exam papers, summaries, and other learning materials to support your computing degree.

---

## How to Download Files

### Option 1: Download Without Git (No Installation Required)

If you don't want to install Git, you can download all files directly from GitHub:

1. Go to the GitHub repository page
2. Click the green **Code** button at the top right
3. Select **Download ZIP** from the dropdown menu
4. Extract the ZIP file to your desired location
5. Access all files through your file explorer

This is the quickest method if you just need to download files once.

---

### Option 2: Download With Git (Recommended for Updates)

Using Git allows you to easily pull the latest updates to the repository.

#### Step 1: Install Git on Windows

- **Official Git Download**: [https://git-scm.com/download/win](https://git-scm.com/download/win)
- **Installation Guide**: [Git for Windows Setup Guide](https://git-scm.com/download/win)

After installation, verify Git is installed by opening Command Prompt or PowerShell and running:
```
git --version
```

#### Step 2: Clone the Repository

Open Command Prompt or PowerShell in the folder where you want to download the repository, then run:

```
git clone https://github.com/your-username/repository-name.git
```

Replace `your-username` and `repository-name` with the actual GitHub repository details.

#### Step 3: Update Files

To get the latest updates, navigate to the repository folder and run:

```
git pull
```

---

## Git Learning Resources

New to Git? Here are some helpful resources:

- **Git Basics - Official Guide**: [https://git-scm.com/book/en/v2/Getting-Started-Git-Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- **GitHub's Git Handbook**: [https://guides.github.com/introduction/git-handbook/](https://guides.github.com/introduction/git-handbook/)
- **Atlassian Git Tutorial**: [https://www.atlassian.com/git/tutorials/what-is-git](https://www.atlassian.com/git/tutorials/what-is-git)

---

## Repository Structure

The repository is organized by course:

- **Computer Networks I (COS2626)**
- **Computer Systems Fundamental Concepts (COS1521)**
- **Human-Computer Interaction I (NF1520)**
- **Introduction to Business Information Systems (INF1505)**
- **Introduction to Programming II (COS1512)**
- **Linear Algebra I (MAT1503)**
- **Theoretical Computer Science I (COS1501)**
- **Visual Programming I (INF1511)**

---

## Contributing

### Important: How Changes Are Handled

The way your changes are submitted depends on your access level:

#### For Users WITHOUT Push Access (Most Contributors)

If you don't have push access to this repository, follow these steps to contribute:

1. **Fork the Repository**
   - Click the **Fork** button on the GitHub repository page
   - This creates your own copy of the repository

2. **Clone Your Fork**
   ```
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```

3. **Create a New Branch**
   ```
   git checkout -b your-branch-name
   ```

4. **Make Your Changes**
   - Edit files locally on your machine
   - Save your changes

5. **Commit Your Changes**
   ```
   git add .
   git commit -m "Describe your changes here"
   ```

6. **Push to Your Fork**
   ```
   git push origin your-branch-name
   ```

7. **Create a Pull Request (PR)**
   - Go to the original repository on GitHub
   - Click **Pull Requests** → **New Pull Request**
   - Select your fork and branch
   - Describe your changes and submit the PR
   - Wait for review and approval before your changes are merged

**Important**: Your changes will **NOT** overwrite the main branch directly. Instead, a PR is created for review.

#### For Users WITH Push Access (Repository Maintainers)

If you have been granted push access:

- You can push directly to the main branch: `git push origin main`
- Your changes will be applied immediately (use with caution!)
- It's still recommended to use branches and PRs for code review best practices

### Before Contributing

- Review existing materials to avoid duplicates
- Ensure your contributions align with the course content
- Check that files follow the repository's organization structure

---

## Support

For questions or issues with this repository, please contact the repository maintainer or refer to the course materials provided by UniSA.

Happy studying! 📚
