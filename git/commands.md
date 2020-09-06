### Clonar repositorio remoto en directorio local.

```pwsh
git clone <url> <local_dir>
```

### Clonar branch remoto en repositorio local

```pwsh
#clone repo
git clone <url> <local_dir>
# get all branches names
git branch -a
# quick view to a branch
git checkout origin/<branch_name>
# clone remote branch
git checkout <remote_branch_name> #git will create a local tracking branch

