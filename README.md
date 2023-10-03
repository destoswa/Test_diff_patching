# Test_diff_patching

## In order to create a patch:
- Make all the modifications to the files
- On a command line, go to the root of the cloned repo (where the `.git` folder is)
- You can enter the command `git.diff` to visualize the changes (not necessary)
- Enter the command:
```
git diff > name_of_patch.patch
```

## In order to apply the patch:
- On a command line, go to the root of the cloned repo (where the `.git` folder and the patch are)
- Enter the command:
```
git apply name_of_patch.patch
```