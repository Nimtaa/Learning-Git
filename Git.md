Initializing the directory
```
git init
```
stage: State of the modified or new file that is ready to be committed.
everything you have changed --> Stage --> Commit
```
git add [FileName]: staging the file
```
Staging all files in directory
```
git add -A
```
Every commit has uniqe code
```
git commit -m "commit message"
```
Log things you have done until now
```
git log
```
Difference between head and current state
HEAD : last committed state
```
git diff HEAD
```
Difference between staged and current state
```
git diff --staged
```

Take out the file from stage
```
git reset [FileName]
```

Replace the file with it's last committed version for example if you had corrupted a file.
```
git chekcout -- [FileName]
```

Remote
-------------------------
Git is distributed system so we can add remote host, push or pull our code to that location.


Clone a project from remote ( github || gitlab || other locations )
```
git clone [SSH or HTTP Address]
```

Clone repository from another remote machine through ssh   
remote machine needs to be ssh-enabled.  
```
git clone git+ssh://machineName@ipAddress/path/to/required/directory
```

We can list,add remotes.
```
git remote
```
```
git remote add origin [Address]
```

If a same file modified by two or more different users we have conflict when push or pull.
Git detects the conflict(for example rejects push objects), if modifications located at same place.
otherwise git merges modifications.

Tag
-------------------------------
We can tagging the different parts of a project, for example different release versions of a project.

List the all tags.
```
git tag
```
Add tag, We can add tag to a specific commit by mentioning the commit hash string too.
```
git tag -a [annotation] -m "your message"
git tag -a V2.0 -m 'tag added'
```
Show  commit of the tag.
```
git show [tag_Name]
```
