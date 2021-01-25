github fork: Creates a copy of the repository on your GitHub account. The original repository becomes the upstream repository of the fork, of which you can make pull requests to merge commits from the fork repository to the upstream repository.

git clone: Creates a local copy of the repository on your local machine. You can push any commits on your local repository to the remote repository with git push.

git branch: Creates a new head pointer to your commits. The new branch will have the same commits of the branch it is branched off of, but any new commits created on that branch will stay on that new branch and won't be reflected in the original branch, unless the commits are merged or cherry-picked.