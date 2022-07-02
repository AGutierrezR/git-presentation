# Git Alias

Git nos permite agilizar nuestro workflow utilizando Alias haciendo que `git checkout` sea `git co`

Para crear alias no existe un comando especifico, se debe hacer uso del comando `git config`

```bash {all|1|2|3|4|all}
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
```

Esto realizara una modificación en el archivo global `.gitconfig` y nos dara los alias para todos los proyectos. Si ingresamos al archivo `.gitconfig` veremos lo siguiente:

```plain {all|2|3|4|5|all}
[alias]
  co = checkout
  br = branch
  ci = commit
  st = status
```
