### Creando una nueva rama

Se puede crear una nueva rama usando el siguiente comando

```bash
git branch <branch-name>
```

La nueva rama que se crea es exactamente igual al estado actual del repositorio

### Cambiando de rama

Para cambiarse a una rama diferente, se usa el comando **git checkout**:

```bash {all|1|2|all}
git switch <branch-name>
git checkout <branch-name>
```

Con eso, se cambia a una linea temporal aislada del proyecto. Existe una manera mas rápida de crear y cambiar de rama:

```bash {all|1|2|all}
git switch -c <new-branch-name>
git checkout -b <new-branch-name>
```
