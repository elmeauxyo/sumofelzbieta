# sumofelzbieta

Do the following to understand the basics of git collaboration (all of the following is to be done in the terminal on your computer!):

1) Navigate to your sumofelzbieta folder: cd something/something/sumofelzbieta
2) Checkout the name of my branch here (task/git-basics): git checkout task/git-basics
3) Pull down the latest changes to that branch: git pull
4) Make a new branch off of my branch: git checkout -b task/my-new-branch
5) Create a new file in this project folder.  Fill it with a message saying hi to me (any file of any type is fine, such as .txt).
6) Add that file to be indexed in the git repo (here the period means add all files to the repo): git add .
7) Commit your changes in those files to the git repo with a commit message: git commit -am "Adding a new file to say hi!"
8) Push up those changes to the cloud! (after you do the "set upstream" option you will be able to just say "git push" instead of all this junk each time): git push --set-upstream origin task/my-new-branch
9) Go to the GitHub UI and create a new Pull Request for me to review your changes.
