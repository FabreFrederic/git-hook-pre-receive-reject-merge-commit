# Rejects a push if it contains merge commits from remote tracking branch 
# into the same local branch are not allowed.
# This kind of merge commits are created when the user is pulling 
# the remote repository with merge default option. To update a git local repository,
# we have to use 'pull --rebase' or 'pull --preserve'
# 
# The script compares the commits messages with a pattern
