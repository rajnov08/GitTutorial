# gitutorial 
https://www.udemy.com/course/git-and-github-crash-course-creating-a-repository-from-scratch/learn/lecture/10650294#overview

First Clone repo, Create a file
Do git status to see untracked changes
//Below command will add the untracked file to staging
git add README.md 
//Do once below command 
git config --global user.email "rajnov08@gmail.com"
git commit -m "Commit 1"
//Git status after above command will show no untracked changes but still no code on Github.
git push origin master
//Above command will push the commit to github cloud. 
//to see changes in code before adding file to staging
git diff Readme.md

//to see log of commits
git log 