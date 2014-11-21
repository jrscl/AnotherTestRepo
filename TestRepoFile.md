## This a markdown file
I have set it up as part of testing the whole Git process for updating a Repo on GitHub, ie.
* on GitHub - first create AnotherTestRepo on GitHub (with a ReadMe file) and copy the link to the Repo
* in Git Bash - $ git clone <link to repository - which can be pasted by pressing the Insert key>
* in Git Bash - $ cd AnotherTestRepo
* in Git Bash - $ touch TestRepoFile
* in Windows Explorer - navigate <username>/AnotherTestRepo folder and open TestRepoFile in Notepad
* in Notepad - edit the file (as I am doing right now) and save it
* in Git Bash - $ git status - to see file waiting to be added to the staging area
* in Git Bash - $ git add TestRepoFile.md - to add it to the staging area
* in Git Bash - $ git commit -m "add TestRepoFile.md to the repository"
* in Git Bash - $ git push origin master - to push it up to GitHub (requires input of GitHub username and password)
* on GitHub - check file has been added to AnotherTestRepo