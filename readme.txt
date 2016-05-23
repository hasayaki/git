learning git

1. cd /e/Project
2. mkdir git
3. cd git
4. pwd
5. git init
6. ls -ah

// create readme.txt file in git directory

6. git add readme.txt
7. git commit -m "add readme.txt"
8. git status

// modify readme.txt and save

9. git status
10. git diff readme.txt
11. git add readme.txt
12. git status
13. git commit -m "modify readme.txt"

// modify readme.txt and save

14. git status
15. git checkout -- readme.txt

// modify readme.txt and save

16. git status
17. git diff readme.txt
18. git add readme.txt
19. git status
20. git reset HEAD readme.txt
21. git status

// modify readme.txt and save

22. git add readme.txt
23. git commit -m "modify readme.txt"

24. git log --pretty=oneline
25. git reset --hard HEAD^
26. git reflog
27. git reset --hard commint_id
28. git reset --hard HEAD^^
29. git reset --hard HEAD~100

30. git remote add origin https://github.com/hasayaki/git.git
31. git clone https://github.com/hasayaki/java.git

32. git checkout -b dev
33. git branch
34. git branch develop
35. git checkout develop

