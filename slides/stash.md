# Commits sin branch con Stash

El **Stash** es un lugar donde podemos almacenar commits que podemos usar luego sin tener que crear una rama para esto.

```bash
git stash [-m "Mensaje descriptivo"]
```

Con esto, todos los cambios que estén en el **Working Directory** y en el **Staging Area** seran guardados en el Stash

Para ver la lista de Stash solo hace falta escribir

```bash
git stash list
```

Para "destapar" algun stash solo hace falta usar el comando

```bash
git stash pop <stash-hash>
```
