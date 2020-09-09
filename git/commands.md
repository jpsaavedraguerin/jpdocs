### Comandos repositorio local

```pwsh
#crear repositorio
mkdir <nombre_directorio>   #crea un directorio
cd <nombre_directorio>      #entra en el directorio
git init                    #inicia un repositorio en el directorio actual

#agregar archivos a stage area
git add .

#crear commit
git commit -m "Mensaje_descriptivo"

#ver registro de commits
git log

```




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
```

### Cambiar url de repositorio remoto
```pwsh
#Set upstream url
git remote --set-upstream <nombre_rep_remoto> <url> # Si no se especifica protocolo, asume SSH
```
```pwsh

# quick view to a branch
git checkout origin/<branch_name>
# clone remote branch
git checkout <remote_branch_name> #git will create a local tracking branch
```
