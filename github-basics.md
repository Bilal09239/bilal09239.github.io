[Home](index.md) | [Linux Installation](linux-installation.md) | [GitHub Basics](github-basics.md)

---

# GitHub Basics

GitHub is a platform used to host and manage code projects.  
It is based on the version control system **Git**.

GitHub allows developers to:

- store code online
- track changes
- collaborate with others
- manage projects
- host websites using GitHub Pages

---

# What is a Repository?

A **repository (repo)** is a project folder on GitHub.

A repository can contain:

- source code
- documentation
- images
- configuration files
- websites

Every change in a repository is stored in the version history.

---

# Creating a Repository

To create a new repository:

1. Log in to GitHub
2. Click **New Repository**
3. Enter a repository name
4. Choose public or private
5. Click **Create Repository**

![Alt text for image](images/Creating%20a%20Repository.jpg)

You can now add files to your project.

---

# Using Git in the Terminal

Git is usually used in the terminal or command line.

Below are some important commands.

---

# Clone a Repository

Download a repository from GitHub to your computer.

```bash
git clone https://github.com/username/repository-name.git
```

---

# Check Repository Status

Shows which files have changed.

```bash 
git status
```

---

# Add Files to Git

Adds files to the staging area.

Add a single file:
```bash 
git add filename
```

---

# Create a Commit

Save the changes with a message.

```bash 
git commit -m "Added new tutorial page"
```

---

# Upload Changes to GitHub

Push your changes to the remote repository.
```bash 
git push
```

---

# Get Latest Changes

Download updates from GitHub.
```bash 
git pull
```

---

# Conclusion

GitHub and Git are essential tools for modern software development.

They help developers:

- track code changes
- collaborate with others
- manage projects efficiently
- publish open source projects

.