# Assignment #1

## Define N-Tier Architecture and Explain MVC

- **N-Tier Architecture**:  
  N-Tier architecture is a software architecture model that separates an application into logical layers or tiers. Common tiers include:
  - **Presentation Tier**: The user interface.
  - **Business Logic Tier**: Application functionality, rules, and logic.
  - **Data Access Tier**: Handles communication with the database.
  - **Database Tier**: Where the data is stored.

  This separation improves scalability, maintainability, and flexibility.

- **MVC (Model-View-Controller)**:  
  MVC is a design pattern used to build web applications:
  - **Model**: Manages the data and business logic.
  - **View**: Displays data (the UI).
  - **Controller**: Handles user input and updates the Model and View accordingly.

---

## Differentiate Between Frontend vs Backend Development

| Aspect          | Frontend                           | Backend                             |
|-----------------|------------------------------------|--------------------------------------|
| Description     | Focuses on the user interface      | Focuses on server-side logic         |
| Languages       | HTML, CSS, JavaScript              | Node.js, Python, Java, PHP, etc.     |
| Purpose         | Enhances user interaction          | Handles data processing and storage  |
| Tools/Frameworks| React, Angular, Vue                | Express, Django, Spring, Laravel     |

---

## Full Stack vs MEAN vs MERN Stack

| Stack         | Components                                                                 |
|---------------|----------------------------------------------------------------------------|
| **Full Stack**| Combination of frontend and backend technologies, can vary widely          |
| **MEAN**      | MongoDB, Express.js, Angular, Node.js                                     |
| **MERN**      | MongoDB, Express.js, React.js, Node.js                                    |

### Choosing a Stack – Deciding Factors:
- **Team expertise**
- **Community support**
- **Project requirements (e.g., real-time apps vs static sites)**
- **Performance needs**
- **Learning curve and development speed**
---

# Assignment #2

## Difference Between a Library and a Framework

- **Library**: A collection of functions or classes used to perform specific tasks. You are in control.
- **Framework**: A structured platform for building applications. It calls your code (Inversion of Control).

---

## React vs Angular – Key Considerations

| Criteria       | React                                 | Angular                               |
|----------------|----------------------------------------|----------------------------------------|
| Type           | Library (UI)                          | Full-fledged framework                 |
| Language       | JavaScript, JSX                       | TypeScript                             |
| Learning Curve | Moderate                              | Steep                                  |
| Flexibility    | More freedom to choose tools          | Built-in tools and strict structure    |
| Performance    | Fast with Virtual DOM                 | Slightly slower due to real DOM        |

---

## Module vs Package

- **Module**: A single file or group of related functions/classes (e.g., `.js` file).
- **Package**: A collection of modules grouped together, often published to a package manager.

### NPM and Node.js

- **Node.js**: JavaScript runtime for executing JS code outside the browser.
- **NPM (Node Package Manager)**: A tool for managing JavaScript packages and dependencies.

---

# Assignment #3

## What is a VCS?

- **VCS (Version Control System)**: A tool to track changes in code over time.
  - **Centralized VCS**: Single central server (e.g., SVN).
  - **Distributed VCS**: Each user has a full copy of the repository (e.g., Git).

---

## Git vs GitHub vs GitLab

| Tool       | Description                                              |
|------------|----------------------------------------------------------|
| **Git**    | A distributed version control system                     |
| **GitHub** | A cloud-based platform for hosting Git repositories      |
| **GitLab** | Similar to GitHub but includes CI/CD and private repo hosting |

---

## Top 10 Git Commands

1. `git init` – Initialize a new repository  
2. `git clone <repo-url>` – Clone a remote repository  
3. `git status` – Show the current status of your repo  
4. `git add <filename>` – Add changes to the staging area  
5. `git commit -m "message"` – Commit changes with a message  
6. `git push` – Push commits to a remote repository  
7. `git pull` – Fetch and merge changes from a remote repo  
8. `git branch` – List, create, or delete branches  
9. `git checkout <branch>` – Switch branches  
10. `git merge <branch>` – Merge another branch into the current one  

---

# Lab: Pushing Your First Code to Git

### Steps:

1. **Create a remote repository** on GitHub or GitLab and initialize it with a `README.md`.
2. **Clone** the repository to your local environment:  
   ```bash
   git clone <your-repository-url>
   ```
3. **Navigate** into the cloned directory:  
   ```bash
   cd <repository-name>
   ```
4. **Create a file** named `myFirstPush.txt` and save some content inside.
5. **Add the file** to the staging area:  
   ```bash
   git add myFirstPush.txt
   ```
6. **Commit the changes** locally:  
   ```bash
   git commit -m "Added my first push file"
   ```
7. **Push the changes** to the remote repository:  
   ```bash
   git push origin main
   ```

Congratulations! You've successfully pushed your first code to Git!