# Viajar a un Commit 

Para volver a un punto especifico la historia podemos hacer uso el comando

```bash
git switch --detach <commit-hash>
-o-
git checkout <commit-hash>
```

Se debe reemplazar el `<commit-hash>` por el hash del commit al que queremos volver o visitar.

Esto nos ubica en un ambiente llamado **DETACHED HEAD** que es como una linea temporal donde podemos experimentar sin miedo a romper nada.

Para volver al punto anterior al viaje lo podemos hacer con:

```bash
git checkout master
```
