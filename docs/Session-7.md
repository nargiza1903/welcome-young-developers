## Session 7: Git: Your Website's Time Machine! ⏰

### 🎯 Learning Objectives:

* Understand the concept of version control and why it's important for managing your website's codebase.
* Learn essential Git commands for tracking changes, saving snapshots (commits), and reviewing your project's history.
* Practice using Git to confidently experiment with your website, knowing you can easily revert to previous versions.

### 🗺️ Session Flow:

1. **Warm-Up Activity (5 minutes):**
    * Quick review: Ask students to explain what HTML and CSS do.
    * Brainstorm: Pose the question: "What would you do if you accidentally deleted or changed something important on your website? How could you go back?"
      [Image of a student with a worried expression looking at a broken website]

2. **Introduction to Version Control (10 minutes):**
    * Explain version control: It's like having a "time machine" for your code. You can save different versions (snapshots) as you work and easily go back if needed.
      [Image of a time machine with a website code icon]
    * Git: Introduce Git as the most popular version control tool. It's used by professionals worldwide!

3. **Git Basics (20 minutes):**
    * Installing Git: If students haven't already installed Git (Session 2), guide them through the process. Provide a link to the official Git download page: [https://git-scm.com/downloads](https://git-scm.com/downloads)
    * Repository: Explain that a repository is like a special folder where Git tracks changes.
      [Image of a folder icon with the Git logo]
    * Initializing Git:
      ```bash
      git init
      ```
      [Screenshot of a terminal showing the command `git init` being run]
    * Essential Git Commands:
        * `git add <filename>`: Tell Git which files to include in the next snapshot.
        * `git commit -m "your message here"`: Save a snapshot of your changes with a descriptive message.
        * `git status`: Check which files have been modified.
        * `git log`: View the history of your commits (snapshots).
        *  Briefly introduce `git checkout <commit-hash>` as a way to jump back to a specific snapshot (like stepping into a photo and bringing that version of your project back to life).

4. **Hands-On Practice (20 minutes):**
    * Guide students through exercises like:
        * Editing their website's `index.html` or `style.css` files.
          [Image of a student editing code in a text editor]
        * Using `git add` and `git commit` to track their changes.
      ```bash
      git add index.html
      git commit -m "Added a new heading"
      ```
      [Screenshot of a terminal showing `git add` and `git commit` commands]
        * Reviewing the commit history with `git log`.

5. **Wrap-Up (5 minutes):**
    * Recap: Emphasize how Git empowers them to experiment and be creative without fear of messing up their website.
    * Encourage: Tell them to use Git regularly as they build their awesome websites.

### 🧰 Materials Needed:

* Students' computers with:
    * **Visual Studio Code** (or their preferred code editor)
    * **Git** installed
* A sample website project or their own work from previous sessions.
* Optional: Slides or visual aids to illustrate Git concepts.

### 🎯 Homework/Challenges:

* **Challenge:** Make several commits throughout the week as you work on your website.
* **Explore:** Try using `git diff` to see the specific changes between commits.
* **Optional:** If time allows, introduce the concept of branches for experimenting with new features separately from the main website.
