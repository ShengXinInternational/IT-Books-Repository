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

#### MardDown Syntax
- Italics * or _ \
   This is *italic* text \
   This is also _italic_text
- Bold text ** or __ \
  This is **BOLD** text, and __Another Bold__ text.
- Link to an image \!\[]()
- Link to website \[name](url)
- List (need space after the character) \
    Order lists start with numbers. \
    Unorder lists start with \_
- Table: \| and \_
  Header1|Header2
  -|-
  Hello|World
  amazing|cool
- Quote text \>
 > Hello world!
- code \` \
`code`
- code segment \```
```javascript
//this is javascript
var first = 1;
var second = 2;
var sum = first + second;
```
- cross-link issues and pull requests \#ID (no space, or else it is a header)

- Mention users and teams @\
@sheng0321
- task lists \- [] and \- [x] \
 \- [] todo \
 \- [x] done

 - slash commands \
 /code \
 /details
