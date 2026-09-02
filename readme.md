## Commands


```
git init							# initializes the repo
git add <fileName>					# Add specific file to stage
git add -A							# Adds all files not on ignore to stage, and removals
git commit -m "<msg>"				# Commits with inline msg
git checkout -b <name>				# create new branch
git checkout <branchName>			# Change to target branch
git status							# HELP!
git merge <branchName>				# integrate target branches commit history

git tag -a '<semVer>' -m '<msg>'	# make a tag
git remote add <origin> <url>		# connect to github
git pull origin <branchName>		# Fetches and merges changes from target remote branch
git push origin <branchName>		# Integrates local branch into remote
git push origin --tags				# tags push seperately

git reset --hard <id>				# send branch to target id. [soft, mixed, hard]
git log								# git history of commits
git reflog							# show last few git commands and related ids
```
