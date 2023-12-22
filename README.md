## ConfiguracionGit
Configuracion de Git.
#### implementar en git 
Debemos usar el siguiente comando 
```bash
git config --global -e
```
---

GNU nano 7.2                              /home/kan/.gitconfig      
  
##### Este es el archivo de configuración de Git por usuario.
[user]
        email = kan@gmail.com
        name = kan

Por favor, adapta y descomenta las siguientes líneas:
       name = Kan       
       email = kan@gmail.com
[init]
        defaultBranch = main
[color]
        u1 = true
[alias]
        s  = status --short
        c  = config --global
        lg = log --decorate --all --oneline --graph --abbrev-commit
        l  = log --graph --abbrev-commit   --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(b>
        a  = add .
[core]
        pager =
