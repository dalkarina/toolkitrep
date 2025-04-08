### My info 
- **Name:** Karina Dal
- **Date:** 08.04.2025
- **Gender:** Woman
- **Age:** 21
- **Course:** Basic Toolkit for Bioinformatics Research
- **Major:** Bioinformatics
- **University:** Jagiellonian University in Cracow
- **Favourite food:** Fried Onigiri, Sago soup, Ketchup Pringles 

### The concept of GIT
**Git is a version control system that is used to track changes in the code.**
**In git, there are some key concepts to be understood:**
1. **Repository** is a project folder tracked by git.
2. **Commit** is a saved snapshot of changes
3. **Branch** is a parallel version of the code
4. **Remote** is a hosted repository


### Git Commands Summary

**GIT -"-** 

- **init** - starting a new repository
- **clone (url)** - copying a remote repository
- **add (file)** - stage changes
- **add .** - stage all changes
- **commit -m "message"** - save changes with a message
- **push** - upload to remote
- **pull** - download updates 
- **push origin main** - push to remote if linked to GitHub
- **status** - check file status
- **log** - check commit history 
- **branch** - list branches
- **remote -v** - check linked remote repositories
- **branch -m x y** - rename branch x to y
- **remote remove origin** - deletes old remote
- **checkout -b (branch)** - create and switch to new branch
- **restore (file)** - discard unstaged changes
- **reset --hard HEAD** - deletes all uncommitted changes 
- **revert (commit-hash)** - undoes a specific commit 

### TIPS AND TRICKS
1. Commit often and declare clear messages so you understand what was going on in the future when you'll come back to your previous code
2. Pulling before pushing is optimal to avoid conflicts
3. Usage of few branches is optimal to test new features or to fix something
4. To successively complete the given task of creating a repo, you have to: 
- 1. open git bash and type "git init"
- 2. or else, you can create a repo online and then use git clone (repourl) to link it
- 3. create your desired files
- 3.5. git status checks the status 
- 4. save your file
- 5. do git add (file-name) to add the file to staging 
- 6. git commit -m "comment" to commit your staged work with a message
- 7. git push origin main to push to the remote 

