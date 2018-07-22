Initializing the directory
```
git init
```
Everything you changed --> Stage --> Commit

Stage: State of the modified or new file that is ready to be committed.

Staging the file
```
git add [FileName]
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

HEAD: last committed state
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
