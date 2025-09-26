# A02
Part 1 — Directions on Using WebStorm (with GIT & Github)
A) Create Your Github Repository
1) Sign in at https://github.com
2) Create an account
From here on out you can do it later once you have your file ready as well
3) Click the + (top-right) → New**repository**.
4) Choose**Public** (unless told otherwise or don't want to). You can check Add a README or add it later in WebStorm.
5) Click Create **repository**. Copy your repo URL (it looks like https://github.com/username/nameofrepository) (GitHub, n.d.).

B) **Clone** the **Repository** in WebStorm
1) On GitHub, click Code → HTTPS → copy the .git URL (GitHub, n.d.).
2) In WebStorm: Get from VCS → paste URL →**Clone** (JetBrains, n.d.). 
4) If prompted, sign in to GitHub and confirm WebStorm detects **GIT**(JetBrains, n.d.).


This step can be done after any (THIS IF YOU HAVE A FILE IN WEBSTORM)
C) Add a New File in WebStorm and Publish It to GitHub
A1) Create the file in WebStorm
1) In the Project pane, right-click the folder where you want the file.
2) New ▸ File (or pick a template) → name it (e.g., notes.md) → Enter.
3) Add your content and Save.

A2) Commit the new file (local snapshot)
1) Open **Git** ▸ **Commit** .
2) Make sure your new file is checked.
3) Write a clear message, e.g., Task: add notes.md → **Commit** (or **Commit** and **Push**).

We will now go over push so you aren't confused about what to do with the file
3) Push to **GitHub** (publish)
* If you chose **Commit** only: **Git** ▸ **Push** → confirm **branch** (usually main) → **Push**.

Refresh your repo on **GitHub**; you’ll see the new file.
If your project isn’t connected to **GitHub** yet
VCS ▸ Share Project on **GitHub** (or Git ▸ GitHub ▸ Share) → sign in → repo name → Share.
WebStorm will create the **remote**, push your **commits**, and open the repo.


D) Add/Edit README.md in WebStorm
1) In Project pane: right-click repo root → New ▸ File → README.md.
Paste a document.
Save.

The use of clear, scannable README documentation aligns with the principles of user-focused writing (headings, lists, concise language) in Murach's guidelines for writing for the web (Ruvalcaba & Boehm, 2022, ch. 16).

THIS IS IF YOU ARE EDITING IN THE README FILE
E) **Commit** Your Changes (Local Snapshot)
1) Open **Git** ▸ **Commit**.
2) Write a concise message, then **Commit**.

Frequent, descriptive **Commits** create an understandable history and support collaborative quality—paralleling the book’s emphasis on iterative improvement and validation (Ruvalcaba & Boehm, 2022, ch. 2; ch. 16).

F) Push to **Github** (**Publish** to the Cloud)

**Git** ▸ **Push** → confirm main → **Push** (GitHub, n.d.).
Refresh the **GitHub** repo page to verify your updated README.md.


G) Keep in Sync

**Pull** = **Fetch** + **Merge remote** changes (Git, n.d.).

**Fetch** only downloads updates so you can review before merging (Git, n.d.).

Regular syncing and validation reflect the book’s testing/quality mindset (Ruvalcaba & Boehm, 2022, ch. 2).


References

Part 2 — Glossary 

**Branch** — A branch is a separate line of programming that can be modified without affecting the main code (Git, n.d.).

**Clone** — An exact copy of a **remote** repository (Git, n.d.).

**Commit** — A saved snapshot of changes done on the file that could be a message describing what/why (Git, n.d.).

**Fetch** — Data is downloaded from a **remote** without merging into your current **branch** (Git, n.d.).

**GIT** — A distributed version control system for tracking file changes and collaborating (Git, n.d.).

**Github** — A website that hosts Git Repository data and adds collaboration features (pull requests, issues, reviews) (GitHub, n.d.).

**Merge** — Combines changes from one **Branch** into another, creating an integrating **Commit** (Git, n.d.).

**Merge Conflict** — When **GIT** can’t automatically combine edits and requires manual resolution (Git, n.d.).

**Push** — Sends your local Commits to a **Remote Repository** on **Github** (Git, n.d.; GitHub, n.d.).

**Pull** — **Fetches** **remote** changes and **Merges** them into your current **Branch** (Git, n.d.).

**Remote** — A named reference to a **Repository** hosted elsewhere (e.g., origin on **Github**) (Git, n.d.).

**Repository** — The project folder tracked by **GIT**, including files and full history (Git, n.d.).


References

Git. (n.d.). Downloads. https://git-scm.com/downloads

GitHub. (n.d.). Creating a new repository. https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

JetBrains. (n.d.). WebStorm download. https://www.jetbrains.com/webstorm/download/

Ruvalcaba, Z., & Boehm, A. (2022). Murach’s HTML and CSS (6th ed.). Mike Murach & Associates.
