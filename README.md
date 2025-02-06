1 - to remove locally branch 
    git branch -d dev 
    git branch -d test
    (-d) if there are unmerged changes in the branch don't remove 

2 - to remove remotely branch 
    git push origin --delete dev
    git push origin --delete test 

checkout another branch without commit
changes 
    git stash
    git checkout test 
    
