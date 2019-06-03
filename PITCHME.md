## Git Primer and Workflow
Twitter: @Taylor_Vories

![](assets/img/slide1.jpeg)

---

### Version Control with Snapshots

- Changes are stored as a snapshot
- Does not track based on file but on snapshot in time
- If file not changed, it is referenced by the snapshot instead of storing it twice


![](assets/img/git_snapshot.png)

+++

### Locally owned and operated

- Once cloned or initialized, the work you do is local
- To share changes you must push to shared repository

---

### The "areas" of git

- Git is comprised of 4 main areas.
- Stash
- Working Area
- Index (staging area)
- Repository (not shared repository, local)

![](assets/img/git.png)

---

### Stash

- The stash is not used often but it is useful.
- You can store changes you aren't ready to commit and work on something else for a while
- Put your work aside quickly and then get back to it

+++

### Stash commands

- `git stash` - Stores your un-committed data in the stash
- `git stash list` - Shows you your stashes
- `git stash apply` - Brings back the stash to the working directory
- `git stash clear` - Destroys the stash area and removes anything in there

---

### Working Area, Index, and Repository

- The three main git areas
- Working Area - Where you are working
- Index (Staging) - Where you stage your changes
- Repository - All the files and their committed history.

---

### Working from left to right

- Your workflow when using git should move from left (working area) to right (staging and then repository)
![](assets/img/git.png)

+++

### Working Area

- You make changes here that you don't care about tracking
- Example: Get your PowerShell to work before you add it

+++

### Index (Staging)

- This is where you stage your files to be added to version control
- `git add` is an example of staging your changes

+++

### Repository (local)

- The magic
- Files and their history
- All the changes you have checked in over time
- `git commit` is an example of moving your changes from index to repository

---

### Recap

@snap[west span-60]

- Version control is good
- Git is a popular version control system
- Multiple areas in git to manage workflow

@snapend

@snap[east span-40]

![](assets/img/gitkcd.png)

@snapend
