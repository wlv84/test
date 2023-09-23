# test the feature branch workflow as below
0. download origin into local pc
1. commit changes in README.md from local main branch
2. create local feature0 branch before commit more changes in README.md from feature0 branch
3. commit more changes in README.md from local main branch
4. rebase feature0 onto main before merge feature0 to main to resolve merge conflicts and push to origin
5. create local feature1 branch before create test1.txt and commit a series of changes in test1.txt
6. create local feature2 branch before create test2.txt, commit a series of changes in test2.txt, and push to origin
7. merge feature2 to main with a pull request in origin to form a diverged development fork
8. upon pulling updates from origin/main into local pc, rebase feature1 onto main before merge feature1 to main and push to origin

in summary, 4 shows conflicts from modifying one file from different sources, while 9 shows no conflicts from modifying two files from different sources
