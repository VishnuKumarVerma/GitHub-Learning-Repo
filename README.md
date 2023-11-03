# GitHub-Learning-Repo

Author:-  Vishnu Kumar Verma
<br>
Readme is also updated with HTML syntax like above.

steps to start  the github:-

# first make the new folder in your desktop (wherever you want), then follow these steps👇👇👇
1.first clone the repo(after creating from the github) from the github through the command 
    git clone "link from https"

2. now run to enter into that one git folder.
    cd path directory 

3. to view the file in the repo folder which are exist already in that repo run ls(list status)
    ls

4. to view hidden files into your repo folder run 
    ls -Hidden

5. to view the status of the changes file run 
    git status
6. Types of the status/ or the flow of the code to final addition of the changed file:-<br> 
[change(modified)/newfile(untracked) -> add(staged) -> commit(commit the changes of file)]<br>

7. to commit all the changes
    git commit -m "(meassage of what the changes are made)

8. to add all the changes to final pushing stage
    git add .

    To make final push to our change from local folder to remote folder throgh this command:-

    git push origin main 

⚠️ To push the current branch and set the remote as upstream, use:-

    git push --set-upstream origin branchname

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

⚠️ to rever the particular commit use the below command:-

    git reset --hard HEAD~1

then run:-

    git push origin HEAD --force

to push the changes forcefully