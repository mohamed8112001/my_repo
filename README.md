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


//lab2
    
to list all tags ==> git tag

to delete tag remotely ==> git push origin  --delete v1.7
to delete tag locally ===> git tag -d v1.7  
 <img src='img.webp'>
