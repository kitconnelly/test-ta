# GitHub Flow Exercise

## Step 1
- Select a team member who will create a repository (be sure to include a ReadME) in the Teams GH organization
- Make the repo name: 'Team-#-GH-Flow' with your appropriate team number
- Invite all other members of the team

## Step 2
- Once all team members have access to the repository, clone it
- Easiest to clone through terminal window with 'git clone *link*' command
- NOTE: Be sure if you have GitHub set up through SSH that you use the proper link

## Step 3
- Each team member will write an issue for another team member
- The task of the issue is to simply create a text file with your name (ex: 'Kit.txt', or 'Sovann.txt')
- Each team member will then *assign* the proper team member to the task

## Step 4
- Before completing the task, each team member will create a branch for said task
- This branch can be created in terminal window with 'git checkout -b *branch_name*'
- Now, each team member can complete the task on the appropriate branch
- If you do not know how to create a text file, you can use 'touch Kit.txt' (replace Kit with your name)

## Step 5
- With the file created, each member can now commit and push their branch to the repository (include 'Closes *issue number*' in the commit message)
  - To make a commit, remember to add your changes ‘git add .’, commit with ‘git commit -m “message”’. Pushing new branches is a little bit different from pushing changes to an existing branch. To push a new branch (i.e. the one you created in step 4), run  ‘git push -u origin *branch_name*’
- Now on GitHub, create a pull request with your new commit, assigning the writer of the issue to the pull request
- Each team member will review a request and merge the commit (be sure to delete the branches after merging)
- NOTE: If there is a merge conflict, please let us know. That means there was an error in branching or you edited the same file.
