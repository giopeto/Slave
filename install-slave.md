# 		Create

### git init
### git add .
### git commit -m "First commit on slave"
### #git remote add origin remote-repository-URL
### git remote add origin https://github.com/giopeto/Slave.git
### git remote -v
### git push origin master


# 		Add Upstream

### # List the current remotes
### git remote -v

### Set a new remote
### git remote add upstream https://github.com/giopeto/Master.git

### # Verify new remote
### git remote -v


### # Grab the upstream remote's branches
### git fetch upstream


### # List all local and remote-tracking branches
### git branch -va

### # Check out our local master branch
### git checkout master

### # Merge upstream's master into our own
### git merge upstream/master