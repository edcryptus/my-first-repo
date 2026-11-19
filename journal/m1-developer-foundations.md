# Dev 1 - Developer Foundations Journal

## 2026-11-10, Day 1: Set up your tools

**What I built:**

**Answers to the Check yourself questions:**

What is a terminal, and why do developers use it instead of clicking?
- The terminal is a tool used by developers to perform actions instead of clicking. Developers use the terminal to do these actions because it basivally much more faster than manually clicking buttons, since typing a script can achieve the same thing.
What does Git do for you?
- Git is a tool that help me track the history of my files and will also allow me to revert back to my early version when needed.
What is the difference between Git and GitHub?
- Git is basically a tool that exists on your local device for tracking your file history, while GitHub is an online platform that allows you to store your projects online and make it possible for the public to access your work
What is Markdown, and what do you use it for?
- Markdown is usually used to format plain text using symbols. It is used so users can easily write formatted plain text files quickly using simple symbols like # if you need text to be a heading.
Why turn on 2FA?
- Turning on 2FA for your GitHub account adds an extra layer of protection, even if your password gets stolen.
**What went wrong and how I fixed it:**

**What I changed or tried beyond the instructions:**

**What I still do not understand:**

## 2026-11-10, Day 2: Move around in the terminal

**Commands:**
pwd - Display the current directory I am using
ls - Show the list of all existing files inside the directory
cd - Switch or change to another directory
mkdir - Create a new folder
touch - Create a empty file
cp - Copy a file to another
mv - Move and rename a file
rm - Delete a file
rm -r - Delete a folder
ls -R - List all files and folders including all that inside of every folders


**What I built:**

**Answers to the Check yourself questions:**

What do pwd, ls, cd, mkdir, touch, cp, mv and rm do?
- Pwd display the current directory I'm using, ls command show all the existing files in your current directory, cd allow you to switch to a different directory, mkdir is a command use to create a folder, cp is for copying a file, mv is a command for renaming or moving a specific file, rm let you delete a folder.
What is the difference between an absolute and a relative path?
- Absolute path always start from the top while relative path will start where you currently are.
What do . and .. mean?
- . means here or which folder you currently accessing and .. means the folder above your folder or the folder where your current folder you currently accessing.
Why is rm -r dangerous?
- rm -r is a dangerous command because it is impossible to get deleted folders back, since they do not go to the Recycle bin.
How do you fix "No such file or directory"?
- I fix it by checking the syntax or the spelling if what I typed are correct.
**What went wrong and how I fixed it:**
- The exercise asked me to do touch docs/readme.txt and touch code/app.txt, but it only shows error. I scanned the lecture and do a research and learned that touch is command does not work in Windows Powershell (https://bobbyhadz.com/blog/touch-is-not-recognized-as-internal-or-exernal-command). I follow the documentation and open Command prompt and entered npm install touch-cli -g then the touch command are now working properly.
**What I changed or tried beyond the instructions:**
- For touch, I troubleshoot it first from the command prompt using npm install touch-cli -g before doing the touch
**What I still do not understand:**

2026-11-10, Day 3: Git basics

**What I built:**

**Answers to the Check yourself questions:**

What is a repository? What is a commit?
- A repository is a folder that the git is tracking that remember all the changes within the file inside the folder. Commit is a command that let you to take a 'snapshot' of your folder so you will be able to revert any changes if something wrong happened.
What are the working folder, staging area and history?
- Working folder is where you edit your files, staging area is where you choose all changes for you next commit, and history hold all saved commits.
Why does Git have both add and commit?
- Git have both command because they serve different purpose and use in two different things. The 'add' command makes us choose which among the changes will be included to your commit, and 'commit' command save the one you add to your commit history to serve as your back up especially when needed.
What makes a good commit message?
- A good commit message should be short and direct to the point about what the commit does.
How do you undo an uncommitted change?
- You can undo a uncommitted change using the command 'git restore <filename>'
Why must you never commit a password, even if you remove it later?
- Password is a private key and once you commited it even though you deleted it, history still show it.
**What went wrong and how I fixed it:**

**What I changed or tried beyond the instructions:**

**What I still do not understand:**

2026-11-10, Day 4: GitHub

Step 1: Creating a GitHub Repository
- I created a public GitHub repository named `my-first-repo` while leaving the README and `.gitignore` options unchecked.

Step 2: Pushing My Local Repository to GitHub
- I ran the following commands in my terminal: `git remote add origin https://github.com/edcryptus/my-first-repo.git`, `git branch -M main`, and `git push -u origin main` to connect my local repository to GitHub and push my files.

Step 3: Creating a README.md File
- I created a `README.md` file to describe my repository. I added a title and a few lines explaining what the repository is about.

Step 6: Editing a File Directly on GitHub
- I edited `README.md` directly on GitHub using the pencil icon. I added a new line and committed the changes on GitHub.

Step 7: Pulling Changes from GitHub
- I ran `git pull` in my local repository to download the updated version of the README file from GitHub.

**What I built:**

**Answers to the Check yourself questions:**
What are a remote, origin, push and pull?
- A remote is a copy of your repo online, and origin is the default name of your main remote repository. Push means sending your commits from your local device to your remote, while pull means retrieving updates from your remote to your local machine.
Why use GitHub if you already have Git?
- GitHub hosts your repo online, while Git is only for your local machine. Using GitHub is super convenient because you can access your repo even if you use a different device. Another good thing about using GitHub is that even if your device breaks down, you still have a backup of your project.
What goes in a README and who reads it?
- Developers usually access the README file first because it defines what your repo is and answers "What is this?" and "How do I use this?".
What must never be pushed to a public repo?
- Secrets, such as passwords or any personal data, must not be pushed to a public repo because even if you delete them, the commit history will still show them.
What does "rejected, fetch first" mean and how do you fix it?
- The "rejected, fetch first" error means that the remote repository contains changes that are not yet present in your local repository. You need to fetch and integrate the latest changes before pushing your commits.
**What went wrong and how I fixed it:**

**What I changed or tried beyond the instructions:**

**What I still do not understand:**

2026-11-10, Day 5: HTML
**What I built:**

**Answers to the Check yourself questions:**
What is the difference between a tag, an element and an attribute?
- Tag is the <> that tell the browser what is it, element are the whole line from opening tag to closing tag, and  an attribute is the extra information you add inside the opening tag to tell the browser what it is specifically.
Which tags create a link, an image, a list and a table?
- <a> create a link, <img> is the tag that create image, <ul>, <ol>, <li> are the tag for list and <td>, <tr>, and <table> are the tag used for creation of table.
Why does an image need alt?
- alt is necessary especially for screen reader because it serve as a description that says what is that img when the image failed to load.
Why choose headings by meaning and not by size?
- Because the main use of headings are literally just for telling the visitors what the website and each sections are all about.
What is a semantic element? Name three.
- Semantic element are the specific tag that tell us the specific section of the website is for. Three of the most common semantic elements are <main>, <header>, and <footer>.
**What went wrong and how I fixed it:**

**What I changed or tried beyond the instructions:**

**What I still do not understand:**