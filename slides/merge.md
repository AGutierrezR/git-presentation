### Fusionando ramas (Merging)

Se pueden fusionar ramas en situaciones donde se quiere implementar los cambios que se han realizado en una rama en otra rama diferente

Por ejemplo, después de crear y testear una nueva feature en el proyecto, querrás implementar dichos cambios en una rama estable del proyecto (puede ser **develop**) 

Para realizar el merging de una rama diferente a tu rama actual se puede usar el comando:

```bash
git merge <branch-name>
```

<br/>

### Eliminando un branch

Para eliminar un branch, se usa el comando **git branch** con la opción **-d**:

```bash
git branch -d <branch-name>
```