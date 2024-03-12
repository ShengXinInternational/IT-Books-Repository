# Git / GitHub
They are very important for a programmer. They are designed for version control and collaberation, and Github is also good for project management.
I hope I can get the Github foundation certification as soon as possible.

## Git
### Git Terminology
- Working tree (tree = directory)
- Repo (bare repository)
- Hash (160 bits long)
- Object (Blob, tree, commit, tag)
- Commit
- Branch (head, main, HEAD: the head of the current branch)
- Remote (origin)
- Commands, subcommands, options

### Git command
- git checkout -- <file> (get the specific file from repo after "rm <file>", no work after "git rm <file>", but we can use "git reset HEAD <file>" first to get the file from history)
- git reset --hard HEAD^ (then "git checkout -- <file>" to correct miscommit )
- git revert --no-edt HEAD (undoes what you just did, the HEAD is not changed)
- git checkout <commit> . (go to sepecific history commit.)


## GitHub
### Key features:
- Issues
- Discussions
- Pull requests
- Notifications
- Labels
- Actions
- Forks
- Projects
#### Foundation
- Gist (gists are a simplified way to share code snippets with others. Every gist is a Git repository)
- 