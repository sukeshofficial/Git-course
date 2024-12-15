# **Git-Course Demo**

**Started on:** *14.12.2024*  
---

### **Topics Learned:**

#### **1. Basics:**
- How to create an SSH key:  
  ```bash
  ssh-keygen
  ```
- Connect remote repository:  
  ```bash
  git remote -u <SSH-key>
  ```

#### **2. Git Commands:**
- **Adding files:**
  - Add a specific file:  
    ```bash
    git add <fileName>.type
    ```
  - Add all unstaged changes:  
    ```bash
    git add .
    ```

- **Committing changes:**  
  ```bash
  git commit -m "Your commit message"
  ```

- **Pushing to a branch:**  
  ```bash
  git push origin <branch>
  ```

- **Pulling updates from remote to local:**  
  ```bash
  git pull origin main
  ```

- **Checking status:**  
  ```bash
  git status
  ```

- **Viewing commit history:**  
  ```bash
  git log
  ```
  - With graph view:  
    ```bash
    git log --graph
    ```

- **Branch Management:**
  - View available branches:  
    ```bash
    git branch
    ```
  - Switch to a branch:  
    ```bash
    git switch <branch>
    ```
    (or)
    ```bash
    git checkout -b <branch>
    ```
  - Go to the previous branch:  
    ```bash
    git switch -
    ```
  - Create and switch to a new branch:  
    ```bash
    git checkout -c <branch>
    ```

---

**Completed on:** *15.12.2024*  
---
