FSD Lectorial Week 01 examples  

#from your terminal in your working folder:  
git clone https://github.com/rmit-fsd-2026-s1/lectorial01.git  
  
#to get latest changes
git pull  

Do not push changes back to this public repo, you have your own GitHub classroom repo to use.  

  
#side notes to use git in another repo:  
git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/your-repo/lectorial01.git  
git branch -M main  
git push -u origin main  


#to unlink the current remote repo
git remote remove origin

#to link with the next origin, e.g. GitHub classroom
1. Accept the invite. Once accepted, you will be given your own dedicated repo to submit your work like: https://github.com/rmit-fsd-2026-s1/git-and-github-fundamentals-dipto-pratyaksa-rmit.git  
2. Once you see the repo you use it to practice using git and upload your read me file.

git remote add origin https://github.com/rmit-fsd-2026-s1/git-and-github-fundamentals-dipto-pratyaksa-rmit.git  

git pull origin main --allow-unrelated-histories
git add README.md
git commit -m "practice with git"
git push --set-upstream origin main  
  
Please refer to GitHub documentation or seek tutor assistance.
