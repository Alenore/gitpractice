  606  git init
  
  607  git config --local user.email "herbin.thomas@popschool.fr"
  
  608  git add .
  
  609  git commit -m "initial commit"
  
  610  git checkout -b develop
  
  611  git checkout -b feature/nav-bar
  
  612  git commit -am "adding navbar menu"
  
  613  git commit -am "changing background color and font color for navbar"
  
  614  git rebase develop
  
  615  git checkout develop
  
  616  git merge feature/nav-bar
  
  617  git checkout -b feature/footer
  
  618  git stash
  
  619  git checkout master
  
  620  git checkout develop
  
  621  git checkout -b release
  
  622  git checkout master
  
  623  git merge release
  
  624  git checkout -b hotfix
  
  625  git commit -am "adding my_menu id on navbar's ul"
  
  626  git checkout master
  
  627  git merge htofix
  
  628  git merge hotfix
  
  629  git checkout hotfix
  
  630  git checkout develop
  
  631  git merge hotfix
 
  632  git checkout feature/footer
  
 
  633  git stash list
  
  634  git stash pop stash@{0}
  
  635  git commit -am "adding footer and a paragraph"
  
  636  git commit -am "changing background color of footer"
  
  637  git rebase develop
  
  638  git checkout develop
  
  639  git merge feature/footer
  
  640  git checkout -b feature/content
  
  641  git commit -am "adding content of page in a section"
  
  642  git commit -am "changing background color of the content section"
  
  643  git rebase develop
  
  644  git merge develop
  
  645  git checkout develop
  
  646  git merge feature/content
  
  647  git checkout release
  
  648  git merge develop
  
  649  git checkoutj master
  
  650  git checkout master
  
  651  git merge release
