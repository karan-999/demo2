This is a demo file to check how one can add repo in github from a local machine where they both have different histories 

**first** :If you haven't made any changes locally, you can use git pull to bring down any new commits and add them to your master.

`git pull origin master`

If you have made changes, and you want to avoid adding a new merge commit, use git pull --rebase.

`git pull --rebase origin master`


and if you get error like: <br>
`error: src refspec main does not match any
error: failed to push some refs to 'github.com:karan-999/demo2.git'`
