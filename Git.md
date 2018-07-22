Hi
There is some practical git instructions from this persian course.
https://faradars.org/courses/fvgit9609-managed-distributed-edition-using-git
instructor: @jadijadi

  git init: initializing the directory

  git add [FileName]: staging the file
stage: State of the modified or new file that is ready to be committed.
everything you have changed --> Stage --> Commit

  git add -A: staging all files in directory
  git commit -m "commit message"
every commit has uniqe code

  git log: log things you have done until now
----------------------------------------------------------
  git diff HEAD: difference between head and current state
HEAD : last committed state
  git diff --staged: difference between staged and current state
  git reset [FileName]: take out the file from stage
  git chekcout -- [FileName]: replace the file with it's last committed version
----------------------------------------------------------
