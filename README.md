**CSCI 5828 – Spring 2018**

**Homework 2**

**Team Member: Yihua Shi, Xueyan Wu, Yijun Zhang**

**Due: by 11:59 PM MST on Monday, February 19, 2018**

Git command:
1. git init[initialize the empty repo]
2. vim README.md[create the readme file]
3. git add .
4. git commit -m "0"

5. vim test.txt[create test.txt file for further updates]
6. git add .
7. git commit -m "1"

8. vim test.txt[edited test.txt file]
9. git add .
10. git commit -m "2"

11. git checkout -b "bug-fix"[Switched to a new branch 'bug-fix']
12. vim test.txt[edited test.txt file]
13. git add .
14. git commit -m "3"

15. vim test.txt[edited test.txt file]
16. git add .
17. git commit -m "4"

18. git merge master
19. vim test.txt[fix conflict in test.txt file]
20. git add .
21. git commit -m "5"

22. vim test.txt[edited test.txt file]
23. git add .
24. git commit -m "6"

25. git checkout 3417b5aabccd96208dc7d207316ae115fa2a1b87[checking out to commit "4"]
26. git checkout -b "bug-fix-experimental"[Switched to a new branch 'bug-fix-experimental']
27. vim test.txt[edited test.txt file]
28. git add .
29. git commit -m "7"

30. vim test.txt[edited test.txt file]
31. git add .
32. git commit -m "8"

33. vim test.txt[edited test.txt file]
34. git add .
35. git commit -m "9"

36. git checkout master[Switched to branch 'master']
37. vim test.txt[edited test.txt file]
38. git add .
39. git commit -m "10"

40. git checkout bug-fix[Switched to branch 'bug-fix']
41. git merge bug-fix-experimental
42. vim test.txt[fix conflict in test.txt file]
43. git add .
44. git commit -m "11"

45. vim test.txt[edited test.txt file]
46. git add .
47. git commit -m "12"

48. git checkout master[Switched to branch 'master']
49. git merge bug-fix
42. vim test.txt[fix conflict in test.txt file]
43. git add .
44. git commit -m "13"

45. git add .[add README and git image file]
46. git commit -m "14"
