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

36. git log --graph --pretty=oneline --abbrev-commit

37. git merge --no-ff -m "merge with no-ff" dev

38. git stash
39. git stash apply
40. git stash drop
41. git stash pop
42. git stash list
43. git stash apply stash@{0}

44. git remote -v
45. git push origin branch-name
46. git pull
47. git branch --set-upstream branch-name origin/branch-name
48. git checkout -b branch-name origin/branch-name

49. git tag
50. git tag v0.1
51. git tag v0.2 commit_id
52. git show tag-name
53. git tag -a tag-name -m "message" commit_id
54. git tag -s tag-name -m "message" commit_id
55. git tag -d tag-name
56. git push origin <tagname>
57. git push --tags
58. git tag -d <tagname>
59. git push origin :refs/tags/<tagname>

