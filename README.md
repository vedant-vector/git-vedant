# Practical of LMS Course Git & Git FLow
## Submission By Vedant Soni (Block-chain Trainee 2023)

### Aim:- 
Create one repository for practical and provide the link of it for review.

Work on below points:

1. Pull and Merge difference

- Make example of pull request and two branch merge event.

2. Rebase

- Try to rebase feature branch with master branch 

3. Change commit message

- Commit push on commit in feature branch and then change commit message

4. cherry pick

- Pick some commits from feature branch to master branch

5. Drop commit

- Remove some commit from feature branch.

### Below commands are used by me
#### 1. Pull and Merge difference
![Screenshot from 2023-01-10 18-35-21](https://user-images.githubusercontent.com/122250819/211728025-68d722d0-22c9-4c24-b58a-7d893e135e1d.png)

#### For merge
                  git merge feature-branch 

#### 2. Rebase
                  git rebase feature-branch 

#### 3. Change commit message
                  git rebase -i HEAD^ 
#### 4. cherry pick
                  git cherry-pick 81ca3b5   
#### 5. Drop commit
                  git rebase -i HEAD~4 
#### For detail submission is in PDF named "Vedant-Soni_Git-Practical"
