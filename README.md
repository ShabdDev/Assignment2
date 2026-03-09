Assignment 2
 
Tasks To Be Performed: 
1. Create a Git working directory with feature1.txt and feature2.txt in the master branch 
2. Create 3 branches develop, feature1 and feature2 
3. In develop branch create develop.txt, do not stage or commit it 
4. Stash this file and check out to feature1 branch 
5. Create new.txt file in feature1 branch, stage and commit this file 
6. Checkout to develop, unstash this file and commit 
7. Please submit all the Git commands used to do the above steps

solution
1. cd Assignment2
2. git init
3. touch feature1.txt feature2.txt
4. git add .
5. git commit -m "feature1.txt and feature2.txt files are created in master/main branch"
6. git remote add origin https://github.com/ShabdDev/Assignment2.git
7. git branch -M main
8. git push -u origin main
9. git log
10. git branch develop
11. git branch feature1
12. git branch feature2
13. git checkout develop
14. touch develop.txt
15. git stash -u
16. git checkout feature1
17. touch new.txt
18. git add .
19. git commit -m "new.txt file is created in feature1 branch"
20. git checkout develop
21. git stash show
22. git stash show stash@{0}
23. git stash list
24. git stash pop
25. git add develop.txt
26. git commit -m "develop.txt file is committed in develop branch"
27. history
