# mlops-activity-1

MLOps course activity for Git &amp; Github

## Commands Used

1. `git init` - Initialized a git repository
2. `git add .` - Added all files to the staging area
3. `git commit -m "message"` - Commited the changes to the repository
4. `git remote add origin https://github.com/Umar-Waseem/mlops-activity-1.git` - Added the remote repository
5. `git push -u origin main` - Pushed the changes to the remote repository
6. `git checkout -b dev` - Created a new branch called dev
7. `git push -u origin dev` push dev branch to remote
8. `git checkout -b test` - Created a new branch called test
9. `git push -u origin test` push test branch to remote
10. `git pull origin main` - Pulled the changes from the remote repository
11. `git checkout -b {member-name}-branch` - new branch created by both members
12. both members made relevant changes in their respective branches
<!-- member name branch merged to dev branch -->
13. `git checkout dev` - switched to dev branch
14. `git merge {member-name}-branch` - merged the changes from member branch to dev branch
15. `git push origin dev` - pushed the changes to the remote repository

## Instructions

1. Create a virtual python environment using

```
python -m venv venv
```

2. Activate the virtual environment

```
source venv/bin/activate
```

3. Install the required packages

```
pip install -r requirements.txt
```

4. Run the main python script

```
python main.py
```
