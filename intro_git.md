Introduction to Git/Github
===
  - Version Control ( Create, Edit, Update, Save )

    Saving is where version control helps but creating points
      in time which you can name and refer to later and roll back to them.
  - Git is distributed version control.

  - Github is hosting service for git repositories. Bitbucket is
another good hosting service.
  - Who should use it?
    Anyone who is working with colleborated text files.
  - Tutorial [try.github.com](https://try.github.com)


Initial Commands
---
- `git init`
- `git config`
- `git help`


Commit
---
- Commit ID: sha-1 hash for the content
- Author name <email id>
- Date Timestamp
  - Commit Message (summary and description)

###Commands
- Make changes.
- Add them using `git add .`
- Commit changes using `git commit -m "<Descriptive Message here>"`

###Message
One line summary and a descriptive paragraph explain what are the changes.

####Do's
- It should be in present tense.
  e.g "Fixes admin authentication bug"
- Short single-line summary less than half a line.
- Optional complete description could be there in a paragraph for larger
  commits.
- Try to have Line break after every 80 characters.
- You can use bullet points "\*" "-" in the commit description.
- Commit subject can have tags: bugfix, ticket number typo
e.g. "bugfix:"
     "#4830: " Jira ticket number

####Don'ts
- Not descriptive.
  e.g "Fix typo"
- Don't make them too general.
  e.g "Update login code"
- It shouldn't be in the past tense.
  e.g "I fixed a bug" They aren't about me.
- Large sentences explanation.
  "This Commit changes javascript css and html to add new buttons which send ajax requests to fetch product informations"
  "Fetches and Displays Product information \n Updated markup to add buttons clicking
them sends an ajax call which fetches information about the product as a json object"


Git Log:
---
`git log <options>`

####Options
1. `-n number of commits`
2. `--since=2014-06-21`
3. `--until=<yyyy-mm-dd>`
4. `--author="Wasim"`
5. `--grep="Typo"`


Git Interels
---
Three tree arch.

1. Working
2. Staging Index (Used for staging multiple files to be commited)
3. Repository

*Working and repository you checkout from repository and you commit into
repository from working tree.*


Github
---
1. `git remote add origin https://github.com/user/repo.git`
2. `git remote -v`
3. `git push -u remotename branchname` Remote and branch name are optional
4. `git pull` `git fetch && git merge remotename/branchname`


Refferences
---
1. Git http://git-scm.com/
2. [PSD support] (https://cloud.githubusercontent.com/assets/2546/3165594/55f2798a-eb56-11e3-92e7-b79ad791a697.gif)
3. Mac GUIs http://git-scm.com/download/gui/mac
4. Talks http://vimeo.com/album/2763106
5. Tutorial [Try Git](http://try.github.com/)
