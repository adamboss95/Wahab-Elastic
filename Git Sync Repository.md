1. Open Git -> git repository
2. Create Repository
3. Open CMD, 
run 
```
ssh-keygen
```
4. copy the .pub file path and display it using cat /path.pub
5.  copy the displayed content and open git settings -> ssh and gpg keys -> new ssh key (if ssh is not already there)
6. give it a name, and paste the content of .pub there.
7. now go back and open repository that we created in git
8. click code -> ssh and copy
9. open cmd, run this command
```
git clone paste-the-copied-ssh-here
```
10. once the directory is cloned on desktop or whatever path, we can just copy data from obsidian and paste into that folder.
11. open obsidian, and open the cloned folder using obsidian
12. on obsidian -> settings -> community plugins -> browse -> search git -> install git -> go to its options -> set the time interval for syncing
13. then ctrl + P, and search commit -> commit all changes.
14. directory is synced with git