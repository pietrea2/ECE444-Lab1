Adam Pietrewicz 

Activity 5 (Rebase) Screenshots/notes:
1. First I did "git rebase rebase" while on the develop branch
2. A merge conflict within README appeared, so I manually fixed all merge conflicts
3. develop git log became: ![image](https://user-images.githubusercontent.com/60241038/133941127-df8aeead-60d1-4f6b-afad-f8448865c559.png)
4. Next, i used "git rebase -i" on the developement branch to change the order of commits: 
![image](https://user-images.githubusercontent.com/60241038/133941206-ae459931-9926-44d1-877a-69259fc6fcd5.png)
![image](https://user-images.githubusercontent.com/60241038/133941208-745d5a41-1968-4f57-9105-7432d6043f92.png)
5. However I faced Merge Conflicts again, so I fixed them manually: ![image](https://user-images.githubusercontent.com/60241038/133941225-429cbf67-ea7d-4b8d-9f8c-4173cd2107f3.png)
6. But after doing this, the commit log of develop was "c3, c4", so I re-did the rebase command
7. On the developement branch, I used "git rebase -i -last commit on develop before i made rebase branch-": ![image](https://user-images.githubusercontent.com/60241038/133941350-68951406-0f7a-4e0a-87ba-04d52fcecb67.png)
8. Worked on manually fixing all Merge Conflicts again
9. Finally this rebase worked, develop's git log became re-ordered to: ![image](https://user-images.githubusercontent.com/60241038/133941370-e92dfb0e-c9d2-4bfc-80f2-8a97251d1e6a.png)
10. The branch rebase has git log: ![image](https://user-images.githubusercontent.com/60241038/133941383-1e4e530f-2657-4a8f-ac8a-1e2114f0fdd0.png)
